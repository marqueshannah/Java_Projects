# Credit Card and Money Management

This repository contains three Java classes that demonstrate credit card and money management functionalities. The classes include:

1. `CreditCardDemo`: This class demonstrates the usage of the `CreditCard` class. It creates an instance of a credit card and performs various operations such as charging amounts, making payments, and displaying the credit card information.

2. `MoneyDemo`: This class demonstrates the usage of the `Money` class. It creates an instance of a money object and performs operations such as addition, subtraction, comparison, and equality checks.

3. `Person`: This class defines a person by their name and address. It is used in the `CreditCardDemo` class to create an instance of the credit card owner.

## Usage

To run the demos and explore the functionalities, follow these steps:

1. Clone the repository to your local machine.

git clone https://github.com/marqueshannah/Java_Projects.git

2. Navigate to the `Credit_Card_and_Money_Calculator` folder.

```cd Java_Projects/Credit_Card_and_Money_Calculator```

3. Compile and run the `CreditCardDemo` class.

javac CreditCardDemo.java
java CreditCardDemo

4. Compile and run the `MoneyDemo` class.

```
javac MoneyDemo.java
java MoneyDemo
```

## Class Descriptions

### `CreditCardDemo`

This class demonstrates the functionalities of the `CreditCard` class. It creates an instance of a credit card, performs operations such as charging amounts and making payments, and displays the credit card information.

### `MoneyDemo`

This class demonstrates the functionalities of the `Money` class. It creates an instance of a money object, performs operations such as addition, subtraction, comparison, and equality checks, and displays the results.

### `Person`

This class defines a person by their name and address. It is used in the `CreditCardDemo` class to create an instance of the credit card owner.

## Sample Output:
### CreditCardDemo.Java:
```
Diane Christie, 237J Harvey Hall, Menomonie, WI 54751
Balance: $0.00
Credit Limit: $1000.00

Attempting to charge $200.00
Charge: $0.00
Balance: $200.00

Attempting to charge $10.02
Charge: $200.00
Balance: $210.02

Attempting to pay $25.00
Payment: $25.00
Balance: $185.02

Attempting to charge $990.00
EXCEEDS CREDIT LIMIT
Balance: $185.02
```
### MoneyDemo.java:

``` 
The current amount is $500.00
Adding $10.02 gives $510.02
Subtracting $10.88 gives $499.14
$10.02 equals $10.02
$10.88 does not equal $10.02
```


