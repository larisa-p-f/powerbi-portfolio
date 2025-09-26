
# Beauty & Skincare E-Store Report

## Project Overview
This project analyzes sales volumes and profitability for a **global skincare and beauty e-store**.  
The business case (provided by [ZoomCharts](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/challenges/fp20-analytics-september-2024)) set the following strategic goals:
- Achieve an **average annual profit margin of 15%** across all product groups  
- Reach **20% annual overall sales growth**, with a higher target of **30% for the corporate segment**  
- Ensure **at least $400K annual sales per market**  

The report highlights whether these KPIs were met and provides actionable insights into **profitability, discount strategy, and geographic performance**.  

---

## Key Insights
### 1) Executive KPI Readout
- **Profit Margin:** Strong at **>24% in 2020–2022**, but **fell to ~16% in 2023** (still above the **15% target**, yet a steep decline).  
- **Sales Growth:** The **20% overall YoY target** was **exceeded in 2021 and 2022** (>26%), but **missed in 2023 (~19.9%)**.  
- **Corporate Growth:** The **30% target** for the corporate segment **was not met in any year**.  
- **$400K per Market:** **Asia Pacific** first crossed **$400K in 2022**; **no other market** hit this threshold until this year; in **2023 Africa was the only market to not reach $400K**.  

---

### 2) 2023 Performance Dynamics
- **Profit** rose each year until **2023**, where it **declined (~–17% YoY)** despite **sales increasing ~19.9%** → **unit costs rose** and **margins compressed**.  
- **Average Order Value** increased through **2021–2022**, then **fell by ~$12 in 2023**.  

---

### 3) Markets
- **Asia Pacific** is the **largest market by sales** every year; **Africa** is consistently the smallest.  
  In **2023**, APAC sales were **~4× Africa**.  
- **Europe** is the **fastest-growing market by sales**; **USCA** is the slowest.  
- **Profitability:** **Europe** is the **most profitable** region (avg margin **~22%**), **Asia Pacific** the **lowest (~13%)**.  
  **Margins fell across all markets in 2023**, but **Europe’s absolute profit held up** (profit didn’t fall, margin did).  
- **Total profit (all years):** **Africa** is least profitable (~**$66K**).  
  **USA** is most profitable (~**$208K** profit on **$1.3M** sales); **~21% of US sales** come from **California**.  

---

### 4) Segments
- **Profit share by segment** is stable: **Corporate > Consumer > Self-Employed** across all years and markets.  
- Despite leadership in profit share, **Corporate** still **misses the 30% YoY growth target** each year.  

---

### 5) Categories
- **Body Care**: **Most profitable** overall — **~59% of total profit** while only **~41% of sales**.  
- **Face Care**: **Highest margin (~36%)**.  
- **Makeup**: **Sales +43% in 2023**.  
- **Hair Care**: Roughly **break-even** over all years.  
- **Home & Accessories**: **Only category with negative profit** (≈ **–$57K**) despite being **second-best by sales**.  

---

### 6) Discount Strategy
- **Discounted profit margin** is **negative most years** and **falls to ~–5.5% in 2023**;  
  **Non-discounted margin** remained **positive but also fell in 2023**.  
- **~45% of revenue** comes from **discounted lines each year** — the negative margins therefore have a **sizeable impact**.  
- By category:  
  - **Hair Care** and **Home & Accessories**: discounted margins **~–15%** and **~–18%** (deeply value-destructive).  
  - **Body Care**: discounted margin **~3.6%**, non-discounted margin **~36.9%**.  
  - **Makeup** and **Face Care**: discounted margins **~12%** and **~16%** — still positive but **far below** non-discounted margin **(~47%)**.
- By market:
  - **Asia Pacific**: **57% of sales came from discounted goods**, the highest share; **Africa** had the lowest at **26%**.  
  - **Africa**: worst discounted margin (~**–37%**).  
  - Other markets: discounted margins were **negative or barely break-even**.  
  - **USCA** and **Europe** were the **only markets making any profit** from discounted goods (**$18.7K** and **$2.8K** respectively).  

---

## Actions Recommended

### Pricing & Promotions
- Stop blanket discounts. Prohibit where **historical discounted margin <5%** (e.g., **Hair Care**, **Home & Accessories**).
- Keep discounts off our strongest performers (**Body Care, Face Care, Makeup**) and use **loyalty rewards or freebies** instead. 
- Try **A/B testing price points**, or **short targeted promos** tied to stock or seasonality, then track whether they actually add profit, not just sales volume.  

### Merchandising
- Scale **Body Care** (biggest profit driver) and **Face Care** (highest margin).  
- For **Home & Accessories**, either fix the cost structure or stop selling it (it’s a consistent money-loser).  
- For **Hair Care**, cut costs and streamline the range before trying more promos.  

### Market & Segment Strategy
- Push growth in underperforming regions, especially **Africa**. Focus on a few “hero” products and avoid discount-led strategies there.  
- In the **Corporate segment**, stop chasing growth through discounts. Instead, use **contracts, repeat orders, and higher order value incentives** to keep clients locked in while protecting margins.    
---

## Report Pages

### Executive Overview
![Executive Overview](./images/01-Overview.png)

### Geographic Insights
![Geographic Insights](./images/04-Geographic%20Insights.png)

### Discount Strategy
![Discount Strategy](./images/07-Discount%20Strategy.png)

*(See `/images/` folder for additional report screenshots including drillthroughs and tooltips.)*  

---

## Tools & Skills Demonstrated
- Power BI  
- DAX (calculated measures for profit margin, YoY growth, sales splits)  
- Report design & storytelling (executive summary, geographic deep-dive, discount analysis)  
- Drillthrough, tooltips, and interactive slicers   

---

## Source
Dataset and business brief provided by [ZoomCharts Analytics Challenge, September 2024](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/challenges/fp20-analytics-september-2024).
