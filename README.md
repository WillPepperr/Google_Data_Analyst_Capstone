<h1>Cyclistic User Data Summary</h1>


<h2>Description</h2>
In this simulated work project, I was given user data for a mock company named Cyclistic which provided bike rentals in Chicago. I was given data from trips taken which included information about the bike trip and the rider making the trip. Personal information was limited, so individual users and their ride habits could not be identified. My task was to analyze the data and find how subscribers use the service differently from users who pay for each ride individually. Finally, I was asked to give data-based recommendations on how to convert more of the "Casual" riders to Subscribers of the service. 
<br />


<h2>Languages and Programs Used</h2>

- <b>Power BI<b> 
- <b>MySQL
- <b>Excel
- <b>Powerpoint</b>



<h2>Program walk-through:</h2>

The data I needed was located in the form of 4 .CSV files. I realized the data files were too big to clean and transform in Excel. I decided the best option was to insert the tables into a MySQL database to clean the data.
<br />
<br />
<a href="https://imgur.com/hIjHesv"><img src="https://i.imgur.com/hIjHesv.png" title="source: imgur.com" /></a>
<br />
<br />
<a href="https://imgur.com/AJV8a2O"><img src="https://i.imgur.com/AJV8a2O.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
I first attempted to use the Import Wizard in MySQL workbench. However, the program would take hours to import the .CSV files. I decided to use the LOAD DATA INFILE function in a command window instead.
<br />
<br />
<a href="https://imgur.com/YJjTjUm"><img src="https://i.imgur.com/YJjTjUm.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
After I had all of the year's data into a single table, I began to clean the data. I removed trips with missing data cells and trips with unreliable data such as a person riding whose age is over 84. <br />
<br />
<br />
<a href="https://imgur.com/GzIzJRq"><img src="https://i.imgur.com/GzIzJRq.png" title="source: imgur.com" /></a>
<br />
<br />
<a href="https://imgur.com/gAtJAsv"><img src="https://i.imgur.com/gAtJAsv.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
After thoroughly cleaning the data, I launched Power BI and connected it to the MySQL database. <br/>
<br />
<br />
<a href="https://imgur.com/6IbS6UQ"><img src="https://i.imgur.com/6IbS6UQ.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
I then needed to calculate extra values to create the visuals. I used formulas in the data view to create calculations and new columns to create insightful visualizations.  <br/>
<br />
<br />
<a href="https://imgur.com/LLYmDr0"><img src="https://i.imgur.com/LLYmDr0.png" title="source: imgur.com" /></a>
<br />
<br />
<a href="https://imgur.com/Ho4vdOw"><img src="https://i.imgur.com/Ho4vdOw.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
I then proceeded to create the visualizations. I kept in mind the goal of the project which was to compare Subscribers to Casual Customers when creating the charts. I compared the trip data between the two across multiple metrics such as trip duration, day of the week, gender, and time of day<br />
<br />
<br />
<a href="https://imgur.com/n8jxnz2"><img src="https://i.imgur.com/n8jxnz2.png" title="source: imgur.com" /></a>
<br />
<br />
<a href="https://imgur.com/bMLel9Q"><img src="https://i.imgur.com/bMLel9Q.png" title="source: imgur.com" /></a>
<br />
<br />
<a href="https://imgur.com/gm2jrq7"><img src="https://i.imgur.com/gm2jrq7.png" title="source: imgur.com" /></a>
<br />
<br />
<br />
<br />
After I selected the most relevant charts, I created a PowerPoint presentation to present to investors. This included my conclusion to my analysis and my recommendations for converting Casual Riders to Subscribers.
<br />
<br />
<a href="https://imgur.com/l1hmOY9"><img src="https://i.imgur.com/l1hmOY9.png" title="source: imgur.com" /></a>
<br />
<br />
<h1>Conclusion</h1>
My prior analysis lead me to the conclusion that Casual Riders typically use the service for longer leisure trips and Subscribers use it for regular commutes. My conclusion is backed by the data and can be clearly understood by visualizations. 
<br />
<br />
I made 3 recommendations to convert Casual riders to Subscribers.
<br />
<br />
1. Visitors of Chicago are not incentivized to subscribe, unless they have access to the same service in their home city or if they travel to other cities enough with the service provided. Expanding service to other cities will increase subscribers for travelers and workers who frequently travel.
<br />
<br />
2. Adding another type of subscription service may be beneficial. Whether it be for weekend use or seasonal. However, this may discourage people to sign up annually and choose the smaller commitment.
<br />
<br />
3. Increasing the cost of weekend rides could make Casual Riders more inclined to switch to subscription service if they frequently use the bikes on weekends.

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
