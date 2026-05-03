# OIBSIP — Oasis Infobyte Data Science Internship

**Intern:** Aviraj Seal
**Program:** AICTE Oasis Infobyte Internship — Data Science & Machine Learning

---

## Overview

This repository contains five end-to-end Machine Learning and Data Science projects completed during the Oasis Infobyte Internship Program. Each project covers the full workflow from data preprocessing and exploratory analysis through model training, evaluation, and insight generation.

---

## Repository Structure

```
OIBSIP/
├── Projects/
│   ├── Task1_Iris_Classification/
│   ├── Task2_Unemployment_Analysis/
│   ├── Task3_Car_Price_Prediction/
│   ├── Task4_Email_Spam_Detection/
│   └── Task5_Sales_Prediction/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Tech Stack

**Language:** Python
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK
**Tools:** VS Code, Jupyter Notebook, Git & GitHub

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/OIBSIP.git
cd OIBSIP
```

### 2. Create a Virtual Environment

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS / Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then navigate to the relevant `Projects/Task_X/` folder and open the `.ipynb` file.

> **Note:** Always ensure the virtual environment is activated before running any notebook.

---

## Projects

---

### <img src="assets/logos/iris.svg" width="22" style="vertical-align:middle"/> Task 1 — Iris Flower Classification

Classify Iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on sepal and petal measurements.

| | |
|---|---|
| **Algorithm** | K-Nearest Neighbors (KNN) |
| **Features** | Sepal Length, Sepal Width, Petal Length, Petal Width |
| **Visualizations** | Pairplot, Heatmap, Boxplots, Confusion Matrix |
| **Result** | High-accuracy multi-class classification with manual prediction testing |

---

### <img src="assets/logos/unemployment.svg" width="22" style="vertical-align:middle"/> Task 2 — Unemployment Analysis in India

Analyze unemployment trends across Indian states, with a focus on the impact of the Covid-19 pandemic.

| | |
|---|---|
| **Approach** | Exploratory Data Analysis (EDA) |
| **Analysis** | State-wise trends, Rural vs. Urban comparison, Covid-19 impact |
| **Visualizations** | Line Chart, Bar Graph, Boxplot, Histogram |
| **Key Insight** | Unemployment spiked sharply during 2020 lockdown, with significant variation across states |

---

### <img src="assets/logos/car.svg" width="22" style="vertical-align:middle"/> Task 3 — Car Price Prediction

Predict the resale price of used cars based on vehicle attributes.

| | |
|---|---|
| **Algorithm** | Linear Regression |
| **Features** | Present Price, Driven Kilometers, Fuel Type, Transmission, Owner, Car Age |
| **Visualizations** | Correlation Heatmap, Actual vs. Predicted Price |
| **Metrics** | Mean Absolute Error (MAE), R² Score |

---

### <img src="assets/logos/email.svg" width="22" style="vertical-align:middle"/> Task 4 — Email Spam Detection

Classify emails and SMS messages as Spam or Ham using Natural Language Processing.

| | |
|---|---|
| **Algorithm** | Multinomial Naive Bayes |
| **Techniques** | Text Preprocessing, TF-IDF Vectorization |
| **Visualizations** | Spam vs. Ham Countplot, Confusion Matrix |
| **Result** | High-accuracy binary text classifier with minimal false positives |

---

### <img src="assets/logos/sales.svg" width="22" style="vertical-align:middle"/> Task 5 — Sales Prediction

Predict product sales volume based on advertising spend across different channels.

| | |
|---|---|
| **Algorithm** | Linear Regression |
| **Features** | TV, Radio, and Newspaper advertisement budgets |
| **Visualizations** | Pairplot, Heatmap, Actual vs. Predicted Sales |
| **Metrics** | Mean Absolute Error (MAE), R² Score |

---

## Key Learnings

- Exploratory Data Analysis and Data Cleaning
- Classification and Regression model development
- Natural Language Processing (NLP)
- Feature Engineering and Encoding
- Model Evaluation and Performance Metrics
- Professional project documentation and version control

---

## Acknowledgment

Special thanks to **Oasis Infobyte** for providing structured, practical exposure to Machine Learning and Data Science through this internship program.