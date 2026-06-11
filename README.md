# Global Sales Performance Insights 📊

An executive-level Power BI dashboard engineered to translate complex global retail data into actionable business strategy. This project features an end-to-end analytics pipeline, utilizing Python for data cleaning and engineering, and Power BI/DAX for interactive visual intelligence and data modeling.

---

## 🖥️ Dashboard Preview

![Global Sales Performance Insights Dashboard]
*Note: Clean, high-contrast, cinematic dark-themed UI designed to reduce cognitive load and emphasize key metrics.*

---

## 🚀 Interactive Links
* 🌐 **Live Interactive Dashboard:** *(publish to Power BI Service and add link here)*
* 📂 **Dataset Source:** [Global Retail / Superstore Transactional Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
* 📊 **Local Dataset:** [`Data/global_retail_sales.xlsx`](Data/global_retail_sales.xlsx)

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Data Engineering & Cleaning:** Python (Pandas, NumPy), Power Query
* **Data Modeling & Analytics:** Power BI Desktop, DAX (Data Analysis Expressions)
* **UI/UX & Visualization:** Advanced Charting, Dual-Axis Visualizations, Custom Theme Design

---

## 🔧 Core Project Workflow

### 1. Data Cleaning & Preprocessing (Python & Power Query)
* Handled missing values, verified structural consistency, and formatted date dimensions (`Order Date`, `Ship Date`).
* Optimized schema attributes by disabling unnecessary auto-summations on non-additive numeric fields (like `Postal Code` and `Row ID`) to ensure strict data integrity.
* Structured categorical variables (`Segment`, `Region`, `Category`, `Sub-Category`) for seamless cross-filtering performance.

### 2. Data Modeling & DAX Formulation
* Developed explicit DAX measures to calculate overall performance metrics dynamically.
* Structured hierarchical date tables to enable time-series slicing across multi-year horizons (2015–2019).

### 3. Visual Engineering & UI/UX Design
* **Executive KPIs:** Implemented high-level cards for quick-glance tracking of **Total Sales (2M)** and **Product Offerings (9,800)**.
* **Geographic Breakdown:** Utilized tree-maps and volume trend lines to highlight regional dominance, isolating the **West Region (710K)** as the top revenue driver.
* **Dual-Axis Sub-Category Analysis:** Engineered a complex combo chart tracking **Category Volumes** simultaneously against **Total Sales** to instantly separate high-volume transactional items from high-value revenue drivers.

---

## 📈 Key Business Insights

* **Segment Distribution:** The **Consumer Segment** represents the primary growth engine, commanding **50.76%** of total global sales, followed by Corporate (30.44%) and Home Office (18.79%).
* **Regional Disparities:** While individual states like California and New York dominate single-state volume profiles, the **West** and **East** geographic regions command the overwhelming majority of market share compared to the South.
* **Product Mix Strategy:** Deep-dive analysis reveals that high-volume sub-categories like *Binders* and *Paper* maintain lower individual price points, whereas *Phones* and *Chairs* serve as the core anchors for high-value revenue injection.

---

## 📂 Repository Structure
```text
├── Data/
│   └── global_retail_sales.xlsx   # Source transactional sales dataset
├── Scripts/                       # Python scripts / Jupyter Notebooks for data preprocessing
├── Global_Sales_Insights.pbix     # Power BI Desktop project (dashboard + data model)
├── .gitignore
└── README.md
```

---

## 🏁 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/pareekmannu/Global-Sales-Performance-Insights.git
   cd Global-Sales-Performance-Insights
   ```
2. **Open the dashboard** — Launch `Global_Sales_Insights.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. **Refresh data (if needed)** — Point the report data source to `Data/global_retail_sales.xlsx` if the file path differs on your machine.
