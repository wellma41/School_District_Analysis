# School_District_Analysis

## Overview of the school district analysis
	The purpose of the analysis was to quantify and qualify the performance of schools based on various metrics and categorizations.
	In addition, this analysis was preformed to gain a more accurate picture of the performance of these schools after suspisious test scores were removed.
	There are boradly speaking 7 analysis I've made in this file
	-The percent of students passing reading, math, and overall (meaning they passed both) per school.
	-The top 5 schools in terms of overall passing rate
	-The botom 5 schools in terms of overall passing rate
	-The average scores for math and reading per grade for each school
	-The scores by spending per student
	-School size and its relationship toward score
	-Score averages by the type of school (district or charter) 
	

## Results
	
### District Summary
	After our audit of Thomas High School it was found that the overall passing percentage of districts decreased by one point.
	
![District Summary Before](https://user-images.githubusercontent.com/90660790/138393487-eafbde9d-70ee-437e-959c-d18d288324f7.png)
	
![District Summary After](https://user-images.githubusercontent.com/90660790/138393465-a8d72a2a-42f3-44eb-81de-c6fdee89b746.png)

### School Summary 
	After the audit we saw Thomas High School's overall passing percentage droped by about 0.21 percent.
	
![THS Summary Before](https://user-images.githubusercontent.com/90660790/138393707-d32f7f52-9cc2-4869-8c3c-80d7cfd2dd4d.png)
	
![THS Summary After](https://user-images.githubusercontent.com/90660790/138393773-50639d16-6f45-49ed-b108-1e0e9f0e3e90.png)


### Relative Performance
	Even after the audit Thomas High School still ranked 2nd in terms of overall passing rate.
	
	(top before)
	(top after)

### Other metrics affected by the audit
	-After the Audit Thomas High Schools 9th grade math and reading scores went from 83.6 and 83.7 respectively to NaN. 
	

	- Thomas High School is in the 630-644 range of spending so that was the only range affected.
	We saw a small drop in average overall passing rate of 0.08% in that spending range
	
![Spending Before](https://user-images.githubusercontent.com/90660790/138393814-e6f62379-30de-4e1c-a3c7-e9c6ebe8819e.png)

![Spending After](https://user-images.githubusercontent.com/90660790/138393836-af902af7-5139-4838-8023-7e505e5c7b62.png)


	- The difference between the scores by school type was small enough that it becomes negligible when you format to one decimal place.
	However, since Thomas High School was a charter school, we do see a 0.04% drop in overall passing when looking at the unformated data frame.

![Type Summary Before](https://user-images.githubusercontent.com/90660790/138393869-b9923264-7312-4584-b09d-d67ec0e76766.png)

![Type Summary After](https://user-images.githubusercontent.com/90660790/138393911-73b01c74-f307-4741-b47a-757eba789b95.png)


	- The difference in scores by size is small enought to the point that it becomes nigligible when you format to one deciaml place.  
	However, since Thomas High School was a middle sized school (1000-2000 students), we do see a 0.07% drop in overall passing when looking at the unformated data frame.
	
![Size Summary Before](https://user-images.githubusercontent.com/90660790/138393943-f4cda604-c922-4716-a6dc-d33d5f859bb3.png)

	
![Size Summary After](https://user-images.githubusercontent.com/90660790/138393989-3e24f9f8-e07d-4720-ab0f-1844a8d4e7c6.png)
	
	
## Summary
	Changes after the audit
	-We saw Thomas High School's preformance metrics decrease slightly
	-While still ranked 2nd in the top schools the margin between 2nd and 3rd has decreased from 0.35 % to  0.03 %
	-Middle sized schools saw a slight drop in all metrics
	-Charter schools saw an slight drop in all metrics as well.

 
