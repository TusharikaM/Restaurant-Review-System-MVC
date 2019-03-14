
# Restaurant_Review-Sysytem
A Play2 framework based java web application

This is a Restaurant Review System where customer rate the restaurant and owner can create a restaurant.

## How to run
Start mysql server and edit the conf file under ...\RestaurantReview\conf\application.conf

-enter database name
-enter mysql admin name
-enter mysql password 

To successfully run the application, system needs two things.
-SBT to run Play2 framework.
-MySql server.

In the application.conf file present in conf folder, please change default.username and default.password of MySql server according to your mySQL server credentials. The default.url points to the database schema it is connected to.


Just run the following command via sbt and it will automatically download all the play dependencies.

- sbt update
- sbt compile
- sbt run

Initially, it will take 10-15 minutes to download all the resources needed.
Once the project is started to go to the web browser and type localhost:9000

Follow the below given flow to go through the application.
Create Owner --> Login as Owner(Note: Use the same credentials used in Registration)-->Create Restaurnt.--> Create a Customer.--> Register as Customer.--> Login as Customer(Note: Use the same credentials used in Registration)-->Search Restaurnt based on pincode,
Rate Restaurant,
Review Restaurant
