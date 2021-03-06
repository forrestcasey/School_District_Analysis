# PyCitySchools Analysis

## Overview

- Because the reading and math grades for Thomas High School ninth graders appeared to have been altered, we were given the task to replace the math and reading scores for ninth graders at Thomas High School with NaNs while keeping the rest of the data intact. Afterward, we are to evaluate how these changes affect the overall analysis. 


## Results: 

#### There was slight variation in the Average Reading, Average Math, % Passing Math, % Passing Reading & Overall Passing scores values

### How is the district summary affected?

- #### Before modification:

![district_summary_original.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/district_summary_original.png)

- #### After modification:

![district_summary_df_updated.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/district_summary_df_updated.png)



### How is the school summary affected?



- #### Before modification:

![PyCitySchools_Challenge_original.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_original.png)


- #### After modification:



![PyCitySchools_Challenge_updated.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_updated.png)



### How does replacing the ninth graders’ math and reading scores affect Thomas High  School’s performance relative to the other schools?

- Performance is minimally impacted relative to other schools.

## How does replacing the ninth-grade scores affect the following:

- ### Math and reading scores by grade

#### The scores were removed & replaced with NaN's:


![Math and reading scores by grade](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/Math%20and%20reading%20scores%20by%20grade.png)


- ### Scores by school spending

	- These values were not affected.


- ### Scores by school size

	- Not affected and remain in Medium bin.


- ### Scores by school type


	- #### Before modification:
	![type_summary_df_before.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/type_summary_df_before.png)



	- #### After modification:
	![type_summary_df_updated.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/type_summary_df_updated.png)


## Summary: 

- Thomas High School's total number of students was reduced due to removing 9th grade values, so we have a new total student count
- The Average Reading, Average Math, % Passing Math, % Passing Reading & Overall Passing scores values were slightly altered.
- A result of these overall and average score discrepancies menetioned in the above bullet-point, the district, school summary, and charter school type values have all been changed as such. The percentage of overall passing with regard to district was more affected than others since it dropped from 65.17% to 64.86%, whereas most of the other change in values involved a tenth or hundreths of a percentage.
- 9th graders math and reading scores in Thomas High School cannot then be included in the overall analysis, affecting the credence of the analysis itself






