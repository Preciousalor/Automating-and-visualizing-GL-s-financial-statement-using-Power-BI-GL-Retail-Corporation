# Automating and visualizing GL’s financial statement using SQL, Power Query, and Power BI — GL Retail Incorporation

### **Project Overview**
GL Retail Corporation (GL) is a successful retail company with a headquarters and five retail outlets. With years of prosperous operations, GL has maintained its position as a market leader in the FMCG retail industry. GL intends to take a data-driven approach that transforms good performance into valuable insights for future decision-making. In this project, I played the role of a business intelligence developer. I focused on automating and visualizing GL's financial statement using SQL, Power Query, and Power BI. Subsequently, I replicated the three financial statements in Excel, employing Cube formulas that reference the data model, thus providing the team of Excel users with seamless access to Power BI data.

![Sales data 2](https://github.com/Preciousalor/Automating-and-visualizing-GL-s-financial-statement-using-Power-BI-GL-Retail-Corporation/assets/130922537/ec134e64-0945-421c-950b-287821337ddb)



### **CONTENTS**
1. [Background](#background)
2. [Methodology](#methodology)
3. [Insights](#insights)
4. [Conclusions](#conclusions)

### **Background**
Companies of all sizes have experienced significant advantages from data analysis, including enhanced decision-making, streamlined operations, personalized marketing, a competitive edge, and an improved customer experience. However, for a retail entity like GL, which has traditionally relied on Excel for analysis, the challenge lies in dealing with disorganized data and reports. The current process demands considerable time and manual effort each month, resulting in inconsistent answers. GL is actively pursuing a transition to Power BI to automate and visualize its existing Excel reporting, aiming to enhance efficiency, ensure reporting integrity, and gain new insights for a competitive advantage. Power BI, a robust data visualization tool, is ideal for analyzing GL Retail Corporation's extensive financial and non-financial data from various sources.


### **Methodology**
To create a Power BI dashboard for GL Retail Incorporation, I followed a systemic approach.
 
### **Step 1: Data Preparation**
The first step is to gather the necessary data, which can be achieved by extracting data from the GL Retail transaction database through Azure Data Studio using confidential database credentials. The next step involves understanding the entity relationship diagram (ERD), followed by writing a query that consolidates the required data from all relevant tables. Finally, modify the query so database administrators can use it to create an SQL view. Once all modifications are completed, the data can be imported into Power BI.
 
### **Step 2: Data Analysis**
After extracting, transforming, and loading (ETL) the data, you need to analyze it to identify patterns and insights. Power BI offers a range of visualization options, including bar charts, scatterplots, column and stacked column charts, and maps, that can help you explore the data. Some useful questions to ask when analyzing the GL Retail dataset include:
· What key KPIs are required in the income statement and statement of financial position (e.g., gross profit, EBIT, net income, current ratio, EPS, debt ratio, etc.)?
· What are the key drivers behind changes in revenue, and how have they evolved?
· Can the report identify areas of increased or decreased expenses, and what factors contribute to these changes?
· Can the report break down revenue and profitability by customer segments, revealing high-value or underperforming segments?
· How is cash flow affected by operating, investing, and financing activities, and what implications does this have?


### **Insights**
Upon completing the analysis on Power BI, numerous insightful findings emerged. Notably, I successfully migrated, automated, and visualized the current reporting on Power BI, replacing Excel. This transformation improved efficiency and reporting integrity and provided new insights, offering a competitive advantage. Key insights include:


### **I. Income Statement:** 
I utilized the table visual to automate and visualize the income statement on Power BI, seamlessly integrating with various data sources for real-time and automated data refresh. This ensures stakeholders always have access to the latest financial information. The analysis aligns with our current Excel reports but stands out with dynamic and interactive visualizations. Users can explore income statement data through drill-up, drill-down, and filtering, enhancing comprehension and decision-making. Leveraging Power BI's DAX tool, I simplified complex calculations, reducing the likelihood of errors in income statement calculations. Robust collaboration features allowed real-time sharing and collaboration on income statement reports, ensuring everyone worked with the same up-to-date information.
A closer look at the income statement for GL Retail Corporation revealed stable revenue and cost of sales over the past three years. The gross profit ratios for 2019, 2020, and 2021 stood at 22.12%, 19.15%, and 20.87%, respectively. However, a significant decline in net profit and net profit ratio occurred in 2020 and 2021, possibly attributed to growing operating expenses and non-declining interest expenses amidst lower gross profit. Despite this, GL maintained a positive gross profit for all three years analyzed.


### **II. Revenue and Gross Margin%:**
This metric illuminates the correlation between revenue and gross profit, serving as a pivotal gauge of a company's profitability. It signifies the efficiency with which a company manages its production costs and stands as a crucial indicator of overall profitability. A higher gross margin ratio implies superior cost control, translating to increased profitability on each unit of product or service sold.
### **Key Observations**
The gross profit ratio witnessed a decline from 2019 to 2020.
In 2020, the GP% experienced a dip to 19.15%, signaling a reduction in profitability compared to the preceding year.
Encouragingly, there was a modest improvement in 2021, with the GP% rising to 20.87%.
Upon conducting a meticulous analysis to comprehend the factors contributing to these shifts, it was identified that a declining gross profit ratio in 2020 was attributed to challenges in managing production costs. In 2021, strategic measures were implemented, resulting in an increased GP ratio, indicative of enhanced cost control.
Revenue and Gross Margin %III. Income Statement Expenses Analysis
I employed a waterfall chart to illustrate the intricate connection between revenue and all expenses over the three-year reporting period. GL faces elevated costs of goods sold (COGS) and substantial operating expenses, primarily driven by escalating employee-related costs. Consequently, this leaves a narrow margin, with a net profit ratio hovering around a modest 5% or even less.


### **IV. Balance Sheet:**
The preparation of the balance sheet mirrored the approach taken for the income statement. It unveiled a robust financial position for GL Retail, exemplified by a current ratio of 2.25 and a debt ratio of 0.04. This comprehensive report facilitates a detailed exploration, allowing for in-depth analysis of the financial positions on a monthly, quarterly, bi-annual, and annual basis. A clustered column chart illustrates the relationship between current assets and liabilities, consistently maintaining a current assets-to-liabilities ratio exceeding 2:1 across all periods. This portrayal aligns with favorable financial standing standards, as indicated by current ratio benchmarks.


### **Excel** 
In Excel, utilizing pivot tables, cube formulas, and various other Excel functions, I established a unified and accessible data source for all Excel users within the company. This ensures the creation of a single source of truth, streamlining data access and enhancing consistency across the organization.




### **Conclusions**
In conclusion, the adoption of Power BI has ushered GL Retail Corporation into a new era of financial acumen. This transformative journey, led by the integration of SQL, Power Query, and Power BI, goes beyond automation and visualization. It encapsulates enhanced efficiency, reporting integrity, and a plethora of new insights, solidifying GL's standing in the FMCG retail industry.
The nuanced exploration of GL's financial landscape reveals stability in revenue and cost of sales over the past three years. The Income Statement, dynamically rendered through Power BI, not only aligns with existing Excel reports but surpasses them in depth with drill-up, drill-down, and filtering capabilities. Strategic interventions in 2021 showcase GL's adaptability and prowess in cost control.
Observations on revenue and gross margin percentage underscore GL's profitability dynamics. A dip in the gross profit ratio in 2020 signals challenges, yet strategic interventions in 2021 usher in a rebound. The analysis of income statement expenses, visualized through a waterfall chart, highlights GL's delicate balancing act between expenditure and profitability.
On the balance sheet front, GL's financial strength is evident with a current ratio of 2.25 and a debt ratio of 0.04. Monthly, quarterly, bi-annual, and annual analyses consistently portray a current assets-to-liabilities ratio exceeding 2:1, aligning with favorable financial standing standards
In essence, this data-driven approach positions GL Retail for informed decision-making in the dynamic retail landscape. The revelations from this analysis serve as a compass, guiding GL towards continued success in the FMCG retail industry.



You can interact with the dashboard here: [GL Retail Corporation Report-Power BI](https://app.powerbi.com/view?r=eyJrIjoiZGEzNGVkYWYtYTBmYy00YzQxLTk4OTMtMjU3MjdmYWM3ZGM2IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)


Your questions and contributions are highly appreciated.
