# AWS-Sagemaker-Mobile-Price-Classification
Deployed a mobile price range prediction model using scikit-learn on AWS SageMaker. Trained a Random Forest classifier for accurate predictions based on key features. Streamlined deployment with a concise guide and seamless integration of AWS services.
## Article
https://guneet-kohli.medium.com/mobile-price-range-classification-using-aws-sagemaker-5ddaf9d59777


## Introduction
This project presents an end-to-end deployment of a Random Forest multi-class classifier model on AWS SageMaker for predicting the price range of mobile phones. The code and dataset can be found in this repository.

##  Project Overview
The primary goal of this project is to train and deploy a Random Forest multi-class classifier model using AWS SageMaker. The model predicts the price range of mobile phones. The implementation is based on Krish Naik’s tutorial "End-to-end Machine Learning Project Implementation Using AWS SageMaker". 
##  Tools
* Development Environment: Visual Studio Code, Anaconda
* AWS Services: SageMaker, S3, IAM
## Project Structure
* sagemaker-custom-script.ipynb: Jupyter Notebook containing the project implementation.
* script.py: Python script used for model training.
* requirements.txt: File listing the required packages for the project.
* mob_price_classification_train.csv: Dataset used for training the model.
* train-V-1.csv and test-V-1.csv: Train and test data files.
## Installation
To install the necessary packages, run the following command:
* pip install -r requirements.txt
## Usage
Follow the steps outlined in the sagemaker-custom-script.ipynb notebook for a detailed walkthrough of the project. This includes setting up the AWS environment, training the Random Forest model, and deploying it on SageMaker.

## Conclusion
This project serves as a comprehensive guide for deploying a machine learning model on AWS SageMaker, emphasizing the importance of deploying models for real-world applications. For a step-by-step walkthrough, please refer to the provided notebook (sagemaker-custom-script.ipynb).
