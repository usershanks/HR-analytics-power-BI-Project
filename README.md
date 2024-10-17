# HR-analytics-power-BI-Project

## Project Overview
As part of a data-driven HR initiative at Atliq Technologies, the HR department was struggling with managing and analyzing real-time employee data, including attendance, performance metrics, and employee engagement levels. The existing manual reporting process was time-consuming, prone to errors, and lacked real-time insights, which delayed decision-making.

## Challenge:
The company needed a more efficient, scalable solution that could track these metrics in real-time and provide actionable insights to improve employee performance, retention, and overall workplace satisfaction. The challenge was to design an automated and user-friendly dashboard in Power BI that would integrate with multiple data sources, including HR software, spreadsheets, and internal databases.

## Solution Approach:
Working closely with the HR team, I leveraged Power BI to build an interactive dashboard that visualized key HR metrics. Using DAX and Power Query, I was able to transform raw data into meaningful insights. I also set up real-time data connections to ensure that the dashboard would update dynamically as new data came in.

The dashboard allowed HR leaders to easily track individual and team performance, analyze trends in absenteeism, and measure employee engagement through survey data. This automation not only reduced reporting time by 50% but also provided real-time insights that empowered the HR team to make informed decisions faster.

## Tech stacks

- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)

### Questions to ask before starting with dashboard
## 1. Objective and Purpose
- **What is the primary purpose of the HR analytics dashboard?**  
  (E.g., to track employee performance, monitor retention, measure engagement, etc.)
- **What are the specific business problems or HR challenges we are trying to solve with this dashboard?**
- **What decisions will this dashboard help HR leaders make?**

## 2. Stakeholder Requirements
- **Who will be the main users of the dashboard?**  
  (E.g., HR managers, senior executives, department heads)
- **What are the key metrics that each stakeholder group needs to see?**
- **How often will the dashboard be accessed and updated?**

## 3. Data Sources and Integration
- **What data sources will the dashboard pull from?**  
  (E.g., HRIS systems, payroll software, employee surveys, attendance systems)
- **Are these data sources structured, clean, and up-to-date?**
- **How will the data be integrated and transformed?**
- **Will the data be pulled in real-time or at scheduled intervals?**

## 4. Key Metrics and KPIs
- **What are the essential HR metrics and KPIs that need to be tracked?**  
  (E.g., turnover rate, time-to-hire, absenteeism, employee satisfaction, training effectiveness)
- **Are there any specific targets or benchmarks to compare the metrics against?**
- **Do we need to measure both individual and organizational performance?**
- **Are there any compliance or regulatory metrics we need to include?**

## 5. Data Visualization
- **What type of visualizations would be most helpful for understanding the data?**  
  (E.g., bar charts, line graphs, heat maps, tables, etc.)
- **Should the dashboard support drill-down capabilities to explore data in more detail?**
- **What kind of filters or customization should the dashboard offer?**  
  (E.g., filtering by department, location, or time period)

## 6. Time Periods
- **Over what time periods should data be tracked and displayed?**  
  (E.g., weekly, monthly, quarterly, or yearly trends)
- **Do we need historical data to observe trends over time?**
- **How frequently should the dashboard update?**  
  (E.g., daily, real-time, or at specific intervals)

## 7. User Experience and Accessibility
- **How easy should the dashboard be to use for non-technical stakeholders?**
- **What level of customization do users need to personalize the dashboard view?**
- **Should the dashboard be accessible on different devices?**  
  (E.g., desktop, mobile)

## 8. Security and Permissions
- **What data privacy considerations should be taken into account?**  
  (E.g., ensuring compliance with GDPR or local data protection laws)
- **Who should have access to the dashboard, and are there different permission levels?**  
  (E.g., managers viewing department data vs. executives viewing global data)

## 9. Success Criteria and Feedback
- **How will we measure the success or effectiveness of the dashboard?**
- **What ongoing feedback mechanism will we have to ensure the dashboard continues to meet HR needs?**
- **How often should we review and adjust the dashboard as new data or needs arise?**

## Dataset loading, Cleaning and organizing
 
## Step 1: Import Data into Power Query
- The first step is to import data from various sources (e.g., Excel, CSV files, databases, or cloud services) into Power Query.
- You can access Power Query from the “Data” tab in Excel or directly in Power BI.

**Example Data Sources:**
- Employee attendance records
- Payroll data
- Employee performance ratings
- Training data

Once the data is loaded, Power Query provides a preview of the dataset, allowing you to review and transform the raw data.

---

## Step 2: Data Cleaning in Power Query
Data cleaning ensures the dataset is accurate, consistent, and ready for analysis. Some key data cleaning steps include:

### A. Removing Errors and Duplicates
- **Remove Empty Rows/Columns:** Eliminate any blank rows or columns to ensure the dataset only contains relevant data.
  - Select the table, and under the “Home” tab, click **Remove Rows** → **Remove Blank Rows**.
  
- **Remove Duplicates:** To avoid inaccurate reporting, remove duplicate entries.
  - Select the relevant column, and from the “Home” tab, choose **Remove Duplicates**.

### B. Fixing Data Types
- Ensure the **Date** fields are formatted correctly as **Date** types rather than text or numeric values.
  - Right-click on the “Date” column, select **Change Type**, and choose **Date**.

### C. Handling Missing Data
- For missing values in key fields, decide to remove or fill them in.
  - Use **Fill Down** or **Fill Up** options to populate missing cells based on previous or following data.

---

## Step 3: Arranging Data by Date and Month
Once the data is cleaned, you can arrange it based on **Date** and **Month**. This is crucial for analyzing time-based trends.

### A. Extracting Month and Year
To extract **Month** and **Year** from the **Date** column:
- Select the **Date** column.
- Go to the **Add Column** tab and choose:
  - **Date** → **Month** → **Month Name** to extract the name of the month.
  - **Date** → **Year** to extract the year.

### B. Sorting Data by Date and Month
- Select the **Date** or **Month Name** column.
- In the **Home** tab, click **Sort Ascending** or **Sort Descending** to arrange data chronologically.

You can also group data by month using the **Group By** feature to calculate aggregate metrics.

---

## Step 4: Loading Clean Data into Power BI or Excel
Once the data is cleaned, click **Close & Load** to load the processed data back into Excel or Power BI for visualization or further analysis.

---

## Practical Use Cases

- **Attendance Dashboard:** Arrange attendance data by date and month to track trends in absenteeism or punctuality.
- **Employee Performance:** Sort performance evaluation data by month to track performance over time.
- **Retention Analysis:** Group employee exit data by month and year to observe trends in turnover.
 
 ### Dashboard View
![hr analytics](https://github.com/user-attachments/assets/9fd8b277-e4cf-42d9-9500-db2b1051d72e)

## Project Outcome
## 1. Data-Driven Decision Making
- **Improved Decision-Making**: HR leaders and managers can make more informed, data-driven decisions regarding hiring, performance management, employee retention, and workforce planning.
- **Actionable Insights**: The dashboard provides real-time insights into workforce trends, allowing HR to quickly address issues like high turnover, absenteeism, or low employee engagement.

## 2. Enhanced HR Efficiency
- **Automation of Reporting**: The dashboard automates routine reporting processes, reducing the manual effort required to collect, clean, and analyze HR data.
- **Time Savings**: Significant reduction in time spent on manual data preparation and report generation, freeing HR teams to focus on strategic initiatives.

## 3. Monitoring and Improving Employee Performance
- **Tracking Key Performance Indicators (KPIs)**: HR can closely monitor KPIs such as employee performance, productivity, and satisfaction, helping to identify top performers or areas for improvement.
- **Performance Trends**: By arranging data by date and month, HR leaders can observe performance trends over time and implement timely interventions.

## 4. Proactive Talent Management
- **Predictive Analytics**: The dashboard enables predictive analysis to identify patterns, such as employees at risk of leaving, and helps the organization take preemptive actions to retain top talent.
- **Talent Development**: Insights from the dashboard help in identifying skill gaps, leading to better planning for training and development programs.

## 5. Employee Retention and Engagement
- **Retention Tracking**: The dashboard can track retention rates and provide insights into reasons for employee exits, helping HR design targeted retention strategies.
- **Improved Engagement**: By measuring employee satisfaction and engagement through metrics, HR can take steps to enhance the work environment and improve employee morale.

## 6. Compliance and Risk Management
- **Regulatory Compliance**: Monitoring compliance metrics ensures the organization adheres to labor laws and regulations (e.g., working hours, overtime, diversity tracking).
- **Risk Mitigation**: Identifying trends related to high turnover, absenteeism, or other HR risks can help HR leaders address issues before they escalate into larger problems.

## 7. Customization and Flexibility for Stakeholders
- **Tailored Views for Stakeholders**: Different departments or managerial levels can have customized views to access the most relevant data, ensuring that each stakeholder sees the information they need.
- **Accessibility and User-Friendliness**: The dashboard can be accessible across devices and is designed to be intuitive for both technical and non-technical users, enhancing its utility across the organization.

## 8. Continuous Improvement
- **Ongoing Feedback Loop**: The dashboard allows for continuous monitoring of HR strategies and initiatives. HR can adjust policies and programs based on real-time data, ensuring constant improvement in workforce management.
- **Performance Benchmarking**: HR can set benchmarks for performance and continuously measure progress, fostering a culture of accountability and improvement.

## 9. Alignment with Business Objectives
- **Strategic HR Alignment**: The dashboard aligns HR activities with overall business objectives, ensuring that workforce management contributes directly to achieving the company’s strategic goals.
- **Impact on Organizational Success**: By enabling better workforce planning, performance management, and talent retention, the HR analytics dashboard contributes to long-term organizational success.

