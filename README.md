# School_District_Analysis

## Overview
School data will be analyzed against student test scores to identify any correlation in student outcomes with school types, size, and budget per student. The data analyzed consist of approximately 39,000 student test results from 15 schools.

## Results
Allegations have been made that 9th grade testing scores from Thomas High SChool have been compromised. As such, a seperate set of analysis will be performed with Thomas High School ninth grade data removed. The unfiltered dataset are part of the "Iniital" results, and the filtered data is reported as the "Adjusted" results.


|Analysis| Dataset | Results | Interpretation|
| --- | --- |---|---|
|Spending|Initial|![](resources/School_Spending.png)|Overall, students from schools with smaller budgets per student seem to achieve both higher averages and passing rates than schools with higher budgets per student. Math scores look to vary more than reading scores. As well, the overall % of students passing are far more sensitve than the average scores.|
||Adjusted|![](resources/Adj_Spending.png)|The adjusted dataset is identical to the initial|
|Student Size|Initial|![](resources/School_Size.png)|Small(<1000) and Medium (1000-2000) student sized school have very comparable results. Hwoever, there is a consistent decline in performance across all metrics in Large (2000-5000) student-sized schools.|
||Adjusted|![](resources/Adj_Size.png)|The adjusted dataset is identical to the initial|
|School Type|Initial|![](resources/School_Type.png)|Charter schools consistently out-perform District schools in all metrics. The discpreancy is particularly larger in % Passing Math and % Overall Passing|
||Adjusted|![](resources/Adj_Type.png)|The adjusted dataset is identical to the initial|

