# E-Commerce Website(Online Shopping website)

This is an E-Commerce Website build for selling electronics products online.

This project has two section ->user and admin.

User can visit the websites, register and login to the website. They can check all the products available for shopping, filter and search item based on different categories, and then add to cart. They can add multiple item to the cart and also add or delete the quantity in the cart. Once the cart is updated, the user can proceed to checkout and click the credit card payment details to proceed. Once the payment is success the orders will be placed and users will be able to see the orders details in the orders section along with the shipping status of the product.

The admin also plays an important role for this project as the admin is the one responsible for adding any product to the store, updating the items, removing the item from the store as well as managing the inventory. The admin can see all the product orders placed and also can mark them as shipped or delivered based on the conditions.

One of the best functionality that the projects include is mailing the customers, so once a user registers to the website, they will recieve a mail for the successful registration to the website, and along with that whenever a user orders any product or the product got shipped from the store, then the user will also receive the email for its confirmation. Sometimes, if the user tried to add any item which is out of stock, them they will get an email one the item is available again the stock.

Note: The payment page is created only for demo purpose and its not fully integrated with any payment gateway. So for now any credit card details will be accepted and the demo orders will be placed.



## Technologies Used

**Frontend:** HTML, CSS, JavaScript, BootStrap

**Backend:** Java, JDBC, Servlet, JSP

**Database:** Mysql





## Software and Tools Required

• Java [JDK 19]
• Eclipse EE (Enterprise Edition) 
• Apache Maven 
• Tomcat v8.5
• MySQL Server 
• MySQL Workbench 


## Database Intialization

STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the administrator user of MySql: `mysql -u <username> -p` (Enter Password if asked)

STEP 3: Copy paste and execute the MySQL Query from the following file:-
Run the Sql Query From this file: databases/mysql_query.sql


## Generatin Gmail App Password [For Mailing Functionalities]

Step 1: Create a gmail account or login to existing account in any browser

Step 2 : Go to https://myaccount.google.com/security and check if 2 step verifications is enabled or not, enable it if not enabled

Step 3: Go to https://myaccount.google.com/apppasswords and enter password if asked

Step 4: In Select an App Section: select Other (custom name) => enter "Electronics" => Generate

Step 5: After that it will generate 16 digits app password which you need to copy and save for future configurations.

Step 6: Done : Now continue to importing the project. [Don't share the above password generated to anyone]



## Importing and Running The Project Through Eclipse 

Step 1: Extract the downloaded file in a folder.

Step2: Open Eclipse.

Step3: Click on File-> Open Project from file system-> Directory-> select the Extracted folder-> Finish.

Step 4: Go inside `Java Resources > src > application.properties` and update the values as below:

a) Update value for db.username and db.password according to your installed mysql credentials.

b) Update value for mailer.email and mailer.password, with the same email and app password that you generated earlier in above section [ NOTE:Actual gmail password will not work].

Step 5: Right Click on Project-> Run as-> Maven Build-> In the goals field enter "clean install"-> apply-> run.

Step 6: Right click on project-> Build Path-> Configure Build Path-> Add Library-> JRE system Library-> workspace default JRE(jdk19)-> Finish.

Step 7: Right Click on Project-> maven-> update project-> select force update-> apply-> close.

Step 8: Right Click On Project-> Run As-> Run On Server-> Select Tomcat Version-> Next-> Add the project-> Finish.

Note: Default Username And Password For Admin Is "admin@gmail.com" And "admin"

The default Username And Password For User Is "guest@gmail.com" And "guest"



## Screenshots of project
Home page





![Home page](https://github.com/pooja4242/E--commerce-website/assets/74983858/ee174c03-6e7b-4968-9495-625d3efb221f)



Register




![Registration](https://github.com/pooja4242/E--commerce-website/assets/74983858/2cfa7640-78c3-48a7-8346-7630ed204d53)


Login




![Login form](https://github.com/pooja4242/E--commerce-website/assets/74983858/7289a9d6-01ef-4071-888f-a54551434e88)

User Profile




![User profile](https://github.com/pooja4242/E--commerce-website/assets/74983858/8f2c6b16-22a6-4287-8c7c-7580e1fc803d)

Cart




![Cart](https://github.com/pooja4242/E--commerce-website/assets/74983858/8fe860d0-2abd-48a6-bf71-0ff03ac79d63)

Credit Card Details





![Credit Card Details](https://github.com/pooja4242/E--commerce-website/assets/74983858/2dedccc0-488d-4e63-8e9f-3d2564c7d74e)


Admin- Homepage




![Admin- Home](https://github.com/pooja4242/E--commerce-website/assets/74983858/336bafc0-e339-44a8-8e5f-f6a5a6c653ea)

Admin-Add Product





![Add Product](https://github.com/pooja4242/E--commerce-website/assets/74983858/d4f62cc9-4ce2-45c9-a70c-ef011926c07d)


Update Product





![update product](https://github.com/pooja4242/E--commerce-website/assets/74983858/c6ebe627-0432-406e-90b7-ac3f1db92d13)


Stock






![Stock](https://github.com/pooja4242/E--commerce-website/assets/74983858/37e0fddf-502e-4304-999a-84c1ada2449a)




Unshipped Products





![Unshipped orders](https://github.com/pooja4242/E--commerce-website/assets/74983858/dd165cf7-bdcf-4c89-a186-5c879f5d652a)


Shipped Products






![Admin- order shipped](https://github.com/pooja4242/E--commerce-website/assets/74983858/ad6d5e5e-35d3-4831-83ca-0d9c8275bcb6)




Feedback






![Comment](https://github.com/pooja4242/E--commerce-website/assets/74983858/7f481a74-fb9a-48c0-9312-36391a83a677)



User- order shipped





![User-order shipped](https://github.com/pooja4242/E--commerce-website/assets/74983858/8cbbffb0-9dd8-4aec-ad60-ecb1aee92571)


Mails


Registration Mail




![Registration mail](https://github.com/pooja4242/E--commerce-website/assets/74983858/aae422a9-85f2-4061-baa1-91069023389f)


Order Mail




![Order Mail](https://github.com/pooja4242/E--commerce-website/assets/74983858/c2b03212-0afb-4ab4-9f17-e8e078ebc0df)


Order Shipped Mail




![Shipped Mail](https://github.com/pooja4242/E--commerce-website/assets/74983858/513c1fb2-6cf4-4e49-b516-c94fdfe05335)

Class Diagram




![Sql Diagram](https://github.com/pooja4242/E--commerce-website/assets/74983858/57b9c9b3-d2ae-41c0-9b6b-90841fa389e6)
