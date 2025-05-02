# Instacart Market Basket Analysis

**Predicting Reorders & Suggesting Personalized Product Bundles**

## Overview
This project analyzes over 3 million Instacart orders to build a recommender system that helps retailers:

- Predict which products users are likely to reorder
- Suggest personalized product bundles based on shopping behavior

The final solution combines user-level behavioral analysis with association rule mining to generate both individual recommendations and frequently purchased item sets.

---

## Objectives
1. **Predict Reorders**  
   Build a personalized recommender system using reorder frequency and recency to suggest items each user is most likely to buy again.

2. **Suggest Product Bundles**  
   Use Market Basket Analysis (Apriori algorithm) to identify items frequently bought together and generate smart cross-sell opportunities.

---

## Dataset
- **Source:** [Instacart Market Basket Analysis (Kaggle)](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)
- **Size:** ~3.2 million orders across 200,000+ users and 50,000+ products

---

## Methodology

### Exploratory Data Analysis (EDA)
- Identified most ordered products, aisles, and departments
- Analyzed order frequency, reorder rates by category, and basket size distribution

### Market Basket Analysis
- Filtered top 50 products and 20,000 orders for performance
- Applied Apriori algorithm to discover frequent itemsets
- Generated association rules to uncover common bundles

### Personalized Recommender System
- Calculated reorder scores for each user-product pair
- Included both frequency and recency components
- Provided ranked recommendations and user behavior profiles

---

## How to Use This Notebook

### Option 1: Use the Attached Preprocessed Dataset
- If you’re using the `cleaned_full_instacart.parquet` file provided in this repo, you can **skip the data preprocessing section**.
- Start directly from the **EDA section** to explore the data and build the models.

### Option 2: Use Raw Instacart Dataset
- If you’re using the original Instacart dataset from Kaggle, you’ll need to **run the entire notebook from the beginning**, including downloading, merging, and cleaning the data.

---

## Try It Yourself
Open the Colab notebook here 👉 [Colab Link](https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK)

---

## 📎 Files Included
- `Final_Customer_Analytics_Instacart.ipynb` – Full Colab notebook
- `cleaned_full_instacart.parquet` – Cleaned dataset (optional, recommended)
- `README.md` – Project documentation

---

## 🙋‍♂️ Questions?
Feel free to open an issue or connect with me on GitHub!
