# 🛍️ Zara Sales — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-EDA-lightblue) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A comprehensive Exploratory Data Analysis (EDA) of Zara's product sales data — uncovering patterns in pricing, promotions, seasonal trends, product categories, and sales performance to support data-driven business decisions.

---

## 📁 Project Structure

```
Zara-Sales-EDA/
├── dataset/
│   └── Zara_sales_EDA.csv
├── Zara_EDA.ipynb
└── README.md
```

---

## 🎯 Objective

To analyze Zara's sales dataset and extract actionable business insights related to:
- Product pricing distribution and outliers
- Impact of promotions on sales volume
- Seasonal trends in pricing and demand
- Category-wise and position-wise product performance
- Relationship between price and sales volume

---

## 📊 Dataset Overview

| Feature | Description |
|---|---|
| `Product ID` | Unique identifier for each product |
| `Product Category` | Category of the product (e.g., Clothing, Accessories) |
| `price` | Listed price of the product |
| `Sales Volume` | Number of units sold |
| `Promotion` | Whether the product was on promotion |
| `season` | Season in which the product was listed |
| `Product Position` | Shelf/catalog position (New Collection, Bestseller, etc.) |

---

## 🔧 Tools & Libraries

- **Python** — Core programming language
- **Pandas** — Data loading, cleaning, and manipulation
- **NumPy** — Numerical operations
- **Matplotlib** — Base plotting
- **Seaborn** — Statistical visualizations

---

## 🧹 Data Cleaning Steps

- Identified and removed missing values using `dropna()`
- Checked and confirmed zero duplicate records
- Validated data types and column structure

---

## 📈 Visualizations

| Chart | Purpose |
|---|---|
| Histogram — Price Distribution | Understand price spread and skewness |
| Histogram — Sales Volume | Identify high vs low performing products |
| Count Plot — Product Category | Category dominance analysis |
| Count Plot — Promotion | Promotion frequency distribution |
| Box Plot — Price | Detect premium outlier products |
| Scatter Plot — Price vs Sales Volume | Explore price-demand relationship |
| Bar Plot — Average Price by Season | Seasonal pricing strategy |
| Bar Plot — Promotion vs Sales Volume | Measure promotion effectiveness |
| Heatmap — Sales Volume by Category & Season | Cross-dimensional performance view |
| Count Plot — Product Position | Catalog positioning distribution |

---

## 💡 Key Business Insights

1. **Clothing Dominance** — Zara's catalog is heavily concentrated in the Clothing category, reflecting its core fashion identity. However, this also signals category concentration risk if fashion trends shift rapidly.

2. **Long-Tail Sales Pattern** — A small group of hero products drives the majority of sales volume. Most products underperform, suggesting a need to identify and prioritize top SKUs for inventory and marketing.

3. **Weak Price-Volume Correlation** — Price and sales volume show a weak negative correlation (-0.34), indicating Zara's customers are driven by brand loyalty and product placement rather than price alone.

4. **Promotions Boost Sales — But Selectively** — Promoted products consistently outperform non-promoted ones. However, over-promotion risks diluting Zara's premium brand image. Strategic, targeted promotions on slow-moving stock would be more effective.

5. **Seasonal Pricing Variation** — Average prices differ across seasons, showing Zara actively adapts its pricing strategy to seasonal demand and collection cycles.

6. **Premium Outliers Exist** — Box plot analysis revealed several high-priced outlier products, representing a premium tier within Zara's otherwise moderate price range.

7. **Product Positioning Matters** — Distribution across New Collections, Bestsellers, and Core inventory reveals how Zara manages its catalog lifecycle and product discovery strategy.

8. **Sales Volume is Highly Skewed** — Only a limited number of products achieve extremely high sales, reinforcing the importance of identifying and scaling what works.

---

## ✅ Conclusion

This EDA revealed that Zara's sales performance is driven less by price competitiveness and more by brand positioning, promotional timing, and product placement strategy. The long-tail sales distribution highlights the critical need for hero product identification and inventory prioritization. Promotions are effective but must be deployed strategically to preserve brand premium perception. Seasonal imbalances present supply chain planning opportunities.

This analysis lays a strong foundation for further work including promotion ROI analysis, category-level sales forecasting, and product lifecycle tracking from New Collection to Bestseller.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Zara-Sales-EDA.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Zara_EDA.ipynb
   ```
4. Update the dataset path in the Data Loading cell if needed.

---

## 👤 Author

**Priyanshu**
- 📧 Connect on [LinkedIn](linkedin.com/in/priyanshu-bharti-a73a13318)
- 💻 More projects on [GitHub](https://github.com/priyanshu70-prog)

