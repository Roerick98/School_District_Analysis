# School_District_Analysis
## Overview of the project
### Purpose
- The purpose of this project was to conduct data analysis upon test scores from the different schools within the district and determine whether or not dishonest test scores from the Thomas High School 9th grade class affected the overall analysis. 
## Results
### How is the district summary affected?
- Comparing the data from PyCitySchools.ipynb and PyCitySchools_Challenge.ipynb, there is no change.
### How is the school summary affected?
- Before the change was implemented, the overall passing percentage for the students of Thomas High School was approximately 90.94%. After the grades for the 9th graders were taken out, the overall passing percentage decreases by about 0.3%.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Overall, replacing the ninth graders' reading and math scores with NaN values increased Thomas High School's average scores. ![ThomasHighSchoolPicBeforeChange](https://user-images.githubusercontent.com/35403433/126927472-9a9fb827-6e42-46cc-bf0b-da123d2a0d3b.png)
![ThomasHighSchoolPicAfterChange](https://user-images.githubusercontent.com/35403433/126927488-25b66bce-6f64-4a59-9a08-6c43d97207d7.png)
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
- Overall, it appears that the math and reading scores did not change.
#### Scores by school spending
- Overall, it appears that the scores predicated upon school spending did not change.
#### Scores by school size
- Overall, it appears that the scores predicated upon school size did not change.
#### Scores by school type
- Overall, it appears that the scores predicated upon school type did not change.
## Summary
- After we have replaced the scores of the 9th grade students we learn that not much has changed. We have nullified the values that we felt would alter size,district, spending and overall passing percentage of the students.

 
