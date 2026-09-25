Healthcare Data Analysis – Part B
Project Overview
This project performs advanced analysis on a healthcare dataset using Python. The study focuses on patient admissions, billing amounts, medical conditions, insurance providers, hospital stay duration, and correlation analysis. Various visualizations are used to identify healthcare trends and patterns.

Objectives
Analyze monthly patient admissions.
Identify peak admission periods.
Compare billing amounts across medical conditions.
Study the impact of insurance providers on billing.
Visualize billing amount distributions.
Analyze relationships between age, hospital stay duration, and billing amount.
Technologies Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook / Google Colab
Dataset Features
The dataset contains:

Patient Age
Medical Condition
Insurance Provider
Billing Amount
Date of Admission
Discharge Date
Hospital Stay Information
Project Workflow
1. Data Loading and Exploration
Load the healthcare dataset.
Display sample records.
Check dataset structure and statistics.
Identify missing values.
2. Monthly Admission Analysis
Convert admission dates into datetime format.
Extract month and year information.
Calculate the number of admissions per month.
Identify the peak admission month.
3. Billing Amount Analysis
Billing data is grouped by:

Medical Condition
Insurance Provider
A stacked bar chart is used to compare total billing amounts among different categories.

4. Billing Distribution by Medical Condition
A violin plot is used to:

Analyze billing amount variations.
Compare treatment costs across medical conditions.
Identify high-cost and low-cost conditions.
5. Billing Distribution by Insurance Provider
Another violin plot is created to:

Compare claim amounts across insurance providers.
Understand billing spread and variability.
6. Average Billing Analysis
The project calculates:

Average billing amount by medical condition.
Average billing amount by insurance provider.
7. Monthly Admissions Trend
A line graph is generated to visualize:

Monthly patient admissions.
Seasonal trends in healthcare demand.
Admission peaks and declines.
8. Hospital Stay Duration Analysis
Hospital stay duration is calculated using:

Stay Duration = Discharge Date − Admission Date

This helps measure how long patients remain hospitalized.

9. Correlation Analysis
A correlation matrix is created using:

Age
Stay Duration
Billing Amount
A heatmap is used to visualize relationships between these variables.

Visualizations Included
Stacked Bar Chart
Violin Plot (Medical Condition vs Billing Amount)
Violin Plot (Insurance Provider vs Billing Amount)
Monthly Admissions Line Chart
Correlation Heatmap
Key Insights
Healthcare costs vary across medical conditions.
Insurance providers show different billing patterns.
Monthly admissions reveal healthcare demand trends.
Correlation analysis helps identify relationships among age, hospital stay duration, and billing amount.

<img width="1290" height="657" alt="image" src="https://github.com/user-attachments/assets/4d929585-4501-4bab-b5bb-a3635d80c7fc" />
<img width="1330" height="665" alt="image" src="https://github.com/user-attachments/assets/9ff23da7-4d0d-46bf-9266-3b74495e897e" />
<img width="1362" height="631" alt="image" src="https://github.com/user-attachments/assets/8d629126-fe8c-4cd4-aaf1-6465408b723d" />



Conclusion
This project demonstrates the use of data analytics in healthcare. By analyzing admissions, billing patterns, insurance data, and patient stay durations, valuable insights can be obtained to support hospital management and healthcare decision-making.
