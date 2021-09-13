# School_District_Analysis
## Overview
The purpose of this analysis is to provide analytical summaries on the affecting averages of school grades, amount of school district budgets, academic passing rates, school size and types. This information is being provided to stakeholders to make decisions for the schools upcoming year to check for correlations between school budgeting, grades and sizes. 

A comparison is being analyzed finding differences in the data to exclude 9th grade reading and math scores due to a academic dishonesty found in state-testing standards at Thomas High School. In order to compare, we excluded those scores from the analysis.

## Results
#### District Summary
We are analyzing 15 school districts with a total of 39,170 students with a total budget is $24,649,428.00. The percent of students passing math stands at 74%, with the percent of students passing reading at 85%. The average math score is 79 in comparison to 82 for reading. The overall percentage of students passing is 64%.

<img width="1153" alt="District Summary" src="https://user-images.githubusercontent.com/88520573/133010345-bc54704d-c90d-4361-a0c1-76f04d2fc04e.png">

###### How is the district summary affected?
The district summary saw an overall decrease in % Passing Math, % Passing Reading, and Average Math Score. 
Original District Summary (includes 9th grade scores at Thomas High School)
<img width="990" alt="District Summary Original" src="https://user-images.githubusercontent.com/88520573/133019224-74b62714-7a36-4153-aaf1-c6c99cade9eb.png">

#### School Summary
There are a total of 7 District schools and 8 Charter schools, each school ranging from 1 to 3.2 million dollars in school budgeting. The Per Student budget is contingent on the total # of students which ranged from up to $584 to $675. 

<img width="995" alt="Per School Summary" src="https://user-images.githubusercontent.com/88520573/133011493-72ea7dfc-73b4-4bd5-bb26-43fb3a18be77.png">

###### How is the school summary affected?
Overall, the school summary is not significantly affected aside from Thomas High School. Thomas High School has an outlier in the Overall % Passing at 2.7% and a significant drop on % Passing Reading from 97% to 65%.

###### New School Summary: Thomas High School
<img width="967" alt="THS_School_Summary_new" src="https://user-images.githubusercontent.com/88520573/133019936-417074ca-e2c1-4269-aa36-46c4987d33c9.png">
###### Original School Summary: Thomas High School
<img width="978" alt="THS_School Summary_Orig" src="https://user-images.githubusercontent.com/88520573/133019913-a741f5f1-8b31-47cd-896f-a36abeaede43.png">


#### Top and Bottom 5 Performing Schools
##### Top Performing Schools
The top five performing schools overall passing % ranges from 96% to 97%. The highest performing high school is Cabrera High School.
<img width="994" alt="Top Schools" src="https://user-images.githubusercontent.com/88520573/133011435-82503f5b-334a-4426-a32b-8495940e940f.png">

##### Bottom Performing Schools
The bottom five performing schools overall passing% range between 52% to 53%. The lowest performing high school is Rodriguez High School.
<img width="990" alt="Bottom Schools" src="https://user-images.githubusercontent.com/88520573/133011439-267b3f75-19f7-41c7-8940-b4869b774dec.png">

##### Reading Scores by Grade
<img width="378" alt="Reading Scores by Grade" src="https://user-images.githubusercontent.com/88520573/133013991-d1c72c44-80c2-47f0-af86-881e4e4e9453.png">

##### Math Scores by Grade
<img width="373" alt="Math Scores By Grade" src="https://user-images.githubusercontent.com/88520573/133014004-fcbd8a11-c701-4516-9d0b-ab30cc69f12c.png">

##### Scores by School Type
<img width="885" alt="Scores by School Type" src="https://user-images.githubusercontent.com/88520573/133017092-55c695e2-9e3a-49fc-802c-7cca6526ee32.png">

##### Spending Summary
<img width="992" alt="Spending Summary" src="https://user-images.githubusercontent.com/88520573/133014490-44d72aca-672b-4561-bc79-e778830fc419.png">


##### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Many categories in the school summary sees a decreases in the following categories:
<ul>
  <li> Overall % Passing </li>
 
  <li> Middle Size Schools</li>
 
  <li> Reading Scores </li>
 
  <li> Scores by School Spending </li>
</ul>

## Summary Analysis: 

<ul>
  <li> Math and reading scores by grade: The overall average scores for reading decreases for all schools in reading when replacing the 9th grade scores for Thomas High School. There were no changes to the math scores for each school except for Thomas High School. </li>
  
<img width="371" alt="Math Scores By Grade_Original" src="https://user-images.githubusercontent.com/88520573/133017705-7fa26876-6eb1-45d7-a855-ce7ca4ba8e8d.png">
<img width="373" alt="Reading Scores By Grade_Orig" src="https://user-images.githubusercontent.com/88520573/133017709-1e295e58-35e0-491e-97c7-262256fc050c.png">
 
  <li> Scores by school spending : In the spending summary, the overall % passing is significantly lower in the $630-644 spending ranges per student. After removing the 9th grade students from Thomas High School, that percent dropped from 56% to 41%. Subsequently, the Overall % Passing on the School Summary changed from 65% to 2.7%, which shows there's a possible outlier in the data without the 9th grade reading and math scores. </li>
  
  Thomas High School Summary excluding 9th grade scores
  <img width="992" alt="Spending Summary_original" src="https://user-images.githubusercontent.com/88520573/133016655-9f3d7f14-12da-4caf-b720-111fae453c6b.png">

  Thomas High School Original Summary
  <img width="999" alt="THS School Summary _original" src="https://user-images.githubusercontent.com/88520573/133016590-82f30a0f-8f48-42f3-9f87-16759f008d04.png">
  
  <li> Scores by school size : When looking at the School size summaries we can see a decline also in the medium(1,000-2,000) school size range. This decreased from and 85% Overall Passing to 73% overall passing. </li>

<img width="949" alt="School Size Summary_original" src="https://user-images.githubusercontent.com/88520573/133016506-eba8b03b-575f-42ca-9fd1-c750539f1f40.png">
  
  <li> Scores by school type : The overall % passings by school type, the Charter school type decreases from 87% to 79%, while District type schools are unaffected and remain the same at 54%. </li>

  <img width="882" alt="Scores by Type_original" src="https://user-images.githubusercontent.com/88520573/133016414-8a33d506-0efb-4a40-941b-4ce6743e8c0c.png">

</ul>
