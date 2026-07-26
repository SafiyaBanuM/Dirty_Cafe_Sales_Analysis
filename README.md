#  Dirty Cafe Sales Analysis

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on a dirty café sales dataset. The dataset contains missing values, invalid entries, and inconsistent data. The objective is to clean the data, analyze customer purchasing behavior, and visualize important business insights.

---

##  Objectives

- Explore the dataset
- Clean missing and invalid data
- Convert columns into appropriate data types
- Analyze sales patterns
- Visualize customer purchasing behavior
- Identify relationships between numerical variables

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

##  Dataset

The dataset contains information about:

- Transaction ID
- Item Purchased
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

---

## Data Cleaning

The following preprocessing steps were performed:

- Replaced invalid values (`ERROR` and `UNKNOWN`) with `NaN`
- Converted numeric columns using `pd.to_numeric()`
- Converted transaction dates using `pd.to_datetime()`
- Filled missing values in:
  - Payment Method
  - Location
- Calculated missing values in **Total Spent** using:

```
Total Spent = Quantity × Price Per Unit
```

- Removed rows with missing values in essential columns:
  - Item
  - Quantity
  - Price Per Unit
  - Transaction Date

---

##  Visualizations

The project includes:

-  Top Selling Cafe Items (Bar Chart)
-  Customer Purchase Location (Bar Chart)
-  Payment Method Distribution (Pie Chart)
-  Monthly Sales Trend (Line Chart)
-  Distribution of Total Spent (Box Plot)
-  Revenue by Item (Bar Chart)
-  Correlation Heatmap

---

##  Key Insights

- Juice was the most frequently sold item.
- Coffee sales were close to Juice.
- Customers preferred both In-store and Takeaway purchases almost equally.
- Digital Wallet, Cash, and Credit Card were widely used payment methods.
- Monthly sales trends highlighted changes in revenue over time.
- Revenue varied across different café items.
- Correlation analysis showed relationships among Quantity, Price Per Unit, and Total Spent.

---

##  Project Structure

```
Dirty_Cafe_Sales_Analysis/
│
├── dirty_cafe_sales.csv
├── cleaned_cafe_sales.csv
├── Dirty_Cafe_Sales_Analysis.py
├── README.md
```

---

##  How to Run

1. Clone the repository.

```
git clone <repository-link>
```

2. Install the required libraries.

```
pip install pandas numpy matplotlib
```

3. Run the Python script.

```
python Dirty_Cafe_Sales_Analysis.py
```

---

##  Learning Outcomes

Through this project, I learned:

- Data cleaning techniques
- Handling missing values
- Data type conversion
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib
- Correlation analysis
- Business insight generation

---

## Author

**Safiya Banu M**

Computer Science and Engineering Student

GitHub: https://github.com/SafiyaBanuM
