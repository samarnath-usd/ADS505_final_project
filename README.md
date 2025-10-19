# 📊 E-commerce Customer Segmentation and Prediction

## Project Summary

This repository contains the full code and analysis for the final project on **E-commerce Customer Segmentation and Prediction**. The goal of this project was to leverage machine learning techniques to gain a deeper understanding of customer value and purchasing behavior, enabling the business to implement highly targeted marketing and retention strategies.

## Key Deliverable

The main deliverable in this repository is the **`E_commerce_Customer_Segmentation_Notebook.ipynb`** (or your actual notebook filename), which serves as the **Technical Notebook**.

## Methodology Overview

The project followed a two-pronged data science approach:

1.  **Customer Segmentation (Unsupervised Learning):**
    * **Feature Engineering:** **Recency, Frequency, and Monetary (RFM) Analysis** was used to quantify customer value.
    * **Clustering:** **K-Means Clustering** was applied to the scaled RFM features to partition the customer base into three distinct behavioral segments: **Champions, Potential Customers, and At Risk/Churned.**
2.  **Purchase Prediction (Supervised Learning):**
    * **Modeling:** **Logistic Regression** and **Random Forest Classifiers** were compared to predict a customer's likelihood of making a future purchase within a 90-day window.
    * **Performance:** The **Logistic Regression** model was selected as the best performer, achieving a cross-validated **ROC AUC of 0.750**, providing a reliable tool for forecasting customer activity.

## How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/samarnath-usd/ADS505_final_project.git](https://github.com/samarnath-usd/ADS505_final_project.git)
    ```
2.  **Install Dependencies:** Ensure all required Python packages (e.g., pandas, numpy, scikit-learn, matplotlib, seaborn) are installed.
3.  **Run the Notebook:** Open the Jupyter Notebook (`E_commerce_Customer_Segmentation_Notebook.ipynb`) and execute all cells sequentially.
