# School District Analysis

## Overview of Project
### Purpose

Maria, the chief data scientist for a city school district, has been tasked with analyzing standardized test data to determine the prevalence of any performance trends. The school board would then use the results of her analysis as justification for future budget allocations. Her analysis should include a district summary, school summary, the top 5 performing schools by overall passing rate, the bottom 5 performing schools by overall passing rate, the average math score for each grade level for each school, the average reading score for each grade level from each school, and the scores by school spending per student, by school size, and by school type. Maria utilized a jupyter notebook in a Python environment to analyze the data and delivered her initial analysis to the school board.

Reviewing her analysis, the school board has informed Maria that her raw data potentially includes altered and false data. Specifically, the reading and math grades for Thomas High School ninth grades seemed to have been manipulated. The school board has asked for the analysis to be rerun but with the aforementioned grades replaced with NaNs. The rest of the data should stay intact as is. The school board also wants to identify how each deliverable was affected by the rerun. 

## Analysis Results 
With the rerun completed, Maria determined how each deliverable was impacted by null valuing the Thomas High School ninth grade scores. The comparisons are listed below:

•	How is the district summary affected?

 Original District Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/district_summary_original.PNG">
 
 Rerun District Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/district_summary_rerun.PNG">

Comparing the two summaries, the school board can see that the rerun decreased the Average Math Score from 79 to 78.9, decreased the % Passing Math percentage from 75 to 74.8, decreased the % Passing Reading percentage from 86 to 85.7, and decreased the % Overall Passing percentage from 65 to 64.9.

•	How is the school summary affected?
   
 Original School Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/school_summary_original.PNG">
 
 Rerun District Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/school_summary_rerun.PNG">

The comparison yields that for Thomas High School its % Passing Math percentage decreased from 93.27 to 93.18, its % Passing Reading percentage creased from 97.30 to 97.01, and its % Overall Passing percentage from 90.94 to 90.63.

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

 Original Top 5 Performing Schools:  <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/top_5_original.PNG">

 Rerun Top 5 Performing Schools:  <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/top_5_rerun.PNG">

## Analysis Results Summary

