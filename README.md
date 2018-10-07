## Purpose of the project
In recent years in our country, farming products prices is increased highly by the time that consumers buy them. The goal of this platform is to decrease workload, time and economic burden and increase satisfaction of last consumer.


Use Case Diagram
===========

![alt text](img/UseCaseDiagram.png)

### Use Case of Registration

 1. User open the web page
 2. Click the **registration** button
 3. Fill the registration form correctly
 4. Submit the form
	1. Validation of user informations
	2. If validation successful go to step 4, else go to step step 3
5. The user check the mail box
	1. The mail is not sent user click the **resend mail** button and go to step 5
6. Click the **confirm** button in the mail
7. Registration completed.

### Use Case Of Selling Product

1. User login the account
2. User click the **sell product** button which on the profile page
3. Fill the product information's form
4. Submit the form
	1. Validation of product informations
	2. If validation successful go to step 5, else go to step step 4
5. The sale advertisement seem on the profile 
6. If the user want edit the product profile click the **edit** button, and go to step 3

### Use Case Of Buy Product

1. User login the account
2. User can search product with filter
    1. User sort the products (price, kind, date etc.)
    2. User comparate any product each other and choose whatever user wants    
3. User communicate the seller
4. If user and seller executive trade agreement, user click **contract** button and send feedback the system
    1. If user and seller do not deal each other, user go to step 2 
5. System delete the product info

### Use Case Of Auction System

1. The auctions should create 1 week ago before the auction date
2. Throughout the auction time who gives the most money is buy the product

**Auction For Seller**

1. Seller login the account
2. Seller create an auction event
    1. Fill the product info
    2. Fill opening price
    3. Fill increasing price
    4. Fill auction start date
    5. Fill amount of time of auction
3. The auction is added the system

**Auction For Buyer**

1. User login the account
2. User go to auction page
3. User choose the auction
4. User join the auction he chose
5. The system send a notification to User, before auction start an hour ago
6. User start the auction
