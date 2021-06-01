# Kickstarter Data Organizing and Analysis in Excel

## Background:
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project’s initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.

## Objective: 
Analyze a dataset consisting of 4,000 crowdfunding projects to uncover hidden trends, create charts and tables, and interpret the data in Excel.
  
* Sheet 1- Cover sheet
* Sheet 2- Kickstarter data set with conditional formatting with 3-color scale for "state" of the project, new columns created using formulae- 
    O- Percentage Funded
    P- Average Donations by Backers
    Q- splitting Category/Sub-category into Category
    R- splitting Category/Sub-category into Sub-Category
    S- Date stamp conversion for Date Created
    T- Date stamp conversion for Date Ended
* Sheet 3- Category- pivot table and chart- for number of projects in each category
* Sheet 4- Sub-Category- pivot table and chart- for number of projects in each Sub-Category
* Sheet 5- Date Created Conversion- pivot table and chart- with values of Count of state, filtered by the year of the project.
* Sheet 6- Report
* Sheet 7- Deeper Analysis (bonus activities): sorted projects depending on their goal values, with ability to tell their percentage of success for a specific year. The sheet includes a chart to represent this new data.
* Sheet 8- Statistical Table and Analysis (bonus activity 2)- evaluated data to determine if its meaningful, and what values better help user to make a decision.

## Conclusions:

* Category Analysis: KickStarter campaigns in music, theater and film & video have the highest success rates at 77%, 60% and 58% respectively. On the other hand food, publishing, and games categories have lower success rates at 17%, 34% and 36%. Also, the technology category has the most cancellations (51% of all the events) and has a cancellation rate of 1/3 for that category.

![](https://github.com/poonam-ux/Excel-kickstarter_data_organization_analysis/blob/main/visualizations/Excel_kickstarter_viz1.png)

* Sub-Category Analysis: The sub-categories rock, documentary, and hardware have a success rate of 100%, while the sub-categories animation, drama, and video games have a 100% failure rate. The sub-category 'plays' has the most number of campaigns, 1066.

![](https://github.com/poonam-ux/Excel-kickstarter_data_organization_analysis/blob/main/visualizations/Excel_kickstarter_viz2.png)

* Month Analysis: The time of the year matters when campaigning. The month of May had the best success rate of 61%, while the month of December showed the lowest success rate of 44%.

![](https://github.com/poonam-ux/Excel-kickstarter_data_organization_analysis/blob/main/visualizations/Excel_kickstarter_viz3.png)

* Goal amount Analysis: The lower goal amounts show better success rate. The goal amounts above the $45,000 show a decline in success rate, and increase in cancellation and failure rates.

![](https://github.com/poonam-ux/Excel-kickstarter_data_organization_analysis/blob/main/visualizations/Excel_kickstarter_viz4.png)

## Limitations of dataset: 
* The dataset includes some projects that had a very low goal but a high pledged amount. These are the outliers for Percentage Funded. 
* Some of the categories/sub-categories don't have projects in all years/months, so there is no continuous relationship over the time. 
* One third of the projects come from a single category- theater. So, it limits the span of categories to choose from. 
