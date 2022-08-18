# Kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
# Kickstarting with Excel
## Overview of Project
In this project we have an excel sheet with raw data about different fundraisers over the years, that we used to analyze the data in a better way. In the raw data sheet, we have different types of data formats like numbers and text. The data shows different types of fundraising projects that include different categories like television, theatre, short videos, food etc.

Each columns specifies different type of information; as goal column shows the target amount set for a different project and the pledged column shows total amount of money each campaign raised. 
 
### Purpose
In this project we helped Louise to understand data from previous fundraising campaigns to her to make decisions for running a successful campaign. She wants to launch a project campaign for her play “Fever”. To be more successful, we analyze the data from different angles.

## Analysis and Challenges
Firstly, we analyzed the data based on Launch Date (which is campaign starting date) and secondly, based on Goals (the amount of money required to be successful).
# Challenges
The main challenge is to understand data in raw form and calculate information from the unorganized data and represent it in a better format which makes it easier to understand.

### Analysis of Outcomes Based on Launch Date
From the table and chart, we can clearly see that month of May has most successful fundraisers followed by June. At the same time May has highest number of failed campaigns. So, we can clearly observe from chart the curve of successful and failure are following each other as the curve of successful campaigns goes up the curve of failure follow it except the month of December. So, In December we have highest rate of failure than other months, which could have happened due to Holidays. The curve for canceled projects shows data in different manner it does not depend upon total number of outcomes. It does indicate that the highest percentage of cancelations happen in January which might be due to lack of volunteers or sponsors as people are getting back to work/school after Christmas/New year break. There was no cancelation for month of October over the years which makes a strong case for organizing one during that period of the year.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111101038/185292345-367d8332-d3a5-4908-9790-32e53e6b24cc.png)

### Analysis of Outcomes Based on Goals
The Goal chart and table represent information based on the target amount of projects. We divided our amount into different groups for comparing successful, failed, canceled projects. The projects that raised the target funds comes under successful category. The projects that failed to accomplish the target funds come under failed category. The rest are those canceled and falls under canceled category. 
After this, we added three columns to represent the percentage of successful, failed and canceled projects.
The table represents all the information in graphical form.
One important thing we learned from this set of data was that there were no cancelations for subcategory of plays. It also helps us understand the fundraising goals for a successful project.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111101038/185292438-08f7b61a-d528-44bd-a0ed-6f1ce1df1533.png)

### Challenges and Difficulties Encountered
The first challenge that I faced was to ungroup Launch Date in Pivot table to show months and years separately.
My second challenge was to use “countifs” function to select a range of target amount for Goals.


## Results
From both tables and graph, we can conclude that to run a more successful fundraising campaign the goal amount should be realistic. The higher she set the Goal the chances of success will decrease.
- What are two conclusions you can draw about the Outcomes based on Launch Date?
Most of the fundraising campaigns are organized in the months of May and June. 
The month of October has zero cancelation.
- What can you conclude about the Outcomes based on Goals?
The projects with lower fund goals are more successful.


- What are some limitations of this dataset?
The data set does not specify the number of volunteers who signed up for any project, or the reason for which some of the projects failed or were canceled over the years. This data could help us to avoid some common mistakes and increase our chances of running a successful campaign.
- What are some other possible tables and/or graphs that we could create?
We could include another chart to show the different types of plays which have been most successful, which could include categories like comedy, musical, melodrama etc. We could also possibly include name of the authors to determine if there is a probability of higher success rate depending on category or author.

