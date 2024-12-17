# Personalized Healthcare Recommendations

## Abstract
Blood datasets typically encompass a broad array of information related to hematology, blood chemistry, and related
health indicators. These datasets often include data points such as blood cell counts, hemoglobin levels, hematocrit,
platelet counts, white blood cell differentials, and various blood chemistry parameters such as glucose, cholesterol,
and electrolyte levels.
These datasets are invaluable for medical research, clinical diagnostics, and public health initiatives. Researchers
and healthcare professionals utilize blood datasets to study hematological disorders, monitor disease progression,
assess treatment efficacy, and identify risk factors for various health conditions.

## Data Set Information :
To demonstrate the RFMTC marketing model (a modified version of RFM), this study adopted the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. 

The center passes their blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. 

To build a FRMTC model, we selected 748 donors at random from the donor database. These 748 donor data, each one included 

R (Recency - months since last donation), 

F (Frequency - total number of donation), 

M (Monetary - total blood donated in c.c.), 

T (Time - months since first donation), and a binary variable representing whether he/she donated blood in March 2007 (1 stand for donating blood; 0 stands for not donating blood).

Variable Data Type Measurement Description min max mean std
Recency quantitative Months Input 0.03 74.4 9.74 8.07 Frequency quantitative Times Input 1 50 5.51 5.84
Monetary quantitative c.c. blood Input 250 12500 1378.68 1459.83
Time quantitative Months Input 2.27 98.3 34.42 24.32
Whether he/she donated blood in March 2007 binary 1=yes 0=no Output 0 1 1 (24%) 0 (76%)


# objective
Set up the project environment with necessary libraries.

Load the dataset into a DataFrame.

Preview the initial entries of the dataset.

Preview the final entries of the dataset.

Get an overview of the dataset's structure

Check the dimensions of the dataset

Checking for Missing Values:
Identify and handle missing data

Checking for Duplicated Values:
Detect and remove duplicate entries

Confirm the data types of each column

Compute descriptive statistics

Exploratory Data Analysis and Visualization with Seaborn:

Visualize data to uncover patterns and insights

Prepare the data for model training and evaluation

Train a model and evaluate its performance


