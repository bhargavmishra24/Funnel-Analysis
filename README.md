# Funnel-Analysis
You are looking at data from an e-commerce website. The site is very simple and has just 4 pages: <br /> The first page is the home page.When you come to the site for the first time, you can only land on the home page as a first page.From the home page, the user can perform a search and land on the search page.From the search page, if the user clicks on a product, He/she will get to the payment page,where they will be asked to provide payment information in order to buy that product.If user does decide to buy, she ends up on the confirmation page.<br /> Goal of this project is to:<br /> 1) A full picture of funnel conversion rate for both desktop and mobile.<br />2) Some insights on what the product team should focus on in order to improve conversion rate as well as anything you might discover that could help improve 18 conversion rate. 
# Goal
The goal is to perform funnel analysis for an e-commerce website.Typically, websites have a clear path to conversion: for instance, you land on the home page,then you search, select a product, and buy it. At each of these steps, some users will drop off and leave the site. The sequence of pages that lead to conversion is called 'funnel'. Funnel analysis allows to understand where/when our users abandon the website. It gives crucial insights on user behavior and on ways to improve the user experience. Also, it often allows to discover bugs.</p>
# Data
We have 5 tables downloadable by clicking here.<br />
All the tables refer to only the user first experience on the site. The 5 tables are:<br />
 "user_table" - info about the user<br />
Columns:<br />
user_id : the Id of the user. It is unique by user and can be joined to user id in all other
tables<br />
date : the date when the user firstly landed on the site<br />
device : user device. Can be mobile or desktop<br />
sex : male/female<br />
 "home_page_table" - Users who landed on the home page<br />
Columns:<br />
user_id : the Id of the user. It is unique by user and can be joined to user id in all other
tables<br />
page : it is always home_page.<br />
 "search_page_table" - Users who landed on the search_page<br />
Columns:<br />
user_id : the Id of the user. It is unique by user and can be joined to user id in all other
tables<br />
page : it is always search_page
19<br />
 "payment_page_table" - Users who landed on the payment_page<br />
Columns:<br />
user_id : the Id of the user. It is unique by user and can be joined to user id in all other
tables<br />
page : it is always payment_page<br />
 "payment_confirmation_table" - Users who landed on the
payment_confirmation_table. That is, these are the users who bought the product.<br />
Columns:<br />
user_id : the Id of the user. It is unique by user and can be joined to user id in all other
tables<br />
page : it is always payment_confirmation_page<br />
