# 📊 Business Sales Intelligence Dashboard with Predictive Analytics

This project presents an end-to-end data analytics solution for analyzing business sales performance and predicting future sales trends. It combines data preprocessing, exploratory data analysis (EDA), machine learning, and dashboard visualization to generate actionable business insights.

The goal of this project is to simulate a real-world Business Intelligence (BI) workflow by transforming raw sales data into meaningful insights that support data-driven decision-making.

---

## 🛠️ Tools & Technologies

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Machine Learning:** Random Forest Regression
* **Visualization:** Google Sheets Dashboard
* **Version Control:** Git & GitHub

---

## 📂 Dataset Description

The dataset contains structured business sales records with the following features:

* Order_ID
* Date
* Region
* Category
* Product
* Sales
* Quantity
* Discount
* Profit

---

## 🔍 Project Workflow

### 1. Data Preprocessing

* Handled missing values and ensured data consistency
* Converted date columns into proper datetime format
* Encoded categorical variables using one-hot encoding

### 2. Exploratory Data Analysis (EDA)

* Analyzed sales trends over time
* Evaluated region-wise and category-wise performance
* Identified top-performing products
* Studied relationships between discount and profit

### 3. Feature Engineering

* Created model-ready dataset
* Selected relevant features for prediction
* Transformed categorical variables

### 4. Machine Learning Model

* Model Used: Random Forest Regressor
* Objective: Predict Sales
* Performance: **R² Score = 0.95**

### 5. Dashboard Development

* Built a Business Intelligence-style dashboard using Google Sheets
* Included KPI cards:

  * Total Sales
  * Total Profit
  * Total Orders
  * Average Discount
* Created pivot-based charts:

  * Sales by Region
  * Profit by Category
  * Top Products / Sales Trend

---

## 📊 Key Insights

* West region contributes the highest share of total sales
* Electronics category generates the highest profit
* Higher discount values tend to reduce overall profit margins
* A small group of top products drives the majority of revenue (Pareto effect)
* Sales trends indicate seasonal variation over time

---

## 📈 Dashboard Preview


Example:
![Dashboard](dashboard.png)

---

## 💡 Business Impact

* Helps businesses identify high-performing regions and products
* Supports pricing strategy optimization by analyzing discount impact
* Enables data-driven decision-making through KPI monitoring
* Provides predictive insights for future sales planning

---

## 🔗 Project Structure

* `Business_sales_data.csv` → Dataset
* `BUSINESS_SALES_INTELLIGENCE_DASHBOARD.ipynb` → Python code (EDA + ML model)
* `dashboard.png` → Dashboard preview
* `README.md` → Project documentation

---

## 👩‍💻 Author

**Shana Parveen KT**
Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you like this project

Feel free to star ⭐ the repository and connect with me!
