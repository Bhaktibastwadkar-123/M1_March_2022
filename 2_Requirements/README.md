# Requirements

## Introduction

-  A hexadecimal number can be converted to octal by writing the binary equivalent of each hexadecimal digit in the same order. 
-  Converting the binary number obtained in the previous step to octal leads us to reach the overall result.
-   A binary number can be converted to octal by partitioning the binary digits in groups of three bits.

## Objective of the system

-  In the number system, we come across four different types of the number system, i.e. hexadecimal, octal, decimal and binary. 
-  The conversion of these numbers from one form to another is possible. 
-  To convert hexadecimal to octal numbers, we need to convert hexadecimal to its equivalent decimal number first and then decimal to octal

 Octal Number System
  - Octal number system has only eight (8) digits from 0 to 7. Every number (value) represents with
    0,1,2,3,4,5,6 and 7 in this number system. The base of octal number system is 8, because it has
    only 8 digits.
   
Decimal Number System
   - Decimal number system has only ten (10) digits from 0 to 9. Every number (value) represents
     with 0,1,2,3,4,5,6, 7,8 and 9 in this number system. The base of decimal number system is 10,
     because it has only 10 digits.
     
 Hexadecimal Number System
   - A Hexadecimal number system has sixteen (16) alphanumeric values from 0 to 9 and A to F.
     Every number (value) represents with 0,1,2,3,4,5,6, 7,8,9,A,B,C,D,E and F in this number
     system. The base of hexadecimal number system is 16, because it has 16 alphanumeric values.
     Here A is 10, B is 11, C is 12, D is 14, E is 15 and F is 16.

# Steps to following Hexadecimal to Octal conversion

- step1: First enter Hexadecimal number on to the input side
- step2: Press enter button.
- step3: Converted number is octal on the output side. 


# Hexadecimal to octal conversion
  Method 1:
   - Follow the method to find the octal decimal value of a hexadecimal number. We know that the hexadecimal number comprises binary digits. In this method, you can        combine these binary digits in pairs of three and you can relate them to the octal numbers. The steps involved in this method are given below.

   1. For every given hexadecimal number’s digit, note down the number equivalent to the binary number. Add 0’s to the left side, if any of the binary equivalents are       less than 4 digits.
   2. Next, combine the numbers and make the groups of binary digits from right to left, each containing 3 digits. In case there are less than 3 digits in the last           group, add 0’s to the group.
   3. Find the value equivalent to the octal numbers of each binary group.
  
 ## Example:
         Given, 1BC16 is a hexadecimal number.

          1 → 0001, B → 1011, C →1100

            Now group them from right to left, each having 3 digits.

           000, 110, 111, 100

           000→0, 110 →6, 111→7, 100→4

           Hence, 1BC16 = 6748
   
      
## High level Requirements:

| ID   | Description                                              | Category  | Status      |
| ---- | -------------------------------------------------------- | --------- | ----------- |
| HR01 | User shall be able to access                             | Techincal | IMPLEMENTED |
| HR02 | User shall be able to choose number                      | Techincal | IMPLEMENTED |
| HR03 | Choices of positions are set respectively                | Techincal | IMPLEMENTED |
| HR04 | User can see the results displayed                       | Techincal | IMPLEMENTED |
| HR05 |Extra grids can be added                                  | scenario  | Future      |
| HR06 | User shall be able to perform future implementations     | Scenario  | FUTURE      |   

## Low level Requirements:

| ID   | Description                                              | HRId   | Status (Implemented/Future) |
| ---- | -------------------------------------------------------- | ------ | --------------------------- |
| LR01 | User choice can be given to set the input                | HR02   | IMPLEMENTED                 |      
| LR02 | User can see the results displayed                       | HR04   | IMPLEMENTED                 |
| LR03 | Extra grids can be added                                 | HR06   | FUTURE                      |


