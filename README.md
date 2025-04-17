# Titanic Dataset EDA

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover the underlying factors that influenced passenger survival. Using socio-demographic features such as **age**, **gender**, **passenger class**, and **family size**, we examine survival patterns and visualize meaningful insights using Python libraries.

## Objectives

- Understand how different features like age, gender, and class affected survival
- Discover survival trends based on family size and deck assignment
- Practice data preprocessing, handling missing values, and data visualization

## Tools & Libraries

- Python 3.0
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights

- Females had significantly higher survival rates than males.
- First-class passengers had a better chance of survival.
- Solo travelers had the lowest survival rates compared to families.
- Family size of 2–4 showed higher survival than larger or solo groups.

## Files Included

- `Titanic_EDA.ipynb` – Google Colab notebook containing the full EDA
- `README.md` – This file

## Dataset

Dataset is loaded from Seaborn’s built-in `titanic` dataset:
sns.load_dataset('titanic')
