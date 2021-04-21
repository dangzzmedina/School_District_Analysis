# School_District_Analysis

### Overview of the school district analysis: Explain the purpose of this analysis.

** The purpose of this analysis is to understand how to null data and re calculate changes in a dataset. In the Challenge, we were required to use Jupyter Notebook as our tool on solving this issue. We compare the dataset of PyCitySchools to the new PyCitySchools Challenge Testing dataset that has the filtered data.

### Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?
** When we recalculate the district summary we do se a slight decrease in the calculations. For example :
1. Average Math Score: 79 -> 78
2. Average Reading Score: No change
3. % Passing Math: 75 -> 74.8
4. % Passing Reading: 86 -> 85.7
5. % Overall Passing: 65 -> 64.9

### How is the school summary affected?
** The school summary was affected due to the NaN values from the 9th graders in Thomas High School(THS). We nulled 461 students in THS and we see the same slight decrease in the per school summary calculations.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
** The ninth graders math and reading scores did not affect the performance of Thomas High School relative to the other schools.

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
** Math score by grade stays the same for Thomas High School as it is the only school which has null values.

### Scores by school spending
** Scores by school spending made the spending bins increase slightly.

### Scores by school size
** Scores by school size in math and reading scores slightly decreases for the medium range school size bin.

### Scores by school type
** Scores by school size in math slightly decreases for the charter school type while the scores in the reading slightly increases for the charter school type. District types stay the same.

### Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
** To summarize there isnt a very impactful change in the updated school district analysis, but we do se some  changes.
1. math scores are slightly lower for the district
2. % Passing math slightly lowers for the district
3. % Passing reading slightly lowers for the district
4. % Passing overal sligthly lowers for the district

To resume, we can conclude that the average student in the 9th grade from THS had similar scores to each other but also compared to their fellow students in the 10-12th classes.
