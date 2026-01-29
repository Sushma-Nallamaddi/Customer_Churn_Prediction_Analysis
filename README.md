
# Netflix User Clustering using Machine Learning

This project implements a mini machine learning pipeline to analyze and cluster Netflix users based on their activity and profile data. It demonstrates how to apply data preprocessing, exploratory data analysis, and unsupervised learning (clustering) to real-world user behavior data.

## Project Overview

- **Objective:** Identify natural user segments within Netflix user data using K-Means Clustering.
- **Tech Stack:** Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Dataset:** Custom or Kaggle-sourced `netflix_users.csv`

## Features & Workflow

1. **Data Loading and Preprocessing**
   - Cleaned and formatted Netflix user data.
   - Handled missing values and irrelevant columns.

2. **Exploratory Data Analysis (EDA)**
   - Used visualization libraries (Seaborn, Matplotlib) to understand user demographics and behavior patterns.

3. **Feature Engineering**
   - Encoded categorical variables.
   - Scaled numerical features for clustering.

4. **K-Means Clustering**
   - Applied the elbow method to find the optimal number of clusters.
   - Trained a K-Means model to classify users into segments.

5. **Results Visualization**
   - Plotted cluster distributions.
   - Interpreted patterns across clusters.

## Files

- `MLmini.ipynb` – The main Jupyter notebook containing the code, visualizations, and analysis.
- `netflix_users.csv` – Dataset used for the project.

## Requirements

Install dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Sample Output

- Optimal cluster count visualization (Elbow Method)
- Clustered user group breakdowns
- Key insights into user behavior patterns

## Author

**Sushma Reddy** – [LinkedIn](https://www.linkedin.com) 
