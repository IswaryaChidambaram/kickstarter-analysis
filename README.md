# Analysis of Louise Campaign
### This analysis is to let Louise understand how different campaigns fared in relation to their launch dates and their funding goals. With the help of Kickstarter dataset different visulaisations have been created to undertsand the campaign outcomes based on their launch dates and their funding goals 

## Analsyis based on Launch Date :
#### Based on the launch date, number of campaigns which have been successful, failed, cancelled have been calculated. Using a Pivot table to the Dataset , placing the rows, coulmns and filters in appropriate position, filters have been applied to Year and Parent Category. The year have been drilled to months so the details are more specific. The filter to Parent category is set to "Theater" . With these conditions to the Pivot table fiedls, we can see that theater camplaigns have been the most successful in May and less successful in Dec. Theater Campaigns have failed the most in december and. Intrestingly, campaigns generally dont get cancelled in december.

### Screenshot of the Analysis based on Launch Date:
Markdown ![](Launchdate screenshot.png)

## Analysis based on Goals:
#### Baesd on the goal amount, number of campaigns which have been successful, failed, cancelled have been calculated. The Total projectsis the sum of the successful, failed, cancelled campaigns.Also the % of all these outcomes has been calculated.COUNTIFS is used to here to calculate the number of campaigns for all the goal amounts in all the outcomes in the"plays" subcategory. A line chart has been created which covers the goals, % successful, % failed, % canceled. We can see that when the goal amount<1000$ , the campaign tends to be the most successful. When the goal amount is more than 40000$, the campaign tends to fail.
