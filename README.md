#GDM Early Prediction using Machine Learning

Project Overview
This project focuses on the development and training of machine learning models to predict the risk of Gestational Diabetes Mellitus (GDM) early in pregnancy. The trained models leverage clinical and biochemical data (e.g., age, BMI, family history of diabetes) to accurately predict the likelihood of GDM well before the traditional diagnostic window. This tool can potentially help healthcare providers identify at-risk pregnancies earlier and implement timely interventions to improve maternal and fetal health.

This project predicts Gestational Diabetes Mellitus (GDM) using machine learning models:  
• Deep Learning
• MLP
• Logistic Regression
• SVM

The dataset includes medical records with risk factors for diabetes.  

## How to Use  
1. Download the `diabetes.ipynb` notebook from this repository.  
2. Open it in Jupyter Notebook or Google Colab.  
3. Prepare the Dataset:
   Place your dataset in the correct directory. The dataset should include necessary features (e.g., age, BMI, family history, biochemical markers) for training. Update the dataset path in the project files if 
   needed.
4. Train the Machine Learning Model
5. Model Evaluation:
   After training, the script will evaluate the model using a test dataset. The evaluation results, including metrics like accuracy, sensitivity, specificity, and AUC score, will be printed.

## Dependencies  
Ensure you have the following installed:  
- Python 3.8+  
- Jupyter Notebook  
- Required libraries (`pandas`, `numpy`, `sklearn`, `tensorflow`, etc.)

## Results
Below are some images showing the performance of the model:


Confusion Matrix:


ROC Curve:


Feature Importance:

## Author  
*Neeraj Pratap Singh*
