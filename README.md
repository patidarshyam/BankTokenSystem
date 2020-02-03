# BankTokenSystem

Assignment-
You are a developer who has been assigned to design a bank branch token system. To create a market compelling product you have been given the following specifications:
- A customer arrives to a bank will get a token from token machine.
- token will be displayed on the token display machine with the bank counter number.
- privileged customer of the bank would get higher priority by the bank.   

1) Please design your object model for a token system.
2) Please define the methods for your token system. 
3) Describe how your objects and methods would interact to create a token system.
4) implement the same as a demoable java application.
___________
Assumtions-
  Normal Customer - //Token number Start from 10 to 100
  Privileged Customer -//Token number Start from 1 to 10
  Counter's count -//Only 5 counters in a bank	
  
methods-
  getToken() - will generate the token for customer.
  displayToken()- This method display on the display machine with TokenId and BankCounter number.
  makeCounterFree() - This method shows that the work of the customer is completed so counter is free now and ready for another customer's work.
