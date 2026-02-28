# European Pharmacy Performance Analysis  

_Where revenue is generated, where profitability is concentrated, and where strategic growth opportunities exist across a European pharmacy network._

---

## 🏆 Recognition  

Selected as a **winning submission in the ZoomCharts Data Challenge**, recognized for analytical depth, interactive storytelling, and clear business insights.

---

## Quick Look  

- **Total Revenue (2024):** €8.63M  
- **2025 Performance:** Stronger Q2 & year-end growth vs 2024  
- **Top Revenue Markets:** Germany, France, Italy  
- **Underperforming Regions:** Poland, Austria  
- **Top Product Driver:** Legacy product portfolio  
- **Primary Profit Engine:** Urban pharmacies  
- **Dataset:** Internal challenge dataset (ZoomCharts Data Challenge)  
- **Interactive Dashboard:** [View Power BI Report](#)  
- **Full Analysis & Storytelling:** [Read on Medium](https://medium.com/@odzainab1/pharmacy-sales-insights-decoding-the-secrets-behind-revenue-profit-margins-and-units-sold-af45bf1351a0)  

---

## Introduction  

In a competitive pharmaceutical distribution landscape, performance is not defined by sales volume alone, but by how effectively **revenue, margin, and regional contribution align to drive sustainable growth**.

This project delivers a strategic analysis of daily pharmacy sales performance across countries, regions, pharmacies, and product hierarchies.

The objective was to uncover:

- Where value is truly created  
- Which regions and pharmacies drive profitability  
- Which product categories dominate  
- Where performance gaps require intervention  

---

## Business Problem  

The pharmacy network is generating strong sales, but leadership needs clarity on:

- Which countries contribute the most to revenue and margin  
- Whether growth in 2025 is sustainable  
- Which product lifecycle stages drive profitability  
- How promotions impact revenue and margin  
- Why certain pharmacies underperform  
- Whether urban dominance hides untapped suburban and rural opportunities  

The goal is to translate performance metrics into actionable strategy.

---

## Dataset & Tools  

### Dataset Structure (Star Schema Model)

**Fact Table — FactSales**
- SalesID  
- DateKey  
- PharmacyID  
- ProductID  
- UnitsSold  
- RevenueEUR  
- CostEUR  
- MarginEUR  
- PromoFlag  

**Dimension Tables**

- **DimDate:** Year, Quarter, Month, YearMonth  
- **DimPharmacy:** Country, Region, City, PharmacyType, StoreSizeBand, Coordinates  
- **DimProduct:** Category, Brand, Lifecycle Stage, LaunchDate, DiscontinuedStatus  

---

### Tools Used  

- **Power Query** – Data cleaning & transformation  
- **Power BI** – Data modeling, DAX measures, interactive dashboards  

---

## Data Preparation & Validation  

Before analysis, the dataset was validated for structural integrity and analytical readiness:

- Confirmed no missing values in fact and dimension tables  
- Validated uniqueness of SalesID, DateKey, PharmacyID, and ProductID  
- Standardized financial fields to two decimal precision  
- Verified MarginEUR = RevenueEUR − CostEUR  
- Ensured Revenue ≥ Cost across transactions  
- Validated one-to-many relationships between fact and dimension tables  

### Derived Analytical Metrics  

- Profit Margin %  
- Revenue per Unit  
- Cost per Unit  
- Profit per Unit  
- Product Profitability Classification:
  - High Volume / Low Margin  
  - Low Volume / High Margin  

Time dimension enhancements enabled:
- Year-over-Year comparison  
- Seasonal trend analysis  
- Monthly and quarterly reporting  

**Result:** A clean, structured, and analysis-ready data model.

---

## Data Visualization 
![Pharmacy-1_page-0001](https://github.com/user-attachments/assets/e1a4e172-dc1d-49a6-b1b0-3e4000362812)
<img width="1337" height="740" alt="Screenshot 2026-03-01 005412" src="https://github.com/user-attachments/assets/1c23e925-79dd-4399-b18a-220f9e447328" />
<img width="1343" height="756" alt="Screenshot 2026-03-01 005839" src="https://github.com/user-attachments/assets/4d6ec85a-cb78-481c-bbea-afff1bf22ea8" />

---

## 🎨 Dashboard Experience  

The dashboard includes a built-in **Light/Dark theme toggle**, allowing users to switch between visual styles based on preference.

This improves:
- User experience and accessibility  
- Readability in different environments  
- Presentation flexibility for stakeholders  

The toggle enhances interactivity while maintaining consistent data integrity across both themes.

---
## Data Insights  
### 1️⃣ 2025 Shows Stronger Growth Momentum  

- Q2 and December 2025 outperformed 2024  
- April 2025 became the highest revenue month  
- December 2025 recorded the strongest unit sales  
- Growth is more consistent compared to 2024  


### 2️⃣ Legacy Products Dominate Performance  

- Highest revenue contribution  
- Highest gross profit contribution  
- Highest unit sales  

Short-term profitability remains highly dependent on legacy product strength.



### 3️⃣ Regional Contribution Patterns  

Top Revenue & Profit Drivers:
- Germany  
- France  
- Italy  

Underperforming Markets:
- Poland  
- Austria  

Western Europe remains the revenue backbone, while Central and Eastern Europe show expansion opportunities.



### 4️⃣ Urban Pharmacies Drive Performance  

Urban pharmacies lead across:
- Revenue  
- Gross Profit  
- Units Sold  

However, suburban and rural pharmacies represent untapped growth potential.


### 5️⃣ Promotion Impact  

- Non-promoted products drive majority of revenue and units  
- Promoted products show stronger margin efficiency  
- Balanced strategy between volume and profitability is required  



### 6️⃣ Volume vs Margin Trade-Off  

The analysis reveals two strategic product groups:

- High Volume / Low Margin products sustain revenue flow  
- Low Volume / High Margin products maximize profitability  

Portfolio optimization requires balancing both.

---

## Summary  

- 2025 demonstrates stronger and more consistent growth than 2024.  
- Legacy products remain the financial backbone of the network.  
- Germany, France, and Italy dominate performance.  
- Poland and Austria present strategic growth opportunities.  
- Urban pharmacies drive profitability, but expansion potential exists in suburban and rural areas.  
- A balanced mix of high-volume and high-margin products is critical for sustained growth.

The pharmacy network is performing strongly, with clear areas for strategic improvement.

---

## Recommendations  

1. **Prioritize Legacy Product Optimization**  
   Protect and maximize high-performing SKUs.

2. **Strengthen Underperforming Regions**  
   Deploy targeted promotional campaigns in Poland and Austria.

3. **Expand Suburban & Rural Strategy**  
   Tailor product mix and pricing strategies for smaller markets.

4. **Balance Volume & Margin Strategy**  
   Avoid over-reliance on high-volume/low-margin products.

5. **Develop New Product Lifecycle Strategy**  
   Increase margin focus on newer product lines for long-term growth.

6. **Implement Regional KPI Monitoring**  
   Track revenue and margin concentration across geographic markets.

---


