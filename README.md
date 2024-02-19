# Final-Year-Project

This repository contains all the code files and different datasets used during my final year Project.
This was a Data Science project focused on predicting customer review helpfulness. This was done by 
combining Natural Language Processing (NLP) techniques, Text Analysis and Machine Learning methods to 
produce a holistic solution. 

The main focus was conducting predictive modelling by building Classification and Regression models and feeding 
our pre-processed data into these models to determine the most effective features 
(e.g. star rating, review length, readability, etc.) and the Machine Learning Algorithms with the best accuracy. 

In this project, I have performed Data Cleaning, Data Pre-processing, Splitting the data, building Machine Learning 
Models, and evaluating these models across different thresholds. I have also performed Data Visualisation in some instances.

## Project Methodology - Modified CRISP-DM
The Cross Industry Standard Process for Data Mining (CRISP-DM) reference model provides the foundation for the project's methodology. It can be used as a best practice manual to complete data mining-related tasks successfully (Chapman et al., 2000). CRISP-DM is an appropriate option because this technique is a widely established standard in academia and industry and was created with the help of real-world project experience. Empirical studies using a review corpus have been conducted using the selected technique. Data analytics approaches are used to assess the effectiveness of the suggested approach. It comprises of six phases: Business Understanding, Data Preparation, Modelling, Evaluation and Deployment. 

<img width="946" alt="new crisp md" src="https://github.com/Areefkk/Data-Science-Project-Amazon-dataset/assets/36210165/b93b2412-39e6-49bb-8220-779160d9f63e">

#### Business Understanding
This initial phase involves recognising the business perspective of the project objectives. Mining the review data allows the business to gain insight into achieving its goal. The main goal of this project is to determine quality within reviews by finding the best machine learning algorithm. Thus, relevant features must be identified as an essential stage in feature engineering to be used as algorithm input. Through the literature review, we can identify the quality criteria for the corpus and establish the requirements. 
#### Data Understanding
In this second stage, an appropriate data set is identified and collected. Key activities include connecting the business understanding with the data to discover initial insights. Within this stage, we will select appropriate quality criteria that will act as our ground truths, definitively splitting the data into a helpful and unhelpful subset.
#### Data Preparation
This stage contains activities to prepare the dataset for modelling. By examining the data, we can select appropriate and relevant features to extract that will enable us to draw valuable insights later in the experiment. We ensure data quality by cleaning the data of noise and useless information that will not contribute towards the study. The data transformation is conducted towards the later stages of this phase to prepare the data for the modelling stage.
#### Modelling
In this stage, we cover selecting appropriate data, text mining and machine learning algorithms for the given data set. The inputs for this stage are the features established in the previous stage. Using the different Machine Learning techniques, we will build our models to conduct different experiments and test the 
#### Evaluation
This stage is where we cover all the activities that enable the evaluation and verification of the model according to the business objectives and demonstrate the quality of the results. Running the different models on the test set, we will establish the performance of each model and can compare. Therefore, appropriate conclusions will be made on each. 
#### Deployment
The created report will be considered as documentation. No further system deployment is needed. 

## Dataset Used 
Kaggle - Amazon Customer Review Dataset used (https://www.kaggle.com/datasets/bittlingmayer/amazonreviews/data)
