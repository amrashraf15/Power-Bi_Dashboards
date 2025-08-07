# 🛒 Blinkit Sales Dashboard – Power BI Project

## 📌 Project Overview

This interactive **Power BI dashboard** analyzes and visualizes sales performance for **Blinkit**, a grocery and retail delivery service. The report leverages **DAX measures**, slicers, and clean design to break down sales data across multiple attributes including outlet size, location, type, and product details.

The dashboard is designed to help business users identify trends, optimize store performance, and better understand the product landscape.

## DEMO
https://github.com/user-attachments/assets/290b8801-4e7c-4986-b826-573466ea0e1c

---

## 📊 Dashboard KPIs

| Metric               | Value     |
|---------------------|-----------|
| **Total Sales**     | $1.20M    |
| **Average Sales**   | 140.99    |
| **Number of Items** | 9K        |
| **Average Rating**  | 3.92      |

These key metrics are dynamic and update instantly based on slicer selections.

---

## 🎛️ Filter Panel (Slicers)

Users can interactively filter the entire dashboard using the **Filter Panel** on the left:

- **Outlet Location Type** (Tier 1, 2, 3)
- **Outlet Size** (Small, Medium, High)
- **Item Type** (e.g., Dairy, Snack Foods, Canned, etc.)

---

## 📈 Visualizations & Insights

### 🕒 Outlet Establishment Trend
- A line chart showing total sales by **year of establishment**.
- Peaks in **2018 ($205K)** followed by decline till **2020**, with a slight recovery in **2022**.
- Helps identify how the age of outlet impacts sales.

---

### 🛍️ Sales by Outlet Location
- Bar chart comparing total sales by **Outlet Tiers**:
  - **Tier 3**: $472.13K
  - **Tier 2**: $393.15K
  - **Tier 1**: $336.40K
- **Tier 3** outlets contribute the highest sales (≈ 39%).

---

### 🧁 Item Type Analysis
Bar chart of **item types** sorted by total sales:

| Item Type            | Sales    |
|----------------------|----------|
| Fruits and Vegetables | $0.18M  |
| Snack Foods          | $0.18M  |
| Household Items      | $0.14M  |
| Frozen Foods         | $0.12M  |
| Dairy                | $0.10M  |

Enables users to understand **which categories contribute most to revenue**.

---

### ⚖️ Fat Content Distribution
A donut chart shows the split of sales by fat content:

- **Regular:** 65%
- **Low Fat:** 35%

Also includes a bar chart showing **Fat Content by Outlet Tier** for comparative analysis.

---

### 🏪 Outlet Size Breakdown
Pie chart shows:

- **High Size Outlets:** 42%
- **Medium:** 37%
- **Small:** 21%

This visualization helps in assessing how **outlet size affects sales and performance**.

---

### 🧾 Summary Table by Outlet Type

| Outlet Type        | Total Sales | Items | Avg Sales | Avg Rating | Visibility |
|--------------------|-------------|-------|-----------|------------|------------|
| Grocery Store      | $151.94K    | 1083  | 140.29    | 3.93       | 0.10       |
| Supermarket Type1  | $787.55K    | 5577  | 141.21    | 3.92       | 0.06       |
| Supermarket Type2  | $131.48K    | 928   | 141.68    | 3.93       | 0.06       |
| Supermarket Type3  | $130.71K    | 935   | 138.89    | 3.91       | 0.06       |

This gives a **side-by-side comparison** of each outlet type's performance in terms of:
- Revenue
- Average sales
- Ratings
- Item count
- Visibility

---

## 🛠 Tools & Techniques Used

### 💡 Power BI Features
- Slicers for interactivity
- Card visuals for KPIs
- Bar, Line, and Donut charts
- Summary tables with conditional formatting

### 📐 DAX Measures
- Total Sales
- Average Sales
- Number of Items
- Average Rating
- % of Total (for Tier and Fat Content)
- Item Visibility Score

---

## 🧠 Key Insights

- **Tier 3 outlets** outperform others in total sales.
- **Regular fat items** generate nearly twice the revenue of low-fat items.
- **Fruits, snacks, and household items** are top-performing categories.
- **Supermarket Type 1** dominates in terms of item count and revenue.
- Visibility score is **highest** for grocery stores, though they contribute less revenue.

---

## 📌 What I Learned

- How to design a user-friendly, insight-rich dashboard using Power BI.
- The power of **DAX** to dynamically calculate measures and KPIs.
- How to communicate business performance through **data storytelling**.
- Techniques to use slicers, filters, and visuals to enable deep data exploration.

---

## ✅ Conclusion

This Blinkit dashboard delivers a **comprehensive performance overview** of retail outlets, products, and locations. With **interactive filters, DAX-powered KPIs**, and a clean design, it empowers decision-makers to explore the data from multiple angles and drive meaningful actions.

