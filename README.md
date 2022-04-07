## Problem Statement

Standardised tests, by its very name, should be a standard made available to the whole student body. The tests should ideally be a fair representation of the capabilities of all high school students. However, the data shows that not all states have good participation rates, in particular, Oregon.

We would like to explore ways in which Oregon can improve in this area.

## Executive Summary
We will be using the datas of ACT and SAT for years 2017, 2018 and 2019 for the project. Data such as participation rates and tests mean scores are used for comparison and analysis. We will be looking out for relationships and patterns among the features between the states and the years. Some sources from outside research will be taken, to better understand the policies and requirements for education in different states. With these information, we will be making recommendation for which state to start improving on.


## Contents:

1. [Datasets Used](#1-Datasets-Used)
2. [Data Dictionary](#2.-Data-Dictionary)
3. [Exploratory Data Analysis](#3.-Exploratory-Data-Analysis)
4. [Data Visualization](#4.-Data-Visualization)
5. [Descriptive and Inferential Statistics](#5.-Descriptive-and-Inferential-Statistics)
6. [Outside Research](#6.-Outside-Research)
7. [Conclusions and Recommendations](#7.-Conclusions-and-Recommendations)
8. [References](#8-References)
9. [Python Library Used](#9.-Python-Library_used)


### 1. Datasets Used :

The following datasets were used for this projects:
- ACT 2017
- SAT 2017
- ACT 2018
- SAT 2018
- ACT 2019
- SAT 2019

The following datasets were created and used during the projects:
- all_merged (Combination of all ACT and SAT data and additional data such as spending and funding)
- all_merged_concat (a long version of all_merged, with type of test and year taken as a differentiator)

### 2. Data Dictionary:

The below is a data dictionary containing all the data features, type and its description:


|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*Object*|all_merged|State data applies to.| <br>
|**Participation_2017_ACT**|*float64*|all_merged|Participation rate in 2017 (in percent).| <br>
|**Participation_2018_ACT**|*float64*|all_merged|Participation rate in 2018 (in percent).| <br>
|**Participation_2019_ACT**|*float64*|all_merged|Participation rate in 2019 (in percent).| <br>
|**Total_2017_ACT**|*float64*|all_merged|Percentage of total score over total possible score for ACT 2017.|  <br>
|**Total_2018_ACT**|*float64*|all_merged|Percentage of total score over total possible score for ACT 2018.|  <br>
|**Total_2019_ACT**|*float64*|all_merged|Percentage of total score over total possible score for ACT 2019.|  <br>
|**Participation_2017_SAT**|*float64*|all_merged|Participation rate in 2017 (in percent).|  <br>
|**Participation_2018_SAT**|*float64*|all_merged|Participation rate in 2018 (in percent).|   <br>
|**Participation_2019_SAT**|*float64*|all_merged|Participation rate in 2019 (in percent).|  <br>
|**Total_2017_SAT**|*float64*|all_merged|Percentage of total score over total possible score for SAT 2017.|  <br>
|**Total_2018_SAT**|*float64*|all_merged|Percentage of total score over total possible score for SAT 2018.|  <br>
|**Total_2019_SAT**|*float64*|all_merged|Percentage of total score over total possible score for SAT 2019.|  <br>
|**Income**|*int64*|all_merged|Median Household income by state.| <br>
|**K12 Spending**|*int64*|all_merged|Amount spent on K12 Education.| <br>
|**Postsecondary Spending**|*int64*|all_merged|Amount spent on Postsecondary Education.| <br>
|**Federal Funding**|*int64*|all_merged|Amount of Federal funding.| <br>
|**State and Local funding**|*Object*|all_merged|Amount of state and local funding.| <br>
|**ACT_ave_par**|*Object*|all_merged|Average of ACT participations for State| <br>
|**SAT_ave_par**|*Object*|all_merged|Average of SAT participations for State| <br>
|**State**|*Object*|all_merged_concat|State data applies to.| <br>
|**Participation**|*float64*|all_merged_concat|Participation rate for specified test and year.| <br>
|**Total**|*float64*|all_merged_concat|Percentage of total score over total possible score for specified test and year.| <br>
|**Test**|*Object*|all_merged_concat|Test that was taken|The year the test was taken.| <br>
|**State**|*Object*|all_merged_concat|State data applies to.| <br>
|**Income**|*Object*|all_merged_concat|State data applies to.| <br>
|**Margin of Error**|*Object*|all_merged_concat|State data applies to.| <br>


### 3. Exploratory Data Analysis

In this section, we worked with the data to find trends and relations to some of the more noteworthy features, like participation rates to scores, income, educational funding and spending.

### 4. Data Visualization

In this section, plotting of different type of diagrams were used to study and visual the trend data more. The following are the different methods used:

##### Heatmap
 - The correlation of SAT and ACT mean data

###### Scatter plotting
- Participation vs Average Score for SAT and ACT for all 3 years
- SAT Participation vs ACT Participation
- ACT Participation vs Income by year
- SAT Participation vs Income by year
- Average K-12 Spending per student vs Average SAT Participation
- State and Local Funding per student vs Average SAT Participation

##### Box plotting
- Maine SAT Participation and Score for 3 years with National Average
- Maine ACT Participation and Score for 3 years with National Average
- North Dakota SAT Participation and Score for 3 years with National Average
- North Dakota ACT Participation and Score for 3 years with National Average
- Oregon SAT Participation and Score for 3 years with National Average
- Oregon ACT Participation and Score for 3 years with National Average
- ACT and SAT Average Scores for 3 years
- ACT and SAT Average Participation for 3 years

### 5. Conclusions and Recommendations

Based on the data, participation rates are heavily influenced by the state department of education's policies. This can see seen from states like Maine, North Dakota and Oregon.

In Maine, as the state mandates SATs for all students and sponsors the test, almost all students attempted their SATs.
In North Dakota, as the state mandates ACTs for all students and sponsors the test, almost all students attempted their ACTs.
In Oregon, the states does not do either, resulting in lukewarm participation for the tests.

Making one of the test free and compulsory is the most direct way to increase the participation rate, making the tests accessible to all students. There are records of states improving participation rates by doing so. This will create a more inclusive test environment, and to ensure that the tests are accessible to a wider range of students in different income brackets.

Other than sponsoring tests, the State can also spend on areas that improve participation rates indirectly.

The data also shows that income, K-12 spending and State & Local funding affect the participation rates for SAT. Although it is not possible for Oregon to increase the median household income directly, they could increase K-12 spending and state funding as they are spending lower than the averge state.

### 6. References

###### College Raptor is used to find out on the states which subsidize ACT or SAT:
https://www.collegeraptor.com/getting-in/articles/act-sat/states-act-sat-given-free/

###### ACT Compulsory for North Dakota:
https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice

###### Oregon Stats, household income etc:
https://www.census.gov/quickfacts/fact/table/OR/INC110219

###### Median household income by State:
https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income

###### Educational spending by State:
https://educationdata.org/public-education-spending-statistics
