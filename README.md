# Starbucks-Capstone-Project-ML-Udacity-aws
# Starbucks Promotions Project 
## This project is the Capstone Project of Udacity's Machine Learning Engineering Nanodegree program.

![intro](/images0/intro.png)

## Problem Statement:
- This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. 
- Once every few days, Starbucks sends out an offer to users of the mobile app. 
- An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). 
- Some users might not receive any offer during certain weeks.  
- Not all users receive the same offer, and that is the challenge to solve with this data set.  
- The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. 
- This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.
- Starbucks collects the customer data to understand their behaviour on the rewards and offers sent via the mobile-app. 
- These customers can respond positively/negatively/neutrally. 
- A key thing to note is that not all the customers receive the same offer. 
- The task of this project is to combine transaction, demographic and offer data of the past (which is already provided) to determine which demographic groups respond best to which offer types.    
- In order to develop this project, we needed to use some tools, packages, systems and services that could help us achieve our goals.  

## Libraries:
- First of all, we used **Python** to write our scripts not only for algorithm training and serving but also for the orchestration of the whole process.   
- Important packages within this environment are listed below:  
    - This project is developed in Python 3.6.   
    - You will need install some libraries in order to run the code are:   
      -   `pandas` so we could work with tabular data in dataframes; 
      -   `Ploty` so we could visualize our Dataset; 
      -   `matplotlib` for Dataset visualization; 
      -   `numpy` so we could easily manipulate arrays and data structures; 
      -   `seaborn` and `matplotlib` so we could generate insightful visualizations; 
      -   `sklearn` so we could build and develop our model pipeline; 
      -   `imblearn` so we could apply SMOTE to our training data; 
      -   `xgboost` so we could have our main classifier; 
      -   `sagemaker` so we could easily interact with AWS. 
      -   `json` for reading our Dataset Files. 
      -   `boto3`  
    - Finally, we used **AWS environment** in order to launch **training jobs, deploy our model and serve predictions**. 
 
 ## The main services used are also listed below:  
 -  __AWS SageMaker__: 
    - training, hyperparameter tuning and endpoint serving; 
-  __Amazon S3__: 
    - saving our data and model artifacts;   
## Files Descriptions:
- This project is structured as follows: 
-  #### 01. Proposal  Project 
   - proposal documentation. 
- #### 02. Data_Cleaning_[Dataset]  
   - Folder to perform data preparation and Dataset Cleaning and Prepare the Final Data for Further using in model algorithms.  
- #### 03. Pre-processing Dataset Visualization  
   - Folder to perform final Pre-processing Dataset to be used in Visualization and exploration.   
- #### 04. Dataset_Visualization  
   - Folder to perform Visualizations for the Pre-processed Dataset.   
- #### 06. ORG_Starbucks_Capstone_Project.ipynb  
   - Jupyter notebook file that deploy final model and create an endpoint and orchestrates the end-to-end process in AWS SageMaker and also interacts with other services.
