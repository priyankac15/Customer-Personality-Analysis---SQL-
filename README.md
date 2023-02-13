# Customer-Personality-Analysis---SQL-
Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It  helps a business to better understand its customers and makes it easier for them to  modify products according to the specific needs, behaviors, and concerns of different  types of customers.
<h1> PROJECT OVERVIEW </h1

Customer Personality Analysis dataset consists data of a company's ideal customers.

<b> Primary Use Case: </b>

- Modeling an enterprise database
- Store the structured data related to the Customer and services 
- Track customer information to manage the sales of products.
- Perform analysis to predict future trends of customer preference for tactical and strategic decision making. 

<b> Key Business Challenges: </b>
- Collection of inaccurate data.
- Lack of insight.
- Missing data points

<b>Application Solution </b>
- use of real-time validation tools.
- specific process in place to identify and resolve conflicting and out of date information.

<b>Cost Model </b>
The company for web purchases is freemium revenue model as the focus is on building the large customer base while ensuring they service free users cost-effectively.

<b> Personas' </b>

- Casual end-users: The managers of the company who occasionally access the database, but they look for different information each time.
- Naïve or Parametric end-users: The administrators or the store managers, cashiers of the stores who will enter the customer information.
- Sophisticated end-users: These are the business analyst, data scientists and engineers who need to have a thorough knowledge of the facilities provided by the DBMS. 

![image](https://user-images.githubusercontent.com/117341679/218349925-c7392d99-73e1-4a1e-9694-1feb5c4445ba.png)


<h2>BUSINESS RULES </h2>

- 1.A Customer will purchase Products.
- 2.A Customer can use different Platforms to purchase.
- 3.Different Promotional offer campaigns can be chosen by the Customer.
- 4.A Customer Complain will be registered only if it is less than 2 years old.
- 5.Feedback can be provided by the Customer.

<h3> FEW SQL EXAMPLES </h3>

<h3> Example 1 : Customers who are married and are born after 1980 and purchases wines. </h3>
 
 ![image](https://user-images.githubusercontent.com/117341679/218350731-c72e2944-1d95-4c19-8d15-78a8daf11c0a.png)


To retrieve the data for the above example, JOIN clause have been used to join tables (Customer-Platform-Products_Purchased)

<h3> Example 2 : Customers who are single and their promotional offer details.</h3>

![image](https://user-images.githubusercontent.com/117341679/218350761-cc9e98f3-c55d-4c88-9038-75eca090142c.png)
 
To retrieve the data from the Customer and Promotion table, JOIN clause have been used and it has been joined on Customer_ID of both the tables!

 <h3> Example 3 : Customer with 2 kids and are married prefers which platform. </h3>

![image](https://user-images.githubusercontent.com/117341679/218350940-7c779b39-2f76-4625-9b43-012a53636a8d.png)

To retrieve the data from the Customer and Platform table, JOIN clause have been used and it has been joined on Platform_ID of both the tables.
![image](https://user-images.githubusercontent.com/117341679/218350966-8f22b7cf-43e9-4956-90ae-48e79c0c117d.png)


<h3> METRICS & ANALYTICS </h3>

Database performance metrics help with database performance monitoring and optimize it for the business. Below listed our primary goals and traced the goal with data and metrics: 

![image](https://user-images.githubusercontent.com/117341679/218351011-b3aa29ab-c8d2-4f0e-abbc-483d10b0bc71.png)
 
<h3> SECURITY & ARCHITECTURE </h3>

As we are storing sensitive information of customers (birth year and income), there could be privacy/security concerns for our database.
The data is likely to be targeted by the hackers 
- Architecture :
We are planning to host the solution for this model on cloud due to the following reasons:
- Ease of access 
- Scalability 
- Reduced cost 
- Data Security 
- Data Analysis 
 
- Storage Requirements:
Initially 5gb storage is enough for our data. Later on, it can be expanded as per the needs

<h3> LESSONS LEARNED & NEXT STEPS </h3>
 
- Learnt about database architecture and use-cases using ER diagrams.
- Understood referential integrity and data normalization along with basic SQL syntax
- Got hands on experience of different SQL commands like SELECT and JOIN which helps in manipulating and retrieving data 
- Learnt trade offs between different architecture types, SDLC and data security 
- Learnt how to generate valuable insights, metrics and reports from raw data
- Future Ideas – Gaining more knowledge on advanced SQL concepts such as data warehousing, cloud and use of analytics to solve complex business problems. Also working on multiple real-world use-cases or scenarios.

