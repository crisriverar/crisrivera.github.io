
# Professional Profile

Bilingual Junior Data Analyst with experience in data analysis, business intelligence (BI), data visualization, and process improvement in international environments. Proficient in SQL, Python (Pandas, NumPy), Excel, and Power BI for data extraction, cleaning, transformation, and analysis. Experienced in dashboard creation, reporting, trend identification, and process optimization through data-driven insights. Skilled at translating business requirements into analytical solutions that support strategic decision-making.

## Technical Skills

- Data analysis and manipulation with **Python (Pandas, NumPy)**
- Database querying and management using **SQL (MySQL)**
- Data visualization with **Tableau, Power BI, Matplotlib, and Seaborn**
- Advanced **Excel and Google Sheets**
- A/B Testing design and analysis

## Contact Information

[![LinkedIn](https://img.shields.io/badge/LinkedIn-001C4D?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristian-riverar)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-001C4D?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:cristianrivera.r@hotmail.com)

---

# Selected Projects

## RappiPlus Funnel Analysis and A/B Testing Experimentation

This project evaluates RappiPlus, a subscription service within the Rappi ecosystem designed to increase purchase frequency and maximize user-generated value. A reproducible data cleaning pipeline was developed, conversion funnel and cohort retention analysis were performed, and the impact of a checkout design change was evaluated through an A/B test.

### Tools and Project Type

![Python](https://img.shields.io/badge/Python-001C4D?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Cohort Analysis](https://img.shields.io/badge/Cohort_Analysis-6A5ACD?style=for-the-badge&logo=googleanalytics&logoColor=white)
![A/B Testing](https://img.shields.io/badge/A%2FB_Testing-FF6F00?style=for-the-badge&logo=testinglibrary&logoColor=white)
![Funnel Analysis](https://img.shields.io/badge/Funnel_Analysis-00897B?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### Key Questions

- Which product categories generate the highest share of profit?
- At which funnel stage are users dropping off the most?
- Does the checkout design change significantly improve conversion?

### Methodology

- **Data Quality and KPIs:** Reviewed data quality across orders, product catalog, and marketing spend datasets.
- **Funnel Analysis:** Calculated drop-off rates between funnel stages using user event and activity data.
- **Cohort Retention Analysis:** Evaluated whether users return after registration.
- **A/B Testing:** Performed statistical comparison between two checkout versions using hypothesis testing and p-value analysis.

### Results Dashboard

<img width="1077" height="285" alt="image" src="https://github.com/user-attachments/assets/a5eb5395-88d2-4bfa-8873-3c5ff8865cf6" />

### Conclusions and Recommendations

- 83% of total profit comes from the Electronics category, concentrated in a single product (Laptop Gaming 16GB), representing a dependency risk. Diversifying the promoted product catalog is recommended.
- The largest funnel drop-off (13.29%) occurs between "begin checkout" and "add payment info", indicating payment process friction rather than lack of user interest.
- Checkout Version B showed a 0.60% higher conversion rate, but the difference was not statistically significant (p = 0.42). Extending the experiment before scaling the change is recommended.

**View complete project repository[repositorio completo](https://github.com/crisriverar/Analisys-RappiPlus).**

---

## Customer Behavior Correlation Analysis for NovaRetail+

In e-commerce, understanding which customer behavior factors are associated with generated revenue is essential for designing sustainable growth strategies and optimizing acquisition and retention investments. Identifying these relationships allows NovaRetail+, a Latin American e-commerce platform with millions of users, to anticipate business opportunities and allocate resources more efficiently for the 2024 year-end strategy.

### Tools and Project Type

![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-001C4D?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Correlation Analysis](https://img.shields.io/badge/Correlation_Analysis-6A5ACD?style=for-the-badge&logo=googleanalytics&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-FF6F00?style=for-the-badge&logo=databricks&logoColor=white)

### Key Questions

- Which customer behavior factors are most strongly associated with annual revenue?
- Is there a relationship between targeted advertising investment and monthly purchases?
- Does platform traffic (monthly visits) influence purchases and generated revenue?

## Methodology

- **Data Preprocessing:** Worked with the `novaretail_comportamiento_clientes_2024.csv` dataset containing customer behavior information (targeted advertising spend, monthly purchases, monthly visits, annual revenue, among other variables), composed of 15,000 records.
- **Exploratory Data Analysis (EDA):** Analyzed variable distributions and identified initial behavioral patterns among customers.
- **Correlation Analysis:** Applied multiple correlation techniques (heatmaps and scatterplots for key variable pairs) to identify significant relationships and detect potential misleading correlations.

**Documentation of Findings:**  
Documented assumptions and limitations while translating analytical findings into business recommendations.

### Relationship Heatmap

<img width="800" height="399" alt="image" src="https://github.com/user-attachments/assets/a96f556e-ee4f-48e8-8353-ace303bc9840" />

### Conclusions and Recommendations

### Identified Relationships:

- Targeted advertising spend and monthly purchases show a moderate positive correlation (r=0.57): both variables tend to increase together, although direct causation cannot be confirmed.
- Monthly visits show a moderate positive relationship with both monthly purchases (r=0.35) and annual revenue (r=0.33), suggesting that increased platform traffic may contribute to higher revenue generation.

### Recommended Strategies:

- **Validate targeted advertising in a controlled environment:** Explore increasing targeted advertising spend through A/B testing or pilot campaigns before scaling investment.
- **Reduce friction in the purchase process:** Prioritize navigation improvements and UX optimizations to convert traffic into purchases more effectively.

**View complete project repository[repositorio completo](https://github.com/crisriverar/Analisys-NovaRetail-).**

---

## Telecommunications Data Analysis for ConnectaTel

This project analyzes ConnectaTel's customer usage behavior, a telecommunications company operating in Mexico and Colombia. Three different data sources were integrated to build a statistical profile of service usage (calls and messages) by customer and demographic segment. The objective was to identify commercial opportunities through consumption patterns and unusual behaviors.

### Tools and Project Type

![Python](https://img.shields.io/badge/Python-001C4D?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Data Cleaning](https://img.shields.io/badge/Data_Cleaning-795548?style=for-the-badge&logo=databricks&logoColor=white)
![Outlier Detection](https://img.shields.io/badge/Outlier_Detection-D32F2F?style=for-the-badge&logo=python&logoColor=white)
![Segmentation](https://img.shields.io/badge/Segmentation-6A5ACD?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Exploratory Data Analysis](https://img.shields.io/badge/Exploratory_Data_Analysis-00897B?style=for-the-badge&logo=plotly&logoColor=white)

### Key Questions

- How can datasets from three different sources be integrated and cleaned?
- Which customer segments show the highest service usage levels?
- Are there unusual behaviors (outliers) that represent commercial opportunities?

### Methodology

- **Data Preprocessing:** Validated, standardized data types, and detected inconsistencies across three data sources (plans, users, and actual usage).
- **Exploratory Data Analysis (EDA):** Built a statistical profile of usage patterns by customer and demographic segment.
- **Outlier Detection:** Identified unusual behaviors using statistical and visual methods.
- **Segmentation:** Grouped customers based on age, country, and usage behavior.

### Conclusions and Recommendations

- The adult segment shows the highest service usage level, making it a key target for premium plan migration campaigns.
- The senior segment, although smaller, may represent a valuable opportunity due to potential financial stability and suitability for loyalty strategies.
- Low usage levels observed among younger customers may be underestimated because mobile data consumption was not included, which is likely the dominant communication channel for this group.

**View complete project repository[repositorio completo](https://github.com/crisriverar/Analisys-ConnectaTel).**
