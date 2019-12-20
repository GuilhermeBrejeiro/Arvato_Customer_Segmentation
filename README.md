# Arvato Customer Segmentation

## Table of Contents
1. Installation
2. Project Motivation
3. Overview
4. File Desciption
5. Results
6. Licensing, Authors, Acknowledgements

## Installation
To run the Jupyter notebooks and python scripts, you will need a standard installtion of Anaconda with Python 3.6.x

**Additional libraries:**
* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* warnings
* imblearn

## Project Motivation
This project is part of the capstone requirement for Udacity's Data Scientist Nanodegree. My DSND was an incredible journey. Now, the final project in this context delves into a real-life problem. The goal was to characterize what types of individuals are more likely to be customers of a mail-order retailer and predict which customers would respond positively to marketing campaigns. This project is a significant opportunity to share my skills and deploy incredible techniques in a big business problem.

## Overview
The goal of this project was to apply unsupervised learning on this vast demographic dataset of a mail-order sales company to identify people in the population who are likely becoming customers. The second step is to apply supervised learning to predict whether a group of people are prone to become customers.
To accomplish these goals, I applied the following steps:
* Investigate demographics data of Germany's general population and a smaller set of customers of a mail-order company.
* Preprocess the data, including feature scaling and PCA.
* Apply KMeans clustering as an unsupervised learning algorithm to segment the population into clusters.
* Apply supervised learning to predict whether a person is likely to become a customer following a marketing campaign.
* Investigate the essential features trained in the model and compare the target/non-target population.
* To evaluate the model, I use AUC/ROC as the evaluation metric because of a highly imbalanced dataset.

## File Description
* For simplicity reasons, all coding is done in detailed steps in the jupyter notebook
* The data used for this project not publically available. Hence, no data is provided in this public Github repository.

Arvato_Project_Workbook.ipynb

## Results
The detailed analysis of the results can be read in this Medium post:

## Licensing, Authors, Acknowledgements
