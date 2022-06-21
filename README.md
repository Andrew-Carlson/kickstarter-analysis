# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to use campaign data obtained from Kickstarter. The data is in a spreadsheet and contains information about different Kickstarter campaigns including the goal amount of money for the campaign, the amount pledged, the category, whether the campaign was successful or not, when the campaign was launched, and the country where the campaign is. The purpose of this project is to uncover trends that can be found within the Kickstarter data by taking advantage of the pivot table, pivot chart, and function features of Microsoft Excel. The trends uncovered include the outcomes of the campaigns based on the date that the campaign was launched and the outcomes of the campaign based on the monetary goal of the project. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A useful pivot table and chart was created to discover trends between the outcomes of different categories of Kickstarter campaigns based on the date in which the campaign was launched. The visualization made is useful in helping decide when the best time to launch a Kickstarter campaign for a given category of campaigns. The pivot chart could also be filtered based on a specific year to see how trends have changed or remained the same year to year. The line chart shown below displays the campaign outcome based on Launch date for all years in the dataset for the parent category of theater. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98781992/174678659-cfc6e419-877d-446f-9c6f-160617562576.png)
Figure 1. Line chart for theater outcomes based on launch date. 

### Analysis of Outcomes Based on Goals
A line chart was created to establish the percent of campaigns that were successful, failed, or canceled based on the monetary goal for the campaign. This chart is useful in determining what is a realistic goal for a Kickstarter campaign. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98781992/174681422-21d7c484-ed86-4993-954a-16fef649a757.png)
Figure 2. Line chart for Kickstarter campaigns based on the monetary goal amount. 

### Challenges and Difficulties Encountered
One of the challenges encountered was finding the correct syntax for the COUNTIFS function when making the data table for the outcomes based on goal line chart. The COUNTIFS function was useful in finding the amount of Kickstarter campaigns that were successful, failed, and canceled. It is important to know where to put quotations and to make sure that absolute cell references should be used within the function. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In the line chart shown in Figure 1, it can be noted that the best month to launch a Kickstarter campaign for the theater category is in May. The lowest amount of successful Kickstarter campaigns occur in December. The amount of canceled campaigns stays relatively constant month-to-month, while failed theater Kickstarter campaigns occur most in May and October.

- What can you conclude about the Outcomes based on Goals?
In the line chart shown in Figure 2, it can be noted that the success rate of campaigns decreases as the monetary goal amount increases, and there is an inverse relationship between the percent successful campaigns and the percent failed campaigns with the goal amount. 

- What are some limitations of this dataset?
A limitation of the dataset could be that there is no data past the year 2017 which does not show the potential changes in trends in more recent years. Another limitation is that the dataset does not provide information to find out what are the most lucrative dates in which the most backers donate to campaigns. 

- What are some other possible tables and/or graphs that we could create?
It may be useful to include a pivot table that shows what are the countries with the most campaign backers that can be filtered by category to see which categories are more popular in certain countries. The count of backers successful, failed, and canceled campaigns can also be included. Figure 3 shows the pivot table that could be of potential use. 
![Country_vs_backers_count](https://user-images.githubusercontent.com/98781992/174690041-d6ba5fd9-8319-409a-8a89-e54bd77fbeed.png)
Figure 3. Country of campaign vs. Backers count for successful, failed, and cancelled campaigns.

# kickstarter-analysis (Module 1 lessons)
Performing analysis on Kickstarter data to uncover trends

![outcome_vs_launch_date](https://user-images.githubusercontent.com/98781992/174171521-0a3ef9e8-73ca-43d6-8ba5-afb1a7772f78.png)

Fig. 1. Outcome of Kickstarter campaign versus launch date.



![parent_category_outcomes1](https://user-images.githubusercontent.com/98781992/174171525-7d57496f-bf92-4bd8-8f50-ccabed856be3.png)

Fig. 2. Outcomes for theater Kickstarter campaigns.



![subcategory_statistics](https://user-images.githubusercontent.com/98781992/174171551-32fdaeeb-619d-4c9b-9585-d8995e14ed34.png)

Fig. 3. Outcome of Kickstarters for plays in Great Britian.



![GB_Musical_Distribution](https://user-images.githubusercontent.com/98781992/174171569-d15e19dc-6744-4765-bdd5-f84898c7bc6f.png)

Fig. 4. Distribution of goals (left) and amount pledged (right) for musicals in Great Britian. 
