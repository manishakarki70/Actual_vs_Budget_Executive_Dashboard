# 📊 Actual vs Budget Executive Dashboard

## 🎯 Objective
Designed a dynamic **Actual vs Budget Executive Dashboard** in Power BI to provide a clear and insightful view of income and expense performance across projects. This dashboard enables finance and executive teams to:
- Monitor budget adherence in real time
- Identify underperforming or overspending projects
- Visualize year-over-year trends and variances

This project demonstrates practical financial reporting using **custom DAX**, **SVG visuals**, and **slicer-driven interactivity**.

---

## 🔍 Business Problem

Managing multiple projects involves tracking budgeted vs actual income and expenses. Stakeholders require:
- A monthly snapshot of budget utilization
- Year-over-year comparisons
- Quick identification of over/under-performing projects
- An intuitive executive-level summary with color-coded visuals

---

## 💡 Key Insights Delivered

- Identified projects with critical budget overruns or underspending.
- Visual alerts on both income and expense performance with dynamic variance indicators.
- Delivered year-over-year budget and actual trends to support strategic planning.
- Enabled drill-down by **Year**, **Month**, and **Project ID**.

---

## 📈 Dashboard Features

### 🎯 Executive KPIs (Top Section)
- **Total Income Actual vs Budget**
- **Total Expense Actual vs Budget**
- **% of Budget Used**
- Color-coded variance indicators for quick health check

### 📊 Visuals
- **Donut Chart (SVG)** showing Expense % & Income % of Budget
- **Progress Bar (SVG)** for Expense % & Income % of Budget
- **Bar Charts** comparing budget vs actual over multiple years
- **Project-wise Table** with:
  - Actual vs Budget
  - Variance (%)
  - Conditional bars

### 🎛 Filters
- Year
- Month
- Project ID

---

## 🔧 Advanced Custom Visuals (SVG in DAX)

This dashboard includes **hand-coded SVG visuals via DAX**, pushing the boundaries of native Power BI visuals.

### 🟢 Expense & Income Donut Chart
- Created using inline SVG rendered from DAX.
- Visualizes **% of Expense Budget** & **% of Income Budget** with dynamic animation and coloring:
  - 🟢 Green: <95% (on target)
  - 🟠 Amber: 95% (monitor)
  - 🔴 Red: >95% (overspent)

### 📊 Expense & Income Progress Bar
- Custom horizontal bar showing **% of Expense Budget reached** & **% of Income Budget achieved**.
- Dynamic coloring logic:
  - 🔴 Red: Under 95% (underperforming)
  - 🟠 Amber: At 95%
  - 🟢 Green: Over 95%

### ⚙️ Technical Highlights
- Used `SVG` within DAX measures to create dynamic visuals.
- Fully **responsive to filters** (Year, Month, Project).
- Lightweight and visually clean implementation.

---

## 🛠 Tools & Techniques

- **Power BI Desktop**: Data modeling, report layout, UX design
- **DAX**: Custom KPIs, variance %, YoY comparisons, SVG rendering
- **Power Query**: Basic transformations and date hierarchies
- **SVG in DAX**: Created animated gauges and bar charts from scratch
- **UX**: Clear sectioning, consistent colors, iconography, and tooltips

---

## 📈 Simulated Business Impact

- 25% faster identification of projects deviating from budget
- Increased awareness of underutilized budgets (highlighted green bars)
- Easier monthly and YoY financial reviews for project managers

---

![image](https://github.com/user-attachments/assets/cae2914f-0c23-487b-b75f-c33917108577)

