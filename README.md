# Python-Deep-Dive-Functions

CaseStudy1:

1. A Robot moves in a Plane starting from the origin point (0,0). The robot can move toward UP, DOWN, LEFT, RIGHT. The trace of Robot movement is as given following:
UP 5
DOWN 3
LEFT 3
RIGHT 2
The numbers after directions are steps. Write a program to compute the distance current position after sequence of movements.
Hint: Use math module.

2. Data of XYZ company is stored in sorted list. Write a program for searching specific data from that list.
Hint: Use if/elif to deal with conditions.

3. Weather forecasting organization wants to show is it day or night. So, write a program for such organization to find whether is it dark outside or not.
Hint: Use time module.

4. Write a program to find distance between two locations when their latitude and longitudes are given.
Hint: Use math module.

5. Design a software for bank system. There should be options like cash withdraw, cash credit and change password. According to user input, the software should provide required output.
Hint: Use if else statements and functions.
Module 3 – Deep Dive - Functions, OOPs, Modules, Errors and Exceptions

6. Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line.

7. Write a program which can compute the factorial of a given numbers. Use recursion to find it.
Hint: Suppose the following input is supplied to the program:
8
Then, the output should be:
40320

8. Write a program that calculates and prints the value according to the given formula:
Q = Square root of [(2 * C * D)/H]
Following are the fixed values of C and H: C is 50. H is 30.
D is the variable whose values should be input to your program in a comma- separated sequence.
Example:
Let us assume the following comma separated input sequence is given to the program:
100,150,180
The output of the program should be:
18,22,24

9. Write a program which takes 2 digits, X,Y as input and generates a 2-dimensional array. The element value in the i-th row and j-th column of the array should be i*j.
Note: i=0,1.., X-1; j=0,1,¡Y-1.
Example:
Suppose the following inputs are given to the program:
3,5
Then, the output of the program should be:
[[0, 0, 0, 0, 0], [0, 1, 2, 3, 4], [0, 2, 4, 6, 8]]
Module 3 – Deep Dive - Functions, OOPs, Modules, Errors and Exceptions

10. Write a program that accepts a comma separated sequence of words as input and prints the words in a comma-separated sequence after sorting them alphabetically.
Suppose the following input is supplied to the program:
without,hello,bag,world
Then, the output should be:
bag,hello,without,world

11. Write a program that accepts sequence of lines as input and prints the lines after making all characters in the sentence capitalized.
Suppose the following input is supplied to the program:
Hello world
Practice makes perfect
Then, the output should be:
HELLO WORLD
PRACTICE MAKES PERFECT

12. Write a program that accepts a sequence of whitespace separated words as input and prints the words after removing all duplicate words and sorting them alphanumerically.
Suppose the following input is supplied to the program:
hello world and practice makes perfect and hello world again
Then, the output should be:
again and hello makes perfect practice world

13. Write a program which accepts a sequence of comma separated 4 digit binary numbers as its input and then check whether they are divisible by 5 or not. The numbers that are divisible by 5 are to be printed in a comma separated sequence.
Module 3 – Deep Dive - Functions, OOPs, Modules, Errors and Exceptions
Example:
0100,0011,1010,1001
Then the output should be:
1010

14. Write a program that accepts a sentence and calculate the number of upper case letters and lower case letters.
Suppose the following input is supplied to the program:
Hello world!
Then, the output should be:
UPPER CASE 1
LOWER CASE 9

15. Give example of fsum and sum function of math library.


CaseStudy2:

Case Study
Domain – Banking Marketing
focus – Optimization
Business challenge/requirement
Bank of Portugal runs marketing campaign to offer loans to clients. Loan is offered to only clients with particular professions. List of successful campaigns (with client data) is given in attached dataset. You have to come up with program which reads the file and builds a set of unique profession list and given input profession of client – system tells whether client is eligible to be approached for marketing campaign.
Key issues
Tele Caller can only make x number of cold calls in a day. Hence to increase her effectiveness only eligible customers should be called

Approach to Solve
You have to use fundamentals of Python taught in module 2
1. Read file bank-data.csv
2. Build a set of unique jobs
3. Read the input from command line –profession
4. Check if profession is in list
5. Print whether client is eligible
