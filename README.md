# School District Analysis

## Overview

Following the original analysis of the school districts' scores, it was found that the students_complete.csv file shows evidence of academic dishonesty. The math and reading scores for ninth-grade students at Thomas High School (THS) appear to be altered. The purpose of this analysis is to replicate the original school district analysis after replacing the math and reading scores for ninth-grade THS students with NaNs (i.e., omit their data from the analyis) and determine how these changes affected the overall analysis.

*[Original Analysis](https://github.com/rabascoh/school-district-analysis/blob/main/Module%20Materials/PyCitySchools.ipynb)*

## Results
Replacing the THS ninth-grade math and reading scores impacted the School District Analysis in the following ways. 

### District Summary
There is a slight decrease in the district's average math scores as well as a decrease in the passing percentages for math, reading and overall following the removal of the THS ninth-grade students' math and reading scores (*see details below*). 

**Original District Summary**

![District_Summary_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/District_Summary.png)

**Updated District Summary**

![District_Summary_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/District_Summary_Updated.png)

### School Summary
There is a slight decrease in THS students' scores across the board including a drop in math and reading averages as well as a decrease in the percentage passing math, reading and overall as a result of replacing the ninth-grade scores (*see details below*). 

**Original School Summary**

![School_Summary_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/School_Summary.png)

**Updated School Summary**

![School_Summary_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/School_Summary_Updated.png)

### THS Performance Relative to Other Schools
Replacing the THS ninth-grade math and reading scores did not have an impact in THS' overall ranking compared to other schools. THS remains in the top five schools at second place (*see details below*). 

**Original Top Schools**

![Top_Schools_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Top_Schools.png)

**Updated Top Schools**

![Top_Schools_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Top_Schools_Updated.png)

### Scores

#### Math and Reading Scores by Grade

The math and reading scores for THS were impacted by the replacing of the ninth-grade students' scores.

* Math Scores

  * For THS' math scores, ninth-grade scores are now replaced with NaN (i.e., Not a Number) due to their math scores being replaced by null values. No other math scores were impacted (*see details below*). 

* Reading Scores

  * For THS' reading scores, ninth-grade scores are now replaced with NaN (i.e., Not a Number) due to their reading scores being replaced by null values. No other reading scores were impacted (*see details below*). 

**Original Math Scores by Grade**

![Math_Scores_By_Grade_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Math_Scores_By_Grade.png)

**Original Reading Scores by Grade**

![Reading_Scores_By_Grade_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Reading_Scores_By_Grade.png)

**Updated Math Scores by Grade**

![Math_Scores_By_Grade_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Math_Scores_By_Grade_Updated.png)

**Updated Reading Scores by Grade**

![Reading_Scores_By_Grade_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Reading_Scores_By_Grade_Updated.png)

#### Scores by School Spending

The scores by school spending were not impacted by replacing THS ninth-grade math and reading scores (*see details below*). 

**Original Scores by School Spending**

![Scores_By_School_Spending_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Scores_By_School_Spending.png)

**Updated Scores by School Spending**

![Scores_By_School_Spending_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Scores_By_School_Spending_Updated.png)

#### Scores by School Size

The scores by school size were not impacted by replacing THS ninth-grade math and reading scores (*see details below*). 

**Original Scores by School Size**

![Scores_By_School_Size_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Scores_By_School_Size.png)

**Updated Scores by School Size**

![Scores_By_School_Size_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Scores_By_School_Size_Updated.png)

#### Scores by School Type

The scores by school type were not impacted by replacing THS ninth-grade math and reading scores (*see details below*). 

**Original Scores by School Type**

![Scores_By_School_Type_Original](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Original/Scores_By_School_Type.png)

**Updated Scores by School Type**

![Scores_By_School_Type_Updated](https://github.com/rabascoh/school-district-analysis/blob/main/Resources/DataFrames_Updated/Scores_By_School_Type_Updated.png)

## Summary
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
