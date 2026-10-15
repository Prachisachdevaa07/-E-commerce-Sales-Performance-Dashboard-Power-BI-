# 🛒 E-Commerce Sales Dashboard

An interactive business intelligence dashboard that analyses e-commerce sales performance across geography, customers, payment methods, product categories and time. It helps stakeholders quickly see what is selling, where, to whom, and how profitable it is.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Metrics](#-key-metrics-kpis)
- [Dashboard Visuals](#-dashboard-visuals)
- [Interactive Filters](#-interactive-filters)
- [Key Insights](#-key-insights)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 🔍 Overview

The **E-Commerce Sales Dashboard** consolidates order data into a single-page report. It answers questions such as:

- How much revenue, quantity and profit are we generating?
- Which states and customers contribute the most sales?
- Which payment modes do customers prefer?
- Which product categories and sub-categories drive profit?
- How does profit vary month to month?

---

## 📊 Key Metrics (KPIs)

| Metric | Value | Description |
|---|---|---|
| **Sum of Amount** | 438K | Total sales revenue |
| **Sum of Quantity** | 5,615 | Total units sold |
| **Sum of Profit** | 37K | Total profit earned |
| **Sum of AOV** | 121K | Average order value (as shown on the dashboard) |

---

## 📈 Dashboard Visuals

| Visual | Chart Type | Purpose |
|---|---|---|
| Sum of Amount by State | Horizontal bar | Compare sales across states |
| Sum of Quantity by Payment Mode | Donut | Show payment preference (COD, UPI, Debit Card, Credit Card, EMI) |
| Sum of Amount by Customer Name | Column | Identify top customers by spend |
| Sum of Quantity by Category | Donut | Split of units sold by category (Clothing, Electronics, Furniture) |
| Sum of Profit by Month | Column | Track profit trend and spot loss-making months |
| Profit by Sub-Category | Horizontal bar | Rank sub-categories by profit |

---

## 🎛️ Interactive Filters

- **Quarter slicer** – Qtr 1 to Qtr 4
- **State** – filter by state
- **City** – filter by city

All visuals cross-filter, so selecting a quarter, state or city updates every chart and KPI card.

---

## 💡 Key Insights

- **Maharashtra** is the top state by sales amount, followed by **Madhya Pradesh**, **Uttar Pradesh** and **Delhi**.
- **Cash on Delivery (COD)** is the most-used payment mode, with UPI second.
- **Clothing** is the largest category by quantity (~4K units), well ahead of Electronics and Furniture (~1K each).
- **Printers** and **Bookcases** are the most profitable sub-categories.
- Profit is strongest in **January, February, March and November**, while **May, July, September and December** show losses.
- Top customers by spend are **Harivansh**, **Madhav**, **Madan Mohan** and **Shiva**.

> Insights are based on the dashboard's current filter selection (Qtr 2 appears selected in the preview).

---

## 🛠️ Tech Stack

- **Power BI** – dashboard design and interactivity (the layout and slicers suggest Power BI; update if you used another tool)
- **DAX** – measures such as Sum of Amount, Profit and AOV
- **Excel / CSV** – source dataset

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. **Open the dashboard file**
   - Open `E-Commerce Dashboard.pbix` in Power BI Desktop.
3. **Refresh the data** (if the source path has changed)
   - Go to **Home → Transform data → Data source settings** and point to the dataset in the `data/` folder.
4. **Explore**
   - Use the Quarter, State and City slicers and click any chart element to cross-filter.

---

## 📁 Project Structure

```
├── data/
│   └── ecommerce_sales.xlsx        # Source dataset
├── E-Commerce Dashboard.pbix       # Power BI report
├── dashboard.png                   # Dashboard screenshot
└── README.md
```

> Adjust file names to match your repository.

---

## 🔮 Future Improvements

- Add year-over-year and month-over-month comparisons
- Add a profit margin % KPI
- Add drill-through pages for customer and product detail
- Investigate loss-making months and sub-categories
- Publish to Power BI Service with scheduled refresh

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your Name](https://linkedin.com/in/your-profile)

---

⭐ If you found this project useful, consider giving it a star!
