# PyCitySchools Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.
Because the reading and math grades for Thomas High School ninth graders appeared to have been altered, we were given the task to replace the math and reading scores for ninth graders at Thomas High School with NaNs while keeping the rest of the data intact. Afterward, we are to evaluate how these changes affect the overall analysis. 


## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

In diaplaying the before & after results of Thomas High School from the original df to the updated df, I noticed slight variation in the Average Reading, Average Math, % Passing Math, % Passing Reading & Overall Passing scores values.

- How is the district summary affected?

![district_summary_original.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/district_summary_original.png)

![district_summary_df_updated.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/district_summary_df_updated.png)



- How is the school summary affected?



### Before replacing the reading and math scores for Thomas High School with NaNs:

![PyCitySchools_Challenge_original.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_original.png)


### After replacing the reading and math scores for Thomas High School with NaNs:



![PyCitySchools_Challenge_updated.png](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_updated.png)





- How does replacing the ninth graders’ math and reading scores affect Thomas High  School’s performance relative to the other schools?


- How does replacing the ninth-grade scores affect the following:

	- Math and reading scores by grade
	The scores were removed & replaced with NaN's
	![Math and reading scores by grade](https://github.com/forrestcasey/School_District_Analysis/blob/main/Resources/Math%20and%20reading%20scores%20by%20grade.png)


	- Scores by school spending


	- Scores by school size



	- Scores by school type


## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- Thomas High School's total number of students was reduced due to removing 9th grade values, so we have a new total student count.
- The Average Reading, Average Math, % Passing Math, % Passing Reading & Overall Passing scores values were slightly altered.
- 9th graders math and reading scores in Thomas High School cannot then be included in the overall analysis, affecting the credence of the analysis itself






