# Instagram-User-Analytics

### Project Description
User analysis is the process by which we track how users engage and interact with our digital product (software or mobile application) in an attempt to derive business insights for marketing, product & development teams.
These insights are then used by teams across the business to launch a new marketing campaign, decide on features to build for an app, track the success of the app by measuring user engagement and improve the experience altogether while helping the business grow.

### Problem
You are working with the product team of Instagram and the product manager has asked me to provide insights on the questions asked by the management team.

### Approach
<p>For this project, I have used My SQL Knowledge  to connect with SQL Server using My SQL Workbench and extracted the required data from the given database using the Join function, subqueries, Aggregation, where Clause, Group by, Distinct and other functions are required.</p>
<p>keeping the Primary key and foreign key in consideration provided all the reports asked by the marketing department and Investor metrics department.</p>
<p>I have used Google sheets and documents for making this presentation as it contains required Elements, Graphs, Images which made this project more attractive.</p>

### Dataset
[Click here to know the commands used for Analysis](https://docs.google.com/document/d/1I9AUvgB3n_Uql3Il_I22FbAfLQhhz-Rr/edit)
### Insights
#### Findings For Marketing Team
<b>1) Rewarding the Most Loyal Users:</b><br>
Here I am going to find the 5 oldest users who have been using this platform for the longest time.So it will be helpful to the Marketing team to reward the most loyal users.<br><br>
<b><i>Keywords in Query</i></b> : Select( For Selecting the columns ) , order by ( To Sort the Data ) , Limit ( To display the top number of rows ).<br>
![1](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/4ab86913-0e54-4061-8696-09c934f5f030) <br>
[Click here to see Loyal Users](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=657407722)<br>

<b>2)Remind Inactive Users to Start Posting:</b><br>
Here I am going to Identify users who have never posted a single photo on Instagram.So it will help the Marketing team to encourage inactive users to start posting by sending them promotional emails.<br><br>
<b><i>Keywords in Query :</i><b>  Where (Clause is used to filter the data based on condition) ,not in (include rows where a condition is not true)<br>
[Click here to see Inactive Users](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=0) <br>

<b>3) Declaring Content Winner:</b><br>
Here I am going to Identify the maximum number of likes for the Photo and respective information of the user. So it will help the Marketing team to declare the Winner of that Contest.<br><br>
<b><i>Keywords in Query :</i></b> inner join (this join is used to get the rows from the both columns which are having same data based applied on condition) ,group by (which is used to group the data based on column name).<br>
[Click here to see details of Winner](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=2002864564) <br>

<b>4) Hashtag Researching:</b><br>
Here I am going to Identify the top 5 Most used Hashtags by users. So it will help the partner brands  to know the most popular hashtags to use in their posts to reach the most people.<br><br>
<b><i>Keywords in Query :<i></b> as (this command is used to rename a column or table with an alias. An alias only exists for the duration of the query).<br>
[Click here to see top 5 hashtags](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=761976820)<br>

<b>5) Launcg AD Campaign:</b><br>
Here I Identified the Day Of the Week are Thursday and Sunday Which  help the Marketing team to know the best day to launch ads.
(1 - Sunday to 7 - Saturday)<br>
[Click here to see the user regestrations Vs Day of the week](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=338841784) <br>
#### Findings For Investor Metrics
### Conclusion
