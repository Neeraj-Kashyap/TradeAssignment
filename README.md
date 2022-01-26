# TradeAssignment
Trade Assignment from Deutsche Bank



Write a Java program with all the JUNIT cases. TDD approach will be preferred. 
Problem Statement
There is a scenario where thousands of trades are flowing into one store, assume any way of transmission of trades. We need to create a one trade store, which stores the trade in the following order


<img width="1007" alt="Screenshot 2022-01-26 at 11 37 41 AM" src="https://user-images.githubusercontent.com/50650883/151112204-800df172-53f1-4523-8cf2-9ec413c331c4.png">


There are couples of validations, we need to provide in the above assignment
1.	During transmission if the lower version is being received by the store it will reject the trade and throw an exception. If the version is same, it will override the existing record.
2.	Store should not allow the trade which has less maturity date then today date.
3.	Store should automatically update the expire flag if in a store the trade crosses the maturity date.

