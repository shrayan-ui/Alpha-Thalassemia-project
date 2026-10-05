# Alpha-Thalassemia-project
## Project Overview

This project uses machine learning to differentiate between normal individuals and alpha-thalassemia carriers using full blood count (CBC) and haemoglobin-variant measurements.

The project was developed as a beginner-level machine learning classification project using Python and Scikit-learn.

## Objective

The main objective is to build a classification model that can predict whether an individual is:

- Normal
- Alpha-thalassemia carrier

The model uses routinely available blood-test measurements as input variables.

## Dataset

The dataset contains blood-test measurements of individuals classified as either normal or alpha-thalassemia carriers.

The main variables include:

- Haemoglobin (Hb)
- Packed Cell Volume (PCV)
- Red Blood Cell count (RBC)
- Mean Corpuscular Volume (MCV)
- Mean Corpuscular Haemoglobin (MCH)
- Mean Corpuscular Haemoglobin Concentration (MCHC)
- Red Cell Distribution Width (RDW)
- White Blood Cell count (WBC)
- Neutrophils
- Lymphocytes
- Platelets
- HbA
- HbA2
- HbF
- Sex

## Methodology

The project follows these steps:

1. Loaded and inspected the dataset.
2. Checked for missing values.
3. Handled missing numerical values.
4. Explored important blood parameters using visualisations.
5. Prepared the features and target variable.
6. Converted categorical variables into numerical values.
7. Divided the dataset into training and testing sets.
8. Standardised the numerical features.
9. Trained a Logistic Regression classification model.
10. Evaluated the model using accuracy, precision, recall, F1-score and a confusion matrix.
11. Examined model coefficients to understand the contribution of different features.
12. Tested the model on an example individual.

## Machine Learning Model

### Logistic Regression

Logistic Regression was selected because this is a binary classification problem with two possible outcomes:

- Normal
- Alpha-thalassemia carrier

It also provides interpretable coefficients that can be examined to understand how different features contribute to the classification.

## Results

The Logistic Regression model achieved approximately **71% accuracy on the test set**.

The classification report showed stronger performance in identifying alpha-thalassemia carriers than normal individuals.

The model's feature coefficients were also examined to understand which blood parameters contributed to the predictions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Disclaimer

This project is intended for educational and machine learning purposes.

The model is a screening/classification experiment and **should not be considered a clinically validated diagnostic tool or a replacement for medical testing or professional diagnosis**.
