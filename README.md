# Heart Disease Data Exploration with SQLite and Pandas

## Overview

This project is part of a data exploration assignment, where I analyze a healthcare dataset using SQL queries in combination with SQLite and Pandas. The dataset, sourced from Kaggle, focuses on heart disease and offers valuable insights into various factors contributing to heart conditions. 

In this project, I load the dataset into an SQLite database and run a series of SQL queries to explore relationships and patterns within the data. This exercise allows for a deeper understanding of how factors like age, cholesterol levels, and chest pain types relate to heart disease diagnoses.

## Dataset

**Dataset Link**: [Heart Disease Data on Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

The dataset contains information related to heart disease from various patients, such as their age, sex, chest pain type, cholesterol levels, and a few other medical factors. It’s a pretty rich dataset that gives us a lot of opportunities to ask questions like which conditions contribute to heart disease or how age affects diagnoses.

A few key columns to note:
- `age`: The patient's age.
- `sex`: The patient's gender.
- `cp`: The type of chest pain experienced (e.g., typical angina, asymptomatic).
- `trestbps`: Resting blood pressure.
- `chol`: Cholesterol levels in mg/dl.
- `num`: The diagnosis result, where 0 = no heart disease and 1-4 represent different stages of heart disease.

### Steps I Took

1. **Downloaded the Dataset**: You can grab the dataset from Kaggle using [this link](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).
   
2. **Created a Local SQLite Database**: I created a local SQLite database named `healthcare.db` using Python’s `sqlite3` library and then loaded the dataset into this database using Pandas’ `pd.to_sql()` method.

3. **Ran SQL Queries**: I ran several SQL queries on the dataset to explore and understand the data. The queries help to filter, count, group, and sort the records based on different conditions.

## Files in This Repository

- **`heart_disease_analysis.ipynb`**: This is the Jupyter Notebook where all the SQL queries and analysis are carried out.
- **`README.md`**: The file you're reading right now, which explains what this project is about.
- **`.gitignore`**: Ensures that large files (like the dataset and the database) are not included in the GitHub repository.

## Final Thoughts

This project provided a valuable opportunity to apply SQL, SQLite, and Pandas to a real-world healthcare dataset. Through this analysis, I was able to uncover meaningful insights into the relationships between medical factors and heart disease diagnoses. By using SQL queries to filter, group, and analyze the data, I gained a better understanding of how specific health metrics can contribute to disease prediction.

The methods and techniques applied in this project demonstrate how data exploration can reveal trends that may be useful for medical research or clinical decision-making. The Jupyter Notebook includes all the queries and analyses performed, which serve as a foundation for more advanced explorations into the dataset.

