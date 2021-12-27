# Kickstarter_Challenge_Analysis
Performing analysis for a kickstarter excel database
# Kickstarting with Excel

## Overview of Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals
The database displayed information on her entertainment works on a regular basis. It was separated into several categories and subcategories as needed. The database includes about 4,000 historical records
Louise had all of her work's details; nonetheless, it was critical that she had a more complete study of his plays, imported dates, and her success story. It was critical for them to use quantitative techniques to disseminate the information. A precise display of Louise's data would assist her in making the best decisions to fund her next plays.

### Purpose

The main goal of this analysis was to show you quantitatively and graphically 1) What is the behavior and trend of Louise´s entertainment works (primarily theater) and 
2) In addition to the works being classified as Successful / Failed / Canceled, make a second classification and grouping according to her goal.
It is critical that the analysis is carried out appropriately using mathematical and Excel methodologies so that the deployment of information is optimal and correct decisions can be made. The arrangement of the information using pivot tables enables for an accurate and simple to analyze analysis.

## Analysis and Challenges

In general, the conclusions can be stated as follows: of the more than 4,000 datasets that were initially available, around 1370 correspond to works that were performed in theater. The classification and grouping based on aims enabled them to understand the distribution of their works and where they fit in the analysis range, so the interpretation and future analysis will help to make better business decisions.

### Analysis of Outcomes Based on Launch Date

Louise wanted to know how theater outcomes performed on a monthly basis for the first analysis. Similarly, you may view its classification based on its success status: successful, unsuccessful, or canceled. 1370 of the 4,000 data points corresponded to plays that were performed in theaters and behaved as follows: 60% were regarded successful, 36% failed, and 2% were canceled. This was accomplished by the use of a horizontal analysis. For the first time Using a vertical analysis, it was discovered that the busiest months for theater activity were May, June, and July. This analysis was carried out in the following manner: First, the dates were determined, and then a pivot table was created in another Excel tab, with the filters restricted to only theaters. The columns represent the distinctive information of successful, failed, or cancelled, while the lines display the months.
To depict the two studies, both vertical and horizontal, a graph called Theater results by launch date was created, in which you can see all of the behavior of the plays throughout the months' seasonalities.

![Image](Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

Twelve categories were grouped  from  less than 1,000 areas to more than 50,000 areas and a range of 5,000 area analyzes were performed to perform a goal-based analysis  of the results. This gave us an absolute idea of the grouping, but we also got the percentage. So that you can analyze their behavior and their distribution. No pivot table was used for this analysis because there was no range grouping. SO, we used count if formulas with conditionals to get our groups, and in addition to get a better analysis we made a graphic that shows the outliers, the the behavior of the goals by rank and their percentage.


![Image](Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Some of the complications that were found were converting the obtained format into date format and had to be converted and used a time formula standardized by excel. Using is the date that the Unix timestamps began counting from, also known as the epoch. Another problem identified was the ability to visualize information on a monthly basis by providing it  to  the pivot table on a date basis rather than the  monthly basis required for analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion that can be drawn from the analysis is that  summer (the month from May to August) has a seasonality that presents the best results of successful plays.
During the month of October no work was obtained with an outcome of canceled, this may be due to the fact that there is enough space to reproduce the works, since almost all of them are parked during the summer and secondly during the winter.
During this ranges, 60% were regarded successful, 36% failed, and 2% were canceled.
Despite october, failed presentations follow the same characteristics such as successful presentations.
We completely recommend Louise to focus on summer presentations, because are the one with the best performances. The canceled ratio is only 2%, so is a good number. The failed performances are 36% if Louise can focus more on better subjects during summer, the failed ratio could be 30% during the next few years.

- What can you conclude about the Outcomes based on Goals?
The average percentage in succesfull is around 45%, the 76% of the successful outcomes were allocated with a goal lower than 1,000 and 13% was higher than 50,000.

We can conclude that, as the graphic shows, that the best outcomes are in a range 35,000 to 45,000 of the successful projects in a percentage results. However, in absoluts number we can conclude that most of the successful performances outcomes are in a range bewteen less than 1000 to 5,000 of their goal.
The same characteristic is represented with the outcomes failed, most of the outcomes are concentrated in a goal between 1000, 5000.
Based on goals, there are zeros canceled outcomes based on goals, such as percentages and absolutes there is no performance.

We encourage Louise to get a better performances outcomes to get better goals.
And try to get a second analysis to see the performance of the successful outcomes during a period of time, category and subcategory, in that way get better analysis, performances and executions.

- What are some limitations of this dataset?
Some od the limitations on this dataset were duration of the blurb so we can get a better analysis including the time the performance was alive, so we can get better results what are the titles that people prefer.
Additional, another information that can be useful is the expected goal, so we can known how close the real goal was from the expectation.
