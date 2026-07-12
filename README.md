# Titanic Survival Analysis

Exploratory Data Analysis, Statistical Analysis and Machine Learning on the Titanic dataset using Python, Pandas, Seaborn and Scikit-Learn.

---

## Overview

This project investigates the factors that influenced passenger survival during the sinking of the RMS Titanic in 1912. Using a real-world dataset sourced from Kaggle, the analysis covers data cleaning, visualisation, statistical analysis, and the development of a logistic regression classifier to predict survival outcomes.

---

## Dataset

- **Source:** [Kaggle — Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File used:** `train.csv`
- **Observations:** 891 passengers
- **Features:** 12 variables including age, fare, passenger class, gender, and survival status

---

## Project Structure

```
Titanic-Survival-Analysis/
│
├── titanic_analysis.ipynb   # Main Jupyter Notebook with full analysis
├── train.csv                # Titanic dataset
├── titanic_report.pdf               # Full project report
└── README.md                # Project documentation
```

---

## Libraries Used

- `pandas` — data manipulation and cleaning
- `numpy` — numerical operations
- `matplotlib` — data visualisation
- `seaborn` — statistical visualisation
- `scikit-learn` — machine learning model development

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Quode-Benny/Titanic-Survival-Analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Titanic-Survival-Analysis
   ```

3. Install required libraries if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Launch Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter lab
   ```

5. Open `titanic_analysis.ipynb` and run all cells.

---

## Key Findings

- Only **38.38%** of passengers survived the disaster
- **74% of females** survived compared to only **19% of males**, confirming the women and children first evacuation policy
- First class passengers paid an average fare of **84.15** compared to **13.68** for third class
- The strongest negative correlation was between passenger class and fare **(−0.55)**
- The logistic regression model achieved an accuracy of **81.01%**

---

## Author

**Benny** — Computer Science Student, Accra Technical University
