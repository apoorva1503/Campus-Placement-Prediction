# Campus Placement Prediction using Machine Learning

A Machine Learning project that predicts whether a student is likely to get placed based on academic performance, internships, projects, certifications, aptitude score, communication skills, and other placement-related factors.

---

## Project Overview

- Built a machine learning classification model to predict students' placement status.
- Performed comprehensive data preprocessing and exploratory data analysis (EDA).
- Trained and compared multiple machine learning algorithms.
- Evaluated each model using standard classification metrics.
- Identified the best-performing model for campus placement prediction.

---

## Dataset

The dataset contains **100,000 student records** with academic, demographic, and skill-related information.

### Features

- Student ID
- Gender
- Age
- City Tier
- SSC Percentage
- SSC Board
- HSC Percentage
- HSC Board
- HSC Stream
- Degree Percentage
- Degree Field
- MBA Percentage
- Specialization
- Number of Internships
- Number of Projects
- Number of Certifications
- Technical Skills Score
- Soft Skills Score
- Aptitude Score
- Communication Score
- Work Experience (Months)
- Leadership Roles
- Extracurricular Activities
- Backlogs

**Target Variable**

- Placement Status (Placed / Not Placed)

---

## Project Workflow

- Data Loading
- Data Cleaning
- Missing Value Analysis
- Exploratory Data Analysis (EDA)
- Label Encoding
- Correlation Analysis
- Feature Selection
- Train-Test Split
- Model Training
- Model Comparison
- Performance Evaluation
- Feature Importance Analysis

---

## Exploratory Data Analysis

The project includes visual analysis such as:

- Placement Distribution
- Academic Performance Distribution
- Placement Rate by City Tier
- Internship vs Placement
- Projects vs Salary
- Skill Score Trends
- Average Salary Analysis
- Backlogs Impact on Placement
- Leadership Roles vs Extracurricular Activities
- Salary Distribution
- Feature Correlation Heatmap

---

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

---

## Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **85.80%** |
| Support Vector Machine | **85.61%** |
| Random Forest | **85.54%** |
| K-Nearest Neighbors | **83.78%** |
| Gaussian Naive Bayes | **83.31%** |
| Decision Tree | **78.38%** |

**Best Model:** Logistic Regression (85.80%)

---

## Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```
Campus-Placement-Prediction
│
├── dataset/
├── notebook/
├── results/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

- Clone the repository

```bash
git clone https://github.com/apoorva1503/Campus-Placement-Prediction.git
```

- Install the required libraries

```bash
pip install -r requirements.txt
```

- Open the notebook

```
notebook/campus-placement-prediction-model.ipynb
```

- Run all notebook cells to reproduce the results.

---

## Results

- Performed comprehensive data preprocessing.
- Conducted detailed exploratory data analysis.
- Compared six machine learning classification models.
- Evaluated models using multiple performance metrics.
- Achieved **85.80% accuracy** with Logistic Regression.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Advanced feature engineering.
- Ensemble learning techniques.
- Deep Learning-based prediction models.
- Streamlit web application deployment.
- Model deployment using Flask or FastAPI.

---

## Author

**Apoorv Kumar Sahu**

- B.Tech, Information Technology
- National Institute of Technology Raipur

GitHub: https://github.com/apoorva1503
