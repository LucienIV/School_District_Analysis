# School_District_Analysis

## Overview
### Purpose of School District Analysis


The purpose of this analysis is modify the existing dataframes from earlier research by removing the grades of the 9th Grade students at Thomas High School due to suspected academic dishonesty. Specififcally, the preceding research created dataframes to visually display the grades of students from schools in the analyzed district to show the school board how students are performing academically. The dataframes also displayed the influence of additional factors as well including the funding, size, and type of each school analyzed.

## Results
### Effects of the Modified Grades for Thomas High School 9th Graders


- How is the district summary affected?

The overall district summary was impacted much less than was initally expected.

The following is the analysis for Thomas High School prior to removing the 9th graders' scores:
![image](https://user-images.githubusercontent.com/92831138/145235850-60e9d97a-6572-4ea5-a78f-e862801096a6.png)

The next image is the analysis for Thomas High School following the replacement of the 9th graders' scores with NaN:
![image](https://user-images.githubusercontent.com/92831138/145235541-a2ae9e6e-0d90-46ea-b757-7c5ff6485b92.png)

As can be seen, the changes to the average math and reading score were not changed at all, at least once rounded to one decimal place. The percentage of passing students did show a small shift, with the largest being that 1% more studnets are now shown having passed reading in the district. The percentage of students passing math and passing both subjects also increased by .9 and .8% respectively. 

- How is the school summary affected?

The school summary was barely impacted by the change. The school summary dataframe shows the performance of students at each school and no other schools in the district would be impacted in this dataframe by the modifications to Thomas High School.

The following is the original school summary dataframe:
![image](https://user-images.githubusercontent.com/92831138/145238791-0aeca3f2-ae64-416c-8bd8-c9cfee1d9fe8.png)

This is the new information for Thomas High School following the modification:
![image](https://user-images.githubusercontent.com/92831138/145238931-0f614a2b-fc5d-47ed-a08b-d90ebf5afb12.png)

There are undeniably changes to the scores and percentage of passing for students, but the changes are so miniscule that they almost entirely disappear if rounded up to one decimal place. If the percentages are rounded up to a whole number there would be no change between the two dataframes.

- How does replacing the 9th graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Prior to the score replacements Thomas High School had the second highest percentage of students overall passing. Following the replacements their positions has not shifted. As was noted in the prior section the shift in percentagee was very minor. Griffin High School is close to being the second highest, but even after the change their overall passing percentage is still .04% lower than Thomas High School. 

- How does replacing the 9th grade scores affect the following:
  - Math and reading scores by grade
  The score replacement quite obviiously affects the scores by grade for Thomas High School since 
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary
### Changes to Analysis After Grade Modification
