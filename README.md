# Fraud-detection-analysis

## Summary :
This repository discusses fraud detection analysis used to predict fake transactions made to retail shops, utilizing their transaction history details. 

## Project outcome:
1. I have increased the accuracy of the genuine transaction by **47%** after sorting out the best model and data pre-processing. 

2. Analyzed, cleaned, and pre-processed for **41989** records of datasets, assessed using various combinations of samplings and machine learning models.

3. Instead of using a single model used **3** unique models and sampling methods created **9** combinations to select the best combo.


## Steps followed:

1. Import libraries, keep the dataset prepared, ready for analysis, filter important variables, and well-structured by running them in MS Excel.

2. Started with data cleaning, instead of removing incomplete records replaced them with the median of the column to bring more accurate insights.

3. Data pre-processing, need to convert categorical data into, numerical data for convenience, converted 5 categorical variables.

4. Implementing sampling to support the least count data, in the project made use of over-sampling, under-sampling, and SMOTE sampling.

5. With 3 different samples are processed to find fake transactions using 3 models to get 9 predictions.

6. Used PR curve to find each model's behavior precision, recall, and f1 score are compared for each model.

## Outcomes:
### Confusion Matrices of random forest model:
![image](https://github.com/user-attachments/assets/fe6dd920-0b1b-4edc-a4ae-887b92bbf3c8)
![image](https://github.com/user-attachments/assets/d5bf57c6-5fda-4cff-bfd6-fb2bb77360b4)
![image](https://github.com/user-attachments/assets/15566e22-b6bb-47ad-93e1-8d0370131bf9)

### Confusion Matrices for logistic regression: 
![image](https://github.com/user-attachments/assets/ed638378-298c-4f64-874b-4ee9ec9e7263)
![image](https://github.com/user-attachments/assets/db8f0375-d268-42ab-8a18-8cbf6af08478)
![image](https://github.com/user-attachments/assets/ee448cca-dea9-4d92-8981-929381231faf)

### Confusion  Matrices for K-means: 
![image](https://github.com/user-attachments/assets/24044f15-3de1-4544-b14c-5df5faab9b47)
![image](https://github.com/user-attachments/assets/47506e81-c339-473d-84c9-52382eff12e0)
![image](https://github.com/user-attachments/assets/ab903ade-5c6f-4cda-a6b0-0a941bfcf059)


### PR curves of all models :
![image](https://github.com/user-attachments/assets/d7e02622-b911-4c7e-995d-3aedd7573354)
![image](https://github.com/user-attachments/assets/711d05ee-1237-4251-9346-1fd4a8d520ce)
![image](https://github.com/user-attachments/assets/0ab7e948-3caa-45f4-934f-a100402b4a33)








