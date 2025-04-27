# Customer Purchase & Review Analysis

This project provides an end-to-end data analysis of customer purchase behavior and product performance [dataset](https://www.kaggle.com/datasets/atharvasoundankar/fashion-retail-sales) using a combination of **Python (Pandas, Matplotlib, Seaborn)** and **SQL (SQLite)**. It includes insights such as top-selling items, payment method trends, review rating distributions, and customer segmentation.

----------

## 📁 Dataset Overview

Column Name

Description

`Customer Reference ID`

Unique ID for each customer

`Item Purchased`

Name of the item bought

`Purchase Amount (USD)`

Total amount spent on the purchase

`Date Purchase`

Date of purchase (DD-MM-YYYY format)

`Review Rating`

Customer rating from 1 to 5 (nullable)

`Payment Method`

Payment type used (e.g., Cash, Credit Card)

----------

## 📊 Key Features & Analysis Performed

### ✅ Data Cleaning (Python)

-   Standardized column names
    
-   Converted date columns
    
-   Filled missing review ratings
    

### ✅ SQL-Based Analysis

-   Total sales and average review ratings
    
-   Revenue and purchase counts by item
    
-   Grouped sales by payment method and date
    
-   Top-rated products and customer segmentation
    

### ✅ Visualizations (Python)

-   Bar charts for:
    
    -   Most popular items
        
    -   Total sales by payment method
        
    -   Top-rated products
        
-   Line chart for:
    
    -   Sales trends over time
        
-   Histograms for:
    
    -   Review rating distributions
        
    -   Purchase frequencies
        
-   Scatter plot for:
    
    -   Purchase amount vs review rating
        

----------

## 📈 Insights Discovered

-   💰 **Credit Card** and **Cash** both contribute significantly to total sales.
    
-   👜 **Handbags** are among the most frequently purchased items.
    
-   🌟 **Wallets** have some of the highest average ratings.
    
-   📉 Customer reviews range between 2.0 to 4.7, with most ratings around 3.5–4.0.
    
-   🧍‍♂️ High-spending customers can be segmented and targeted differently than low-spending ones.
    

----------

## 🧰 Tech Stack

-   **Python**: `pandas`, `sqlite3`, `matplotlib`, `seaborn`
    
-   **SQL**: `SQLite` (via Python)
    
-   **Jupyter Notebook / .py Script**
    

----------

## 🔍 Future Improvements

-   Add product categories for deeper analysis
    
-   Integrate return/refund tracking
    
-   Build a dashboard using Plotly or Streamlit
    
-   Perform predictive modeling (e.g., CLV prediction, churn detection)
    

----------
