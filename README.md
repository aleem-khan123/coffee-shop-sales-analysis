# Coffee Shop Sales Analysis

A Data Analytics and Machine Learning project that analyzes coffee shop sales data to identify profitable products, detect loss-making items, predict future sales, and provide data-driven business recommendations. The project combines data cleaning, exploratory analysis, predictive modeling, and time series forecasting to support better business decision-making.

---

## 📌 Project Overview

This project analyzes transactional sales data from a coffee shop to uncover valuable business insights. It focuses on identifying top-performing products, evaluating profitability, forecasting future sales, and recommending strategies to improve revenue and reduce losses.

The project includes:

- Data Cleaning & Preparation
- Profitability Analysis
- Exploratory Data Analysis (EDA)
- Predictive Modeling
- Time Series Forecasting
- Business Recommendations

---

## 📊 Dataset

- **Dataset:** Coffee Shop Sales Dataset
- **Analysis Period:** January 2023 – June 2023

### Features Included

- Transaction Date
- Transaction Time
- Store Location
- Product Category
- Product Name
- Transaction Quantity
- Unit Price
- Total Price
- Profit

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels (ARIMA)

---

## Project Workflow

### 1. Data Cleaning & Preparation

The dataset was prepared using the following steps:

- Converted dates into datetime format
- Created Total Price column
- Estimated product profit
- Removed duplicate records
- Verified missing values
- Saved cleaned dataset for analysis

---

### 2. Profitability Analysis

Performed business analysis to identify:

- Top-selling products
- Most profitable products
- Loss-making products
- Revenue by product category
- Profit margin by category

---

### 3. Predictive Modeling

A Linear Regression model was developed to estimate transaction profit.

**Features Used**

- Transaction Quantity
- Unit Price
- Store Location
- Product Category

Categorical variables were encoded using One-Hot Encoding before training.

---

### 4. Time Series Forecasting

Monthly sales were aggregated and forecasted using the **ARIMA (1,1,1)** model.

The model predicts sales for the next six months to support inventory planning and business decisions.

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|-------:|
| Total Sales Revenue | $789,812.08 |
| Total Profit | $236,549.63 |
| Average Profit Margin | 30.0% |
| Top-Selling Product | Sustainably Grown Organic Lg |
| Most Profitable Product | Sustainably Grown Organic Lg |
| Lowest Performing Product | Dark Chocolate |
| Forecasted Sales (July 2023) | $182,539.18 |

---

## 📊 Model & Forecast

### Predictive Model

**Algorithm**

- Linear Regression

### Time Series Model

- ARIMA (1,1,1)

The forecasting model predicts future monthly sales trends, helping businesses optimize inventory, staffing, and promotional strategies.

---

## 📈 Key Findings

- Coffee generated the highest revenue and overall profit.
- Tea and Drinking Chocolate products showed comparatively lower profit margins.
- Several low-priced products contributed minimal profit.
- Sales forecasts indicate continued business growth over the coming months.
- Product category and unit price significantly influenced profitability.

---

## 💼 Business Recommendations

### Increase Profit

- Promote top-performing products.
- Introduce bundle offers for high-margin items.
- Improve pricing strategy for mid-performing products.

### Reduce Losses

- Review pricing of low-profit products.
- Optimize inventory for low-demand items.
- Plan staffing and stock using forecasted sales.

---

## 📊 Visualizations

The project includes visualizations such as:

- Product Performance Analysis
- Top Profitable Products
- Loss-Making Products
- Revenue by Category
- Profit Margin Analysis
- Monthly Sales Trend
- Six-Month Sales Forecast

---

## 🚀 Project Highlights

- Analyzed thousands of sales transactions.
- Built a profit prediction model using Linear Regression.
- Forecasted future sales using ARIMA.
- Generated actionable business recommendations.
- Combined business analytics with machine learning techniques.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/coffee-shop-sales-analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the analysis and forecasting.

---

## 💡 Future Improvements

- Experiment with Random Forest and XGBoost for profit prediction.
- Apply advanced forecasting models such as Prophet or LSTM.
- Build an interactive Power BI or Tableau dashboard.
- Deploy the project using Streamlit.

---

## 👨‍💻 Author

**Aleem Shoukat**

Data Science Intern – Digital Empowerment Network (DEN)

📧 Email: aleemshoukat91@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/aleem-shoukat-9bb3b6356/

### Skills Demonstrated

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis (EDA)
- Business Analytics
- Machine Learning
- Linear Regression
- Time Series Forecasting
- ARIMA
- Data Visualization

---

## 📜 Internship Information

**Organization:** Digital Empowerment Network (DEN)

**Internship:** Data Science Internship

**Task:** Task 04 – Coffee Shop Sales Analysis

---

If you found this project useful, feel free to ⭐ star this repository.
