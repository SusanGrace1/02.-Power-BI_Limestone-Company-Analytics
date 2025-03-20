# Kenyan Limestone Company: Power BI Data Analysis

### Table of Contents

- [Project Overview](#project-overview).
- [Project Goals](#project-goals)
- [Data Source](#data-source)
- [Tools and Technologies](#tools-and-technologies)
- [Power BI Report Visuals](#power-bi-report-visuals)
- [Recommendations for the Limestone Company.](#recommendations-for-the-limestone-company)
- [Conclusion](#conclusion)

### Project Overview

A Power BI project focused on analyzing and visualizing operational data for a simulated limestone company in Kenya. The project includes interactive dashboards that explore production trends, sales performance, customer segmentation, and cost analysis.The dashboards aim to provide actionable insights into the company's performance and identify areas for improvement. This repository serves as a portfolio piece showcasing data analysis and business intelligence capabilities.

### Project Goals
**Core Objectives:**

* Demonstrate proficiency in Power BI.
* Create a professional portfolio piece.

**Analysis and Visualization:**

* Analyze and visualize sales, production, and operational cost data.
* Showcase data storytelling through interactive dashboards.
* Identify key trends and patterns.
* Analyze profitability, sales performance, production efficiency, and operational costs.

**Documentation:**

* Document the data generation process using Python, Pandas, and Faker.

### Data Source

The data used in this Power BI project is AI-generated, simulating two years of operational data for a fictional limestone company in Kenya. To create a realistic dataset, Python was employed using the Pandas library for data manipulation and the Faker library for generating synthetic data. The dataset encompasses four key areas of the company's operations:

* **Production:** Detailing daily limestone extraction across three quarries, including tonnage produced and production costs.
* **Sales:** Recording individual sales transactions, customer details, limestone types sold, and regional sales distribution.
* **Customers:** Providing demographic information for 50 unique customers, including their industry, location, and county.
* **Operational Costs:** Outlining expenses incurred across various categories such as fuel, maintenance, labor, and transportation.

This approach allowed for the creation of a comprehensive dataset, facilitating the analysis of sales trends, production efficiency, and cost management within the Power BI environment.

You can view the [Python script](https://github.com/SusanGrace1/BI_LimestoneAnalytics/blob/main/BI_LimestoneProject.ipynb) used.

### Tools and Technologies

**Data Analysis and Visualization:**

* Power BI Desktop

**Data Generation and Manipulation:**

* Python
* Pandas (Python library)
* Faker (Python library)

**Version Control and Collaboration:**

* Git
* GitHub

### Power BI Report Visuals

The following screenshots showcase the key pages of the Power BI report, providing a visual overview of the analysis:

### 1. Performance Overview Report

![Performance Overview Page Screenshot](https://github.com/SusanGrace1/BI_LimestoneAnalytics/blob/main/1.%20Overview%20page.jpg)

**Key Insights (2023 vs 2024 Performance):**

- Strong Profit Growth: Total Profit increased significantly (13.69%), indicating improved financial health.
- Revenue Up: Total Revenue grew by 6.02%, suggesting increased sales or pricing power.
- Stable Production, Improved Efficiency: Tonnage Produced remained consistent, while Average Production Cost per Ton decreased (-0.98%), highlighting gains in operational efficiency.

**Profit Trend Volatility:**
- Monthly profit showed fluctuations in both years, warranting further investigation into underlying causes. However, 2024 generally outperformed 2023, especially towards the end of the year.

**Regional Disparities:**
- Sales performance varied significantly by region, with the Coast region being a clear leader.

### 2. Profitability Analysis Report

![Profitability Analysis Screenshot](https://github.com/SusanGrace1/BI_LimestoneAnalytics/blob/main/2.%20Profitability%20Analysis.jpg)

**Key Insights**

This page provides a deeper dive into the profitability of the limestone company, segmented by key factors.

**Profit by Limestone Type:** Agricultural limestone is the most profitable type, significantly outperforming High-Calcium and Dolomitic varieties. This suggests a strong market demand or higher margins for agricultural products.

**Profit by Customer Type:** Construction customers generate the highest profit, followed by Agriculture and then Industrial. This highlights the importance of the construction sector to the company's profitability.

**Profit per Ton Trend:** The Profit per Ton fluctuates throughout the year for both 2023 and 2024. However, 2024 generally shows a higher Profit per Ton, particularly in the later months, indicating improved profitability per unit sold year-over-year.

**Profit by Region (2024):** The Coast region is the dominant contributor to profit, followed by Central and Nairobi. Eastern and Rift Valley regions contribute the least. This highlights significant regional disparities in profitability.

**Overall Analysis:**

The profitability analysis indicates that the company's profitability has improved in 2024 compared to 2023, as seen in the "Profit per Ton" trend. Agricultural limestone and Construction customers are key drivers of profit. There are significant regional differences in profitability, with the Coast region being the most lucrative. Further investigation could explore the reasons behind the success of agricultural limestone and the Coast region, as well as strategies to improve profitability in other areas and understand the seasonal fluctuations in profit per ton.

### 3. Sales Performance Page

![Sales Performance Screenshot](https://github.com/SusanGrace1/BI_LimestoneAnalytics/blob/main/3.%20Sales%20Performance.jpg)

**Key Insights**
This page provides a comprehensive overview of the company's sales performance, broken down by key dimensions.

**Sales Trend Over Time:** While both 2023 and 2024 show fluctuations, 2024 generally exhibits higher sales revenue, particularly in the latter half of the year. This indicates positive sales growth year-over-year.

**Regional Sales (2024):** The Western region is the top sales generator, followed closely by Central and Coast. Rift Valley shows the lowest sales volume, highlighting significant regional disparities in market penetration or demand.

**Top 5 Customers:** Kilimanjaro Logistics is the leading customer by a significant margin, followed by Uhuru Mining and Pwani Builders. This emphasizes the importance of these key accounts to the company's revenue stream.

**Sales by Limestone Type:** Agricultural limestone accounts for the largest share of sales revenue (36.54%), closely followed by Dolomitic (36.12%). High-Calcium contributes a smaller portion (27.34%). This indicates the varying market demand for different limestone products.

**Overall Analysis:**

The Sales Performance page reveals a positive sales trajectory for the company, with 2024 outperforming 2023. However, sales are heavily concentrated in specific regions and among a few key customers. Agricultural and Dolomitic limestone are the primary drivers of sales revenue. Further analysis could explore strategies to increase sales in underperforming regions, diversify the customer base, and understand the factors driving the success of the top-selling limestone types. The consistent growth in the latter part of 2024 suggests successful strategies or market factors during that period.

### Operational Costs Page

![Operational Costs Screenshot ](https://github.com/SusanGrace1/BI_LimestoneAnalytics/blob/main/4.%20Operational%20Costs.jpg)

**Key Insights**

**Significant Cost Increases:** Both total costs and cost per ton produced have increased by approximately 23% from 2023 to 2024. This indicates a substantial rise in operational expenses, which requires further investigation.

**Equal Quarry Costs:** All three quarries (A, B, and C) have nearly identical operational costs. This suggests a consistent cost structure across the quarries or possibly centralized cost management.

**Cost Breakdown by Category:** The stacked bar chart shows the cost distribution across fuel, labor, maintenance, and transportation for each quarry. Fuel and labor appear to be the dominant cost categories.

**Monthly Cost Fluctuations:** The monthly operational costs line chart reveals significant fluctuations throughout the year for both 2023 and 2024. 2024 shows a higher average cost throughout the year. There are some dramatic spikes and drops that would warrant further investigation.

**Overall Analysis:**

The "Operational Costs" page highlights a significant increase in operational expenses from 2023 to 2024. The consistent costs across quarries suggest a uniform cost structure. The monthly cost fluctuations indicate potential operational inefficiencies or external factors affecting costs. The increased costs need to be investigated to see if they are justifiable. Further analysis should explore cost efficiency metrics and benchmarking to provide a more comprehensive view of operational performance.

**Note:** Click on the images to view them in full size. 

### Recommendations for the Limestone Company.

The following recommendations are derived from the analysis of the company's performance overview, profitability, sales performance, production efficiency, and operational costs.

**1. Profitability Enhancement Strategies:**

- Prioritize the production and sales of agricultural limestone, which demonstrates the highest profitability. Conduct market research to understand the drivers of its success and explore opportunities to expand its market share.
- Focus on serving the construction customer segment, which is the most profitable customer type. Develop targeted sales and marketing campaigns to strengthen relationships with existing construction clients and attract new ones.
- Analyze the Profit per Ton trend to identify the causes of monthly fluctuations. Investigate factors such as pricing strategies, production costs, and sales volume to implement strategies that stabilize and optimize profitability.
  
**2. Sales Performance Optimization:**

- Leverage the strong sales performance in the Western, Central, and Coast regions by replicating successful strategies in underperforming regions like Rift Valley. Conduct market analysis to understand the unique challenges and opportunities in each region and tailor sales approaches accordingly
- Maintain strong relationships with key accounts, particularly Kilimanjaro Logistics, Uhuru Mining, and Pwani Builders, as they contribute significantly to revenue. Explore opportunities to expand business with these clients and diversify the customer base to reduce reliance on a few major accounts.
- Given that Agricultural and Dolomitic limestone are the top-selling products, ensure that production capacity aligns with demand. Monitor market trends to adjust production strategies and optimize inventory management.
  
**3. Production Efficiency Improvement:**

- Investigate the factors contributing to the decrease in Average Production Cost per Ton in 2024. If attributable to specific process improvements or cost-saving measures, implement these across all quarries to further enhance efficiency.
- Analyze the monthly tonnage produced and production cost per ton trends for both 2023 and 2024 to identify opportunities for process optimization. Implement strategies to minimize cost fluctuations and maximize production output.
- Establish key efficiency metrics, such as "Tonnage Produced per Hour" or "Uptime," to gain a more comprehensive understanding of operational efficiency. Set targets and track performance against these metrics to drive continuous improvement.
  
**4. Operational Cost Management:**

- Given the significant increase in Total Costs and Cost Per Ton Produced from 2023 to 2024, conduct a thorough review of operational expenses. Identify the drivers of this increase and implement cost-saving measures to improve profitability.
- Analyze the cost breakdown by category for each quarry, with a focus on fuel and labor costs, which appear to be the dominant categories. Explore opportunities to negotiate better rates with suppliers, optimize labor utilization, and implement energy-efficient practices.
- Investigate the causes of monthly operational cost fluctuations. Identify factors such as seasonal variations, maintenance schedules, or external factors impacting costs and implement strategies to mitigate their impact.
  
**5. Data-Driven Decision Making:**

- Implement a system for continuous monitoring of key performance indicators (KPIs) across all areas of the business. Regularly review the dashboards and reports to identify trends, track progress against targets, and make informed decisions.
- Establish a process for benchmarking performance against industry standards or competitors. Identify areas where the company is lagging and implement strategies to close the gap.

### Conclusion

The analysis of operational costs has revealed a significant increase in both total costs and cost per ton produced from 2023 to 2024, indicating a substantial rise in operational expenses. This trend warrants immediate attention to mitigate potential impacts on profitability and financial health. The consistent costs across quarries suggest a uniform cost structure, while the monthly cost fluctuations point to potential operational inefficiencies or external factors affecting costs.

The recommendations provided address these findings by focusing on profitability enhancement, sales performance optimization, production efficiency improvement, and operational cost management. Implementing these recommendations will enable the company to gain better control over its costs, enhance operational efficiency, and ultimately improve its financial performance.

It is crucial to adopt a data-driven approach to decision-making, continuously monitor key performance indicators, and benchmark performance against industry standards. By taking proactive steps to address the identified issues and implement the recommended strategies, the company can ensure sustainable growth and maintain a competitive edge in the market.



