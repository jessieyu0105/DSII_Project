Proposal
================
Group 8
2019-03-11

Group Members
-------------

| Name           | Uni     |
|:---------------|:--------|
| Noah T. Kreski | ntk2109 |
| Shuwei Liu     | sl4471  |
| Jie Yu         | jy2944  |

Project Title
-------------

A Predictive Model for Life Expentancy using Community Health Status Indicators (CHSI) Data

Motivation
----------

Average life expectancy is a general health measure stating average lifespan for a given area,

and so our goal is to build predictive models for average life expectancy, and isolate the

best possible option.

Life expectancy in the United States has been declining recently, and as a key indicator for

the Sustainable Development Goal to “Ensure healthy lives and promote well-being for all at all

ages”, improving lifespan is an urgent and necessary goal.

[SDG's utilization of life expectancy](https://www.who.int/gho/publications/world_health_statistics/2016/EN_WHS2016_Chapter3.pdf)

[U.S. life expectancy in decline for the second year in a row](https://www.aafp.org/news/health-of-the-public/20181210lifeexpectdrop.html)

Anticipated Data Source
-----------------------

[Community Health Status Indicators (CHSI) to Combat Obesity, Heart Disease and Cancer, from Centers for Disease Control and Prevention](https://healthdata.gov/dataset/community-health-status-indicators-chsi-combat-obesity-heart-disease-and-cancer)

*Short Description:*

Community Health Status Indicators (CHSI) to combat obesity, heart disease, and cancer are major components of the Community Health Data Initiative. This dataset, which contains over 200 measures for each of the 3,141 United States counties, provides key health indicators for local communities and encourages dialogue about actions that can be taken to improve community health (e.g., obesity, heart disease, cancer).

Response(s) and predictors
--------------------------

Outcome:

ALE (average life expectancy)

Identifiers:

CHSI\_County\_Name (Name of County)

CHSI\_State\_Abbr (Two-character postal abbreviation)

Predictors:

Population\_Size (County Population Size)

Population\_Density (People per square mile)

Poverty (Percent of people living below the poverty line)

All\_Death (Mortality rate per 100,000 from all causes)

Health\_Status (Percent of population self-rating health as poor or fair)

Unhealthy\_Days (Average number of unhealthy days a person had in the past month)

No\_Exercise (The percentage of adults reporting of no participation in any leisure-time physical activities or exercises in the past month)

Few\_Fruit\_Veg (The percentage of adults reporting an average fruit and vegetable consumption of less than 5 servings per day)

Obesity (Percentage with a BMI &gt;= 30.0)

High\_Blood\_Pres (The percentage of adults who responded yes to the question, “Have you ever been told by a doctor, nurse, or other health professional that you have high blood pressure?”)

Smoker (The percentage of adults who responded “yes” to the question, “Do you smoke cigarettes now?”)

Diabetes (the percentage of adults who responded “yes” to the question, “Have you ever been told by a doctor that you have diabetes?”)

Uninsured (The number of uninsured individuals in a county)

Elderly\_Medicare (Number of those aged 65+ on Medicare)

Disabled\_Medicare (Number of those with disabilities on Medicare)

Prim\_Care\_Phys\_Rate (Total active, non-federal physicians per 100,000)

Dentist\_Rate (Total active dentists per 100,000 people)

Community\_Health\_Center\_Ind (Indicates the presence of a health center for low-income and uninsured families with funding from HRSA)

HPSA\_Ind (Indicates that a county has a shortage of health professionals as determined by the department of HHS)

Categorized data for different diseases

Planned analyses
----------------

1.  Data exploration: descriptive and visualization

2.  Variable reduction using Principle Component Analysis

3.  Model building

-   Odinary Least Squares model: using stepwise regression / best subsets regression

-   Ridge regression

-   Lasso

-   Principal components regression (PCR)

-   Partial least squares (PLS) regression

1.  Use k-folds Cross Validation to determine the best model
