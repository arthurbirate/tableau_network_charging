

# VoltCharge Networks — EV Charging Analytics | Tableau 
### Global Network Performance, Demand Patterns & Segmentation

![Global EV Charging Dashboard](Global%20Charging%20.png)

---

## Introduction

VoltCharge Networks is a fictional global provider of electric vehicle (EV) charging infrastructure, operating at the intersection of clean energy, smart mobility, and data analytics. The company manages a distributed network of charging stations across major cities and emerging markets, delivering reliable and scalable charging solutions while supporting sustainable urban transportation.

VoltCharge’s business model combines pay-per-session charging with subscription tiers (Basic and Premium), enabling a balance between high user volume and recurring revenue. With **20,000 customers**, **$13.30M in total revenue**, and an **average revenue per session of $265.91**, the company demonstrates strong monetization in high-demand urban environments.

---

## Problem Statement

VoltCharge Networks operates across diverse global markets with significant variation in demand, usage, and revenue performance. However, the company lacks a unified, data-driven framework to:

- Allocate infrastructure efficiently  
- Identify high-growth vs saturated markets  
- Optimize pricing and utilization  
- Maximize revenue across regions and customer segments  

This results in:
- Overutilization in high-demand regions  
- Underutilization in low-demand regions  
- Revenue concentration risk  
- Missed monetization and expansion opportunities  

---

## Objective

To analyze global EV charging data and uncover actionable insights that support:

- Infrastructure optimization  
- Market expansion strategy  
- Pricing efficiency  
- Customer growth and monetization  

---

# Analytical Insights

---

## 1. Global Energy Consumption Distribution (Macro Level Demand Analysis)

### Analysis  
Energy consumption ranges from **332,660 kWh to 5,558,444 kWh**, indicating a **~17x disparity** across regions.

High consumption is concentrated in:
- **USA and Canada (North America)**
- **Norway and Netherlands (Europe)**  

Emerging markets such as **India, China, and UAE** show moderate to growing consumption levels.

---

### Insight  
EV demand is **highly uneven globally**, with clear segmentation between:

- Mature, high-demand markets  
- Emerging, underdeveloped markets  

Consumption is strongly correlated with **economic development and infrastructure maturity**.

---

### Business Action  
- Optimize operations in mature markets  
- Expand infrastructure in emerging markets  
- Apply region-specific strategies for deployment  

---

## 2. Revenue Distribution by City (Revenue Concentration Analysis)

### Analysis  
- **Total Revenue:** $13.30M  
- Top cities:
  - Dubai (~$2.5M)  
  - Toronto (~$2.0M)  
  - Paris (~$2.0M)  

Top 3 cities contribute **~49% of total revenue**.

---

### Insight  
Revenue is **heavily concentrated in a few urban centers**, creating dependency on limited markets.

---

### Business Action  
- Diversify revenue sources across more cities  
- Replicate high-performing city models  
- Expand in similar high-demand urban environments  

---

## 3. Energy Consumption vs Revenue (Pricing Efficiency)

### Analysis  
Cities with similar energy usage (~3M–4M kWh) generate **different revenue levels**, indicating inconsistency.

---

### Insight  
There is a **misalignment between usage and revenue**, suggesting pricing inefficiencies.

---

### Business Action  
- Implement location-based pricing strategies  
- Optimize tariffs in high-demand areas  
- Align pricing with demand intensity  

---

## 4. Peak Demand Analysis (Sessions by Hour)

### Analysis  
- Morning peak: **~4,340 sessions (8 AM)**  
- Evening peak: **~5,055 sessions (6 PM)**  
- Off-peak: **~700 sessions**  

→ **~7x variation in demand**

---

### Insight  
Demand follows predictable **commuting patterns**, leading to peak congestion and off-peak underutilization.

---

### Business Action  
- Introduce time-based pricing  
- Optimize station availability during peak hours  
- Incentivize off-peak usage  

---

## 5. Customer Segmentation (Monetization Opportunity)

### Analysis  
- Basic: **70.03% (~14,006 users)**  
- Premium: **29.97% (~5,994 users)**  

---

### Insight  
Majority of users are **low-value customers**, indicating strong upsell potential.

---

### Business Action  
- Convert Basic users to Premium through targeted campaigns  
- Introduce subscription incentives  
- Increase customer lifetime value  

---

## 6. Customer Acquisition Trend (Growth Analysis)

### Analysis  
- January: **~1,038 users**  
- Peak (September): **~2,802 users**  
- December: **~2,438 users**  

→ **~170% growth from start to peak**

---

### Insight  
Growth is **non-linear and event-driven**, likely influenced by campaigns or external factors.

---

### Business Action  
- Identify drivers behind peak growth periods  
- Replicate successful acquisition strategies  
- Build predictable growth models  

---

## 7. Revenue Efficiency (Unit Economics)

### Analysis  
- **Avg Revenue per Session:** $265.91  
- **Total Revenue:** $13.30M  

---

### Insight  
Revenue per session is strong but critical for scaling profitability.

---

### Business Action  
- Improve revenue per session via pricing and subscriptions  
- Monitor as a core KPI for profitability  

---

# Business Impact

This analysis enables VoltCharge Networks to:

- Optimize infrastructure allocation globally  
- Reduce operational inefficiencies  
- Diversify revenue streams  
- Improve pricing strategies  
- Increase customer monetization  
- Support data-driven expansion decisions  

---

# Key Takeaway

This project transforms EV charging network data into actionable insights by identifying demand imbalances, revenue concentration risks, pricing inefficiencies, and customer monetization opportunities enabling smarter infrastructure, pricing, and growth strategies.



# Station & Vehicle Performance Segmentation — Analytical Insights

![Station & Vehicle Dashboard](vehicle-station.png)

---

## Problem Statement

While VoltCharge Networks has visibility into global demand and revenue, it lacks granular insight into:

- Which **station types** generate the highest returns  
- How **downtime impacts revenue performance**  
- Which **vehicle segments drive profitability**  
- Where operational inefficiencies reduce revenue potential  

This results in:
- Revenue loss due to station downtime  
- Suboptimal pricing across locations  
- Inefficient allocation of charging infrastructure by vehicle type  
- Missed opportunities to maximize high-value segments  

---

## Objective

To analyze station-level and vehicle-level performance in order to:

- Improve operational efficiency  
- Maximize revenue per session  
- Identify high-performing segments  
- Optimize infrastructure and pricing strategies  

---

# Analytical Insights

---

## 1. Revenue vs Downtime (Operational Efficiency)

### Analysis  
The scatter plot shows a **negative relationship between downtime and revenue**:

- High-revenue stations (~$2M+) operate at **low downtime (~0–5%)**  
- Stations with **high downtime (20–35%) generate near-zero revenue**

---

### Insight  
Downtime has a **direct and significant impact on revenue generation**.

Even small increases in downtime result in **disproportionate revenue loss**, indicating that station reliability is a critical revenue driver.

---

### Business Action  
- Prioritize **maintenance and uptime optimization**  
- Implement **predictive maintenance systems**  
- Set uptime benchmarks for high-performing stations  

---

## 2. Revenue per Session by Location Type (Location Profitability)

### Analysis  
Average revenue per session:

- **Highway:** ~$381.3  
- **Urban:** ~$257.0  
- **Mall:** ~$134.8  

→ Highway locations generate **~2.8x more revenue per session than malls**

---

### Insight  
Charging behavior and willingness to pay vary significantly by location:

- Highway users value **speed and urgency → higher pricing tolerance**  
- Mall users are **price-sensitive and less time-constrained**

---

### Business Action  
- Implement **location-based pricing strategies**  
- Expand highway charging infrastructure  
- Introduce promotional pricing or incentives in low-yield locations (malls)  

---

## 3. Revenue Contribution by Vehicle Type (Segment Performance)

### Analysis  
Top contributors:

- **Electric Truck:** $2.76M  
- **Electric Van:** $2.30M  
- **Luxury EV:** $1.92M  

Lowest contributors:
- **Compact EV:** $0.72M  
- **Motorbike EV:** $0.26M  

---

### Insight  
Heavy and commercial vehicles (trucks, vans) generate **significantly higher revenue** compared to smaller vehicle types.

This suggests:
- Higher energy consumption per session  
- Greater reliance on charging infrastructure  

---

### Business Action  
- Prioritize infrastructure for **high-consumption vehicle segments**  
- Design pricing models tailored for commercial usage  
- Expand partnerships with fleet operators  

---

## 4. Revenue Efficiency Across Location & Vehicle Segments

### Analysis  
The heatmap highlights performance differences across combinations:

- Highest efficiency:
  - **Electric Trucks on highways (~686.6)**  
  - **Electric Vans on highways (~603.2)**  

- Lowest efficiency:
  - **Motorbike EV in malls (~22.2)**  
  - **Compact EV in malls (~71.8)**  

---

### Insight  
Revenue efficiency is driven by a **combination of vehicle type and location**:

- High-value combination: **Heavy vehicles + highways**  
- Low-value combination: **Small vehicles + malls**

---

### Business Action  
- Focus investment on **high-efficiency segments (truck + highway)**  
- Reevaluate ROI of low-performing segments  
- Optimize station placement based on **vehicle-location demand patterns**

---

# Business Impact

This analysis enables VoltCharge Networks to:

- Reduce revenue loss caused by downtime  
- Optimize pricing based on location behavior  
- Focus on high-value vehicle segments  
- Improve infrastructure ROI through targeted deployment  
- Increase overall network efficiency and profitability  

---

# Key Takeaway

This project identifies how station reliability, location type, and vehicle segmentation directly impact revenue, enabling VoltCharge Networks to optimize operations, pricing, and infrastructure for maximum profitability.
