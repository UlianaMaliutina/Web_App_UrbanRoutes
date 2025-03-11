## Requirements Analysis

**FR-CS32:**

* Check the user can add card information to the app:  
  * user can add card information;  
  * click Add button to add card as a payment method;  
* Check that user can order car only after adding card information  
* Check that there’s no limit to the number of cards which user can add to the app

**FR-CS33:**

* Check the field Card number:  
  * user can enter only numbers;  
  * user cannot enter more than 12 characters;  
  * input format is *nnnn nnnn nnnn;*  
  * spaces are added automatically when the field isn’t in focus;  
  * boundary values for input are from 0000 to 9999;  
* Check the CVV/CVC field:  
  * user can enter only numbers;  
  * user cannot put more than 2 characters;  
  * input format is *nn*;  
  * boundary values for input are from 01 to 99;  
* Check the Add button:  
  * Add button remains inactive if the field Card number contains less than 12 characters;  
  * Add button remains inactive if the field CVV/CVC contains less than 2 characters;

**FR-CS35:**

* Ensure that payment details are validated before encryption  
* Ensure that payment details card are encrypted on client side  
* Ensure transmission occurs over a secure channel  
* Specify the format of the encrypted data  
* Check that server gets request(payment details) in encrypted format

**FR-AT4:**

* Check that total travel time is calculated correctly for Aero Taxi  
* Check that total travel cost is calculated correctly for Aero Taxi

**FR-AT6:**

* Check that calculation result displays:  
  * total travel time for Aero Taxi;  
  * total cost for Aero Taxi  
* Check that both travel time and cost are displayed as a result of calculation for Aero Taxi