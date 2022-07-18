# School_District_Analysis

## Overview of the school district analysis
### Purpose
According to Maria and her supervisor, it seems like the student file has shown evidence of academic dishonesty. Especially with ninth graders from Thomas High School with both math grades and reading grades. Althought the extent was unknown, but everything will be hold unstill further investigation. So in this analysis, we will replace math and reading scores for 9th grade from Thomas High School with Nans, re-analyizing the data and see how it affected the overall analysis. 

### Data Replacement with NaNs

![Data_Replacement](https://user-images.githubusercontent.com/107448172/179471654-63292a23-e9bc-4305-b309-834b652ad1b1.png)

## Results:

### How is the district summary affected? 
Overall passing percentage dropped about 0.1%

Before replacement

![DSF_Old](https://user-images.githubusercontent.com/107448172/179472908-bf6ccc65-c062-47dc-a805-0e8e2065bfc1.png)

After replacement

![DSF_New](https://user-images.githubusercontent.com/107448172/179472919-a024993b-205c-43ba-b0f8-cf95553e6960.png)


### How is the school summary affected?
Percentage of student passing math dropped >= 26%.
Percentage of student passing reading >= 27%.
Overall percentage of student passing both math and reading dropped >= 25%.
Before the replacement summary

![SS_Old](https://user-images.githubusercontent.com/107448172/179475367-1abaa370-7a71-426f-b72a-67452fdd0cf6.png)

After the replacement summary 

![SS_New](https://user-images.githubusercontent.com/107448172/179475383-51a7eb40-bb8f-44b8-b384-2f213430b1f2.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The replacement has a high impact on Thomas High School's performance. It decreased by 25% when the replacement happened, which also means it helped Thomas High School 25% when the replacement never happened. 

#### How does replacing the ninth-grade scores affect the scores by school spending:

No change in school spending if you look at the before and after replacement summary above since the population remained unchanges.

Before the replacement

![Spending_Old](https://user-images.githubusercontent.com/107448172/179478388-bd1039ec-6c39-4e96-87d0-f08a2b7c6d73.png)

After the replacement

![Spending_New](https://user-images.githubusercontent.com/107448172/179478422-9c95fd25-0cc7-4c8f-abc7-5d6879861b95.png)

#### How does replacing the ninth-grade scores affect the scores by school size 

No changes is school size since the total student remained the same. 

Before the replacement

![School_Sz_Old](https://user-images.githubusercontent.com/107448172/179477881-9a135ade-b0fb-4c53-97a8-85f69e1fdf24.png)

After the replacement 

![School_Sz_New](https://user-images.githubusercontent.com/107448172/179477903-042321ac-1d80-4d77-98bd-e94b44123d66.png)

#### How does replacing the ninth-grade scores affect the scores by school type

No changes in school type since it won't affected the scores. 

Before the replacement

![School_Type_Old](https://user-images.githubusercontent.com/107448172/179477991-20cc8951-6b11-46d3-9ede-c0f0913252a5.png)

After the replacement

![School_Type_New](https://user-images.githubusercontent.com/107448172/179478009-4115f85f-85f7-4601-bddd-acd7ed14bb86.png)

## Summary: 
After the performance of the new analysis, there are a few things that we noted:

1. The overall score is not affected the entire district much when we removed 9th grade math and reading scores. 
2. The 9th grade student takes over a 25% of population and it affected the overall passing grade of Thomas High School population. 
3. The replacement of grades won't have any impact on school size, type of school and school spending budget per student. 
4. The order of top schools was not affected by the changes.                                     
             
