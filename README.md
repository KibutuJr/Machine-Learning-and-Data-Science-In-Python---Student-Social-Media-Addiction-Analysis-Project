# Machine Learning and Data Science in Python: Student Social Media Addiction Analysis

## 📌 Project Overview

Social media has become an integral part of students' daily lives, influencing communication, learning, entertainment, mental well-being, sleep patterns, and interpersonal relationships. While social platforms provide numerous benefits, excessive usage can contribute to addictive behaviors and negatively affect academic performance, mental health, and social interactions.

This project leverages **Data Science**, **Exploratory Data Analysis (EDA)**, and **Machine Learning** techniques in Python to analyze student social media behavior and identify patterns associated with social media addiction. The project aims to uncover meaningful insights from data and build predictive models capable of understanding factors that contribute to addictive social media usage among students.

The analysis combines statistical exploration, feature engineering, data visualization, and machine learning algorithms to transform raw survey data into actionable insights.

---

# 🎯 Project Objectives

The primary objectives of this project are to:

* Analyze social media usage patterns among students.
* Investigate relationships between social media addiction and:

  * Daily usage hours
  * Mental health scores
  * Sleep duration
  * Academic performance
  * Relationship status
  * Demographic characteristics
* Identify the most influential factors contributing to social media addiction.
* Build machine learning models capable of predicting addiction-related outcomes.
* Evaluate model performance using appropriate classification metrics.
* Generate visual insights to support data-driven decision-making.

---

# 🗂 Dataset Description

The project utilizes a student social media addiction dataset containing demographic, behavioral, and psychological attributes.

### Example Features

| Feature                      | Description                                       |
| ---------------------------- | ------------------------------------------------- |
| Age                          | Student age                                       |
| Gender                       | Student gender                                    |
| Academic Level               | Educational level                                 |
| Daily Usage Hours            | Average daily social media usage                  |
| Sleep Hours                  | Average hours slept per night                     |
| Mental Health Score          | Self-reported mental wellness score               |
| Relationship Status          | Current relationship status                       |
| Most Used Platform           | Primary social media platform                     |
| Addiction Score              | Measured social media addiction level             |
| Conflicts Over Social Media  | Relationship conflicts caused by social media     |
| Affects Academic Performance | Whether social media impacts academic performance |

The dataset enables the exploration of how digital behaviors influence student well-being and lifestyle outcomes.

---

# 🛠 Technologies Used

### Programming Language

* Python 3.x

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Plotly

### Machine Learning

* Scikit-Learn
* Random Forest
* Logistic Regression
* Decision Trees
* K-Nearest Neighbors (KNN)

### Development Environment

* Jupyter Notebook
* VS Code

Scikit-Learn provides a robust framework for machine learning model development and evaluation in Python.

---

# 📊 Project Workflow

## 1. Data Collection

The project begins with loading and inspecting the student social media addiction dataset.

Key tasks include:

* Reading raw data
* Understanding feature definitions
* Checking data types
* Identifying missing values
* Reviewing dataset structure

---

## 2. Data Cleaning

Data preprocessing was performed to ensure data quality and consistency.

Tasks include:

* Handling missing values
* Removing duplicate records
* Correcting inconsistent entries
* Encoding categorical variables
* Feature formatting and transformation

---

## 3. Exploratory Data Analysis (EDA)

EDA was conducted to understand the dataset and identify meaningful trends.

### Areas Explored

#### Demographic Analysis

* Gender distribution
* Age distribution
* Academic level breakdown

#### Social Media Usage Analysis

* Daily usage trends
* Most popular platforms
* Addiction score distribution

#### Mental Health Analysis

* Relationship between addiction and mental health
* Sleep patterns versus addiction levels

#### Academic Impact Analysis

* Social media influence on academic performance
* Study behavior trends

#### Relationship Analysis

* Social media-related conflicts
* Relationship status patterns

---

# 📈 Data Visualization

Various visualizations were created to communicate insights effectively.

Examples include:

* Histograms
* Boxplots
* Correlation Heatmaps
* Bar Charts
* Pie Charts
* Scatter Plots
* Distribution Plots

These visualizations help reveal:

* Behavioral trends
* Hidden correlations
* Outliers
* Feature relationships

---

# ⚙️ Feature Engineering

Feature engineering was performed to improve model performance.

Techniques include:

* Label Encoding
* One-Hot Encoding
* Feature Scaling
* Correlation Analysis
* Feature Selection

The goal was to retain the most informative variables while reducing noise.

---

# 🤖 Machine Learning Models

Several machine learning algorithms were trained and evaluated.

### Models Evaluated

#### Logistic Regression

A baseline classification model used for binary prediction tasks.

#### Decision Tree Classifier

Captures nonlinear relationships and provides interpretability.

#### Random Forest Classifier

An ensemble learning method that combines multiple decision trees to improve prediction accuracy.

#### K-Nearest Neighbors (KNN)

A distance-based algorithm used for classification.

---

# 📏 Model Evaluation

Performance was assessed using standard machine learning metrics.

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

Evaluation ensures model reliability and helps compare algorithm effectiveness.

---

# 🔍 Key Insights

The analysis revealed several notable findings:

### Social Media Usage

* Higher daily social media usage is associated with increased addiction scores.
* Certain platforms exhibit higher engagement levels among students.

### Mental Health

* Students with higher addiction levels tend to report lower mental health scores.
* Excessive usage may contribute to emotional and psychological strain.

### Sleep Patterns

* Increased social media use often corresponds with reduced sleep duration.
* Sleep deprivation appears more common among highly active users.

### Academic Performance

* Excessive social media engagement can negatively affect academic outcomes.
* Students reporting addiction symptoms often indicate reduced study productivity.

### Relationships

* Higher addiction scores are linked to increased social media-related conflicts.
* Digital behavior may influence relationship satisfaction and communication quality.

---

# 📂 Project Structure

```text
Machine-Learning-and-Data-Science-In-Python-Student-Social-Media-Addiction-Analysis-Project/

│
├── data/
│   ├── raw_data.csv
│
├── Python File/
│   ├── Student_Social_Media_Analysis.ipynb
├── models/
│   ├── trained_models/
│
├── screenshots/
│   ├── vimages/isualizations/
│
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/KibutuJr/Machine-Learning-and-Data-Science-In-Python-Student-Social-Media-Addiction-Analysis-Project.git
```

## Navigate to Project Directory

```bash
cd Machine-Learning-and-Data-Science-In-Python-Student-Social-Media-Addiction-Analysis-Project
```

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📚 Skills Demonstrated

This project demonstrates proficiency in:

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization
* Feature Engineering
* Machine Learning
* Model Evaluation
* Python Programming
* Data Storytelling
* Predictive Analytics

---

# 💼 Portfolio Value

This project showcases practical end-to-end data science skills commonly used in industry:

* Real-world dataset analysis
* Business and behavioral insight generation
* Predictive modeling
* Data-driven decision making
* Machine learning workflow implementation

The project reflects the ability to move from raw data to actionable insights while applying industry-standard Python data science tools.

---

# 🔮 Future Improvements

Potential enhancements include:

* Hyperparameter tuning
* Cross-validation optimization
* Model deployment using Streamlit
* Interactive dashboards
* Advanced ensemble models
* Feature importance analysis
* Explainable AI (SHAP/LIME)
* Real-time prediction interface

---

# 👨‍💻 Author

### Fred Kibutu

Data Analyst | Data Engineer | Software Engineer | MSc Financial Engineering Candidate

Portfolio:
[View My Portfolio](https://kibutujr.vercel.app/)

LinkedIn:
[Connect on LinkedIn](https://www.linkedin.com/in/fred-kibutu)

---

# ⭐ If You Found This Project Useful

If this project helped you learn something new or inspired your own work, consider giving the repository a star.

Your support helps grow the open-source and data science community.
