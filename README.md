# Final Project Plan

## Backgroud

The choice of a marriage partner is one of the most serious decisions people face. In contemporary Western societies, this
decision usually follows a long learning period during which people engage in more informal and often polygamous relationships
dating. However, in today’s busy world, finding and dating a romantic partner seems more time consuming than ever. As a result, many people have turned to speed dating as a solution that allows one to meet and interact with a large number of potential partners in a short amount of time. 

As in all matching markets, determining dating preferences from equilibrium outcomes is difficult because a given correlation of attributes across partners is often consistent with various preference structures. In this project, we want to explore what people are looking for in their speed dating matches, what it takes to become successful in getting approvals from a potential partner, if there exist any gender differences in dating preferences, and if any other factors influence peoples’ decisions. Also, we would like to determine if people really know what they want by comparing their self-reported answers to what actually influences peoples’ decisions.


## Data 

#### Data Source

Kaggle: Speed Dating Experiment (What attributes influence the selection of a romantic partner?)

https://www.kaggle.com/annavictoria/speed-dating-experiment

#### Data Collection

The data set we will analyze in this project is named “Speed Dating Experiment”, as found on Kaggle.com. It was compiled by professors Ray Fisman and Sheena Iyengar from Columbia Business School, originally used for their paper “Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment.” It was generated from a series of experimental speed dating events from 2002 to 2004 and includes data related to demographics, dating habits, lifestyle information, an attribute evaluation questionnaire taken when the participants sign up, and each participant’s ratings for others during the 4 minute interactions. Finally, individuals were asked if they would like a second date with their partners and rated again on similar questions after the event, when matches have met with each other and dated for several times.

The subjects of the data were drawn from students in graduate and professional schools at Columbia University. Participants
were recruited through a combination of mass e-mail and fliers posted throughout the campus and handed out by research assistants.

#### Data Description

The raw dataset contains 195 colunms and 8370 rows. Most variables in the dataset are numeric values. Some of the numeric variables represent scale from 1 to 10, or 1 to 100. Some of the numeric variables also represent categories, such as the race, occupation, the fields people work in, etc. A more detailed data description will be provided after data cleaning. Here are some sample variables from raw dataset listed below,

| Variable | Type |
| ------ | ------ |
| Gender | The gender of participant |
| Match | if the participant matches with his/her partner |
| sameRace | if participant and the partner are the same race  |
| age_partner | the age of the partner |
| race_partner | the race of the partner |
| field_code | The code of the field where participant work in |
| race | the race of participant |
| interested_activities | the interested activities of the participant  |

The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information. See the Speed Dating Data Key document below for details.

Participants need to assign points between 6 attributes: attractiveness, sincere, intelligent, fun, ambitious and shared interests. The total point ranges from 1 to 10, or 1 to 100. For each participande, the sum of points for each survey should either be 10 points or 100 points.


## Data Analysis

Statistis analysis will be the main method performed on the data. We will perform data transformation or data computation on the dataset to visualize the data properly. 

#### The analysis intended to perform:

- What are the most desirable attributes in a female partner? What are the most desirable attributes in a male partner? Does this differ for female partners?

We will get the total points of each attributes for male and female seperately. A bar chart will be appropriate here to compare the difference between attributes and gender.

- How important do people think attractiveness is in potential mate selection vs. its real impact?
- Are shared interests more important than a shared racial background?
- Can people accurately predict their own perceived value in the dating market?
- In terms of getting a second date, is it better to be someone's first speed date of the night or their last?
- What are participants looking for in their matches?
- Which of the 6 attributes actually influence decision making?
- What are correlation coefficient scores in Male and Female (attractiveness, sincerity, intelligence, fun, ambitious, shared interest)?
- How meeting orders influence decision making?

#### Anticipated outcomes and deliverables

For each question listed above, the anticipated outcomes will be one or more data visualizations. The experimental results will be compared with the initial hypothesis. We will then draw the conclustions based on each visualization and discuss the related human-centered problems.

## Project Dependencies

1. Data Cleaning

Based on the analysis we intend to perform, only related variables will be included. Missing values will also be either eliminated or filled with other values. Ideally, we will use pandas to pre-process the data into appropriate dataframe and get ready for data visualizations.

2. Data Analysis

It is necessary to preform some data transformation, data computation to answer those questions. 

3. Data Visualization

In order to convey information to audience effectively, we need to choose the appropriated methods to display visualizations. 

## Human-centered Aspects of The Project


