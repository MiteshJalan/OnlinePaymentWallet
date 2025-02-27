
# Online Payment wallet Application REST-API

REST API for an online payment wallet application which can be used by bank customers for different services like creating a bank account, log in and Sign Up to an account, creating a wallet from a bank account, adding money to a wallet, Bill payment from a wallet, get transaction details from a wallet, etc.



## REST API Use for below functions
- User can Login and Signup.
- Create Bank account and wallet.
- Delete Bank account.
- Adding money to wallet.
- Money Transfer from one wallet to another wallet.
- Any Bill payments from wallet.
- User can see transactions details from wallet.
- CashBack Section.

## Tech Stack
- Java
- Hibernate
- Spring Framework
- Spring Boot with JPA
- MySQL
- Maven
- Lombok
- Swagger UI


## ER Diagram
Following ER diagram indicates the database tables and thier interaction which we are using.
![Untitled Workspace](https://user-images.githubusercontent.com/101566029/185031322-cca7cf0e-652d-4a75-8ca5-062b8d21614a.jpg)



## Modals
- Authentication 
- Bank Account
- Customer
- Wallet
- Bill Payment
- Cashback
- Transactions
- Beneficiary



## MySql database details

Install and connect with database

```bash
#db specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/walletdb
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=12345
```
## Running Tests
Run the following command on swagger UI
![swagger](https://user-images.githubusercontent.com/101566029/185036837-17caf0e0-94c6-4280-8719-20d52e2570c3.png)

## API Functionality are-
- #### User features
1.  User can login and SignUp.
2.  User can logout.

- #### Bank Account features
1.  User can create the bank account.
2.  User can get the account details.
3.  User can delete the account details.

- #### Customer features
1.  Customer can save the details with bank.
2.  Customer can update the details with bank.

- #### Wallet features
1.  User can seen the wallet balance.
2.  User can add the money to the wallet.
3.  User can transfer the money from wallet.

- #### Bill payment features
1.  User can pay any bill from wallet.
2.  User can get all bills details.

- #### Cashback features
1.  User can get the cashback whenever they pay the bills in range of 5% to 25%.

- #### Transaction features
1.  User can seen the transaction details with date wise.
2.  User can see the transaction details with wallet user.
3. User can see all the transaction details.

## Possible Next Steps/Things to improve:-
- Need to improve the Beneficiary like connection with wallet.
