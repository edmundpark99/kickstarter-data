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

  Overall, there were no particular challenges that got in the way of this analysis, as overall it went fairly smoothly. The first is that the data revealed that there were no canceled plays. This creates a slight bias in the data sample as it is unknown if the presence of canceled plays would have affected the results differently. Secondly, the formulas and coding with which to calculate the number of successful and failed plays was quite long, and required multiple different criteria to filter, and thus it may have taken multiple attempts to get to code right and to ensure the COUNTIFS function produced the proper results. Moreover, another potential difficulty would be in creating a proper pivot table and filtering it based on the criteria and ensuring the desirable outcomes are listed can be another potential hurdle, especially if the data is not categorized properly according to the needed criteria. Otherwise, few of these challenges arose during the analysis and the overall process went as expected.
  
**Results**

*Conclusions*

  Based on the final results presented in both analyses, a few conclusions can be made. For the first analysis, with outcomes being analyzed relative to theater projects' launch dates, one conclusion that can be made is that May is the best month of the year to launch a theater project and a subsequent fundraising campaign, as May had not only the highest amount of theater fundraising projects launched, but it also had the highest proportion of successful theater projects relative to the number of failed and canceled projects, as over twice as many projects were successful as they were failed or canceled. This implies that there is a high chance that a theater fundraising project released in May will end up successful. On the other hand, the other conclusion that can be made is that December is the worst month to release a theater fundraising project, as it featured not only the fewest number released, but the number of successful projects was close in number to failed projects and canceled projects combined, implying the odds that a theater project launched in December will fail or end up canceled are higher in December. When it comes to the second analysis, assessing outcomes based on goals, a conclusion that can be made is that plays with a smaller amount of money as the fundraising goal are more likely to succeed than those with higher fundraising goals, as those with higher goals had more failed plays than those with lower goals. This makes sense, as the lower the goal, the more likely enough money will be raised to reach such goal.
  
 *Limitations and Future Directions*

  There are a few limitations of the dataset. The first is that the method to which the data was gathered is unknown, and for the most part unclear, and without proper knowledge of the method behind which the data was collected, combined with the wide variety of data over different time periods, it is difficult to truly consider this dataset applicable to the wider population that we aim to assess with these analyses. Moreover, the sample size, while large, especially for the outcomes based on goals, is still skewed towards plays that had a smaller goal, and fewer that had larger fundraising goals. This may affect the reliability of the results in that they may not be totally representative and accurate of how successful projects are across the entire population. Moreover, the data was collected from a broad number of places and a broad number of time periods, meaning things may have changed depending on differences in time and place. 
  
  As for other potential tables and graphs that could be formed, we could formulate a bar graph determing successful outcomes over different months, and filter it accordingly. We could also create a pivot table determining the number of successful, failed, and canceled outcomes for plays specifically, and filter it further based on country or other related criteria. A frequency table for such data could also be created. Moreover, a stacked column graph could be created to stack the number of failed, successful, and canceled projects for the different analyses performed.
