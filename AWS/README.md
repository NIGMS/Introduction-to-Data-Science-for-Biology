## Overview of Page Contents

+ [Getting Started](#getting-started)
+ [Software Requirements](#software-requirements)
+ [Workflow Diagrams](#workflow-diagrams)

## **Getting Started**

Included is a tutorial in the form of Jupyter notebooks. The main purpose of the tutorial is to help beginners without much coding experience to familiarize themselves with basic fundamental concepts within machine learning using health data (COVID dataset). It is also meant to be extended to other kinds of structured data. The tutorial walks through step by step the process of creating a Decision Tree and interpreting it. This module intends to provide an intuitive understanding of how machine learning model performance is evaluated. In order to get to this module from the AWS Cloud, you will need to have access to an AWS account, this module is located within Amazon SageMaker. For more technical information about AWS please click on the following link: [NIH Cloud Lab README](https://github.com/STRIDES/NIHCloudLabAWS)


**1)** Follow the steps highlighted [here](https://github.com/NIGMS/NIGMS-Sandbox/blob/main/docs/HowToCreateAWSSagemakerNotebooks.md) to create a new user-managed notebook in Amazon SageMaker. Follow steps and be especially careful to enable idle shutdown as highlighted. For this module, in step 4 in the "Notebook instance type" tab, select ml.m5.xlarge from the dropdown box. select conda_python3 kernel in step 9. 

**2)** Now you will need to download the tutorial files from GitHub. The easiest way to do this would be to clone the repository from NIGMS into your SageMaker notebook. To clone this repository, use the Git command `git clone https://github.com/NIGMS/Introduction-to-Data-Science-for-Biology.git` in the terminal as it illustrated in steps 7 and 8. Please make sure you only enter the link for the repository that you want to clone. There are other bioinformatics related learning modules available in the [NIGMS Repository](https://github.com/NIGMS). This will download our tutorial files into a folder called `Introduction-to-Data-Science-for-Biology`.


**IMPORTANT NOTE** 

Make sure that after you are done with the module, close the tab that appeared when you clicked OPEN JUPYTERLAB, then check the box next to the name of the notebook you created. Then click on STOP at the top of the SageMaker menu. Wait and make sure that the icon next to your notebook is grayed out as it was described in step 10.


## **Software Requirements**

Software requirements are satisfied by using a pre-made AWS environment SageMaker Notebook. In addition all package requirements are installed by following the instructions Step 1 of the notebook **"Intro to Machine Learning Decision Trees"**.
    
## **Workflow Diagrams**

Submodule 1 and Submodule 3 will download CSV files stored in an Amazon S3 bucket to the SageMaker notebook, then it will output additional CSV files that will be used optionally if students want to work on the (optional) Submodule 2. Below is a diagram that illustrates our workflow:

![Architecture-diagram.PNG](images/Architecture-diagram.PNG)