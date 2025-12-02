# Customer Segmentation Using K-Means Clustering

A machine learning project that demonstrates customer segmentation using K-Means clustering on mall customer data.

## Overview

This project analyzes customer data to identify distinct market segments based on:
- **Annual Income**
- **Spending Score**

Using K-Means clustering with different values of K (3, 4, and 5), we identify the optimal number of customer segments and provide actionable business insights.

## Dataset

- **Source**: [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Records**: 200 customers
- **Features**: CustomerID, Gender, Age, Annual Income, Spending Score

## Key Findings

The analysis reveals **5 distinct customer segments**:

| Segment | Description | Business Strategy |
|---------|-------------|-------------------|
| Premium | High income, High spending | VIP programs, exclusive offers |
| Careful | High income, Low spending | Targeted quality marketing |
| Enthusiastic | Low income, High spending | Flexible payment options |
| Budget | Low income, Low spending | Discounts, value products |
| Average | Medium income, Medium spending | General promotions |

## Technologies Used

- Python 3
- Pandas & NumPy
- Scikit-learn (K-Means, StandardScaler)
- Matplotlib & Seaborn

## How to Run

1. Clone this repository
2. Open `Customer_Segmentation_KMeans_Clustering.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells

## License

This project is open source and available for educational purposes.

