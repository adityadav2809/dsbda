# DSBDA (Data Science and Big Data Analytics)

This repository contains practical assignments and projects related to the **Data Science and Big Data Analytics (DSBDA)** course. The focus is on implementing data science techniques, machine learning algorithms, and performing data analysis on various datasets.

## Table of Contents

1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Practical 1: Data Wrangling I](#practical-1-data-wrangling-i)
5. [Practical 2: Data Wrangling II](#practical-2-data-wrangling-ii)
6. [Practical 3: Descriptive Statistics](#practical-3-descriptive-statistics)
7. [Practical 4: Data Analytics I](#practical-4-data-analytics-i)
8. [Practical 5: Data Analytics II](#practical-5-data-analytics-ii)
9. [Practical 6: Data Analytics III](#practical-6-data-analytics-iii)
10. [Practical 7: Text Analytics](#practical-7-text-analytics)
11. [Practical 8: Data Visualization](#practical-8-data-visualization)
12. [Practical 9: Data Visualization II](#practical-9-data-visualization-ii)
13. [Practical 10: Data Visualization III](#practical-10-data-visualization-iii)
14. [How to Run](#how-to-run)
15. [License](#license)

---

## Overview

This repository is part of the **Data Science and Big Data Analytics** course, containing practical assignments and tasks for various concepts like **data wrangling**, **data preprocessing**, **statistical analysis**, **machine learning algorithms**, **text analytics**, and **data visualization**. Each practical demonstrates the use of Python and related libraries to analyze datasets and implement real-world solutions.

---

## Technologies Used

- **Python** (Version 3.x or higher)
- **Pandas** (Data manipulation and analysis)
- **NumPy** (Numerical computing)
- **Matplotlib** (Data visualization)
- **Seaborn** (Statistical data visualization)
- **Scikit-learn** (Machine learning algorithms)
- **NLTK** (Natural Language Toolkit for Text Processing)
- **Jupyter Notebooks** (Interactive development environment)

---


## Practical 1: Data Wrangling I

This practical covers various data wrangling techniques using Python, including data preprocessing, handling missing values, and converting categorical variables into quantitative ones.

- **Dataset**: [20k Musical Artists Dataset](https://www.kaggle.com/datasets/sbhatti/20k-musical-artists)
- **Techniques Used**:
  - Missing value detection and imputation
  - Data normalization and formatting
  - Categorical to quantitative conversion

---

## Practical 2: Data Wrangling II

This practical involves creating a dataset for academic performance and applying techniques to handle missing data, outliers, and transformations to improve data quality.

- **Techniques Used**:
  - Outlier detection and handling
  - Data transformations (log transformations)
  - Missing value imputation

---

## Practical 3: Descriptive Statistics

In this practical, descriptive statistics methods are used to analyze data, such as calculating the mean, median, and standard deviation for different subsets of data.

- **Dataset**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Techniques Used**:
  - Grouping data by categorical variables
  - Calculating summary statistics (mean, median, etc.)
  - Visualizing distributions

---

## Practical 4: Data Analytics I

This practical implements a **Linear Regression Model** to predict house prices using the Boston Housing dataset.

- **Dataset**: [Boston Housing Dataset](https://www.kaggle.com/c/boston-housing)
- **Techniques Used**:
  - Linear Regression modeling
  - Model evaluation using Mean Squared Error

---

## Practical 5: Data Analytics II

In this practical, **Logistic Regression** is used to perform classification tasks on the Social Network Ads dataset.

- **Dataset**: [Social Network Ads Dataset](https://www.kaggle.com/)
- **Techniques Used**:
  - Logistic Regression for classification
  - Confusion Matrix and evaluation metrics (accuracy, precision, recall)

---

## Practical 6: Data Analytics III

This practical applies the **Naïve Bayes** classifier to the Iris dataset and evaluates its performance using a confusion matrix.

- **Dataset**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Techniques Used**:
  - Naïve Bayes classification
  - Performance evaluation using confusion matrix

---

## Practical 7: Text Analytics

In this practical, text preprocessing techniques like **tokenization**, **POS tagging**, **stop words removal**, **stemming**, and **lemmatization** are applied to process sample text documents.

- **Techniques Used**:
  - Text tokenization and cleaning
  - TF-IDF vectorization

---

## Practical 8: Data Visualization

This practical covers visualizing the **Titanic dataset** using Seaborn and Matplotlib to identify patterns and relationships in the data.

- **Dataset**: [Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Techniques Used**:
  - Histogram and boxplot visualizations
  - Survival analysis by age, gender, and class

---
## Practical 9: Data Visualization II

This practical covers advanced data visualization techniques, particularly focusing on box plots and their interpretation using Python. The goal is to explore the relationship between age, gender, and survival status from the Titanic dataset.

- **Dataset**: [Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Techniques Used**:
  - Box Plot visualization for the distribution of age based on gender and survival status.
  - Exploratory data analysis (EDA) using Seaborn for pattern recognition.

### Operations:
- Create box plots to visualize the age distribution for each gender, categorized by survival status.
- Identify insights from the box plot, such as age differences between survivors and non-survivors across genders.

---

## Practical 10: Data Visualization III

This practical dives into advanced visualizations using the Iris dataset. The focus is on creating histograms and box plots to explore the distribution of features across different species of Iris flowers.

- **Dataset**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Techniques Used**:
  - Histogram visualization to illustrate the distribution of features in the dataset.
  - Box plot visualization to check for outliers and compare feature distributions across Iris species.
  - Exploratory data analysis to identify patterns and key insights from the data.

### Operations:
- Visualize the feature distribution of the Iris dataset using histograms.
- Create box plots to identify outliers in the dataset and analyze the distribution of features across different Iris species.

---

## How to Run

### Prerequisites:

To run the code in this repository, you must have Python installed. You will also need to install the required libraries.

### Installation:

1. Clone the repository:

   ```bash
   git clone https://github.com/adityadav2809/dsbda.git
   cd dsbda
Install dependencies:

2. Create a virtual environment (optional) and install the required libraries:

pip install -r requirements.txt

3. Run individual scripts for each practical. For example, to run Practical 1:

python Practical_1_Data_Wrangling_I/data_preprocessing.py

---

### Key Points:

1. **Overview**: Describes what the repository is about.
2. **Technologies Used**: Lists the libraries and frameworks used.
3. **Project Structure**: Describes the folder structure and where to find practical assignments.
4. **Individual Practicals**: A brief description of each practical with the dataset used.
5. **How to Run**: Instructions for setting up the environment and running the code.
6. **License**: Specifies the repository license.
