# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the report was to determine how different campaigns succeed or failed according to their launched date and their funding goal.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
The first analysis was to determine the campaign outcomes based on launched date by using the pivot table and a graph. The first step of analysis was adding to the worksheet was the YEAR function. From this calculation, I was able to select "outcomes", "Years" on Kickstarter worksheet to create the pivot table. This pivot table shows the number of "successful", "Failed", "Canceled", and Grand Total of each month every year for theater category. The line graph show this information but in a visual way.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/110945895/187044833-c1b77c90-54b9-4cdf-bc65-934555b4041f.png)
Figure 1. This line graph is demonstrating the number of outcomes of successful, failed, and canceled theater kickstarters during the months of all years combined. The number of successful outcomes are more abundant than the failed and canceled. The successful outcomes peak in May as well as the failed attempts of theater kickstarter.

### Analysis of Outcomes Based on Goals
I created a new sheet and labelled it "Outcomes Based on Goals." I labeled 8 columns called "Goal," "Number Successful," "Number Failed," "Number Canceled," "Total Projects," "Percentage Successful," "Percentage Failed," and "Percentage Canceled." In the goal column, I created a range of dollar-amount so that projects are grouped on goal amount. I used the COUNTIFS to determine number outcomes mentioned above. Below the number outcomes, I calculated sum of outcomes and COUNTIF of countcomes to confirm the previous calculations. Then calculated the total projects for each range goal to determine the percentage of outcomes. The line graph was used to show a visual representation of outcomes based on goal. 

![Outcome_vs_Goal](https://user-images.githubusercontent.com/110945895/187045715-566e5c8c-a219-4e46-a7db-f94787cdb48c.png)
Figure 2. This line graph is demonstrating percentage of "successful," "failed," and "canceled" theater kickstarter over ranges of kickstarter funding goal. The percetage of "successful," and "failed" interchange between each other with the increase of funding goal. 

### Challenges and Difficulties Encountered
For the first deliverable, my first challenge is was using the YEAR function. I have not previously used this function and I was confused about using the function. I searched up the function of year function to learned that the function displayed the year of the date selected. Creating the pivot table was my second challenge. The second challenge was putting the right variables in the right section. I knew the "Years" and "Parent Catergory" went into the filtering section because it was directly mentioned in the instructions. I later realized that "Outcomes" had to go into column because in later instruction, I would have to filter "Outcomes" to specifically canceled, failed, and successful. In previous pivot tables that was created in the modules, we used "Outcomes" in the values, so I tried this too. In the confirmation photo, there were months displayed, with the only respresentation of time I used years. After this process, my pivot table looked like the photo of the confirmed pivot table in the instructions.

For the second deliverable, my third challenge was to properly display the "Number Successful," "Number Failed," and "Number Canceled" through the COUNTIFS function. I wrote notes about this function but when I first came across this function, I completely forgot how to use. I used the hint video to show me how to use the function and how to check the equation that I wrote out by writing the sum and the function without a range. 

## Results
The two conlusions about the Outcomes based on Launched Date was the peak successful month is May that is about 111 successful kickstarters in theater. The peaked failed months May, June, July, August, and October that is about 50 failed kickstarters in theater. The Outcomes based on Goals is that the line bar demonstrated that the higher the kickstarter goal, the higher chance that the kickstarter will fail. From 15000 to 34999 and 39999 to 44999, the percentage fail is higher than percentage successful. The limitation of this dataset is the still live sessions to not be able to add that to the data set and the cancellations restrict the dataset that we could have. We have no income possible data from this set. Some possible tables and graphs that we could create is stacked bar graph of number of outsomes for each month. 
