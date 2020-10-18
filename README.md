# School District Analysis

## Overview of the School District analysis

Tasked with preparing all standardizrd math and reading test data for analysis, reporting, and presentation to provide insights about performance trends and patterns.  These insights are used to inform discussions and strategic decisions at the school and district level.

After initial analysis was completed, it was noted that all the 9th grade math and reading scores were altered (academic dishonesty) and needed to be removed from the analysis.  These scores were replaced with NaN in the student dataset and the analysis was repeated.

A comparison of the two analyses for key insights is provided below.

Resources - Data Sources : schools_complete.csv, students_complete.csv; Software: Python 3.8; Jupyter Notebook 6.1.1; Libraries: pandas, numpy

## School District Results

Comparison of District Summary from orignal analysis and revised analysis (without Thomas HS 9th grade scores) shown below:

Original:

![District_original](https://user-images.githubusercontent.com/71353552/96372035-3030d900-1122-11eb-9418-9e6754d9f677.PNG)

Revised:

![District_revised](https://user-images.githubusercontent.com/71353552/96372037-32933300-1122-11eb-8adb-3a91233cd237.PNG)

  - Revised Average Math Score lower by 0.1; from 79.0 to 78.9
  - Revised Average Reading Score unchanged at 81.9
  - Revised % Passing Math lower by 20 bps; from 75.0% to 74.8%
  - Revised % Passing Reading lower by 10 bps; from 85.8% to 85.7%
  - Revised % Overall Passing lower by 30 bps; from 65.2% to 64.9%
  
Revised school summary:

![School_Summary_revised](https://user-images.githubusercontent.com/71353552/96372684-33799400-1125-11eb-9737-561ef0a2c5bc.PNG)

All schools unchanged in revised analysis with the exception of Thomas High School where the 9th grade scores were changed 

Original Thomas HS:

![Thomas_original](https://user-images.githubusercontent.com/71353552/96372754-a256ed00-1125-11eb-9533-f9d1b2a923e4.PNG)

Nominal changes in Thomas HS are summarized below:
  - Revised Average Math Score lower by 7 bps; from 83.42 to 83.35
  - Revised Average Reading Score higher by 5 bps; from 83.85 to 83.90
  - Revised % Passing Math lower by 8 bps; from 93.27% to 93.19%
  - Revised % Passing Reading lower by 29 bps; from 97.31% to 97.02%
  - Revised % Overall Passing lower by 32 bps; from 90.95% to 90.63%

Top 5 schools by Overall Passing: (revised analysis) :

![Top5_revised](https://user-images.githubusercontent.com/71353552/96373853-5bb8c100-112c-11eb-9f5e-ef72a9578746.PNG)

Bottom 5 schools by Overall Passing: (revised analysis

![Bottom5_revised](https://user-images.githubusercontent.com/71353552/96373855-5d828480-112c-11eb-9023-1774baa82c6d.PNG)

Math Scores (left) and Reading Scores (right) by Grade: (revised analysis)

![MathbyGrade_revised](https://user-images.githubusercontent.com/71353552/96373861-65422900-112c-11eb-938c-02b760a9e4e7.PNG)
![ReadingbyGrade_revised](https://user-images.githubusercontent.com/71353552/96373871-75f29f00-112c-11eb-8378-26f65832cbec.PNG)

Scores by Spending : (revised)

![ScoresbySpending_revised](https://user-images.githubusercontent.com/71353552/96373881-80149d80-112c-11eb-939a-61a8e0796701.PNG)

Scores by School Size (revised)

![ScorebySize_revised](https://user-images.githubusercontent.com/71353552/96373882-84d95180-112c-11eb-8292-bf628a779650.PNG)

Scores by School Type (revised)

![ScorebyType_revised](https://user-images.githubusercontent.com/71353552/96373886-873bab80-112c-11eb-8e99-ab7c0e47caa6.PNG)



## School District Summary

Summarize four (4) major changes in the updated analysis after the Thomas HS scores have been replaced with NaNs

  

