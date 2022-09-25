# School_District_Analysis
School District Analysis, Python, Jupyter Notebook

## Overview
We have analyzed all student and school state testing data. However, evidence has come forward to show that there has been some academic dishonesty, specifically with the 9th grade data at Thomas High School. To uphold state-testing standards, we have been asked to repeat the analysis, except we will be replacing math and reading scores of the ninth graders at Thomas High School with NaNs. This report will describe how these changes affected the overall analysis.

## School District Results
- How is the district summary affected?
  
  - The number of 9th graders at Thomas High School equaled 461.
  
  - Complete school district summary (with 9th grade Thomas High School data included):
  
  ![image](https://user-images.githubusercontent.com/111028230/192120279-774dd2e4-274f-452b-b9cf-31b00190bef5.png)

  - School district summary (without 9th grade Thomas High School data):
  
  ![image](https://user-images.githubusercontent.com/111028230/192120306-ef437701-826c-4fd5-a59c-5be48a8fa5c4.png)

  Although the number of 9th graders at Thomas High School (461) was small in comparison to the total number of students in the district (39,170), the NaNs had a negative affect on all categories, except one (Average Reading Score).  

- How is the school summary affected?
  - Complete school summary (with 9th grade Thomas High School data included):
  
  ![image](https://user-images.githubusercontent.com/111028230/192121402-809be451-dc86-4055-bc35-3dc383b15bc7.png)
  
  - School summary (without 9th grade Thomas High School data):

  ![image](https://user-images.githubusercontent.com/111028230/192121491-ff004c24-82a6-4056-a01c-d91305fdb11a.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - Removing the ninth grade data negatively impacted all categories. However, the difference was minimal (<1%). Thomas High School still was a top 5 school in comparison to the other schools in the district.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    There is no data for the ninth graders' math and reading scores at Thomas High School. All other grades levels (10th, 11th, and 12th) were not affected.
    
    Math scores by grade:
    
    ![image](https://user-images.githubusercontent.com/111028230/192122471-b763b5d5-98e8-4cae-a4b0-c2a9e78406b3.png)
    
    Reading scores by grade:
    
    ![image](https://user-images.githubusercontent.com/111028230/192122518-9f72d91d-b30d-48f3-b894-c6b8a1e7a098.png)

  - Scores by school spending
    - Scores by school spending were not affected.
  - Scores by school size
    - Scores by school size were not affected.
  - Scores by school type
    - Scores by school type were not affected.

## School District Summary

Overall, comparing the analysis with the complete data vs the analysis without Thomas High School ninth graders, the difference was small. Once we re-ran the anlaysis after replacing Thomas High School with NaNs, we saw that averages for math and reading and % passing in math and reading all saw a negative impact. However the impact was minimal, less than 1% in delta change.

Other aspects of the analysis, scores by school spending, size, and type, were not affected at all.

The number of ninth graders at Thomas High School (461) made up such a small segment of total number of students in the district (39,170).

One aspect to note with the new analysis is that there is no representation for the ninth graders at Thomas High School since all of that data was removed and replaced with NaNs.
