# Final Project Plan

## Backgroud

The choice of a marriage partner is one of the most serious decisions people face. In contemporary Western societies, this
decision usually follows a long learning period during which people engage in more informal and often polygamous relationships
dating. In today’s busy world, finding and dating a romantic partner seems more time consuming than ever. As a result, many people have turned to speed dating as a solution that allows one to meet and interact with a large number of potential partners in a short amount of time. 

As in all matching markets, determining dating preferences from equilibrium outcomes is difficult because a given correlation of attributes across partners is often consistent with various preference structures. In this project, we want to explore what people are looking for in their speed dating matches, what it takes to become successful in getting approvals from a potential partner, if there exist any gender differences in dating preferences, and if any other factors influence peoples’ decisions. Also, we would like to determine if people really know what they want by comparing their self-reported answers to what actually influences peoples’ decisions.

## Data 

#### Data Source

Kaggle: Speed Dating Experiment (What attributes influence the selection of a romantic partner?)

https://www.kaggle.com/annavictoria/speed-dating-experiment

#### Data Collection

The data set we will analyze in this project is named “Speed Dating Experiment”, as found on Kaggle.com. It was compiled by professors Ray Fisman and Sheena Iyengar from Columbia Business School, originally used for their paper “Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment.” It was generated from a series of experimental speed dating events from 2002 to 2004 and includes data related to demographics, dating habits, lifestyle information, an attribute evaluation questionnaire taken when the participants sign up, and each participant’s ratings for others during the 4 minute interactions. Finally, individuals were asked if they would like a second date with their partners and rated again on similar questions after the event, when matches have met with each other and dated for several times.

#### Data Description

The raw dataset contains 195 colunms and 8370 rows. Most variables in the dataset are numeric values. The values of some of the numeric variables represent scale from 1 to 10, or 1 to 100. The values of some of the numeric variables also represent categories, such as the race, occupation, the fields people work in, etc. Thus, the number of variables of the dataset is less than 195. The accurate number will be count after data cleaning and data transformation. Some variables are listed below,

| Variable | Type |
| ------ | ------ |
| Gender | boolean |
| Match | boolean |
| sameRace | boolean |
| age_partner | numeric |
| race_partner | text |
| field_code | categorical number |
| race | categorical number |
| interested_activities | text |

The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information. See the Speed Dating Data Key document below for details.


## Data Analysis

#### The Hypothesises:

Several intended analysis are listed below. We will make our own assumption to each question before conducting the analysis. 

#### The analysis intended to perform:

- What are the most desirable attributes in a female partner? What are the most desirable attributes in a male partner? Does this differ for female partners?
- How important do people think attractiveness is in potential mate selection vs. its real impact?
- Are shared interests more important than a shared racial background?
- Can people accurately predict their own perceived value in the dating market?
- In terms of getting a second date, is it better to be someone's first speed date of the night or their last?
- What are participants looking for in their matches?
- What paricipants think their same-sex peers are looking for?
- What do participants think the opposite sex is looking for?
- Which of the 6 attributes actually influence decision making?
- What are correlation coefficient scores in Male and Female (attractiveness, sincerity, intelligence, fun, ambitious, shared interest)?
- How meeting orders influence decision making?

#### Anticipated outcomes and deliverables

For each question listed above, the anticipated outcomes will be one or more data visualizations. The experimental results will be compared with the initial hypothesis. We will then draw the conclustions based on each visualization and discuss the related human-centered problems.

## Project Task Dependencies

1. Data Cleaning

Based on the analysis we intend to perform, only related variables will be included. Missing values will also be either eliminated or filled with other values. Ideally, we will use pandas to pre-process the data into appropriate dataframe and get ready for data visualizations.

2. Data Analysis

It is necessary to preform some data transformation, data computation to answer those questions. 

3. Data Visualization

In order to convey information to audience effectively, we need to choose the appropriated methods to display visualizations. 

## Human-centered Aspects of The Project
