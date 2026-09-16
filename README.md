# Blinkit._sales_dashboard
# Blinkit Sales Analysis Dashboard

## 📌 Overview
An interactive **Power BI** dashboard analyzing sales performance for **Blinkit** (India's quick-commerce grocery delivery app). The report consolidates sales, item, outlet, and rating data into a single-page view with slicers for dynamic filtering.

## 🎯 Objective
To help business stakeholders understand:
- Overall sales performance and item-level trends
- How fat content, item type, and outlet characteristics influence sales
- Which outlet types, sizes, and locations (tiers) drive the most revenue
- How sales have trended across outlet establishment years

## 🧰 Tools Used
- **Power BI Desktop** — data modeling, DAX measures, and visualization
- **Power Query** — data cleaning and transformation

## 🗂️ Data Fields
The dataset includes attributes such as:
- Item Type, Item Fat Content, Item Visibility, Item Weight
- Outlet Identifier, Outlet Establishment Year, Outlet Size, Outlet Location (Tier), Outlet Type
- Sales, Rating

## 📊 Dashboard Components

**KPI Cards**
- Total Sales
- Average Sales: 
- No. of Items:
- Average Rating: 

**Visuals**
| Visual | Insight |
|---|---|
| Outlet Establishment (area chart) | Sales trend by the year outlets were established (2010–2020+) |
| Fat Content (donut) | Sales split between Low Fat and Regular items |
| Fat by Outlet (bar) | Low Fat vs. Regular sales broken down by location tier |
| Item Type (bar) | Sales ranked by item category — Fruits & Vegetables and Snack Foods lead |
| Outlet Size (donut) | Sales share by outlet size — Medium, Small, High |
| Outlet Location (bar) | Sales share by tier — Tier 3 leads, followed by Tier 2 and Tier 1 |
| Outlet Type (table) | Total sales, item count, average sale, average rating, and item visibility by outlet type |

**Filter Panel**
Slicers for **Outlet Location**, **Outlet Size**, and **Item Type** allow users to drill into specific segments of the business.

## 🔑 Key Insights
- **Fruits & Vegetables** and **Snack Foods** are the top-selling item categories.
- **Low Fat** items outsell **Regular** items across all outlet tiers.
- **Tier 3** locations generate the highest share of sales, followed by Tier 2 and Tier 1.
- **Supermarket Type1** outperforms other outlet types in total sales and item count.
- Sales by outlet establishment year peaked around outlets opened mid-decade, suggesting store maturity correlates with performance.

## 🚀 How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Use the **Filter Panel** on the left to slice by outlet location, size, or item type.
3. Click the tabs above the Item Type chart (**Total_sales, Average_Sales, no of items, average_rating**) to switch the metric being visualized.
4. Hover over any chart for tooltip details.

