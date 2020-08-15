# Best Buy Sales Marketing
## INFO7374-Algorithmic Digital Marketing - Final Project
Claat - https://codelabs-preview.appspot.com/?file_id=1Ewn3JD5UzfQQh1AWXfZ9d3jPKBuVexSPUzFezK-Og4s#15 <br/>
React App - https://bestbuyap-24e00.web.app/ 

![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/BEST%20BUY.png)
<br/>

## Purpose
The global consumer electronics e-commerce market is expected to grow from $282.6 billion in 2019 to about $373.6 billion in 2020 as the market initially experienced a surge due to purchase of electronic products that support work from home. The market is expected to stabilize and reach $548.4 billion at a CAGR of 18% through 2023.
Consumers are shifting from offline to online shopping, and this factor is the key driving factor of the consumer electronics e-commerce market. 
The stakeholders for our Application are the Decision Makers at Best Buy 

## Objectives
<ul>
<li>Identify the proposed trend in electronic sales</li>
<li>Find Customer Lifetime Values and Churn Rates</li>
<li>Use RFM analysis to segment the customers and run an effective promotional campaign for personalized service</li>
<li>Predicting Next Purchase Date for a particular customer to improve Retention Rate</li>
<li>Monthly Sales Forecasting</li>
<li>Build dashboards around the KPIs to empower decision makers</li>
</ul>


## Architecture
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/Architecture.jpg)

## Web Scrapping 
We've used Beautiful Soup to Web Scrap the Product Details like Product, Type, Img, UnitPrice.<br/>
This folder contains the Data generated and the code.<br/>
[/Web Scrapping/](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/tree/master/FinalProject/Web%20Scrapping)

### React App
Deployed using Firebase.<br/>
Frontend - [click here](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/tree/master/FinalProject/React%20App/bestbuyfront) <br/><br/>

We've used Flask to generate API as the backend and have deployed it on AWS EC2 instance.<br/>
Backend - [click here](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/tree/master/FinalProject/React%20App/bestbuyback) <br/>

## RFM Analysis

![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/RFM%20Analysis.jpg)<br/>
RFM stands for Recency, Frequency, and Monetary. It is the easiest form of customer database segmentation and is based on user activity data. RFM segmentation can be applied to activity-related data that has measurable value and repeatable. Therefore, it is a perfect strategy for eCommerce, because purchase history and website visits can be measured and tracked. Let’s look at each of the RFM components in more detail:<br/>

1.<b>Recency:</b> Recency is the most important predictor of who is more likely to respond to an offer. Customers who have purchased recently from you are more likely to purchase again from you compared to those who did not purchase recently.<br/>
2.<b>Frequency:</b> The second most important factor is how frequently these customers purchase from you. The higher the frequency, the higher is the chances of them responding to your offers.<br/>
3.<b>Monetary:</b> The third factor is the amount of money that customers have spent on purchases. Customers, who have spent higher amounts, are more likely to purchase compared to those who have spent less.<br/>


## Promotional Strategies
After predicting the next purchase date of the customer our strategy should be to expedite the purchase by the customer.<br/>
We have created different strategies on the basis of prediction and RFM scores<br/>

![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/Promotional%20Campaign.jpg)<br/>

On the basis of next purchase prediction and RFM Analysis we will be sending 3 different Mails for different customers.<br/>
1. 
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/More50.jpg)<br/><br/>
Mail sent to the user:<br/>
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/Mail50.jpg)<br/><br/>

2. 
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/Mail20to50.jpg)<br/><br/>

3. 
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/MailWithin20.jpg)

## Amazon SES
To generate the promotional mails we've used Amazon SES.
Amazon Simple Email Service (SES) is a cost-effective, flexible, and scalable email service that enables developers to send mail from within any application.<br/>

![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/AWS%20SMTP/step-1.png)

## Folders
Data has already been uploaded on S3 bucket<br/>
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/S3Bucket.png)<br>
To get the Data from S3 bucket run the below code<br/><br/>
![Alt Text](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/blob/master/FinalProject/Images/S3code.jpg)<br/>

Data Cleaning and Preprocessing - Removing NaN, duplicate values, Date Conversion etc. [click here](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/tree/master/FinalProject/Data%20Preprocessing)<br/>
 
Exploratory Data Analysis - [click here](https://github.com/rhnyewale/INFO7374-Algorithmic-Digital-Marketing/tree/master/FinalProject/EDA)<br/>

