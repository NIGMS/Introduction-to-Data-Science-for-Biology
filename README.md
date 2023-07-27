![course card](images/SFSU-course-card-2.png)

# San Francisco State University   
## Introduction to Machine Learning for COVID Predictions
---------------------------------
This module teaches you how to create a simple Decision Tree using a structured dataset. In addition to the overview given in this README you will find the four Jupyter notebooks. The second notebook is optional.
- **1- Intro to Machine Learning: Decision Trees**: This notebook provides a basic introduction to Machine Learning concepts, steps for creating and understanding a Decision Tree model, making predictions with it, and intuitively evaluating its performance. 

- **2- (Optional) Quant. Comparison of 2020 DT Model Performance for (2020 vs 2021) Data**: This notebook is optional, for students who would like to know a bit more about how to evaluate model performance quantitatively, and offers an introduction to why machine learning models require retraining from time to time. 

- **3- Practice**: This notebook provides a way to practice and test what you have learned from the first notebook. It includes basic instructions outlining every step discussed in the first notebook. Students are free to either copy and modify the code from the first notebook or they can choose to write it themselves.

- **4- Practice - Answer Key**: This notebook provides the answers and explanation to the previous Practice exercise notebook. Check this notebook only after you have tried to complete the previous exercise yourself. 

This module will cost you about $1.00 to run, assuming you tear down all resources upon completion.

## Overview of Page Contents

+ [Getting Started](#getting-started)
+ [Overview](#overview)
+ [Software Requirements](#software-requirements)
+ [Workflow Diagrams](#workflow-diagrams)
+ [Data](#data)
+ [Funding](#funding)

## **Getting Started**

Included is a tutorial in the form of Jupyter notebooks. The main purpose of the tutorial is to help beginners without much coding experience to familiarize themselves with basic fundamental concepts within machine learning using health data (COVID dataset). It is also meant to be extended to other kinds of structured data. The tutorial walks through step by step the process of creating a Decision Tree and interpreting it. This module intends to provide an intuitive understanding of how machine learning model performance is evaluated. In order to get to this module from the Google Cloud Platform, you will need to have access to a Google Cloud Platform account, this module is located within Vertex AI Workbench. For more technical information about Google Cloud Platform please click on the following link: [NIH Cloud Lab README](https://github.com/STRIDES/NIHCloudLabGCP)

**1)** Please click on the link for steps to open your GCP project: [How to open your GCP Project](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/docs/open_GCP_project.md).

**2)** Please click on the link for general steps to create a [Vertex AI Notebook](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/docs/vertexai.md).

Choose the following settings for the new notebook created: 

Create a New Notebook and make sure you choose the first option that says **Customize...** in the menu within Vertex AI Workbench, like in the example shown in the picture below. This should take you to a new menu with advanced options to customize your notebook.

![GCP-New-notebook.png](images/GCP-New-notebook.png)

   
In the menu, make sure you input a unique notebook name. We suggest you use your own name initials such as in the example below (lm-tester). Then make sure you have the following configurations selected:
![New-Notebook-config1.png](images/New-Notebook-config1.png)
   
Keep scrolling down and you will see the following options as well to configure:
![New-Notebook-config2.png](images/New-Notebook-config2.png)
   
Choose **single user** and input the email you used to sign up to Google Cloud Console, as indicated make sure that the email is attached to a Google account:
![New-Notebook-config3.png](images/New-Notebook-config3.png)
   
At the end of this menu, click on the **CREATE** button.
   
After this it will take some time for the notebook to get started, please be patient and wait for it to be ready. It will be ready when a small green circle with a white check appears next to it. Once this happens please click **OPEN JUPYTERLAB** located next to the notebook with the name you have created in the previous step, this should take you to a separate window tab.
   
Now that you have created your virtual machine, and are in the JupyterLab screen, you can run our tutorial files. But first you will need to download them.
The easiest way to do this would be to clone the repository from NIGMS into your Vertex AI notebook. This can be done by using the `Git` menu in JupyterLab, and selecting the clone option. 
Next you can type in the link of repository: "https://github.com/NIGMS/Introduction-to-Data-Science-for-Biology" (without quotation marks) and click `Clone`. Alternatively, in a new Terminal window you can type `git clone https://github.com/NIGMS/Introduction-to-Data-Science-for-Biology.git` to download all files from the repository.

This should download our repository, and the tutorial files inside, into a folder called `Introduction-to-Data-Science-for-Biology`. Double-click this folder now. Inside you will find all our tutorial files, which you can double-click and run.

![how to clone a repo](images/Clone-a-Repository.png)


**IMPORTANT NOTE** 

Make sure that after you are done with the module, close the tab that appeared when you clicked **OPEN JUPYTERLAB**, then check the box next to the name of the notebook you created in step 3. Then click on **STOP** at the top of the Workbench menu. Wait and make sure that the icon next to your notebook is grayed out, like the example below.

![shutdown-machine.png](images/Shutdown-machine.png)

## **Overview** 

This module is geared towards beginners and does not require prior knowledge on a specific scientific discipline. The module is divided into three Jupyter notebooks as outlined at the beginning of this document. In addition to the notebooks mentioned, there are videos containing brief explanations about basic concepts in machine learning and what the code does in each step of the notebook. Below is an outline of the videos contained in each notebook with their respective links. These videos are already attached to the notebook.

### 1- Introduction To Machine Learning: Decision Trees (10 video clips)

- [Introduction Video by Lorena Benitez](https://youtu.be/e3tGQykFC5M)
- [Objectives of Exercise](https://youtu.be/_kAjJ8rJwfU)
- [Step 1: Importing necessary packages into Google Colab](https://youtu.be/jPIQbpdTkbM)
- [Step 2: Loading training data and making sure it looks correct](https://youtu.be/z9dcLYg65uk)
- [Step 3: Separate the training dataset into features and labels](https://youtu.be/qh8C0QRECWU)
- [Step 4: Create a decision tree object and train it](https://youtu.be/M6gY_JywOys)
- [Step 5: Visualize our trained decision tree](https://youtu.be/cFk6vmfU48w)
- [Step 6: Make predictions using testing data with our trained decision tree](https://youtu.be/LtD93dB5JzU)
- [Step 7: Let's see how our decision tree model performed](https://youtu.be/0VK4sLz2wrc)
- [Step 8: Let's try using our summer 2020 tree model to predict 2021 data](https://youtu.be/2r3ZpwM6xDQ)

### 2-  (Optional) Quant. Comparison of 2020 DT Model Performance for (2020 vs 2021) Data

### 3-  Practice Exercise ( 1 video clip)
- [Walkthrough Solution](https://youtu.be/eHI4wMjSGuU)
### 4- Practice Exercise - Answer Key (1 video clip )
- [Walkthrough Solution](https://youtu.be/eHI4wMjSGuU)


## **Software Requirements**

Software requirements are satisfied by using a pre-made Google Cloud Platform environment Workbench Notebook. The notebook environment used is named **"Python 3 with Intel® MKL"** ; and it is listed during Step 3 for accessing our module. In addition all package requirements are installed by following the instructions Step 1 of the notebook **"Intro to Machine Learning Decision Trees".**
    
## **Workflow Diagrams**

Submodule 1 and Submodule 3 will download CSV files stored in a Google Cloud Storage bucket to the Workbench notebook, then it will output additional CSV files that will be used optionally if students want to work on the (optional) Submodule 2. Below is a diagram that illustrates our workflow:

![Architecture-diagram.PNG](images/Architecture-diagram.PNG)

## **Data** 
All original data from this module was originally sourced from the following sites: 

- [COVID cases data (California Health and Human Services Agency)](https://data.chhs.ca.gov/dataset/covid-19-time-series-metrics-by-county-and-state/resource/046cdd2b-31e5-4d34-9ed3-b48cdbc4be7a)
- [COVID vaccination data (Los Angeles Times)](https://github.com/datadesk/california-coronavirus-data)
- [Unemployment data (California Employment Development Dept.)](https://data.edd.ca.gov/Labor-Force-and-Unemployment-Rates/Local-Area-Unemployment-StatisticsdecisionLAUS-/e6gw-gvii)
- [Election data (Harvard University)](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ)

We subsequently picked only certain variables of interest, cleaned and created a composite dataset for the years 2020 and 2021 from the sources listed above. **We manipulated the variable named "Unemployment_rate" by using the 2020 rates in both the 2020 and 2021 Datasets**. We then separated these datasets into training, validation, and testing sets for each of these years to streamline the tutorials. Finally, we stored them in our group's [SFSU GitHub repository](https://github.com/MarcMachineLearning/Introduction-to-Machine-Learning/tree/main/Datasets). 

## **Funding**

- SFSU/UCSF M.S. Bridges to the Doctorate Program: cloud-based learning modules supplement (T32GM142515)
- Demystifying Machine Learning and Best Data Practices Workshop Series for Underrepresented STEM Undergraduate and MS Researchers bound for PhD Training Programs (T34-GM008574)
- The creation of this training module was supported by the National Institute Of General Medical Sciences of the National Institutes of Health under Award Number 3T32GM142515-01S1

## **License for Data**

Text and materials are licensed under a Creative Commons CC-BY-NC-SA license. The license allows you to copy, remix and redistribute any of our publicly available materials, under the condition that you attribute the work (details in the license) and do not make profits from it. More information is available [here](https://tilburgsciencehub.com/about/#license).

![Creative commons license](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)
