# Titanic Data Analysis using Python 

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** using Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib**. The goal is to explore passenger data, understand distributions, and analyze survival patterns.

---

##  Dataset

The analysis is based on the following CSV files from the Titanic dataset:

- `train.csv`
- `test.csv`
- `gender_submission.csv`

These files are typically available on [Kaggle's Titanic competition](https://www.kaggle.com/c/titanic).

---

##  Features

-  Load and preview Titanic datasets
-  Display general information and statistical summaries
-  Identify missing values
-  Analyze categorical distributions:
  - Gender
  - Passenger class
  - Embarked location
-  Visualize survival trends by:
  - Age
  - Sex
  - Passenger class
-  Generate visualizations including:
  - Count plots
  - Histograms
  - Boxplots
  - Pair plots
  - Correlation heatmaps

---

## Visualizations

| Plot | Description |
|------|-------------|
| **Countplot** | Distribution of passengers by gender, class, and survival |
| **Histogram** | Age distribution |
| **Boxplot** | Fare distribution, survival vs age |
| **Pairplot** | Pairwise comparison of Pclass, Age, Fare, and Survival |
| **Heatmap** | Correlation between numerical variables |

---

##  Libraries Used

- [`pandas`](https://pandas.pydata.org/)
- [`matplotlib`](https://matplotlib.org/)
- [`seaborn`](https://seaborn.pydata.org/)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
