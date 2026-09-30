# Amazon Sales Data Analysis

An end-to-end data science project analyzing Amazon product data to explore which product characteristics are associated with higher monthly sales.

## Project Overview

This project examines a dataset of more than 42,000 Amazon products and focuses on the relationship between monthly sales and factors such as product rating, reviews, pricing, discounts, sponsorship, and product category.

The analysis progresses from exploratory data analysis and statistical testing to supervised machine learning and unsupervised clustering.

## Research Question

**Which product characteristics are associated with higher monthly sales on Amazon?**

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Jupyter Notebook / Google Colab

## Project Structure

### 1. Exploratory Data Analysis
`01-exploratory-data-analysis.ipynb`

- Loaded and cleaned the Amazon products dataset
- Checked missing values and duplicate records
- Engineered additional pricing features
- Examined monthly sales and discounted-price distributions
- Compared sponsored and non-sponsored products
- Analyzed sales across product categories and price groups

### 2. Statistical Analysis
`02-statistical-analysis.ipynb`

- Performed hypothesis tests to examine relationships with monthly sales
- Compared sponsored and non-sponsored products
- Compared products with different discount levels
- Tested associations between sponsorship, category, and high-sales status
- Used regression analysis to examine pricing, discounts, and ratings

### 3. Machine Learning
`03-machine-learning.ipynb`

- Built classification models to identify high-sales products
- Evaluated Logistic Regression with L1 and L2 regularization
- Evaluated Elastic Net and Random Forest models
- Compared model performance using classification metrics
- Random Forest achieved approximately **95.6% accuracy** and **96.5% F1 score**

### 4. Clustering Analysis
`04-clustering-analysis.ipynb`

- Applied unsupervised learning to identify product groups
- Used the elbow method to evaluate the number of clusters
- Selected **K = 3** for K-Means clustering
- Compared cluster characteristics to identify different product patterns

## Key Findings

The analysis found statistically significant relationships between several product characteristics and sales. Sponsorship and discount levels showed meaningful differences in sales, while product category was also associated with high-sales status. Regression results suggested that price had a negative relationship with sales while discount percentage had a positive relationship, although the regression models had relatively low explanatory power.

The machine-learning stage showed that product characteristics could be used to classify high-sales products effectively, with Random Forest producing the strongest performance among the tested models.

The clustering stage identified three broader product groups with different combinations of sales, discounts, and review activity.

## Dataset

Amazon Products Sales Dataset (42K+ products, 2025).

The analysis uses product information including:

- Product rating
- Total reviews
- Monthly purchases
- Discounted price
- Original price
- Discount percentage
- Sponsorship status
- Product category

## Skills Demonstrated

Data cleaning, exploratory data analysis, data visualization, feature engineering, statistical hypothesis testing, regression analysis, classification, model evaluation, and unsupervised machine learning.

## Repository Files

- `01-exploratory-data-analysis.ipynb`
- `02-statistical-analysis.ipynb`
- `03-machine-learning.ipynb`
- `04-clustering-analysis.ipynb`

---

This project was developed as a multi-stage data science analysis and has been organized here as a portfolio project.
