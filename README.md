# Recruitment Analysis and Reporting Dashboard

![RecruitmentDashboard](assets/dashboard.png)

This project aims to analyze recruitment data to provide insights into recruiter performance, applicant distribution, and time-to-hire metrics. Using Power BI, various interactive dashboards have been created to help recruitment teams optimize their processes and improve hiring efficiency. Below are the key components of the dashboard and the reports generated, as well as instructions for replicating the analysis.

## Features and Reports

### 1. Applicants by Recruiter and Stage
   - **Objective:** Display the number of applicants each recruiter is assigned, segmented by different stages in the recruitment process, such as applied, interview, offer, and hired.
   - **Metrics Included:** Number of applicants at each stage, recruiter breakdown, and totals.
   - **Visualizations:** <br>
   
  ![Vis_1](assets/Visualization_1.png)
   "Applicants Across Different Stages For Each Recruiter": A stacked bar chart that visualizes the distribution of applicants across various stages for each recruiter, such as Screening, Phone Interview, Qualifier, Trade Test, Job Offer, and Hired. <br>

   ![Vis_2](assets/Visualization_2.png)
   "Average Time Applicant Spent on Each Stage": A line chart showing the average time applicants spend in each recruitment stage, helping to identify potential bottlenecks in the process. Different colored lines represent stages like Screening, Phone Interview, Qualifier, Trade Test, and Hired.

### 2. Recruiter Performance Comparison
   - **Objective:** Compare recruiter performance in terms of the number of applicants handled and the progression percentage to each hiring stage.
   - **Metrics Included:** Number of applicants handled, and the progression rate for each stage, including Screening, Phone Interview, Qualification, Trade Test, Offer, and Hired.
   - **Visualizations:** <br>
 
![Vis_3](assets/Visualization_3.png)
   "Recruiter Performance: Applicant Progression by Stage": A 100% stacked bar chart that shows the distribution of applicants across different stages for each recruiter. This visualization helps identify the proportion of applicants advancing through various stages, providing insights into each recruiter's effectiveness in progressing candidates through the hiring process.

### 3. Distribution of Applicants Across Recruiters
   - **Objective:** Identify if there is an uneven distribution of applicants across recruiters, highlighting any disparities.
   - **Metrics Included:** Percentage distribution of applicants handled by each recruiter.
   - **Visualizations:** <br>
   
   ![Vis_4](assets/Visualization_4.png)
   "Applicant Distribution by Recruiter": A pie chart that shows the proportion of applicants assigned to each recruiter. This helps visualize whether certain recruiters are handling significantly more or fewer applicants compared to others.

### 4. Applicant-to-Hire Conversion Rate Over Time
   - **Objective:** Track and analyze applicant-to-hire conversion rates for each recruiter over a specific period.
   - **Metrics Included:** Conversion rate calculations segmented by quarters, showing trends and any seasonal variations in the hiring process.
   - **Visualizations:** <br>

![Vis_5](assets/Visualization_5.png)
   "Applicant-to-Hire Conversion Rate by Recruiter Over Time (Quarterly)": A line chart that illustrates the trends in conversion rates for each recruiter, broken down by quarters. This visualization helps identify patterns in recruiter effectiveness and potential seasonal impacts on hiring outcomes.

### 5. Average Time to Hire
   - **Objective:** Calculate and display the average time to hire for each recruiter, broken down by each recruitment stage.
   - **Metrics Included:** Average time spent at each stage, overall time to hire.
   - **Visualizations:** <br>

![Vis_6](assets/Visualization_6.png)
   "Recruiter Performance: Average Time to Hire Breakdown by Stage": A line and clustered column chart that shows the average time it takes for recruiters to progress applicants through each stage of the hiring process. This provides additional context for understanding how the time to hire may affect conversion rates.

### 6. Applicant Status Summary
   - **Objective:** Provide a snapshot of the current status of applicants (e.g., in-process, rejected, hired) for each recruiter.
   - **Metrics Included:** Status count and percentages per recruiter, historical trends.
   - **Visualizations:** <br>
![Vis_7](assets/Visualization_7.png)
![Vis_8](assets/Visualization_8.png)
Stacked bar charts and line charts displaying applicant status progression over time, including "Applicant Status Trends Over Time" and "Distribution of Applicants by Status and Recruiter".

### 7. Tracking Recruiter Efficiency Over Time
   - **Objective:** Measure recruiter efficiency through metrics such as the number of applicants processed, time to first contact, and time spent in each stage.
   - **Metrics Included:** Applicants processed, average time metrics, stage time analysis.
   - **Visualizations:** <br>
![Vis_9](assets/Visualization_9.png)
   A matrix titled "Recruiter Performance Summary: Total Applicants and Average Time Metrics" that provides an overview of each recruiter's efficiency metrics, including applicants processed, average time to first contact, and average time spent in each stage.

## Data Source and Processing
The recruitment data used for this analysis was imported from an Excel file containing information about applicants, recruiters, and recruitment stages. The data underwent cleaning and transformation processes to ensure accuracy and consistency before visualization.

## Tools and Technologies
- **Power BI**: Used for creating dashboards and data visualizations.
- **Excel**: Initial data processing and transformation.
- **Power Query and DAX (Data Analysis Expressions)**: Employed for data manipulation, calculations, and dynamic measures.


## Acknowledgments
Special thanks to the Human Resource Department of Sta. Clara International Corporation for providing the opportunity to work on this analysis project.
