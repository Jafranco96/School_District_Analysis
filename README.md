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

The comparison yields that for Thomas High School its % Passing Math percentage decreased from 93.27 to 93.18, its % Passing Reading percentage decreased from 97.30 to 97.01, and its % Overall Passing percentage decreased from 90.94 to 90.63.

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

 Original Top 5 Performing Schools:  <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/top_5_original.PNG">

 Rerun Top 5 Performing Schools:  <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/top_5_rerun.PNG">
 
While the rerun resulted in Thomas High School’s passing percentage in all categories to drop slightly, it did not impact its overall performance relative to other schools. In both the original and rerun Top 5 Performing Schools summary, it was the second best school by overall passing percentage. 

•	How does replacing the ninth-grade scores affect the following:

   o	Math and reading scores by grade
     
   Original Math Scores By Grade:
   
   
   <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/Math_scores_original.PNG">
   
   Rerun Math Scores By Grade:
   
   
   <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/Math_scores_rerun.PNG">
   
Since all scores for Thomas High School’s ninth graders were nulled out, it is nor surprising to see a value of “nan” for the average math score for the ninth graders at that school. This was the only impact the rerun had on this summary.

   Original Reading Scores By Grade:
   
   
   <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/reading_scores_original.PNG">
   
   Rerun Reading Scores By Grade:
   
   
   <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/reading_scores_rerun.PNG">
   
The same is true for the average reading scores by grade. The null value is the only differing element.

 o	Scores by school spending
     
 Original Scores By School Spending Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/spending_original.PNG">
 
 Rerun Scores By School Spending Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/spending_rerun.PNG">
 
The rerun had no effect on this summary. The original and rerun summary are both exactly the same.

 o	Scores by school size
 
 Original Scores By School Size Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/size_original.PNG">
 
 Rerun Scores By School Size Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/size_rerun.PNG">
 
Both summaries are the same as well.

 o	Scores by school type
 
  Original Scores By School Type Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/type_original.PNG">
  
  Rerun Scores By School Type Summary: <img src = "https://github.com/Jafranco96/School_District_Analysis/blob/main/Comparisons/type_rerun.PNG">

These two summaries are the same also. 

## Analysis Results Summary

To summarize for the school board, the four major changes that resulted from rerunning the analysis were:

 •	In the District Summary, Average Math Score dropped by 0.1. The % Passing Math, % Passing Reading, and % Overall Passing     percentages also all dropped by at most 0.3%.
 
•	In the School Summary, the % Passing Math, % Passing Reading, and % Overall Passing percentages for Thomas High School all dropped by less than 1%.

•	In the Math Scores by Grade Summary, there is no average for the math scores by ninth graders at Thomas High School. This is due to the null valuing as per the school board’s instructions. This specific average cannot be determined with the current compromised data.

•	In the Reading Scores by Grade Summary, there is no average for the reading scores by ninth graders at Thomas High School. This average also cannot be determined with the current data source.

With rerunning the analysis, the school board can now allocate future educational budgets based on the performance trends indicated by each summary.



