# END TO END COFFEE SHOP ANALYTICS
### Profitability Demand and Customer Insight

**Prepared by:**  Oluwatosin Ogunwale &nbsp;|&nbsp; **Period:** 2019 – 2022 &nbsp;|&nbsp; **Tools:** Excel 

---
## Summary
This report presents a comprehensive business intelligence analysis of a specialty coffee shop serving 913 customers across three countries; the United States, United Kingdom, and Ireland; over a four-year period from 2019 to 2022. The business fulfilled 3,551 orders generating total sales of ₦45,134.26 and a total profit of ₦1,301.38, representing a profit margin of approximately 2.9%  a figure that sits at the centre of this analysis.
Two interactive Excel dashboards were built to interrogate the data across three critical business dimensions: product profitability, customer behaviour, and demand patterns. Together they surface a business operating with strong sales momentum but structurally compromised profitability a gap that is both explainable and addressable.
The analysis reveals three findings that demand immediate management attention. First, the best-selling product is the worst profit generator; Robusta drives the highest sales volume but returns the lowest profit across all roast types, creating a dangerous misalignment between revenue activity and financial return. Second, the most profitable product is being undermarketed; Liberica Light Roast generates the highest profit margin in the entire range yet does not lead in sales, representing a missed commercial opportunity. Third, the loyalty programme is not working as intended; customers without loyalty cards are purchasing at a slightly higher volume than cardholders, which inverts the fundamental logic of the programme.
The recommendations in this report are structured to address all three problems directly through pricing revision, targeted promotion, and loyalty programme redesign.

## 📌 Table of Contents
1. [Project Overview](#1-project-overview)
2. [Business Problem](#2-business-problem)
3. [Objectives](#3-objectives)
4. [Tools & Methodology](#4-tools--methodology)
5. [Dashboard 1 — Sales & Profitability Intelligence](#5-dashboard-1--sales--profitability-intelligence)
6. [Dashboard 2 — Customer Behaviour & Demand Intelligence](#6-dashboard-2--customer-behaviour--demand-intelligence)
7. [Data Quality & Limitations](#7-data-quality--limitations)
8. [Conclusions](#8-conclusions)
9. [Repository Structure](#9-repository-structure)

---

## 1. Project Overview

This project presents a comprehensive business intelligence analysis of a specialty coffee shop's operations across a **four-year period (2019–2022)**. Using two interconnected Excel dashboards, the analysis delivers actionable insights across 3 critical business dimensions:

| Dimension | Dashboard |
|-----------|-----------|
| Product profitability | Dashboard 1 |
| Customer loyalty & behaviour | Dashboard 2 |
| Demand patterns & trends | Dashboard 2 |

The analysis was conducted **end-to-end** — from raw data extraction and cleaning, through exploratory analysis, to dashboard design and business recommendations. The findings are structured to serve the needs of the **marketing team, operations team, and senior management.**

### At a Glance

| | | | | |
|---|---|---|---|---|
| **4 Years** | **2 Dashboards** | **12 Visuals** | **3 Teams Served** | **360° Coverage** |
| Data Period | Built | Produced | Audience | Business Scope |

---

## 2. Business Problem

The coffee shop had accumulated several years of transactional data but lacked a structured analytical framework to answer key strategic questions. Management could not confidently answer:

- Which products were most profitable?
- What Products do the customers prefer?
- Whether the loyalty programme was actually working?
- How demand was shifting over time?

This project was built to answer all of those questions clearly and visually.

---

## 3. Objectives

- ✅ Identify the most and least profitable coffee types, roast combinations, and product sizes
- ✅ Assess  customer preference of coffee size, type and roast type to inform potential market expansion decisions
- ✅ Evaluate the impact of the loyalty card programme on purchase behaviour
- ✅ Understand demand trends over time to support inventory and staffing planning

---

## 4. Tools & Methodology

| Tool / Technique | Purpose |
|-----------------|---------|
| Microsoft Excel | Data cleaning, transformation, and exploratory analysis |
| Microsoft Excel | Dashboard design, KPI visualisation, and interactive reporting |
| Power Query | Data shaping, column standardisation, and type formatting |


---

## 5. Dashboard 1 — Sales & Profitability Intelligence

> **Dashboard Title:** Where Is the Money? A Coffee Profitability & Sales Analysis
>
> **Primary Audience:** Senior Management • Finance Team • Product Team

### Visuals Included

| Visual Title | Business Question Answered |
|-------------|---------------------------|
| Profit comparism among countries | Which markets generate the highest profit and where should we focus growth? |
| Which Combination of Coffee Type & Roast Makes the Most Profit? ,% Profit Change by Coffee Type, Profit from Coffee Types| Which product combination should we prioritise for margin optimisation? |
| Size Performance Breakdown: Volume, Revenue & Profit Share | Does the best-selling size generate the most profit, or are we over-indexing on low-margin sizes? |
| Trends of Sales,Profit and cost, Total Sales Per year | Is overall revenue growing, declining, or plateauing year on year? |

### 📸 Dashboard Preview
[Dashboard 1 Overview](screenshots/DashboardSales.png)
> *<img width="895" height="424" alt="DashboardSales" src="https://github.com/user-attachments/assets/43b164bc-43fd-4ecc-878a-70ecc40ef7f8" />
*

### Key Findings
The business served 913 customers across 3 countries (US, UK, Ireland) over 4 years (2019–2022), fulfilling 3,551 cups with total sales of ₦45,134.26 and a slim profit of ₦1,301.38 — a ~2.9% profit margin, which is concerningly low.


- **Geographic concentration:** The United States accounts for 78% of total profit, suggesting the business is heavily dependent on the country.Ireland contributes 15% (₦202.02) which is decent for its relative size. United Kingdom only contributes 7% (₦86.60), suggesting either low penetration or poor product-market fit there.
- **Profitability Insights:** From the %profit change by coffee type, The 2022 points should be ignored because we only have data up till august 2022, however,  Robusta (Rob) and Excelsia(EXC) seem to have recorded a decrease in profitability in 2021 (-10.485)while Liberica (Lib) and Arabica (Ara) were able to peak up to 20+% increase in profitability the same year. The combination chart also shows that ROB has maintained a low profit generation trend for the three types of roast while LIB has maintained the highest profit generator for the three roast types. 
- **Coffee Type Best Seller:** Robusta (Rob) is the best seller, it has maintained the highest sales figure and consistently outperforms other types.Arabica (ARA) is the least sales generator, it has maintained a record below #4,000 in total sales over the years
Excelsia and Arabica are relatively stable but declining, suggesting market fatigue or pricing pressure.
- **Size paradox:** All the cups are quite balanced on the quantity ordered but the 2.5litre size ranks number 1 in percent profit of total profit earned and sales made. The 2.5litre size delivers 30 %  of total profit higher  the other sizes despite them having the same number of orders. This show that it has potential and pushing more quantity will result in significant increase in profit.0.2kg bags contribute the least across all three metrics (profit, sales, quantity),even though the number of cups sold is approximately the same as the other sizes(profit per cup is quite low), suggesting they may not be worth the operational overhead.
- **Revenue trend** Revenue grew consistently from 2019 to 2021, with a notable  increase in 2021 anda notable decrease in 2022(because of incomplete data. The trend of sales, profit and cost suggests that the profit is not so responsive the increase in sales and that warrants further investigation.

### Recommendations

1. **Prioritize the Liberica especially the Light roast type** in promotional activity and menu placement. It needs visibility, not discounting .Even though Liberica is the second best sales generating product, L-Light Roast type of Liberica Coffee type generates the highest profit 14% of the total profits generated. Robusta might be dragging the overall profitability down significantly; some action needs to be taken. Robusta’s pricing needs to revised because it powers the most sales but it gives back the least profit.
2. **Review size pricing strategy.** Since all the Sizes have roughly the same number of orders,  the 2.5litre is undermarketed, not underperforming. The opportunity is in steering existing demand, not generating new demand we could display 2.5litre prominently as the "Best Value" option or Offer a "top-up deal" ; "Upgrade from 1litre to 2.5litrefor just ₦X more".Reward loyalty members extra points specifically for purchasing 2.5litre Cups, this would also fix the underperforming loyalty card program. 
3. **Investigate the unresponsiveness of the profit to the increase in sales in 2021.** More investigation needs to conducted.

---

## 6. Dashboard 2 — Customer Behaviour & Demand Intelligence

> **Dashboard Title:** Who Is Buying, What They Want, and When They Come
>
> **Primary Audience:** Marketing Team • Operations Team • Customer Success

### Visuals Included

| Visual Title | Business Question Answered |
|-------------|---------------------------|
| Number of Coffee Cups per month, Intra month Order pattern analysis | When within a month do orders peak — and how can we use this for staffing and stock?|
| Size Preference by quantity Shifts by Year | Are customers gravitating toward larger or smaller sizes over time? |
| Coffee Type Demand Trends by Year | Which coffee types are growing in popularity and which are declining? |
| Loyalty Card Holders vs. Non-Members: Purchase Volume Comparison | Is the loyalty programme driving meaningful additional purchases? |
| Top 9 Customers by Cumulative Spend | Who are our highest-value customers and how much have they spent? |
| Litres of Coffee and Roast Type Consumed| What is the most consumed coffee and Roast type "Customer's Favorite|

### 📸 Dashboard 
[Dashboard 1 Overview](screenshots/DashboardCustomer.png)
> *<img width="897" height="448" alt="DashboardCustomer" src="https://github.com/user-attachments/assets/8c53f6aa-c27a-4a2b-8998-fb3d07353da8" />
*

### Key Findings



- **Demand seasonality:** Monthly order volume peaks in February–March (~400+ cups) and dips significantly(to about 200) in August–October, revealing a clear seasonal trough to plan promotions around. This should also inform us that the number of cups needed for a month is about 200-400 for smooth running. The number of orders however ranges from 109-64, this shows we need an average of 3 cups per order. Not necessarily meaning that each order serves 3 cups.
-**Coffee Size Trends:** The [0.2 litre] and [0.5 litre] cup sizes demand seems  to be increasing as the year runs by, the 1 litre cup demand recorded a dip in 2020 but has turned out to be the most preferred size by 2021. The 2.5 litre cup seems to have maintained its demand approximately.
- **Shifting preferences:** The demand for [Arabica] and [Excelsia] coffee type seems  to be increasing as the year runs by, while [LIB and ROB]’s demand  dipped in 2020 it grew in 2021. This shift should inform procurement and menu prioritisation.
- **Loyalty programme impact:** Non-loyalty card holders slightly outpurchase loyalty members (~53% vs ~47% in volume), which is counterintuitive — the loyalty program doesn't appear to be driving meaningfully higher purchase frequency. The customers who do not have loyalty cards are also more than those that do.
- **Customer concentration risk:** Top customer (Ailey Brash) leads cumulative spend at ~₦320, but the top 9 customers are closely clustered between ₦250–₦340, suggesting no single customer is dangerously dominant.
**Customer's Favorite Drink:** The highest litres of coffee consumed was the Arabica light roast while the least litre of coffee consumed was the Liberica medium roast.
 ### Recommendations

1. **Incentivize demand for 2.5litre sizes.** Since from the sales dashboard we know that 2.5 litres cup generate the most profit , we could put out some incentives to increase the demand for the size
2. **Incentives for Coffee types.** The Robusta and Liberica coffee type are the highest profit generators, their demand should be incentivized.
3. **Grow loyalty card membership aggressively.** If card holders buy significantly more, the priority should be converting casual customers. A sign-up incentive — first drink free, or a points bonus on registration — could meaningfully shift the ratio. And also encouraging the card owners to buy more could increase sale. 
4. **Regulate the customer Favorite coffee type.** The coffee type that’s the customers favorite should be also benefit the business. The price should be regulated. 

---


## 7. Data Quality & Limitations

### Cleaning Steps Performed
- Removed duplicate order records identified through order ID cross-referencing
- Standardised date formats across all tables to enable accurate time-series analysis
- Validated product category labels for consistency — corrected mislabelled roast type entries
- Cross-checked revenue figures against quantity × unit price to identify and correct pricing anomalies

### Known Limitations

| Limitation | Impact |
|-----------|--------|
| No customer demographics | Limits depth of customer segmentation |
| Incomplete 2022 data| The 2022 data input was terminated in august hence it is not truly representative of the year, this is why some of the 2022 visuals were colored grey|

---

## 8. Conclusions

This analysis set out to answer four questions that the business could not previously answer with confidence: which products were most profitable, what customers preferred, whether the loyalty programme was working, and how demand was shifting over time. All four questions now have clear, data-supported answers.
The most consequential finding is structural. Across 3,551 orders and four years of trading, the highest-selling coffee type generated the lowest profit, and the highest-profit coffee type was not the most promoted. Robusta's dominance in sales volume masked a profitability problem that would have remained invisible without this analysis. Meanwhile Liberica, particularly the Light Roast consistently delivered the strongest margins but never received the commercial attention its performance warranted. This inverted relationship between popularity and profitability is the single most important thing this business needs to act on.
The size analysis reinforces this pattern. All four cup sizes attract roughly equal order volumes, yet the 2.5kg size contributes 30% of total profit despite receiving no apparent pricing or promotional advantage over smaller sizes. This is not a product that is underperforming; it is a product that is being underutilised. The opportunity is not to generate new demand but to redirect existing demand toward a higher-margin option that customers are already willing to purchase.
The customer and demand analysis adds important operational context. Order volumes peak between February and March and fall significantly between August and October, providing a predictable seasonal rhythm the business can plan staffing, stock, and promotions around. The top nine customers are closely clustered in spend between ₦250 and ₦340, with no single customer representing a dangerous concentration riskwhich is a healthy sign for revenue stability.
The loyalty programme finding is the clearest call to action. When customers without loyalty cards purchase at a higher volume than cardholders, the programme has failed its primary purpose. It is not enough to have a loyalty programme, it must be structured around behaviours that benefit the business. Tying loyalty rewards specifically to 2.5kg purchases and Liberica orders would simultaneously fix the programme's underperformance and steer customer behaviour toward higher-margin products.
The 2.9% overall profit margin is the number that should keep management awake. It is not a crisis but it is a warning. The good news is that this analysis shows the problem is not a demand problem 3,551 orders across four years from 913 customers demonstrates genuine market traction. The problem is a pricing and product mix problem, and both are within management's control to fix. Repricing Robusta, promoting Liberica Light Roast, and redesigning the loyalty programme around margin-positive behaviour are three targeted actions that could meaningfully lift profitability without requiring a single new customer.
> ### 💡 The Single Most Important Finding
> *The highest sales generator was the lowest profit generator, a serious pricing/costing issue.*

---

## 9. Repository Structure

```
CoffeeShopProject/
  ├── README.md                        ← You are here
  ├── data/
  │    ├── raw_data.xlsx               ← Original unmodified dataset
  │    └── cleaned_data.xlsx           ← Cleaned & transformed dataset
  ├── dashboards/
  │    ├── profitability_dashboard.xlsx
  │    └── customer_dashboard.xlsl
  ├── report/
  │    └── CofeeShopProject.docx
  └── screenshots/
       ├── dashboard_1_overview.png
       └── dashboard_2_overview.png
```

---

## 👤 About the Analyst

**[Oluwatosin Ogunwale]** — Data Analyst | Excel • Power BI | Tech & Finance

- 📧 [oluwatosinogunwale35@gmail.com]
- 💼 [https://www.linkedin.com/in/Oluwatosin-ogunwale.com]
- 🐙 [github.com/Oluwatosin-ogunwale]
- 🌐 [oluwatosin-ogunwale.github.io]

---

*This project was produced as part of a personal data analytics portfolio. All findings and recommendations are based solely on the dataset provided and are intended to demonstrate analytical thinking, data storytelling, and dashboard design capability.*

