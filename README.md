# Analysis of School Districts Using Python/Pandas/Jupyter

In this project I assisted Maria, a chief data scientist for a city school district, in providing insights to performance trends and patterns to be able to inform discussions and strategic decisions at the school and disctrict level. Using data on student funding, student's standardized test scores, and school information, we will be able to showcase trends in school performance so that the school board can make decisions on budgets and school priorities. 
Unfortunately, when initial analysis took place, there was evidence of academic dishonesty from one of the grade levels from a high school in the data provided. In order to maintain the integrity of the data, we were tasked with removing this specific high school's grade-level and write up a report to describe how removing this specific grade level affecred the overall analysis. 
# Resources
* Data Source: schools_complete.csv & students_complete.csv
* Software: Python 3.8.9, Jupyter Notebook 6.4.6

# Results
## Effects on District Summary: 
* Prior to removing school grade-level:
  ![PRE - District Summary](https://user-images.githubusercontent.com/94571150/146498066-90bd3c46-feda-4e65-b6be-1163b72d1d38.png)
* After removing school grade-level:
  ![POST - District Summary](https://user-images.githubusercontent.com/94571150/146498274-ad1b0c60-eae7-41b4-a4ee-346c13a7f4c0.png)

## Effects on School Summary:
* Prior to removing school grade-level:
<img width="1117" alt="Screen Shot 2021-12-16 at 10 24 25 PM" src="https://user-images.githubusercontent.com/94571150/146499096-9a4aec69-67b6-4672-be44-8a17652ff4bf.png"> <img width="1104" alt="PRE - School Summary - THS" src="https://user-images.githubusercontent.com/94571150/146498892-4c49c24c-cd9e-45af-96ef-c330a6ea47a6.png">
* After removing school grade-level:
<img width="1103" alt="POST - School Summary - THS" src="https://user-images.githubusercontent.com/94571150/146498918-02fe0d75-5f85-4e14-b647-ce56fcd6fda4.png">

## Top 5 Schools - Overall Passing Scores:
* Prior to removing school grade-level:
![PRE - Top 5 School Overall Passing'](https://user-images.githubusercontent.com/94571150/146502270-6abb1d54-80da-4029-8c36-c6033a309ac6.png)

* After removing school grade-level:
![POST - Top 5 Schools - Overall Passing](https://user-images.githubusercontent.com/94571150/146499337-27f81942-7edf-43b3-9305-832d2fa946f6.png)

## Math & Reading Score By Grade
* Prior to removing school grade-level:

<img width="312" alt="PRE - Math scores by grade" src="https://user-images.githubusercontent.com/94571150/146500814-6776bf78-98c4-4f66-be04-e5cf4d3b11b0.png"> ![PRE - Reading scores by grade](https://user-images.githubusercontent.com/94571150/146502842-2b36bf63-0f58-4230-afaa-400c645f2c7c.png)

* After removing school grade-level: 

 ![POST - Math scores by grade](https://user-images.githubusercontent.com/94571150/146500027-c2252c8b-01d9-4679-b4ff-9ed7129dcfa1.png)
 ![POST - Reading scores by grade](https://user-images.githubusercontent.com/94571150/146500294-4b160e89-65ad-4ff2-ab7e-5691bde34060.png)

## Scores By School Spending
* Prior to removing school grade-level:
![PRE - Spending Summary](https://user-images.githubusercontent.com/94571150/146501124-894bb0da-191f-46fe-9b21-4d8f3fca006c.png)

* After removing school grade-level: 
![POST - Spending Summary](https://user-images.githubusercontent.com/94571150/146501155-a58fb32a-5165-4a83-b812-c10a9a063a5c.png)

## Scores By School Size
* Prior to removing school grade-level:
![PRE - Scores by School Size](https://user-images.githubusercontent.com/94571150/146501315-dac01399-a04e-4044-8b8c-806bcfb07cb1.png)

* After removing school grade-level: 
![POST - Scores by School Size](https://user-images.githubusercontent.com/94571150/146501324-aa5b1b00-d404-4545-997f-ad2efa5ec0e2.png)

## Scores By School Type
* Prior to removing school grade-level:
![PRE - Scores by School Type](https://user-images.githubusercontent.com/94571150/146501393-d23d4f93-a66f-425a-80c7-a316707b05d5.png)

* After removing school grade-level: 
![POST - Scores by School Type](https://user-images.githubusercontent.com/94571150/146501406-4f396c22-54d8-4288-a650-bceee70083a9.png)

# Summary
In terms of the updated school district analysis after reading and math scores for the ninth grade at Thomas High School has been replaced with NaNs, there are a few changes that can be noted.
1. The District Summary showed a slight decrease of roughly .3% in each category of math and reading scores. 
2. The School Summary showed a slight decrease of roughly .3% in each category of math, reading, and percentage of overall scores.
3. In comparison with other schools, Thomas High School remained second in ranking for overal passing scores. However, there was a slight decrease of .3% in percentage of overall scores. 
4. The visible difference in math and reading scores by grade is the replacement of the ninth grade at Thomas High School with NaNs.
5. There were no significant changes in scores by school spending, scores by school size, or scores by school type.

