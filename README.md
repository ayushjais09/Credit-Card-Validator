# Credit-Card-Validator

## Introduction
* The credit card validator - an application that verifies the authenticity and integrity of credit card numbers.  
* In this presentation, we will explore the importance of credit card validation, understand the structure of credit card numbers, learn about the Luhn algorithm, and discuss the significance of validation in 
  preventing fraud. So, let's embark on this enlightening journey into the realm of credit card validation!

## Importance Of Credit Card Validation 
* With the increasing prevalence of online transactions, credit card validation plays a crucial role in ensuring the security and integrity of payment processes.
* Validating credit card numbers helps prevent fraudulent activities, such as identity theft, unauthorized transactions, and card skimming.
* It provides merchants and financial institutions with a reliable method to verify the legitimacy of credit card information provided by customers.

## Structure Of Credit Card Validator
* Credit card numbers follow a specific pattern and structure that vary across different card issuers.
* Major card issuers, such as Visa, Mastercard, American Express, Discover, have their unique numbering schemes.
* The structure of credit card numbers typically includes a prefix (Issuer Identification Number), a variable-length account number, and a check digit.

## Introduction to Luhn Algorithm
* The Luhn algorithm is a simple checksum formula used to validate identification numbers.
* It is also known as the modulus 10 or mod 10 algorithm.
* The algorithm was created in the late 1960s by a group of mathematicians.
* Credit card companies adopted the LUHN formula shortly thereafter. 
* The algorithm is in the public domain, making it available for anyone to use.
* Most credit cards and many government identification numbers use the algorithm as a simple method of distinguishing valid numbers from mistyped or otherwise incorrect numbers. 
* The algorithm was designed to protect against accidental errors, not malicious attacks.

*Steps involved in the Luhn algorithm
Let’s understand the algorithm with an example: Consider the example of an account number “79927398713“. 
Step 1 – Starting from the rightmost digit, double the value of every second digit. 
![image](https://github.com/ayushjais09/Credit-Card-Validator/assets/154812179/d2450623-7109-4e45-ac08-9527b3b3eec1)

Step 2 – If doubling of a number results in a two digit number i.e greater than 9(e.g., 6 × 2 = 12), then add the digits of the product (e.g., 12: 1 + 2 = 3, 15: 1 + 5 = 6), to get a single digit number. 
![image](https://github.com/ayushjais09/Credit-Card-Validator/assets/154812179/f5f63553-c70c-44f6-b4f4-605473968aaf)

Step 3 – Now take the sum of all the digits.
![image](https://github.com/ayushjais09/Credit-Card-Validator/assets/154812179/7a800cdc-d800-442f-90b1-5d38f0c0e8a5)

Step 4 – If the total modulo 10 is equal to 0 (if the total ends in zero) then the number is valid according to the Luhn formula; else it is not valid.
![image](https://github.com/ayushjais09/Credit-Card-Validator/assets/154812179/e0a0beeb-3f40-4ec1-9872-96bfa98b826a)

Since the sum is 70 which is a multiple of 10, the account number is possibly valid.

# Flowchart
![image](https://github.com/ayushjais09/Credit-Card-Validator/assets/154812179/e84ce68a-1e52-44cf-bfd1-fc60bf164135)




