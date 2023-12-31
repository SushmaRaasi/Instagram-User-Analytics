# Instagram-User-Analytics

- [Project Description](#project-description)
- [Problem](#problem)
- [Approach](#approach)
- [Dataset](#dataset)
- [Insights](#insights)
  - [Findings For Marketing Team](#findings-for-marketing-team)
  - [Findings For Investor Metrics](#findings-for-investor-metrics)
- [Conclusion](#conclusion)

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
![Loyal Users](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/82322e38-21b7-44c4-870d-a8c6c1625402)<br>
[Click here to see Loyal Users](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=657407722)<br>

<b>2)Remind Inactive Users to Start Posting:</b><br>
Here I am going to Identify users who have never posted a single photo on Instagram.So it will help the Marketing team to encourage inactive users to start posting by sending them promotional emails.<br><br>
<b><i>Keywords in Query :</i><b>  Where (Clause is used to filter the data based on condition) ,not in (include rows where a condition is not true)<br>
![2](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/cc52bd58-6328-4cad-b5f5-c64549fe8178)
<br>
[Click here to see Inactive Users](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=0) <br>

<b>3) Declaring Content Winner:</b><br>
Here I am going to Identify the maximum number of likes for the Photo and respective information of the user. So it will help the Marketing team to declare the Winner of that Contest.<br><br>
<b><i>Keywords in Query :</i></b> inner join (this join is used to get the rows from the both columns which are having same data based applied on condition) ,group by (which is used to group the data based on column name).<br>
![3](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/1cc1f3e8-94cd-4e42-9fb1-c8ac67f1773b)
 <br>
[Click here to see details of Winner](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=2002864564) <br>

<b>4) Hashtag Researching:</b><br>
Here I am going to Identify the top 5 Most used Hashtags by users. So it will help the partner brands  to know the most popular hashtags to use in their posts to reach the most people.<br><br>
<b><i>Keywords in Query :<i></b> as (this command is used to rename a column or table with an alias. An alias only exists for the duration of the query).<br>
![4](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/a9f331a3-c668-4c31-b003-38175dcf9216)
<br>
![4 1](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/0e692c69-82f8-47b4-880b-7203cb4e452f)
<br>
[Click here to see top 5 hashtags](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=761976820)<br>

<b>5) Launcg AD Campaign:</b><br>
Here I Identified the Day Of the Week are Thursday and Sunday Which  help the Marketing team to know the best day to launch ads.
(1 - Sunday to 7 - Saturday)<br>
[Click here to see the user regestrations Vs Day of the week](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=338841784) <br>
![5](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/cf0ac4f8-6c08-46c3-923c-22810eb17882)
<br>
![5 1](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/67c3c938-1567-46cb-b79e-bcfca6bb9c47)
<br>

#### Findings For Investor Metrics
<b>1) User Engagement:</b><br>
Here I am going to calculate the average number of posts per user on Instagram. So It will help the Investors to know if users are still active and posting on Instagram or if they are making fewer posts.<br><br>
<b><i>Keywords in Query :</i></b> left join (this join is used to get the all rows from the left table and matching rows from the right table based applied on condition)<br><br>
<b><i>Quantitative Metrics:</b></i><br>
Also, I would like to provide details like the total number of photos on Instagram (257) & total number of users (100),Active users (74). So the Average is 2.57
Based on the results, there are –
    so the average will be 257/74 = 3.47, Based on the data. we can say that an average user posts 3-4 times.<br>
![6](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/0217f3c4-7c23-4fb2-b254-cc06e03d22b8)
<br>
[Click here to see the Average number of posts per user](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=475570987) <br>

<b>2)Bots & Fake Accounts:</b><br>
Here I am going Identify users (potential bots) who have liked every single photo on the site, as this is not typically possible for a normal user.So it will help the Investors to know if the platform is crowded with fake and dummy accounts. By this metric we have identified a potential impact for the investors.<br><br>
<i><b>Keywords in Query :</i></b> count() (This function is used to count the number of rows.<br>
![7](https://github.com/SushmaRaasi/Instagram-User-Analytics/assets/79751402/374f23f2-caa1-4dd5-9879-c57c28aa6851)
<br>
[Click here to see the Duplicate Accounts](https://docs.google.com/spreadsheets/d/1OPE56YzaY_bdorXgr4XLzBNEXPd4NKiyoQ9K6WI5up0/edit#gid=1672255612) <br>

### Conclusion 
<p>From this project, I got an idea about how as a business or data analyst we work on real-time data to take and data-driven decisions.
One thing I infer about this project is the dataset provided was very limited and small in respect of Rows and columns, but still, it was a very good experience working on such a project.
It helped me a lot to understand the analysis process well, and to provide insights for the best decision possible.</p>



















