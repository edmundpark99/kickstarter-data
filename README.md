# kickstarter-data
**_A Written Report and Analysis on the Kickstarter Challenge Results_**

**Overview of the Project**

  This project was designed to be a statistical analysis of various fundraising campaigns of various plays that had such campaigns. Namely, the outcomes of the numerous campaigns were assessed relative to the launch dates of said campaigns as well as the goal, or more specifically, the desired amount of money the campaign aimed to raise, of each campaign. First, the data was filtered out so that only theater projects were analyzed and assessed. A pivot table was then created in order to assess how many theater projects successfully achieved their fundraising goal, how many failed to achieve their fundraising goal, and how many were cancelled, and were filtered by their launch date, more specifically, the month they launched in the year. Second, the provided data was filtered out so that plays would be the only samples assessed, and then were further filtered by their desired goal, how many plays ultimately succeeded in raising the desired amount of money they aimed for, how many failed to do so, and how many were cancelled. Both of these assessments were then graphed.
  
**Analysis of the Project**

*Process of the Analysis*

  First, in order to access the outcomes of theater fundraising projects in relation to their release date. This was done by using the data that was gathered in an Excel spreadsheet. We first singled out what year each project was released in, by using the =YEAR() function in Excel, using a base date to convert from. From there, a pivot table was created using the data, and the table was filtered based on the parent category of the project as well as the year of the project. The pivot table was then assessed with the count of outcomes as the legend, and the date created as the category with which to divide the outcomes further. The results were subsequently made into a pivot table based on the month they were released, and how many theater projects in said month were successful in their fundraising goals, how many failed to reach said goals, and how many projects were canceled. 

Below is the filtering process behind the pivot table, as well as the resulting pivot table itself:

![Pivot Table Filters](https://user-images.githubusercontent.com/6594718/156930680-15f81e07-d07b-4105-92a1-de4b545f88f4.png)
![Kickstarter 1 Pivot Table](https://user-images.githubusercontent.com/6594718/156930691-8a035932-1022-4c55-885e-c737f7de1302.png)

  After the outcomes of the theater projects based on their launch date was assessed, the next assessment performed was to analyze the outcomes of plays based on their goal in terms of fundraiding amount. A new sheet was created to the project's goal amount, the number of successful projects in that range, the number of failed projects in that range, and the number that were canceled. From there, the percentage of successful, failed, and canceled projects was calculated relative to the total number of plays with the designated fundraising goal range. The number of each per category was calculated using a COUNTIFS function, with a sample equation being used below:

```
functiontest() {
  console.log("=COUNTIFS(Kickstarter!F:F,"successful",Kickstarter!D:D,"<1000",Kickstarter!R:R,"plays")
}
```

This function was utilized in Excel, and the aforementioned criteria was altered based on the desired range as well as whether the outcome was successful, failed, or canceled. The resulting table is shown below:

![Outcomes Table](https://user-images.githubusercontent.com/6594718/156932441-1f4c8388-1a8a-42e5-8d13-2b43f14f471f.png)

Afterwards, both assessments were then charted unto a line graph, with the following shown:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/6594718/156932642-c5eb9fd4-512c-4fca-b150-2595d1d88613.png)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/6594718/156932645-804872e0-026f-49fe-a476-7eb9139f6746.png)

*Potential Challenges of the Analysis*

  Overall, there were no particular challenges that got in the way of this analysis, as overall it went fairly smoothly. The first is that the data revealed that there were no canceled plays. This creates a slight bias in the data sample as it is unknown if the presence of canceled plays would have affected the results differently. Secondly, the formulas and coding with which to calculate the number of successful and failed plays was quite long, and required multiple different criteria to filter, and thus it may have taken multiple attempts to get to code right and to ensure the COUNTIFS function produced the proper results.
