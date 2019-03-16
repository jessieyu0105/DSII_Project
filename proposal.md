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

Predictors:

CHSI\_County\_Name

CHSI\_State\_Abbr

Population\_Size

Population\_Density

Poverty

All\_Death

Health\_Status

Unhealthy\_Days

No\_Exercise

Few\_Fruit\_Veg

Obesity

High\_Blood\_Pres

Smoker

Diabetes

Uninsured

Elderly\_Medicare

Disabled\_Medicare

Prim\_Care\_Phys\_Rate

Dentist\_Rate

Community\_Health\_Center\_Ind

HPSA\_Ind

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
