# School_District_Analysis

## Overview
### Purpose of School District Analysis


The purpose of this analysis is modify the existing dataframes from earlier research by removing the grades of the 9th Grade students at Thomas High School due to suspected academic dishonesty. Specifically, the preceding research created dataframes to visually display the grades of students from schools in the analyzed district to show the school board how students are performing academically. The dataframes also displayed the influence of additional factors as well including the funding, size, and type of each school analyzed.

## Results
### Effects of the Modified Grades for Thomas High School 9th Graders


- How is the district summary affected?

The overall district summary was impacted much less than was initially expected.

The following is the analysis for Thomas High School prior to removing the 9th graders' scores:
![image](https://user-images.githubusercontent.com/92831138/145235850-60e9d97a-6572-4ea5-a78f-e862801096a6.png)

The next image is the analysis for Thomas High School following the replacement of the 9th graders' scores with NaN:
![image](https://user-images.githubusercontent.com/92831138/145235541-a2ae9e6e-0d90-46ea-b757-7c5ff6485b92.png)

As can be seen, the changes to the average math and reading score were not changed at all, at least once rounded to one decimal place. The percentage of passing students did show a small shift, with the largest being that 1% more students are now shown having passed reading in the district. The percentage of students passing math and passing both subjects also increased by .9 and .8% respectively. 

- How is the school summary affected?

The school summary was barely impacted by the change. The school summary dataframe shows the performance of students at each school and no other schools in the district would be impacted in this dataframe by the modifications to Thomas High School.

The following is the original school summary dataframe:
![image](https://user-images.githubusercontent.com/92831138/145238791-0aeca3f2-ae64-416c-8bd8-c9cfee1d9fe8.png)

This is the new information for Thomas High School following the modification:
![image](https://user-images.githubusercontent.com/92831138/145238931-0f614a2b-fc5d-47ed-a08b-d90ebf5afb12.png)

There are undeniably changes to the scores and percentage of passing for students, but the changes are so miniscule that they almost entirely disappear if rounded up to one decimal place. If the percentages are rounded up to a whole number there would be no change between the two dataframes.

- How does replacing the 9th graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Prior to the score replacements Thomas High School had the second highest percentage of students overall passing. Following the replacements their positions has not shifted. As was noted in the prior section the shift in percentage was very minor. Griffin High School is close to being the second highest, but even after the change their overall passing percentage is still .04% lower than Thomas High School. 

- How does replacing the 9th grade scores affect the following:
  - Math and reading scores by grade
  
  The score replacement quite obviously affects the scores by grade for Thomas High School since the 9th grade scores for the school just show a NaN for the value. Naturally, nothing else in the dataframes will be altered by the modifications.
 
  - Scores by school spending
  
  The bracket for the $630-644 bracket was minutely impacted by the replacement of grades due to that being the bracket Thomas High School is in. The change is indeed minute however, never causing a shift of more than .1%. As a result there is not even a discernable change in the final product once all columns have been formatted. 

  - Scores by school size
  
  As was the case for the school spending dataframe, once formatting is done there is no noticeable impact to this dataframe as a result of the replacement of grades. The output is exactly the same as that of the original analysis. 

  - Scores by school type
  
  Much like the school spending and school size dataframes, there is no change to this dataframe either after formatting. All changes caused by the replacement of the grades were too minute to show an impact in this dataframe. 

## Summary
### Changes to Analysis After Grade Modification

Overall, there was little noticeable impact from the replacement of the Thomas High School 9th Graders' grades. The district summary showed the largest shift of any dataframe due to the .8 to 1% shift in the passing percentage of students. The school summary showed some minute differences in the original output, but once formatting was corrected the differences were not enough to cause any change when compared to the output of the original analysis. Thomas High School remained the school with the second highest percentage of students passing both subjects, though the gap between it and the school in third place was closer than it had been prior to the grade replacement. The math and reading scores by grade showed an obvious but expected change in that the Thomas High School 9th graders had a NaN for their grade average. As was stated above, the analysis of scores by school spending, school size, and school type showed no change after formatting. Overall, the replacement of grades had very little impact on the analysis as a whole. Had the 9th graders' grades been replaced with a 0 instead of NaN then the analysis would have returned drastically different results, but as it stands simply disregarding them for the analysis caused little change. 
