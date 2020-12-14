# School_District_Analysis
using pandas in Juptyter Notebooks for exploratory data analysis of a school district

## 1. Overview: 
We are working on a project to uncover data trends within a single school district. Specifically, we want to better understand the relationship between reading/math test scores and a number of other variables such as school size, type, and funding. After initially performing this [analysis](https://github.com/mathaim/School_District_Analysis/blob/main/PyCitySchools.ipynb
) for all students in the 15 schools in the district, we realized there was academic dishonesty among the ninth graders of Thomas High School. We needed to drop these values from the data and re-perform the analysis.

### Resources:
- Data Source: students_complete.csv, schools_complete.csv
- Software: Python 3.6.1
- Tools: Jupyter Notebook 6.1.4


## 2. Results: 

How is the district summary affected?
![DistrictSummary](Images/District_Summary.png)
- In this way

How is the school summary affected?
 ![SchoolSummary](Images/SchoolSummary.png)
 
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 ![top5](Images/Top5.png)
How does replacing the ninth-grade scores affect the following:
- Math scores by grade
![math](Images/mathbygrade.png)
- Reading scores by grade
![reading](Images/readingbygrade.png)
- Scores by school spending
![spending](Images/spendingrates.png)
- Scores by school size
![size](Images/size.png)
- Scores by school type
![type](Images/type.png)

## 3. Summary: 

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
