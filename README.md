# Sales_Insights_powerBI

1. SQL database dump is in db_dump.sql file above. Download `db_dump.sql` file to your local computer and import it

2. ### Data Analysis Using SQL

1. Show all customer records

    `SELECT * FROM customers;`

2. Show total number of customers

    `SELECT count(*) FROM customers;`

3. Show transactions for Chennai market (market code for chennai is Mark001

    `SELECT * FROM transactions where market_code='Mark001';`

4. Show distrinct product codes that were sold in chennai

    `SELECT distinct product_code FROM transactions where market_code='Mark001';`

5. Show transactions where currency is US dollars

    `SELECT * from transactions where currency="USD"`


<br> 3.  Data Analysis Using Power BI </br>
<br>============================ </br>
<br>Creating Power BI Report and DashBoards and publishing it </br>
