# M-Bank
Banking Management Application is a project application coded in Java programming language built using the basics of core java programming concepts. The application does not use any database and server. This application mocks the flow of a banking application from users perspective where the user accesses the information using the web application interface.
 
#### Following functionalities will be supported in the application:
- Login 
- Create a new account
- View Profile of the existing customer
- Edit Profile 
- Deposit/ Transfer Money from one account to another
- View Previous Transactions
- Change Password of login
- View Active cards
- Reissue New Card 
 
#### Few more advanced features can be made available:
##### Exception Handling: 
- Handle the exceptions using the error handling feature of JAVA. A mock server will be used to generate the availability of servers to let the developers handle the non-server availability option.
- Handle other features when the deposit fails/ withdrawal amount is greater than the available balance.
 
##### Advanced Security: 
- If the application is blocked on a single page for more than 30 seconds, the user is logged out of the application. This feature will use the concept of multi-threading. The account holder will be shown the timed clock. 
- A thread will record the time of total application usage in the last session and the time when the user is logged in. This record will be shown to the user in profile.
- Concurrently three times the pin is wrongly entered, the application is blocked for the user and a message is generated for the user on next login.
 
###### Some user records will be auto-populated in the internal memory of the application to perform the tasks. Please make sure that the application should be kept running in case a concurrent user is doing the transactions, otherwise the transaction record will be deleted.

#####  NOTE: This repository is still under development and new changes are being pushed frequently with added functionality. Make sure you clone the lastest version of the project.
 
[========]

## APPLICATION FLOW:


[========]

### Screenshots

###### Below are some attached image of how the console application will look on running the project.

- [![Intro Screen](https://i.ibb.co/dLVhBBc/Screenshot-from-2021-12-12-20-46-57.png "Intro Screen")](https://ibb.co/LJcGSSP "Intro Screen")

- [![Second screen](https://i.ibb.co/h9BjHhJ/Screenshot-from-2021-12-12-20-47-10.png "Second screen")](https://ibb.co/02CSZ8R "Second screen")

- [![Third Image](https://i.ibb.co/rc1pDXz/Screenshot-from-2021-12-12-20-47-57.png "Third Image")](https://ibb.co/jW1wnjQ "Third Image")

- [![Fourth Image](https://i.ibb.co/3SwKvZ0/Screenshot-from-2021-12-12-20-48-20.png "Fourth Image")](https://ibb.co/JrNZqJz "Fourth Image")
