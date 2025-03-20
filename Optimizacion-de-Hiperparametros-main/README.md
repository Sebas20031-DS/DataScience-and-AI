# Optimization of a k-NN Model for Classification

## Project Description

This repository contains the complete process of optimization and evaluation of a classification model based on k-Nearest Neighbors (k-NN). The model was trained using the customer personality analysis dataset available on Kaggle, and optimized through techniques such as GridSearch and RandomizedSearch.

The main goal was to build an efficient and simple model to predict customers' response to a marketing campaign.

---

## Repository Contents

- `Hyperparameter Optimization.ipynb`: Jupyter Notebook files with the analysis, optimization, and evaluation of the model.
- `Simple knn model.pkl`: Trained model saved as `.pkl` files.
- `README.md`: This file, which describes the project.

---

## Data Used

### Dataset Description

The dataset used is from [Kaggle: Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). This dataset contains demographic and consumption information about the customers, used to analyze behavior patterns and responses.

### Selected Variables
The following variables were chosen as relevant features:
- **Income**: The annual income of the customer.
- **MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds**: Spending in different product categories.
- **NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth**: Purchase behavior.

**Target Variable**:
- **Response**: The customer's response to the marketing campaign (1: Yes, 0: No).

---

## Selected Model

After evaluating multiple configurations, the simplest model was chosen.
