
# Sales Analytics Dashboard

<p align="justify">
This Power BI dashboard presents a focused view of sales performance across products, regions, and time for a fictitious chocolate store. It has been designed to help users track revenue, profit, orders, and shipments while exploring product-level results with interactive filters and clear KPIs.
</p>

## Key Features

- **Data Preparation and Modeling**
  - Data imported and transformed using <b>Power Query</b> with standardized types and merged sources.
  - **Star-schema** data model with fact tables for sales, orders, and shipments and dimensions for product, country, and region.
  - **Date table** for creating effective time-based visualizations and calculations.
  - **DAX measures** includes Total Sales, Total Profit, Total Orders, Total Costs, Profit %, LBS %, MoM %, and trend calculations.
- **Core Visuals and Dashboard**
  - **KPI Cards** for Total Sales (**$34M**), Total Boxes Shipped (**$2M**), Total Profit (**$21M**), Total Orders (**6K**), and Total Costs (**$14M**  ). The cards also contain **reference labels** to provide sub information such as latest month's MoM %, total profit %, total sales, total low-box shipments (orders with less than 6 boxes) and Total orders/ LBS %.
  - **Time-Series Trend** using line chart to review sales, chocolate boxes, orders, profit, costs from **Mar 2024 to Jan 2025**.
  - **Shipments by Boxes** using a **Distribution chart (Histogram)**  with overall LBS percentage (**10.2%**) using a **Gauge chart**.
  - **Product Performance Table** showing Sales, Profit %, and directional arrows for quick benchmarking. The table can be switched to **Sales Person Performance** view using the **buttons** (implemented using bookmarks) under table header from the filter widget.
  - **Interactive Filters** for table views (Products and Salespersons), product categories (Bars, Bites, Other), countries, and regions (Americas, APAC, Europe).
  - **Consistent dark-mode** based color theme and **clutter free** dashboard for an effective visual appearance.

## Dashboard Insights

- **Performance Snapshot:** Sales reached **$34M** with **$21M** in profit and **$14M** in costs, and total orders were **6K**, which indicates a strong margin profile and sustained demand.
- **Monthly Momentum:** Sales in January contributed **$2M** and the **MoM change was 16.6%**, which shows healthy month-over-month growth in the latest period.
- **Shipments Mix:** Total shipments include a low-box segment of **624 shipments**, while the overall **LBS percentage is 10.2%**, which helps monitor packaging efficiency.
- **Top Products:** Several premium SKUs show **Profit % above 70%** (e.g., Smooth Silky Salty, Orange Choco), while tail products trend below **40–45%**, which suggests optimization opportunities.
- **Regional Exploration:** Filters enable quick comparisons across **countries and regions**, which makes it easy to identify where product mixes and margins perform best.

## Previews

#### 1. Data Model

![DM](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/Data%20Model.png)

#### 2. Dashboard with Product Table

![DashboardProductTable](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/DashboardProductsVew.png)

#### 3. Dashboard with Salespersons Table

![DashboardProductTable](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/DashboardSalespersonView.png)

#### 4. Usage of Filter Widget

![DashboardProductTable](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/Filtered%20Data.png)

#### 5. Interacted Dashboard

![InteractedDashboard](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/InteractedDashboard.png)

#### 6. Tooltip

![Tooltip](https://github.com/TSgthb/Power_BI_Projects/blob/main/Sales%20Analytics%20Dashboard/Images/Tooltip.png)

