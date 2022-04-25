# School_District_Analysis

## Analysis Overview

The purpose of this analysis was to view math and reading test performance across factors including school size, per capita spending, and school type. 
The analysis in the challenge was very similar to the module analysis, but all test results from Freshman at Thomas High School had to be removed due to suspicions of cheating. 

## Results

*How is the district summary affected?

![Old District Results] (https://github.com/tbrech4/School_District_Analysis/blob/main/Resources/Screenshots/District_Analysis_OLD.png)

![New District Results] (https://github.com/tbrech4/School_District_Analysis/blob/main/Resources/Screenshots/District_Analysis_New.png)

The district summary does not change much. The passing percentages change slightly, but that is to be expected since the updated analysis removed the results of 461 students. 

*How is the school summary affected?

Thomas High School is the only school in the school summary that is affected by the changes. All of the other schools did not have data affected because the school summary dataframe has each school as its own row. 

Thomas High School's performance changes will be analyzed in the next section.

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Old Top Five Schools] (https://github.com/tbrech4/School_District_Analysis/blob/main/Resources/Screenshots/Top_Five_Schools_OLD.png

![New Top Five Schools] (https://github.com/tbrech4/School_District_Analysis/blob/main/Resources/Screenshots/Top_Five_Schools.png)

Thomas High School was still second in terms of overall passing percentage, even after removing the Freshman results that are suspected of being dishonest. Overall passing % dipped from 90.9% to 90.63%, but this was still higher than Griffin High School's average of 90.59%

*How does replacing the ninth-grade scores affect the following:

 * Math and Reading Scores by Grade

The only change was the removal of Thomas High School's Freshman results. All other results stayed the same since the results were grouped by School and year.

 * Scores by school spending

The passing percentages for the $631-645 spending ranges would be the only results that are affected by the data removal. However, the results did not change when rounding to a whole number.

 * Scores by school size

The only school size group that would be affected is the Medium (1000-1999) size range. However, the results did not change when rounding to a whole number.

 * Scores by school type

The charter school type is the only type that should be affected after removing Thomas High School freshman results. However, the results did not change when rounding to a whole number. 

## Summary

The results did not change much after removing Thomas High School ninth grade results. Most of the changes were not big enough to notice since results were almost always formatted to be a whole number.

Here are some of the minor result changes:

1. The percentage of the students in the district that passed the math test dipped very slightly, from 74.98% to 74.8%. 
2. The total percent of students at Thomas High School that passed both tests dipped from 90.95% to 90.63%. 
3. The total percent of students at Thomas High School that passed the math test dipped from 93.27% to 93.19%
4. The total percent of students at Thomas High School that passed the reading test dipped from 97.3% to 97.01%.

Overall, the results were not changed very much by the removal of the ninth grade Thomas High School data.