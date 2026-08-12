# Brazilian E-Commerce Data Analysis

## 📌 Project Overview

This project analyzes a real-world Brazilian e-commerce dataset to explore customer behavior, order performance, payment patterns, product categories, reviews, and delivery performance.

The project focuses on the complete data analysis workflow, from **data understanding and data wrangling to exploratory data analysis, visualization, and business insights**.

The analysis is currently **under development**, with the data wrangling and data quality assessment stages completed and exploratory/business analysis in progress.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and relationships between multiple e-commerce datasets.
- Assess and improve data quality before performing analysis.
- Identify patterns in customer and order behavior.
- Analyze sales, payment, product, review, and delivery characteristics.
- Develop meaningful visualizations and KPIs.
- Translate analytical findings into actionable business insights.

---

## 📊 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**, which contains information about approximately **100,000 orders** made through an e-commerce platform in Brazil.

The dataset consists of multiple interconnected tables:

| Dataset | Description |
|---|---|
| Customers | Customer information and location identifiers |
| Orders | Order status and order lifecycle timestamps |
| Order Items | Products included in each order |
| Order Payments | Payment methods, installments and payment values |
| Order Reviews | Customer reviews and ratings |
| Products | Product characteristics and categories |
| Sellers | Seller information and location |
| Geolocation | Brazilian zip-code and geographical information |
| Category Translation | Portuguese-to-English product category mapping |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **SQL**

---

## 🔍 Data Wrangling & Data Quality

Before conducting the analysis, each dataset was individually examined to understand its structure, variables, data types, and relationships with the other tables.

The data-cleaning process included:

- Missing-value assessment
- Duplicate detection
- Data-type validation and conversion
- Consistency checks
- Unique-value analysis
- Identification of potential spelling inconsistencies
- Validation of primary and foreign-key relationships
- Timestamp conversion
- Translation of Portuguese product categories into English

### Data Quality Findings

Several data-quality issues were identified during the investigation, including:

- Duplicate records in the geolocation dataset.
- Repeated `review_id` values associated with different orders.
- Multiple reviews associated with the same order.
- Missing delivery timestamps for a small number of delivered orders.
- Delivery timestamps associated with some canceled orders.
- One delivered order without a corresponding payment record.

Rather than automatically removing or imputing these observations, the project investigates their potential causes and assesses their relevance to the subsequent analysis.

---

## 📈 Exploratory Data Analysis

**Currently under development.**

The EDA stage will investigate:

- Order volume over time
- Customer purchasing behavior
- Sales and payment trends
- Payment methods and installment patterns
- Product category performance
- Customer review scores
- Delivery performance
- Order cancellations
- Repeat customer behavior

---

## 💡 Business Questions

The analysis will attempt to answer questions such as:

- How has order volume changed over time?
- Which product categories generate the most sales?
- Which payment methods are most commonly used?
- How do installments relate to order value?
- What factors are associated with lower review scores?
- How does delivery performance affect customer satisfaction?
- What proportion of customers make repeat purchases?
- Which categories or sellers perform particularly well?

---

## 📊 Visualizations

**Coming soon.**

Visualizations will focus on communicating business-relevant patterns and insights.

---

## 🔑 Key Insights

**Coming soon.**

The final section will summarize the most important findings and translate them into potential business recommendations.

---

## 📁 Project Structure

```text
Brazilian Ecommerce Analysis/
│
├── data/
│   ├── raw/                # Original dataset (not included in repository)
│   └── processed/          # Cleaned datasets
│
├── notebooks/
│   ├── 01_data_wrangling.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   └── ...
│
├── .gitignore
├── README.md
└── ...
```

---

## 🚧 Project Status

**Status: In Development**

### Completed

- [x] Dataset exploration
- [x] Understanding table relationships
- [x] Primary/foreign key assessment
- [x] Missing-value assessment
- [x] Duplicate detection
- [x] Data-type validation
- [x] Data cleaning and transformation
- [x] Product category translation

### In Progress

- [ ] Exploratory Data Analysis
- [ ] Business KPI development
- [ ] Data visualization
- [ ] Business insights
- [ ] Final recommendations

---

## 👤 Author

**Konstantinos Klettas**

Physics graduate with a specialization in Astrophysics, currently developing skills in **Data Analysis, Python, SQL, and Business Analytics**.
