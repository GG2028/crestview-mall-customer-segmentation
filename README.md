# Crestview Mall Customer Segmentation Analysis

## Project Overview

This project explores customer segmentation for **Crestview Mall**, a fictional business case, to support evidence-based marketing decisions.

Using a dataset of 200 customers, the analysis combines statistical hypothesis testing and unsupervised machine learning to examine differences in customer Spending Scores and identify potential customer segments.

## Business Objectives

- Assess whether gender-based differences in Spending Score provide meaningful evidence for marketing decisions.
- Identify customer segments that could benefit from differentiated promotional strategies.
- Explore customer characteristics to support more informed marketing resource allocation.

## Tools and Techniques

- **Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy and Scikit-learn
- **Exploratory Data Analysis:** Data validation, descriptive statistics and visualisation
- **Statistical Testing:** Welch's independent two-sample t-test
- **Machine Learning:** K-Means clustering with StandardScaler preprocessing
- **Model Evaluation:** Elbow Method, Silhouette Score, Davies–Bouldin Index and Calinski–Harabasz Score

## Key Findings

- Welch's t-test found no statistically significant difference in average Spending Scores between male and female customers (p = 0.422).
- K-Means clustering identified six customer segments based on Age, Annual Income and Spending Score.
- The selected model achieved an overall Silhouette Score of approximately 0.427.
- The customer segments provide a basis for exploring differentiated marketing strategies rather than relying on gender alone.

## Business Implications

The findings support exploring segment-specific promotional campaigns and evaluating their effectiveness through measurable business outcomes.

The recommendations are exploratory and should be validated using actual customer purchasing behaviour and campaign performance data.

## Dataset

**Dataset:** `Mall_Customers.csv`

**Public reference:** [Mall Customer Segmentation Data — Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset contains 200 customer records and five variables: CustomerID, Gender, Age, Annual Income (k$) and Spending Score (1–100).

The original data collection methodology and Spending Score calculation method have not been independently verified.

## How to Run

1. Download `Mall_Customers.csv` from the Kaggle dataset page.
2. Place the CSV file in the same directory as the Jupyter Notebook.
3. Install the required Python dependencies.
4. Open `Crestview Mall Customer Segmentation Analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

## Limitations

The analysis uses a relatively small dataset without actual transaction records, purchase history or campaign response data. Its findings should therefore be treated as exploratory rather than evidence of proven marketing effectiveness.

## Project Status

Completed exploratory data analysis, statistical hypothesis testing, customer segmentation and business interpretation.