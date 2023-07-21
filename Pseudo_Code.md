# EX 1 Write pseudocode for a program that takes two numbers as input and displays their sum.
- Enter the value of a
- Read a
- Enter the value of b
- Read b
- Sum a and b
- Show the results

# EX 2 Write pseudocode for a program that calculates and displays the average of three numbers.
- Enter the first number a
- Read a
- Enter the first number b
- Read b
- Enter the first number c
- Read c
- Sum the three number and divide by 3
- Display the result

# EX 3 Write pseudocode for a program that checks if a given number is even or odd and displays the result.
- Enter the number a
- Read a
- Devide a by 2
- If the rest is equal to 0 
- Display "The number is even"
- Else Display "The number is odd" 

# EX 4 Write pseudocode for a program that finds the maximum number among three given numbers and displays it
- Input the three numbers a,b,c.
- Create a variable called max to store the maximum
- max  is equal to the greater of a and b.
- Compare max and b , max is equal to the greater of max and c.
- Display "the maximum is : The value of max"

# EX 5 Write pseudocode for a program that calculates the factorial of a given number and displays the result.

- Input the number a
- create a variable n to store the factorial of a
- create a variable i index great than 1 and less than a
- i and n equal to a
- repeat until  i = 1 : n equal to n multiplied by a - i then i--
- Display "The factorial of a is f"

# EX 6 Write pseudocode for a program that prompts the user for their age and displays a message indicating whether they are eligible to vote (considering a voting age of 18 years).

- Input the age in the variable A
- substract A from 2023
- if the reslt is great or equal to 18 
- Diplay "Congratulations you are eligible for voting"
- else Display "Unfortunately you are not eligible for voting"

# EX 7 Write pseudocode for a program that prompts the user for a sentence and counts the number of words in it.

- Input the sentence in the variable S.
- Initiate the index W to 0 to count words.
- Initiate the index i to 0.
- S[i] equal to space increment W.
- Repeat it until the i equal to lenth (of the sentance) - 1
- Display " The number of words is W "

# EX 8 Write pseudocode for a program that takes a list of numbers as input and displays the sum of all the positive numbers in the list.

- Input the list of numbers
- Compare each number of variable with 0
- If the number is less or equal to 0
- Then sum equal to sum plus that number
- Display "The sum of the positive numbers in the list is sum"

# EX 9 Write a program that reads in 7 different numbers, then prints out the smallest value and also prints out the position of the smallest value in the input sequence as a number from 1 to 7.

- Input the 7 numbers in a list L
- Create an index "i" and initiate it to 0
- Create a variable S to store the smallest value
- initiate S by the first value, S = L[0]
- If the value of L[i] is less than S increment i and S=L[i]
- Repeat until i equal to 6
- Display "The smallest number is S, it's position is i+1 "

# EX 10 Write an algorithm allowing to enter 10 integers in an array, and to calculate the number of occurrences of an element N in this array. Where N entered by the user.

- Input the 10 integers in the list L.
- Input N, the number to calculate occurrences for.
- Create index i and initiate it to 0.
- Create Num the variable to store the number of times N is occurrent
- If N equal to L[i]

# EX 11 Ecrire un algorithme qui demande la saisie d'un tableau T de 10 entiers, et de mettre les éléments pairs dans un tableau T1 et les éléments impaires dans un tableau T2. Puis afficher T1 et T2.

- Input 10 integers numbers in a tableau T
- Create tableau T1 to stock even numbers
- Create tableau T2 to stock odd numbers
- create i index for T, and initiate it to 0.
- Devide T[i] by 2
- If the rest equal to 0 add T[i] to T1
- Else add T[i]=T2
- Display T1 and T2

# EX 12 Write an algorithm that displays the multiplication table of 8. Using the Repeat Until loop.

- Create index i and initiate it to 1
- Repeat until i is less or equal to 12
- Display " 8 x i = " Multiply 8 by i

# EX 13 A shop offers these customers a 15% reduction for purchase amounts over 200 dh. Write an algorithm to enter the total price excluding tax and calculate the amount including tax taking into account the reduction and VAT=20%.

- Input the purchase amount P
- create the variable TPex Total price excluding tax
- Create the variable TPinc Total price including tax
- if P greater than 200
- TPex = P multiplied by 0.65
- TPinc = P multiplied by 0.85
- Else 
- TPex = P multiplied by 0.80
- TPinc = P

# EX 14 Write an algorithm that asks the user for two numbers m and n and then informs them whether the product of these two numbers is positive or negative. We include in the program the case where the product can be zero.

- Input two numbers m and n
- create variable M equal to multiplication m and n
- if M is greater than 0
- Display " m x n  is positive"
- if M is less than 0
- Display " m x n  is negative"
- Display " m x n  equal to 0"