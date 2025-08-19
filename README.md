# Global AI Job Market & Salary Trends — Power BI Dashboard
A detailed Power BI dashboard analyzing job market data based on various parameters like job category, experience level, company size, employment type, and more.

**🔍 What this project answers**

 - What is the average/median salary across roles and experience levels?

 - How do company sizes differ in pay and job volume?

 - What share of jobs fall into salary brackets (<60K, 60–100K, 100K+)?

 - How are remote vs on‑site jobs evolving?

 - Which skills and job titles are most in‑demand and best paid?

🔍 **Project Objective**

 - To analyze the latest job trends using an interactive dashboard, helping users explore:

 - Top job categories by demand

 - Job distribution across industries

  - Experience-level insights

 - Salary patterns by company size and type

 - Filter-based exploration (e.g., employment type, job level)

**🧰 Tech & Skills demonstrated**

 - Power BI Desktop (data modeling, visuals, theming)

 - Power Query (cleaning, normalization, splitting skills, unpivoting)

 - DAX (measures for Avg/Median/StdDev/Brackets, time intelligence)

 - UX features: custom tooltip page, slicer panel, Reset Filters bookmark/button, consistent titles & layout grid.

🧰 **Tools Used**

 - Power BI (for data modeling, visualization, DAX calculations)

 - Excel (for data cleaning/preparation)

📁 Project Files

 - Job_Market_Dashboard.pbix → [Main Power BI file](https://drive.google.com/file/d/14bmnN0IfTsuwV2IoSgaKw732_6hKETuN/view?usp=drive_link)

- Job_Data.csv → [Click here to view the dataset](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)

<img width="1300" height="724" alt="Image" src="https://github.com/user-attachments/assets/92fa19f6-590b-427c-8a49-3c959f3174b9" />

**📐 Key DAX measures (excerpt)**

 - Avg Salary = AVERAGE(main_dataset[salary_usd])

 - Median Salary = MEDIAN(main_dataset[salary_usd])

 - Max Salary = MAX(main_dataset[salary_usd])

 - Min Salary = MIN(main_dataset[salary_usd])

 - Job Count = DISTINCTCOUNT(main_dataset[job_id])

 - Salary StdDev = STDEV.P(main_dataset[salary_usd])

 - Posting Month = FORMAT(MAX(main_dataset[posting_date]), "MMM yyyy")

📊 **Dashboard Highlights**

**KPIs**

Maximum Salary, Minimum Salary, Total Jobs, Average Salary (all slicer‑aware)

**Visuals**

 - Avg Salary by Experience Level (bar)

 - Average Salary by Company Size (column)

 - Salary Brackets share (donut/pie)

 - Top 5 Jobs by Avg Salary (column)

 - Job Count by Employment Type (line/area)

 - Count of Jobs by Month with Remote Type (multi‑line)

 - Company Location table with job counts

 - Skills table with average salary

**Filters (slicers)**

 - Mode of Work (Fully remote / Hybrid / No remote)

 - Experience Level (Entry / Senior / Executive)

 - Job Industry

**Interactions**

 - Reset button (Bookmark) to clear all slicers to defaults

 - Custom Tooltip on key visuals (e.g., salary trend by company size, or top job titles within the hovered segment)

🗂️ How to Use

[Download the .pbix file.](https://drive.google.com/file/d/14bmnN0IfTsuwV2IoSgaKw732_6hKETuN/view?usp=drive_link)

Open it in Power BI Desktop.

Use the filters to interact with different visuals.

Hover over visuals to see the tooltip insights.

(Due to Power BI restrictions on personal accounts, the dashboard is available as screenshots and a .pbix file.)

🤝 Connect with Me

Feel free to connect if you have questions or want to collaborate:

📧 aman.kr.9161@gmail.com

💼  [LinkedIn](https://www.linkedin.com/in/aman-kumar-data-analyst/)

⭐ Star this repo if you found it helpful!


