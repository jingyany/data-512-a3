# Final Project Plan

## Backgroud

The choice of a marriage partner is one of the most serious decisions people face. In contemporary Western societies, this
decision usually follows a long learning period during which people engage in more informal and often polygamous relationships
dating. In today’s busy world, finding and dating a romantic partner seems more time consuming than ever. As a result, many people have turned to speed dating as a solution that allows one to meet and interact with a large number of potential partners in a short amount of time. 

As in all matching markets, determining dating preferences from equilibrium outcomes is difficult because a given correlation of attributes across partners is often consistent with various preference structures. In this project, we want to explore what people are looking for in their speed dating matches, what it takes to become successful in getting approvals from a potential partner, if there exist any gender differences in dating preferences, and if any other factors influence peoples’ decisions. Also, we would like to determine if people really know what they want by comparing their self-reported answers to what actually influences peoples’ decisions.

## Data 

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


What is your plan? Describe the data sources will you collect, how data will be collected and processed, the analysis you intend to perform, and the outcomes and deliverables you anticipate.
