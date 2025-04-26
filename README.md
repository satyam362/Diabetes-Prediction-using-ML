# 🩺 Diabetes Prediction using KNN (R Project)

This project predicts whether a patient has diabetes based on diagnostic measurements using the **K-Nearest Neighbors (KNN)** algorithm implemented in **R**.

## 📂 Project Structure

- `diabetes.csv` — Dataset containing patient diagnostic information.
- `KNN algorithm for ca3.R` — R script implementing the KNN model.
- `Project Ca3.R` — Additional analysis, evaluation, and results.

## 🧪 Dataset Information

The dataset (`diabetes.csv`) typically includes the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- Outcome (1 = Diabetes, 0 = No Diabetes)

> *Note: Make sure your CSV file is clean and formatted properly before training.*

## 🛠️ Technologies Used

- **R Language**
- **Libraries**: 
  - `class` (for KNN)
  - `caret` (for data partitioning and evaluation)
  - `ggplot2` (for visualization)
  - `dplyr` (for data manipulation)

## 📈 Project Workflow

1. Load and clean the dataset
2. Perform exploratory data analysis (EDA)
3. Split the data into training and testing sets
4. Scale/normalize the features
5. Train the KNN model
6. Predict on the test data
7. Evaluate the model using accuracy, confusion matrix, etc.
