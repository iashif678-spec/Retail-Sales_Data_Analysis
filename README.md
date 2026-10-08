# 📊 Retail Sales Data Analysis using Python

## 📌 Project Overview

This project focuses on analyzing retail sales data using **Python** to identify sales trends, profitability, product performance, customer distribution, regional performance, and payment preferences.

The goal of this project is to transform raw sales data into meaningful **business insights** using data cleaning, analysis, visualization, and exploratory data analysis (EDA).

---

## 🎯 Project Objectives

* Analyze overall sales and profit performance
* Identify the best-performing product categories
* Analyze sub-category performance
* Understand monthly sales and profit trends
* Identify top-performing states and cities
* Analyze customer payment preferences
* Identify products/sub-categories generating losses
* Create meaningful visualizations for business insights

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **GitHub**

---

## 📂 Dataset

The project uses two datasets:

### 1. Orders Dataset

Contains information related to customer orders.

Main columns:

* Order ID
* Order Date
* CustomerName
* State
* City

### 2. Details Dataset

Contains detailed information about products and transactions.

Main columns:

* Order ID
* Category
* Sub-Category
* Amount
* Profit
* Quantity
* Payment Mode

The two datasets were combined using **Order ID** for analysis.

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Checked dataset structure
* Checked missing values
* Checked duplicate records
* Converted date columns into appropriate datetime format
* Verified data types
* Combined Orders and Details datasets

### 2. Overall Sales Performance

Key performance indicators calculated:

| KPI            |    Value |
| -------------- | -------: |
| Total Sales    | ₹437,771 |
| Total Profit   |  ₹36,963 |
| Total Quantity |    5,615 |
| Total Orders   |      500 |
| Profit Margin  |    8.44% |

---

## 📦 Category Analysis

Sales and profit were analyzed across three major categories.

| Category    |    Sales |  Profit | Quantity |
| ----------- | -------: | ------: | -------: |
| Clothing    | ₹144,323 | ₹13,325 |    3,516 |
| Electronics | ₹166,267 | ₹13,162 |    1,154 |
| Furniture   | ₹127,181 | ₹10,476 |      945 |

### Key Finding

**Electronics generated the highest sales**, while **Clothing had the highest quantity sold**.

---

## 🏷️ Sub-Category Analysis

Some of the top-performing sub-categories were:

| Sub-Category |   Sales | Profit |
| ------------ | ------: | -----: |
| Printers     | ₹59,252 | ₹8,606 |
| Saree        | ₹59,094 | ₹4,057 |
| Bookcases    | ₹56,861 | ₹6,516 |
| Phones       | ₹46,119 | ₹1,847 |

Some sub-categories generated negative profits:

* Furnishings
* Electronic Games
* Kurti
* Skirt
* Leggings

This indicates that these products may require further investigation regarding pricing, discounts, or costs.

---

## 📅 Monthly Sales & Profit Analysis

Monthly sales and profit were analyzed to understand seasonal trends.

### Sales Highlights

* **January:** ₹61,632
* **March:** ₹60,694
* **November:** ₹48,469
* **July:** ₹12,966

January recorded the highest monthly sales, while July recorded the lowest.

### Profit Highlights

* **November:** ₹10,253
* **January:** ₹9,684
* **February:** ₹8,465
* **May:** -₹3,730

November generated the highest profit, while May recorded the highest loss.

---

## 🗺️ Regional Analysis

### Top State

**Maharashtra**

* Sales: ₹102,498
* Profit: ₹6,963
* Quantity: 1,091

### Top City

**Indore**

* Sales: ₹63,680
* Profit: ₹6,763
* Quantity: 980

Maharashtra and Indore were among the strongest-performing locations in the dataset.

---

## 💳 Payment Mode Analysis

Payment modes were analyzed to understand customer preferences.

| Payment Mode |    Sales |
| ------------ | -------: |
| COD          | ₹155,181 |
| Credit Card  |  ₹86,932 |
| EMI          |  ₹77,881 |
| UPI          |  ₹68,641 |
| Debit Card   |  ₹49,136 |

### Key Finding

**Cash on Delivery (COD)** was the most commonly used payment mode based on sales amount.

---

## 📊 Visualizations

The project contains multiple charts to communicate the analysis clearly.

Visualizations include:

* Category Sales Analysis
* Category Profit Analysis
* Monthly Sales Trend
* Monthly Profit Trend
* Sub-Category Analysis
* State-wise Analysis
* City-wise Analysis
* Payment Mode Analysis

All charts are stored inside the **Charts** folder.

---

## 💡 Key Business Insights

1. Electronics generated the highest overall sales.
2. Clothing had the highest quantity sold.
3. Printers generated the highest profit among the highlighted sub-categories.
4. Some sub-categories generated negative profits and need attention.
5. November was one of the strongest months for profitability.
6. January recorded the highest monthly sales.
7. Maharashtra was the top-performing state.
8. Indore was the top-performing city.
9. COD was the most preferred payment mode by sales amount.
10. Overall profit margin was approximately **8.44%**.

---

## 📌 Business Recommendations

Based on the analysis:

* Focus on high-profit products such as Printers and Bookcases.
* Review pricing and discount strategies for loss-making sub-categories.
* Investigate reasons behind negative monthly profits.
* Strengthen sales strategies in high-performing states and cities.
* Analyze customer behavior across different payment modes.
* Develop targeted promotions during months with lower sales.
* Monitor product-level profitability instead of focusing only on sales volume.

---

## 📁 Project Structure

```text
Retail-Sales-Data-Analysis/
│
├── Dataset/
│   ├── Orders.csv
│   └── Details.csv
│
├── Charts/
│   ├── category_sales.png
│   ├── category_profit.png
│   ├── monthly_sales.png
│   ├── monthly_profit.png
│   ├── subcategory_analysis.png
│   ├── state_analysis.png
│   ├── city_analysis.png
│   └── payment_mode_analysis.png
│
├── Retail_Sales_Analysis.ipynb
│
└── README.md
```

> File names can be updated according to the actual files in the project folders.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/iashif678-spec/Retail-Sales-Data-Analysis.git
```

### Step 2: Open the Project

Open the project folder in **Jupyter Notebook, JupyterLab, or VS Code**.

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 4: Open the Notebook

Open:

```text
Retail_Sales_Analysis.ipynb
```

Run the notebook cells sequentially to reproduce the analysis and visualizations.

---

## 📈 Skills Demonstrated

This project demonstrates practical skills in:

* Python Programming
* Data Cleaning
* Data Manipulation
* Exploratory Data Analysis (EDA)
* Pandas
* NumPy
* Data Visualization
* Matplotlib
* Seaborn
* Business Insight Generation
* Data Storytelling
* GitHub Project Management

---

## 🚀 Future Improvements

Possible improvements for this project include:

* Building an interactive dashboard using **Power BI**
* Adding customer-level analysis
* Performing advanced statistical analysis
* Creating sales forecasting models
* Adding product-level profitability analysis
* Automating the data analysis pipeline

---

## 📝 Conclusion

This project demonstrates how Python can be used to convert raw retail transaction data into useful business insights.

Through data cleaning, exploratory analysis, KPI calculation, and visualization, the project provides a clear understanding of **sales performance, profitability, product categories, regional performance, monthly trends, and customer payment preferences**.

The analysis can help businesses identify high-performing products, understand loss-making areas, and make more informed data-driven decisions.

---

## 👨‍💻 Author

**Md Ashif**

Aspiring Data Analyst | Python | SQL | Excel | Data Visualization

GitHub: [iashif678-spec](https://github.com/iashif678-spec)

