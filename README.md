# M1_March_2022
# Hexadecimal to Octal Conversion System
-While understanding the number system, you will come across four different types of number systems. These number systems are mainly - hexadecimal number system, octal number system, decimal number system, and binary number system. It is definitely possible to convert from one decimal system to another number system

![IMG-20220402-WA0008](https://user-images.githubusercontent.com/101447131/161424369-beed808b-a1ca-41d2-a651-00844224c8e9.jpg)


## Method1 :
You cannot convert a hexadecimal number to octal decimal number directly. First, you will have to convert the hexadecimal number to its decimal equivalent and then convert the decimal equivalent to octal decimal number. To understand better, follow the steps given below.
- Note down the given hexadecimal number.
- Count the number of digits and note down the number of digits in the number.
- Multiply each digit with 16x-1, if x is the position of the digit from the right end.
- Find the sum of the terms after multiplication.
- The result what is obtained is in the equivalent decimal form.
- Divide the obtained decimal number with 8.
- Write down the value of the remainder.
- Repeat step 6 and step 7 with the quotient, until the value of the quotient is zero.
- Note the remainders in reverse order.
- The number that is obtained is the required result.

## Method 2:
That was method 1. In case you find that difficult, you can also follow the other method to find the octal decimal value of a hexadecimal number. We know that the hexadecimal number comprises of binary digits. In this method, you can combine these binary digits in the pairs of three and you can relate them to the octal numbers. The steps involved in this method are given below.
- For every given hexadecimal number’s digit, note down the number equivalent to the binary number.  Add 0’s to the left side, if any of the binary equivalents are less than 4 digits.
- Next, combine the numbers and make the groups of binary digits from right to left, each containing 3 digits. In case there are less than 3 digits in the last group, add 0’s to the group.
- Find the value equivalent to the octal numbers of each binary group.
