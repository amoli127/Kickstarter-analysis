# Kickstarting with Excel
Performing analysis on Kickstarter data to identify which factors make a project's campaign successful.
## Overview of Project
An upcoming playwright, Louise, wants to start a crowdfunding campaign to help fund her play. "Fever." Louise is estimating a budget of $10,000. She needs help to determine whether specific factors make a project's campaign successful.
### Purpose
We will use crowdfunding data to help Louise better understand and plan her campaign. We will provide Louise with visualized feedback with the input she needs to mirror other successful campaigns in the same category.
## Analysis and challenges
We initially contrasted data from Louise's Theather campaign category with campaigns from other categories to determine their overall success. The following graph shows that campaigns in the theater category were the most successful in the United States. Of 912 campaigns in the theater category, 525 were successful, 58%, 349 failed, 38%, 26 were canceled, 3%, and 12, 1% were live when the data was gathered. 


![Parent Category Outcomes](https://user-images.githubusercontent.com/117063056/209300926-c58d97c1-b52a-4517-a76e-360fd4a628e5.png)

The theater category has three subcategories: musicals, plays, and spaces. So we unraveled the data further to find out how the play's subcategory compares to musicals and spaces. After filtering the information, we identified that 412 play campaigns were successful, compared to 45 for musicals and 68 for spaces. The graph below shows how the plays subcategory makes up most of the theater campaigns. Of 671 play campaigns, 412 (61%) were successful, 250 (37%) failed, 15 (2%) were canceled, and three were live at the time the data was collected

![Theater Subcategory Outcomes](https://user-images.githubusercontent.com/117063056/209304086-6d1cc394-f09e-4953-ae11-fdee11fe1884.png)
### Analysis of Outcomes Based on Launch Date
One of the factors we examined from the data was how important a campaign's launch date is to its success. The data from the theater campaigns shows that May and June were the months in which the most successful Kickstarter campaigns were launched. On the other hand, the data also shows that there were more failed campaigns in December.


![Theater Outcomes vs Launch](https://user-images.githubusercontent.com/117063056/209306328-ef105e7b-bc8f-4042-a322-81b52c238f14.png)


### Analysis of Outcomes Based on Goals
In order to have a better understanding of the role that the amount of the goal plays, we evaluated the outcomes of all the categories to know how many were successful and in which bracket they were. Of the 186 Kickstarter campaigns with a goal of less than $1,000, 76% were successful, followed by 534 campaigns with goals between $1,000 and $4,999, with 73% success. In contrast, campaigns with a goal of $50,000 or more only had 13% campaign success and 88% campaign failure. It is worth mentioning that campaigns with a goal between $15,000 and $19,999 had 50% successful and 50% failed campaigns.


![Outcomes vs Goals](https://user-images.githubusercontent.com/117063056/209309254-08282ae5-f9f2-4b0b-b879-993a71042894.png)


### Challenges and Difficulties Encountered

One of the most significant difficulties and challenges was calculating the results based on the goals. Using the COUNTIFS formula has little room for error due to the number of goal categories.

## Results

- Based on the launch date, we can conclude that Louise should avoid launching her campaign in winter, especially in December. Louise should aim to launch her campaign in May, June, or July, as these months have the most successful campaigns.

- Taking into account how successful the Kickstarter campaigns were, based on their goals, Louise's estimated $10,000 amount falls into the bracket of $10,000 and $14,999. 54% of the campaigns in this bracket were successful, and 46% failed. Louise should revise the amount and see if there is a possibility to lower the goal since the data shows that campaigns with a smaller amount as a goal have a greater number of successful campaigns.

- This dataset's limitations are that there is no information on the follow-up of the successful campaigns and how the results were after reaching their goal. This data would help us know if the estimate was correct, if the campaigns needed more funds, or if there are other factors that influenced their success in addition to what we can observe.

- Another type of chart we could have used is a pie chart to illustrate how campaign money is budgeted.

