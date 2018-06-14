# Azure 머신러닝 핸즈 온 랩

본 컨텐츠는 사전 머신러닝 지식이 없는 사람들을 대상으로 설계되었습니다. 매우 기초적인 것부터 시작해서 심화된 내용에 이릅니다. 본 컨텐츠가 살아 있도록 노력하겠으며 실제 생활상의 시나리오에 맞춰 더 심화된 랩 세션을 포함하도록 하겠습니다. 본 컨텐츠가 더 나아지도록 도움주신 여러분의 응원과 피드백에 감사드립니다. 

### **Azure 머신러닝 핸즈 온 랩 과정에 대한 제안 시간표**

| 시간 (분) | 활동 |
| ---        | ---      |
| 50         | [머신러닝 ](./000-into-machine-learning.pptx) |
| 20         | Lab1 - [Setting up development environment](./001-lab-setup.md) |
| 45         | Lab2 - [Introduction to R, Python & Data Synth](./002-lab-data-synth.md) |
| 45         | Lab3 - [AzureML Experiments & Data Interaction](./003-lab-data-interact.md) |
| 60         | Lab4 - [Develop and Consume AzureML Models](./004-lab-azureml-experiment.md) |
| 45         | Lab5 - [Custom Scripts (R & Python) in AML](./005-lab-custom-script-r-python.md) |
| 60         | Lab6 - [Evaluate model performance in AML](./006-lab-model-evaluation.md) |
| 60         | Lab7 - [Azure ML Batch Score, Retrain, Production and Automatization](./007-lab-production-ops.md) |
| 45         | Lab8 - [Recommendation System](./008-lab-recommendation-system.md) |
| 45         | Lab9 - [Monetizing Azure ML Solution](./009-lab-monetization.md) |
| 90         | Lab10 - [Case Study: Optical character recognition](./010-lab-cs-ocr.md) |

### **Detailed contents of the HOL**

 - [Introduction to Machine Learning](./000-into-machine-learning.pptx)
    
1. [Setting up development environment](./001-lab-setup.md)  
    * Overview
        * Objectives
        * Requirements
    * Create free tier Azure ML account  
    * Create standard tier Azure ML account  
    * Install R and R Studio  
    * Install Anaconda Python  

2. [Introduction to R, Python & Data Synth](./002-lab-data-synth.md)  
    * Overview
        * Objectives
        * Requirements
    * Generate Synthetic Data
        * Microsoft Excel
        * R
        * Python
        * Microsoft Azure SQL Server
        * Microsoft Azure Blob Storage
    * Other Dataset sources

3. [AzureML Experiments & Data Interaction](./003-lab-data-interact.md)  
    * Overview
        * Objectives
        * Requirements
    * Creating AzureML Experiment
    * Accessing Data
        * Access data, use existing dataset
        * Upload your own dataset
        * Upload your own compressed dataset
        * Manually enter data
        * Access data on Azure Storage
        * Access data on Azure SQL Database
        * Get data from an HTTP web request

4. [Develop and Consume AzureML Models](./004-lab-azureml-experiment.md)
    * Overview
        * Objectives
        * Requirements
    * Working with AzureML Models
        * Training a model
        * Publishing a trained model as Web Service
        * Removing Web Service Redundant input & output parameters
        * Consume the ML Web Service in a C# application
        * Input data type

5. [Custom Scripts (R & Python) in AML](./005-lab-custom-script-r-python.md)
    * Overview
        * Objectives
        * Requirements
    * R & Python Script Modules
        * Using Execute R Script module
        * Using Python Script module
        * R & Python compatibility with Azure ML

6. [Evaluate model performance in AML](./006-lab-model-evaluation.md)
    * Overview
        * Objectives
        * Requirements
    * Performance evaluation
        * Splitting data
        * Scoring the model
        * Evaluate a Regression model
        * Evaluate more than one model
        * Cross Validation
    * Performance evaluation (cont.)
        * Evaluate a Binary classification model
        * Comparing two binary classification model
        * Cross Validation on Binary Classification
        * Evaluating a Multi-class classification model
    * Feature engineering
        * Which feature is or is not important?
        * Simpler method to measure a feature’s importance

7. [Azure ML Batch Score, Retrain, Production and Automatization](./007-lab-production-ops.md)
    * Overview
        * Objectives
        * Requirements
    * Importance of Retraining, seeing the whole picture
    * Batch and Request/Response scoring web services
        * Stages to create a scoring web service
            * Request/Response Service (RRS)
            * Batch Execution Service (BES)
            * Web Service Input/Output Parameter alternatives
    * Azure ML Retraining

8. [Recommendation System](./008-lab-recommendation-system.md)
    * Overview
        * Objectives
        * Requirements
    * Generate synthetic data
    * Recommend items to users
    * Find related users
    * Find related items
    * What to recommend for a brand new user?
9. [Monetizing Azure ML Solution](./009-lab-monetization.md)
    * Overview
        * Objectives
        * Requirements
    * Azure ML Web Service Details
    * Create Azure Management API Service
    * CORS issue with Azure Machine Learnin Web Services
    * Restrict or Rate limit your Web Service
    * Test and Publish your Web Service

10. [Case Study: Optical character recognition](./010-lab-cs-ocr.md)
    * Overview
        * Objectives
        * Requirements
    * Exploring and Understanding the Dataset
        * Process MINST database in Azure ML with Python script
        * Generate image tiles
    * Azure ML solution for OCR
        * Develope Azure ML experiment
        * Deploy as webservice
        * Parameters needed to publish with management API
    * Consuming the ML solution
        * Security of the API
    * Develop web application
        * Publish as Azure Web Application
    * Test the solution
    * Refine Features, Feature Engineering

