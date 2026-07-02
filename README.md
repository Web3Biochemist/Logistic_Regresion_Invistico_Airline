# Logistic Regression – Airline Customer Satisfaction Prediction

## Project Overview

This project develops a **Logistic Regression classification model** to predict whether an airline passenger is **satisfied** or **dissatisfied** based on customer demographics, travel information, and in-flight service ratings.

The project follows a complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and interpretation of results to generate actionable business recommendations.

---

## Dataset

**Dataset:** `Invistico_Airline.csv`

The dataset contains passenger information including:

- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- Seat Comfort
- Food and Drink
- Inflight Wi-Fi Service
- Online Support
- Inflight Entertainment
- Check-in Service
- Cleanliness
- Departure/Arrival Delays
- Satisfaction (Target Variable)

---

## Project Workflow

The project consists of the following steps:

1. Import required libraries
2. Load and inspect the dataset
3. Perform data cleaning
4. Explore the target variable
5. Conduct Exploratory Data Analysis (EDA)
6. Encode categorical variables
7. Split the dataset into training and testing sets
8. Standardize numerical features
9. Train a Logistic Regression model
10. Evaluate model performance using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
   - ROC Curve
   - AUC Score
11. Interpret Logistic Regression coefficients
12. Generate business recommendations

---

## Machine Learning Model

The model was developed using **Scikit-learn's LogisticRegression** classifier.

Feature scaling was performed using **StandardScaler**, and categorical variables were encoded using **One-Hot Encoding**.

---

## Model Performance

| Metric | Score |
|---------|------:|
| Accuracy | **82.89%** |
| Precision | **84.41%** |
| Recall | **84.30%** |
| F1 Score | **84.36%** |
| ROC-AUC | **90.35%** |

These results demonstrate that the model effectively distinguishes between satisfied and dissatisfied passengers.

---

## Key Findings

The Logistic Regression coefficients indicate that the strongest factors associated with higher passenger satisfaction include:

- Inflight Entertainment
- Seat Comfort
- On-board Service
- Check-in Service
- Ease of Online Booking
- Leg Room Service

Factors associated with lower passenger satisfaction include:

- Being a Disloyal Customer
- Economy Class Travel
- Personal Travel
- Arrival Delays
- Lower Food and Drink Ratings

---

## Business Recommendations

Based on the model results, airlines should prioritize:

- Improving inflight entertainment
- Enhancing seat comfort
- Streamlining online booking
- Improving onboard and check-in services
- Reducing arrival delays
- Increasing customer loyalty initiatives
- Improving the travel experience for Economy Class passengers

These improvements can increase customer satisfaction and encourage repeat business.

---

## Repository Structure

```
Logistic-Regression-Airline-Satisfaction/
│
├── Logistic_Regression_Airline.ipynb
├── Invistico_Airline.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Logistic-Regression-Airline-Satisfaction.git
```

Navigate into the project folder:

```bash
cd Logistic-Regression-Airline-Satisfaction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Logistic_Regression_Airline.ipynb
```

Run all cells to reproduce the analysis.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Conclusion

A Logistic Regression model was successfully developed to predict airline passenger satisfaction.

The model achieved strong predictive performance with an **Accuracy of 82.89%** and an **ROC-AUC of 90.35%**, demonstrating excellent classification capability.

Feature importance analysis identified service quality variables—particularly inflight entertainment, seat comfort, and onboard service—as the strongest drivers of customer satisfaction. These findings provide valuable insights that can support data-driven decision-making and improve overall passenger experience.

---

## Author

**Shuaib Usman Karuma**

Graduate Research Assistant | Medical Biochemistry | Bioinformatics | Data Science
