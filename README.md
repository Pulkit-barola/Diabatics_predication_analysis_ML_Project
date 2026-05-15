# Diabetes Prediction Analysis ML Project

## Overview

This project is a Machine Learning-based Diabetes Prediction System built using Python and Support Vector Machine (SVM). The model predicts whether a person is diabetic or non-diabetic based on medical attributes.

The project focuses on:

* Data preprocessing
* Data standardization
* Model training using SVM
* Accuracy evaluation
* Predictive system creation

Repository: GitHub Repository[https://github.com/Pulkit-barola/Diabatics_predication_analysis_ML_Project](https://github.com/Pulkit-barola/Diabatics_predication_analysis_ML_Project)

---

## Features

* Data analysis using Pandas and NumPy
* Data visualization and inspection
* Feature scaling using StandardScaler
* Machine Learning model using SVM
* Train-test split for evaluation
* Accuracy score calculation
* Prediction system for custom input values

---

## Technologies Used

| Technology                      | Purpose                  |
| ------------------------------- | ------------------------ |
| Python                          | Programming Language     |
| NumPy                           | Numerical operations     |
| Pandas                          | Data handling            |
| Scikit-learn                    | Machine Learning         |
| SVM                             | Classification algorithm |
| Google Colab / Jupyter Notebook | Development environment  |

---

## Dataset Information

The project uses the Diabetes Dataset containing medical attributes such as:

* Pregnancies
* Glucose Level
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target Variable

| Outcome | Meaning             |
| ------- | ------------------- |
| 0       | Non-Diabetic Person |
| 1       | Diabetic Person     |

---

## Machine Learning Workflow

### 1. Import Libraries

Required libraries such as NumPy, Pandas, and Scikit-learn are imported.

### 2. Load Dataset

Dataset is loaded using Pandas.

### 3. Data Analysis

* Checking dataset structure
* Statistical summary
* Class distribution

### 4. Data Preprocessing

* Separating features and labels
* Standardization using `StandardScaler`

### 5. Train-Test Split

Dataset is divided into training and testing data.

### 6. Model Training

Support Vector Machine (SVM) with linear kernel is used.

### 7. Model Evaluation

Accuracy score is calculated for:

* Training Data
* Testing Data

### 8. Prediction System

Custom medical input values are passed to the model for diabetes prediction.

---

## Project Structure

```bash
Diabatics_predication_analysis_ML_Project/
│
├── Diabatics_predication.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Pulkit-barola/Diabatics_predication_analysis_ML_Project.git
```

### Move to Project Folder

```bash
cd Diabatics_predication_analysis_ML_Project
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open the notebook:

```bash
jupyter notebook
```

or run using Google Colab.

---

## Example Prediction

```python
input_data = (6,148,72,35,0,33.6,0.627,50)
```

The system predicts whether the person is diabetic or not.

---

## Results

The model achieves good prediction accuracy using SVM classification.

Training and testing accuracy scores are calculated to evaluate model performance.

---

## Future Improvements

* Add Flask or FastAPI web application
* Deploy model on cloud platforms
* Add interactive UI
* Improve accuracy using advanced models
* Add data visualization dashboards

---

## Learning Outcomes

Through this project, you can learn:

* Data preprocessing
* Feature scaling
* Classification algorithms
* Model evaluation
* Machine learning workflow
* Predictive system implementation

---

## Author

### Pulkit Barola

* Machine Learning Enthusiast
* Python Developer
* Exploring AI and Data Science

GitHub Profile  https://github.com/Pulkit-barola

---

## License

This project is open-source and available for learning purposes.
