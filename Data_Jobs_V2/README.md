# Data Jobs Dashboard V2 with Power BI<br><br>


![Dashboard Page](/Images/Project_2.PNG)<br>

[View interactive dashboard here on the Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiYWFkYWNiMWItNzkwNy00Y2YwLTg1ZjUtNTA0ODhmNTZhZjcwIiwidCI6IjZjMDA1NDgxLTkyNjEtNDlhMC05YTdmLWFlMmI3MTExNDBjMyIsImMiOjEwfQ%3D%3D)<br><br>


## Introduction

This dashboard is a follow-up to the V1 version and showcases not only the skills required for data visualization, but also some advanced skills, which are listed below. The purpose of this dashboard is two fold: Firstly, to enable anyone in the world get a good grasp on the most in-demand skills for different Data jobs as well as the expected pay, and secondly, to compare the pay in Pakistan vs rest of the world.<br><br>


## Skills Showcased

-   **⚙ ETL (With Power Query)**: Prepared the data for visualization by performing multiple **transfromations**.  
- **📋Data Modeling:** Created relationships between the **fact and dimsension tables** (Star Schema)

- **🧮DAX measures:** Created simple as well as advanced DAX measures for key insights and also to compare dynamic vs fixed values.
-   **📊 Core charts:** Utilized **bar chart**  to compare skill counts by skills and also to see which skills were the most prevalent among jobs. A second **bar chart** was used to compare the salaries in Pakistan with that of the world.
- **🎯 KPI indicators:** Used **Cards**  to display key metrics, such as Median Yearly and Hourly Salaries, Job Count, and Skills required per job.
-   **🎨 Dashboard design:** Designed an intuitive and visually appealing layout, focusing on the skill count as well as the salaries.
-  **🗄Interactive Reporting:**
    - **Slicers** for dynamic filtering by Job Title and Country.
    - Added two **advanced slicers:** one using **field parameters** to toggle key Skill metrics (Job Count, Job %), and another powered by **SWITCH() in DAX** to compare Salary metrics (Median Yearly and Median Hourly) in Pakistan and globally.<br><br>
 

## Dashboard overview<br><br>
![Dashboard Page 1](/Images/Project_2.PNG)<br><br><br>
This dashboard consists of a single page. At the top are the **Title** and **slicers** (Job Title and Country), followed by **KPI's** (**Job Count, Skills per Job, Median Yearly and Hourly salaries**) and then the 2 **bar charts:** One showing the **top skills by Job Count and Job %**, and the other showing the **comparison between salaries in Pakistan and rest of the world**, which can be filtered down to a single country with the country slicer. This chart also allows you to compare salaries worldwide across different job titles.<br>A **button** at the top right **clears all slicers from the page**. <br><br>


## Conclusion:
This dashboard (Version 2.0) shows how Power BI can transform raw data into clear, streamlined analysis in just one page, allowing **Job seekers, career transitioners, and job swappers** get the relevant and mission-critical insights into the job market, helping them in making and informed decision and guiding their next career move.
