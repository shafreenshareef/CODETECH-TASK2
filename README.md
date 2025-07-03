# PREDICTIVE-ANALYSIS

COMPANY: CODETECH IT SOLUTIONS

NAME: SHAIK SHAFREEN SHAREEF

INTERN ID : CT08DM215

DOMAIN: DATA ANALYTICS

TASK: BIG DATA ANALYSIS

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

# DESCRIPTION
## 🔍 Objective

The objective of this project is to build a **predictive machine learning model** that can classify whether a patient is likely to have heart disease based on various clinical attributes. This fulfills **Task 2 of the CODTECH internship**, where the focus is on demonstrating the end-to-end pipeline of **data cleaning, feature selection, model training, evaluation, and human-interpretable predictions**.


## 📂 Dataset

| Attribute         | Detail                                               |
| ----------------- | ---------------------------------------------------- |
| **Name**          | Heart Disease UCI Dataset                            |
| **File**          | `heart.csv`                                          |
| **Source**        | Public Dataset (Processed UCI Heart Disease Dataset) |
| **Format**        | CSV                                                  |
| **Records**       | 918 rows × 12 columns                                |
| **Target Column** | `HeartDisease` (1 = disease, 0 = no disease)         |


## 🧰 Tools & Technologies Used

| Tool / Library             | Purpose                                        |
| -------------------------- | ---------------------------------------------- |
| **Python**                 | Core programming language                      |
| **Pandas, NumPy**          | Data manipulation and numerical computation    |
| **Matplotlib, Seaborn**    | Data visualization                             |
| **Scikit-learn**           | Model building, training, evaluation           |
| **Logistic Regression**    | Classification algorithm for binary prediction |
| **Google Colab / Jupyter** | Interactive notebook development               |


## 🔑 Key Steps in the Project

### 1. Data Loading

* Loaded `heart.csv` using Pandas
* Explored the structure and summary statistics of the data

### 2. Data Cleaning

* Removed duplicate rows
* Verified there were no missing values
* Preserved the `HeartDisease` column as the binary target
* Applied one-hot encoding to relevant categorical columns:

  * `Sex`, `ChestPainType`, `RestingECG`, `ExerciseAngina`, `ST_Slope`

### 3. Feature Engineering

* Converted categorical features into dummy variables
* Scaled numerical features using `StandardScaler`
* Split the dataset into **train** and **test** subsets (80/20 split)

### 4. Model Training

* Trained a **Logistic Regression model** using `scikit-learn`
* Used the training set to fit the model
* Predicted outcomes on the test set

### 5. Evaluation

* Calculated **accuracy**, **precision**, **recall**, and **F1-score**
* Generated a **confusion matrix** for visual performance review
* Plotted:

  * **ROC Curve** with AUC score
  * **Precision-Recall Curve** with AUC
* Performed **5-fold Cross-Validation** to check model generalizability
* Interpreted **feature coefficients** to understand predictive importance

### 6. Human-Readable Prediction Output

* Generated output like:

  * 🟢 “You may not have heart disease”
  * ✅ “You may have heart disease”

This makes it more understandable for non-technical users.


## 📈 Results Summary

| Metric                 | Score (Example) |
| ---------------------- | --------------- |
| **Accuracy**           | 0.88 (varies)   |
| **ROC AUC**            | 0.93+           |
| **PR AUC**             | 0.92+           |
| **Cross-Val Accuracy** | \~0.86 ± 0.02   |


## 📌 Conclusion

This project demonstrates how supervised machine learning, combined with proper data cleaning and preprocessing, can build a robust binary classifier for medical prediction.


![Image](https://github.com/user-attachments/assets/fc71d712-6630-431c-b2be-ae334146c01b)
![Image](https://github.com/user-attachments/assets/76cd86e5-7a4a-4d84-94bc-a50258e8f873)
![Image](https://github.com/user-attachments/assets/03379ebc-9b86-40d8-a04a-d759438031c6)
![Image](https://github.com/user-attachments/assets/83da8b1b-9064-4fe5-94a6-9632352c58a9)
![Image](https://github.com/user-attachments/assets/0a1b83e2-b9ed-4d8b-988b-af53a9a64df5)
![Image](https://github.com/user-attachments/assets/190860e9-01d8-402e-a5aa-f91ee913ce67)
