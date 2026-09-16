# Inventory & Supply Chain Dashboard

A good dashboard isn't just about attractive visuals — it should turn operational noise into clear action. This project brings scattered supply-chain data into one interactive view so decision-makers can spot bottlenecks, track inventory health, and know exactly where attention is needed.

## 🔍 Key KPIs & Insights

- **Warehouse Utilization:** 34.08%
- **Days Sales of Inventory (DSI):** 15.56 days
- **Inventory Turnover:** 23.47
- **Backorders:** 838 Fulfilled | 248 Pending | 114 Cancelled
- Transportation cost analysis by Region & Category
- Units sold trend across years
- Lead-time analysis by product category
- Inventory levels by Category & Region
- Interactive filtering by Region and Category (slicers)

## 📊 Dashboard Views

| Visual | Description |
|---|---|
| Warehouse Utilization Gauge | Tracks current utilization against a 75% target, highlighting available capacity |
| Days Sales of Inventory & Turnover Cards | Summarize how quickly inventory moves and converts to sales |
| Transportation Cost by Region & Category | Compares logistics spend across North, West, East, South for each product category |
| Units Sold by Year | Shows sales volume trend from 2020–2024 |
| Average Lead Time by Category | Breaks down fulfillment lead time across Accessories, Electronics, Furniture, and Clothing |
| Backorder Count by Order Status | Splits orders into Fulfilled, Pending, and Cancelled to flag fulfillment risk |
| Inventory Level by Category & Region | Shows stock distribution across regions and categories |

## 🎛️ Filters

- **Region:** North / South / East / West / All
- **Category:** Accessories / Clothing / Electronics / Furniture / All

## 💡 Insights

- Warehouse space is significantly underutilized (34.08% vs. a 75% target), pointing to consolidation opportunities.
- Units sold nearly quadrupled between 2020 and 2022 before plateauing — worth investigating for saturation or demand shifts.
- ~72% of orders are fulfilled on time, but pending and cancelled orders together (~31%) represent meaningful fulfillment risk.
- Lead times stay consistent (~15–17 days) across categories, indicating standardized supplier and logistics performance.

## 🛠️ Tech Stack

- **Power BI** — data modeling, DAX measures, and interactive dashboard visuals
- **Excel / CSV** — source inventory and supply chain dataset

## 📁 Repository Contents

```
├── Inventory_and_SCM.pbix      # Power BI dashboard file
├── dataset/                    # Source data
├── dashboard_preview.png       # Dashboard screenshot
└── README.md
```

## 🚀 How to Use

1. Clone this repository
2. Open `Inventory_and_SCM.pbix` in Power BI Desktop
3. Use the Region and Category slicers to filter the dashboard by segment
4. And below is the dashboard .
<img width="377" height="235" alt="Screenshot 2026-09-17 013359" src="https://github.com/user-attachments/assets/fcdc00f2-f936-4bb3-b279-0cf624dc35fb" />

   
## 👩‍💻 Author

**Anshikha Chaurasiya**
[LinkedIn](https://linkedin.com/in/anshikha-chaurasiya-24681328a) · [GitHub](https://github.com/anshikhachaurasiya)
