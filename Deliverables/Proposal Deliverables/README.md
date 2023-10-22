# Gun Violence - Councilor Worrell - Team 3
## Background

- To understand the project, it would be helpful to know the factors that contribute to gun violence, such as poverty, access to firearms, mental health, and social dynamics. 
- Familiarity with the existing programs designed to address gun violence, their effectiveness, and their limitations would also be useful. 

## Motivation
- The recent uptick in gun possession among youth in Boston's District 4 
- Need to understand the drivers of gun violence in the district and the city as a whole. 
- Inform policies that can improve the district and reduce the incidence of gun violence.

> ## Goal
>To understand the drivers of gun violence in Boston's District 4 and the city as a whole, with a focus on identifying the variables associated with increases or decreases in gun violence.

## Datasets explored:
1. [City Council](https://data.boston.gov/dataset/city-council-districts-effective-for-the-2023-municipal-election)
2. [Shots fired](https://data.boston.gov/dataset/shots-fired)
3. [Shootings](https://data.boston.gov/dataset/shootings)
4. [Parks](https://data.boston.gov/dataset/boston-park-assets/resource/56b3003f-f397-43a1-9321-cd46b4ad9097)
5. [Conservation and Recreation](https://data.boston.gov/dataset/open-space/resource/64b42edc-af6e-488b-a6c3-d935b1ebb708)

## Work so far

Firstly we chose to tackle the question:

> What is the rate of gun violence in District 4? How does this compare to the rest of the city?

For giving a well-rounded analysis of the question with the timeframe in mind, we chose to go with the first 3 datasets in the list mentioned above - City Council, Shots fired and Shootings.


- Deliverable 1
    - We familiarized ourselves with the data we were given and made preliminary and initial analysis by plotting the most necessary plots needed to give an analytical backing for the question we chose to answer.
    - Analysis made by plotting:
        1. A geoplot, for sanity-checking the city council dataset shapefile to ensure we have bounded shapes(territories) with distinct boundaries and appropriate labels.
        2. Bar charts to show the number of gun violence incidents per year for each police district.
        3. A bar chart to show the ratio of gun violence incidents per year for District 4 versus the rest of Boston.
        4. A stacked bar chart to show the number of incidents per district and victim race.
        5. A pie chart to show the percentage of Shooting Incidents by Victim Race
        6. A map to show the district-wise gun violence intensity with the help of color gradients. 
    - You can access the code, plots, key results and other reports under the `deliverable-1` folder. (Check `Repository Structure` section below for instructions to access the folder)
- Deliverable 2
    - We delved deeper into the same 3 datasets and created analytical plots by correlating the datasets with each other, which helped us give different perspectives compared to Deliverable 1 plots, for answering the question better.
    - Analysis made by plotting:
        1. Number of Shootings per Hour in the Day from 2015 to 2023
        2. Number of Fatal vs Non-Fatal Shootings per District per Year
        3. Average number of shootings per day of the week vs district (across the years)
        4. Shooting Incidents by Victim's Race and Gender
        5. Multiple Victims vs Single Victims
        6. Shooting Incidents on Holidays and Non-Holidays
    - You can access the code, plots, key results and other reports under the `deliverable-2` folder. (Check `Repository Structure` section below for instructions to access the folder)

As we were able to come up with analytical plots considering various aspects for providing observations and key takeaways with regards to the question we were proposed, we moved on to take up an additional scope of work to look into unexplored datasets (4 and 5 from the datasets list) to see if we can get more insights.

> Rationale: To highlight potential important environmental trends which can pave the way for approvals for redesigning areas of Boston
    
> Hypothesis: Greener environments have less violence than desolate urban settings and More gun violence incidents closer to community centers.
   
- Extension Proposal
    - Analysis made by plotting:
        1. Parks Gun Violence Map
        2. Top 10 community centers with the most shootings within one-mile radius
        3. Race Segmentation for Community Centers
        4. Gender Segmentation for Community Centers

- Scrum Reports: For reviewing our progress of work, across the timeline of the project, please refer to the scrum updates reports under the `reports/scrum` folder. (Check `Repository Structure` section below for instructions to access the folder)

## Repository structure

Make sure you are in branch `team-3` for accessing our work done so far

```
├── spring23-team-3
│   ├── data
│   ├── deliverables
│   │   ├── deliverable-0
│   │   ├── deliverable-1
│   │   ├── deliverable-2
│   ├── reports
│   │   ├── scrum
│   ├── README.md
```

## Team

- [Sarah Bonna](https://github.com/sarahtb25) (GRS'23) - Team Lead
- [Brian Mahabir](https://github.com/bmahabirbu) (ECE'23)
- [Shivangi](https://github.com/shivi-9) (GRS'23)
- [Showndarya Madhavan](https://github.com/Showndarya) (GRS'23)
