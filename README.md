# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
	The Kickstart file, gathered by Louise, contains data on campaigns from theatricals acts gathered in multiple countries based on launch dates and their deadline. Data that is represented in the spread sheet includes: Name of theatrical act, summarization of act (Blurb), Campaigns goals and pledges, outcomes of campaigns (Successful, failed or canceled), number of supporters(backers), and currency in which pledges were collected. More values were inputted as our analyzation of the data expanded. 
The data given from Louise was further analyzed in depth to demonstrates our understanding of utilizing excel via functions and graphs learned in module one. In this process, I was able to help Louise determine how different campaigns fared in relation to their launch dates and funding goals. 

### Purpose
	The main purpose of this analysis is to find how different campaigns faired in relation to their launch date and funding goals. Specifically, a visual representation was created for both. Theater outcomes based on launch dates shows how each campaigned was either successful, canceled, or failed by months regardless of year. Outcomes based on goals shows the percentage of successful, failed and canceled theater plays through specific ranges of pledges collected. These findings are represented in stacked line graphs.  
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
	Some of the challenges faced was when creating the right =Countif equation when it came to the outcome based on goals. There was several mistakes in my formula that would make my data results skewed or create an error when excel would solve it. I had to fine tune the formula as simple errors such as a space in between the variable in the equation would give me an error. Another was that I would put: =COUNTIFS(Kickstarter!F:F,"canceled",Kickstarter!D:D,"=>5000",Kickstarter!D:D,"<10000",Kickstarter!R:R,"plays")
Where as the correct way to format the function is putting “>=5000”.
	Most of the challenges were human error on my part to find the correct analysis of the data set.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?	
Based on the graph I created, I can conclude that the most successful campaign was during the month of May with (111 successful) due to total campaigns launch was also at a high (166 total). The lowest successful campaigns were on the month of December (37). Between the months of March and May, the number of outcomes based on launch dates saw the highest increase (57 successful) in two months, while April to May being the high increase for a single month (40 successful). Failed theater outcomes were at their highest in May (52 failed) and stayed relatively high for the next couple of months until it saw a decrease in September (34 failed). From the month of September to October, Failed campaigns saw its highest increase (17 failed) in a single month. When it came to canceled campaigns, October saw 0 canceled but consequently, the increase of failed campaigns was at a high. (CHART LINK) 
- What can you conclude about the Outcomes based on Goals?
	In conclusion, outcomes based on goals were inversely correlated for successful and failed campaigns when analyzing the percentage of successful and failed based on specific ranges (ex,5000). As percentage of successful campaigns increases, percentage canceled campaigns decrease, vis versa. (CHART LINK) 

- What are some limitations of this dataset?
	Limitation of this data set analysis would be that we only looked at theatrical campaigns and the number of backers who contributed to pledges were not taken into consideration. The other limitation is that we did not take into consideration the length of the campaign. 

- What are some other possible tables and/or graphs that we could create?
	Possible tables or graphs we can create would be looking at the average donation from backer based on the month or year. Another suggestion is finding the length of time it took to reach a successful campaign goal. By doing so we can also analysis if the duration of a campaign impacts the outcome. 
