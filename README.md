# School District Analysis using Panda and Jupyter
## Overview of the school district analysis
The purpose of this project is to analyze the academic record of a school district based on the followings:
1.	Passing percentage of math, reading and overall, of individual school of the district. 
2.	How academic dishonesty can impact the overall result by NOT considering the result of a specific school’s specific grade.
3.	Visualization of average subject score based on school types
4.	Visualization of average subject score based on school size
5.	The summary of district’s total student count, total budget 
6.  District budget per student as well as school spending per student and finally how these effects the overall academic results of a school

## Results
How is the district summary affected?
1.	Average math score went down from 79.0 to 78.9
2.	Average reading score apparently appears same (before and after 81.9)
3.	%age of passing math went down from 75% to 74.8%
4.	%age of passing reading went down from 86% to 85.7%
5.	%age of overall passing went down from 65% to 64.9%

Below is the snapshot of before and after results:

Before- 
![distrcict_summary_before](https://user-images.githubusercontent.com/62515666/125702215-81a17914-e720-4aa1-aade-e8215f455a88.png)
After-
 ![distrcict_summary_after](https://user-images.githubusercontent.com/62515666/125702279-9f319bf5-e59e-4f60-90c0-fcedcdfe4e79.png)

How is the school summary affected?
1.	Individual school summary remains same other than Thomas High school
2.	%age of passing in math, reading and overall significantly went down for Thomas High School

Below is the snapshot of before and after results:

Before- 

![school_summary_before](https://user-images.githubusercontent.com/62515666/125702409-ece3f5e1-74b2-4140-9a40-da7752e77e76.png)

After-

![school_summary_after](https://user-images.githubusercontent.com/62515666/125702461-8936fac0-8f10-497e-9b4d-ef6511997d43.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
1.	Passing %age of math and reading scores went down for Thomas High School in the decimal places relative to the other schools
2.	Below number shows the difference of Thomas High School before and after

![snapshot](https://user-images.githubusercontent.com/62515666/125709364-3c3c60e6-64f9-453a-ac36-4210639883b6.png)


Below snapshot shows the complete table of how it effects after replacing new student count of Thomas High School

![effect_after_replacing](https://user-images.githubusercontent.com/62515666/125702597-50c1fe72-350d-4e1c-a3c1-7688726a43a3.png)

How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade

1.	Below are the snapshots of before and after which shows ‘nan’ for 9th grade for Thomas High School

Before for math-

![math_by_grade_before](https://user-images.githubusercontent.com/62515666/125705846-096ab505-0829-43d1-82d0-5cf2af48179a.png)

After for math-

![math_by_grade_after](https://user-images.githubusercontent.com/62515666/125705981-7d71330f-ca70-4461-8090-a359a717fe30.png)

Reading score before-

![reading_by_grade_before](https://user-images.githubusercontent.com/62515666/125706163-3845fb1a-ba40-4cfa-83fc-5fe79189e70f.png)

Reading score after-

![reading_by_grade_after](https://user-images.githubusercontent.com/62515666/125706201-98c429ac-3875-4761-9e38-2efd450aef65.png)

Scores by school spending
1.	No difference observed in the scores by school spending
Before-

![scores_by_school_spending_before](https://user-images.githubusercontent.com/62515666/125702976-16c9b935-708a-4371-abf1-6000db36ea9a.png)

After-

![scores_by_school_spending_after](https://user-images.githubusercontent.com/62515666/125703004-f6b8d97d-40ec-4782-aad8-f45f765fa577.png)

Scores by school size
1.	No difference observed in the scores by school size

Before-

![scores_by_school_size_before](https://user-images.githubusercontent.com/62515666/125703054-b67ebd3c-956c-4c82-a70d-10bfec33c3b6.png)

After-

![scores_by_school_size_after](https://user-images.githubusercontent.com/62515666/125703127-135ef007-798a-4859-9a7a-d8f17c54e8ae.png)

Scores by school type
1.	No difference observed in the scores by school type

Before-

![scores_by_school_type_before](https://user-images.githubusercontent.com/62515666/125703182-db8b3254-c3d6-4b85-8f4a-7cffb9cecb80.png)

After-

![scores_by_school_type_after](https://user-images.githubusercontent.com/62515666/125703217-99ea7e36-aefa-46c3-a952-29e392759644.png)

## Summary
District summary clearly reflects that the scores for Thomas High School went down because of not considering the results of 9th grader:
1.	Average math score went down from 79.0 to 78.9
2.	%age of passing math went down from 75% to 74.8%
3.	%age of passing reading went down from 86% to 85.7%
4.	%age of overall passing went down from 65% to 64.9%
