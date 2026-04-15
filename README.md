# colombia-agrifood-data-analysis
Economic and technical analysis of the tomato supply chain in Colombia (2007-2024) using Python

## Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) of the tomato production chain in Colombia (2021-2024). Using Python, I analyze production volumes, planted areas, and technical yields to identify regional efficiency gaps.

## Key Insights
* **Production Concentration:** Identified the Top 5 departments leading the national market.
* **Technical Efficiency:** Calculated yields (tons per hectare) to distinguish between intensive and extensive farming models.
* **Regional Clusters:** Visualized municipal dispersion to identify high-productivity hubs.

## Visual Analysis
### 1. National behaviour 
Tomate National production 
![Production Comparison](1_Tomatoes_Production.png)

Tomate National Landed Aerea
![Landed Aerea Comparison](2_Tomatoes_Landed_Aerea.png)

### 2. Regional Comparison (Top 5 Leaders)
Comparing production performance across the most relevant departments.
![Grouped Bar Chart](3_Landed_aerea_Top_5.png)
![Grouped Bar Chart](4_Production_Top_5.png)

### 3. Municipal Dispersion & Efficiency
Identifying production outliers and regional clusters.
![Scatter Plot](5_Scatter.png)

## Tech Stack
* **Data Wrangling:** Pandas
* **Visualization:** Plotly Express, Matplotlib
* **Economic Indicators:** Yield analysis (t/ha), Growth trends.

## Conclusions & Strategic Insights

As an Industrial Engineer and Economist, I have drawn the following strategic conclusions from the 2021-2024 tomato supply chain data:

### 1. Production Concentration & Market Resilience
* **Insight:** Production remains highly concentrated in five key departments (Boyaca, Huila, Antioquia, Santander, and Norte de Santander). This geographical specialization allows for logistical economies of scale but also creates a high systemic risk in the event of regional climate disruptions or localized strike actions.
* **Strategic Take:** Supply chain diversification or the development of secondary production hubs could stabilize national prices during regional off-seasons.

### 2. The Yield Gap: Technical Efficiency vs. Extensive Growth
* **Insight:** The yield analysis ($t/ha$) reveals a significant disparity between high-tech municipalities and traditional farming zones. Many regions increase output simply by planting more hectares (extensive growth) rather than improving technology (intensive growth).
* **Strategic Take:** There is a major opportunity for ROI in agricultural technology (Irrigation, Greenhouse automation, and Seed genetics). Closing the yield gap in underperforming municipalities by just 15% could outweigh the benefits of expanding the agricultural frontier.

### 3. Municipal Pareto Distribution
* **Insight:** A "Pareto" behavior is evident in the scatter plot: roughly 20% of the municipalities are responsible for nearly 80% of the total production volume. 
* **Strategic Take:** Policy and private investment should focus on these "Anchor Municipalities" to strengthen collection centers and cold chain infrastructure, as improvements here have the highest impact on the overall national supply.

### 4. Yield Outliers and Best Practices
* **Insight:** Certain municipalities show yield rates significantly above the national average. These are likely regions with better access to credit, technical assistance, or high-density planting models.
* **Strategic Take:** Benchmarking the operational processes of these "Yield Leaders" is essential for designing scalable technical assistance programs for the rest of the country.

---
**Mario Velasquez** *Industrial Engineer & Economist | Data Analyst*
