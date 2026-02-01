# Student-Placement-Analysis
Power BI Dashboard Project

📌 Project Overview

This project focuses on analyzing student placement outcomes using academic performance, technical skills, internships, and demographic data. The objective is to identify key factors influencing placements and present insights through an interactive Power BI dashboard.

The dataset was sourced from Kaggle and processed end-to-end using Power BI (Power Query + DAX).

🎯 Objectives
Analyze placement rates across different degrees, branches, and demographics/
Identify the impact of CGPA, coding skills, and internships on placement outcomes/
Build interactive KPIs and visuals for data-driven insights/
Practice real-world data cleaning, modeling, and visualization/

🗂️ Dataset Information

Source: Kaggle
Records: 50,000 students
Files: Train & Test datasets (appended as a continuous dataset)

Key Columns:
Degree/
Branch/
Gender/
CGPA/
Coding Skills/
Internships/
Certifications/
Placement Status/

🧹 Data Cleaning & Preparation (Power Query – Power BI)

The following steps were performed using Power Query:

Imported Train and Test datasets from CSV files/
Appended both files to create a single continuous dataset/
Removed unnecessary columns and handled inconsistencies/
Changed appropriate data types (numeric, text, whole numbers)/
Renamed columns for clarity and consistency/
Validated categorical values (Placement Status, Degree, Branch)/
Loaded cleaned data into the Power BI data model/

📐 Data Modeling & DAX Measures

Key DAX measures created:

Total Students/
Placed Students/
Not Placed Students/
Placement Rate (%)/
Average CGPA (Placed Students)/
Average Coding Skill (Placed Students)/

These measures dynamically update based on slicer selections.

📊 Dashboard Features
🔑 KPIs

Total Students/
Placed Students/
Not Placed Students/
Placement Rate (%)/
Average CGPA (Placed)/
Average Coding Skill (Placed)

📈 Visualizations

Placement Distribution (Donut Chart)/
CGPA by Placement Status/
Placements by Degree/
Placements by Branch/
Internships vs Placements/
Skills Impact (Scatter Plot: Coding Skills vs CGPA)

🎛️ Slicers

Degree/
Branch/
Gender/
Placement Status/

All visuals are fully interactive and respond to slicer selections.

🔍 Key Insights

Only 36% of students are placed, indicating a significant employability gap
Higher CGPA and coding skills strongly correlate with placement success
Students with internship experience have better placement outcomes
Tech-focused branches (CSE, IT) show higher placement numbers
Skills and practical exposure matter more than degree alone

💡 Recommendations

Strengthen technical and coding skill training programs/
Introduce mandatory internships or industry projects/
Provide targeted support for low-performing or at-risk students/
Develop branch-specific placement strategies/

🛠️ Tools & Technologies

Power BI Desktop/
Power Query/
DAX/
CSV (Kaggle Dataset)

🚀 Conclusion

This project demonstrates end-to-end data analysis and visualization skills using Power BI, from raw data cleaning to interactive dashboard creation and insight generation. It reflects a real-world education and HR analytics use case.
