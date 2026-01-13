# Student Performance Data Preparation Project

This project focuses on performing **Exploratory Data Analysis (EDA), Data Cleaning, Preprocessing, Feature Extraction, and Feature Engineering** on the StudentsPerformance dataset.  
No prediction or modeling is done — the goal is to prepare a clean, ML-ready dataset.

---

## 📊 Dataset

Dataset: StudentsPerformance.csv  
Source: Public educational dataset  

### Columns:
- gender
- race/ethnicity
- parental level of education
- lunch
- test preparation course
- math score
- reading score
- writing score

---

## 🎯 Project Objective

To transform a raw educational dataset into a structured, clean, and feature-engineered dataset ready for machine learning.

---

## 🛠 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Dataset shape and structure
- Data types analysis
- Missing value inspection
- Statistical summary
- Distribution and correlation analysis

### 2. Data Cleaning
- Duplicate removal
- Missing value handling
- Text normalization

### 3. Preprocessing
- Categorical encoding using One-Hot Encoding
- Feature scaling using StandardScaler

### 4. Feature Engineering
- Total score creation
- Performance level categorization
- Interaction feature between reading and writing scores

### 5. Final Output
A fully numeric, ML-ready dataset saved as:


---

## 🧠 Key Features in Final Dataset

- math score
- reading score
- writing score
- gender_male
- race/ethnicity_group B, C, D, E
- parental education encoded columns
- lunch_standard
- test preparation course_none
- total_score
- performance_level
- read_write_interaction

---

## 🚀 How to Run

Install dependencies:
```bash
pip install -r requirements.txt
```

## Author

Yash  
Machine Learning Data Preparation Project
