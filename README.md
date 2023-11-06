# ite1

**ITE1 Activity**

Construct a class named Account representing a Bank Account

_Private Member Variables:_

1. Balance - a double data type that holds the total amount of money of the customer
2. isEmpty - a Boolean variable that is true when the account has zero balance, or became zero balance, and false otherwise

_Note:_ NO need to declare additional member variables other the ones specified.

_Member Methods:_ (All methods are public)

1. getBalance() this returns the remaining balance of that account.
2. getDateCreated() this method returns the date the account was created
3. deposit( amount ) this convenience method lets you deposit an amount in an account.
4. withdraw( amount) this method lets you withdraw money from the account, it returns true if withdrawal is successful, and returns false otherwise

4.1 successful signifies that the amount to withdraw is a valid amount meaning it's not higher than the balance or a negative value

_Constructor:_

Account( initial\_deposit, thedatecreated) this sets the initial balance of that account, and the date that it was created

_Note:_ NO need to declare additional member function other the ones specified.

Construct a another class named Customer representing a Bank Customer

_Note:_ this object holds another object called Account, keep this in mind when designing the program

_Private Member Variables:_

1. Account – this is the type that you had just made, this will hold the account for the customer.
2. firstname – the firstname of the Customer
3. lastname – the lastname of the Customer

_Note:_ NO need to declare additional member variables other the ones specified.

_Member Methods:_ (All methods are public)

1. getFirstName() – returns the customer's first name
2. getLastName() – returns the customer's last name
3. getAccount() – returns a reference to Account object, which can be use to access member variables/functions of Account object

_Note:_ NO need to declare additional member function other the ones specified.

_Constructor:_

Customer(firstname, lastname, Account) – the constructor accepts 3 parameters the firstname of the customer, lastname, and a reference to his/her account, this will be pass to the member variables of this object

Construct a Tester class within the same namespace that tests the Customer Class

- Create at least 3 different customers
- Demonstrate the use of the different methods specified
- Save your project files as a compressed file named it \<yoursurname\>-\<MM\_DD\_YY\>-drill1.rar to a folder named CSP1
