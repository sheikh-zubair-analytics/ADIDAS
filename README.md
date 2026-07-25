adidas-sales-analysis
# 📊 Adidas Sales Performance Analysis

A data analysis project exploring Adidas retail sales data to uncover trends in revenue, profitability, regional performance, and customer purchasing behavior using Python.

---

## 📌 Objectives

- Analyze Adidas sales data to understand overall business performance
- Identify top-performing products, regions, and cities
- Study the relationship between sales, profit, and pricing
- Analyze customer purchasing patterns and sales methods
- Derive meaningful insights to support data-driven decision-making

## 📖 Introduction

Adidas is a globally recognized brand known for its sportswear and footwear products. This project explores Adidas sales data using data analysis techniques and visualizations to uncover patterns, trends, and insights that support strategic business decisions.

## 🗂️ Data Source

| | |
|---|---|
| **Source** | [Kaggle](https://www.kaggle.com) — Adidas Sales Dataset |
| **Format** | Excel (`.xlsx`) |
| **Type** | Structured, real-world-like sales transaction data |

**Key fields:** Invoice Date, Retailer, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab / Jupyter Notebook

## 🧭 Project Structure

```
├── data/                 # Raw and cleaned dataset
├── notebooks/            # Jupyter/Colab notebooks with EDA & visualizations
├── images/               # Exported chart images
├── Adidas_Sales_Performance_Report.pdf    # Full analysis report
├── Adidas_Sales_Performance_Report.docx   # Editable report
└── README.md
```

## 🔄 Workflow

1. **Data Collection** — obtaining the Adidas sales dataset
2. **Data Cleaning & Preprocessing** — handling missing values, converting `Invoice Date` to datetime, creating a `Month` feature
3. **Exploratory Data Analysis (EDA)** — understanding data distribution and relationships
4. **Data Visualization** — bar, line, pie, and scatter charts comparing key variables
5. **Insight Generation** — interpreting graphs to identify trends and patterns
6. **Conclusion & Recommendations** — summarizing findings and suggesting business improvements

## 📈 Visualizations Included

| # | Chart | Type |
|---|---|---|
| 1 | Total Sales Over Time | Line |
| 2 | Sales by Region | Bar |
| 3 | Sales by Product | Bar |
| 4 | Sales vs Operating Profit | Scatter |
| 5 | Sales Method Contribution | Pie |
| 6 | Monthly Sales Trend | Line |
| 7 | Operating Margin by Product | Bar |
| 8 | Price vs Units Sold | Scatter |
| 9 | Sales by State | Bar |
| 10 | Top 10 Cities by Sales | Bar |
| 11 | Units Sold by Product | Bar |

## 💡 Key Insights

- Sales performance varies significantly across products and regions
- A small set of products (led by **Men's Street Footwear**) dominates revenue generation
- Profitability is not always proportional to sales — margin control matters
- Seasonal trends clearly affect monthly sales, with mid-year peaks
- Pricing has a strong impact on demand, with a mid-range "sweet spot"
- Sales are geographically concentrated — **West** region and cities like **Charleston** and **New York** lead
- **In-store** sales remain the dominant method (39.6%), though online has room to grow

## ✅ Recommendations

- Focus inventory and marketing investment on high-performing products, especially footwear
- Improve strategies and resource allocation in low-performing regions (Midwest, South)
- Optimize pricing around the mid-range sweet spot to balance volume and margin
- Invest further in the online sales channel while sustaining strong in-store performance
- Reduce costs and improve efficiency for lower-margin products
- Plan inventory and campaigns ahead of seasonal peak months

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/<your-username>/adidas-sales-analysis.git
cd adidas-sales-analysis

# Install dependencies
pip install pandas matplotlib seaborn openpyxl

# Run the notebook
jupyter notebook notebooks/adidas_sales_analysis.ipynb
```

## 📄 Reports

Full write-ups with charts and insights are available in this repo:
- `Adidas_Sales_Performance_Report.pdf`
- `Adidas_Sales_Performance_Report.docx`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

## 📜 License

This project is open-sourced for educational and portfolio purposes. Dataset usage follows Kaggle's terms.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
