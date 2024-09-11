In this exercise, we're going to be using the modulus operator (%), also known as mod.

Let's start by creating three integer variables, x , y and z, where their values are 43,  7, and 7, respectively. 

First, create and int variable named result that stores the remainder of x % y and print this result.
```
int result = x % y;
```
Next, reassign this result variable to y % x and print this new result. Remember you have already initialized the result variable so you don't have to use the "int" keyword again.
```
result = y % x;
```
Finally, reassign the result variable again to y % z and print the new result.

Click run and notice the remainders calculated for each number set.


**What do you notice about the examples that had a larger number on the right? What about examples with the same numbers on the left and right?**
When the number on the right is larger the remainder is equal to the number on the left. When the two number are equal then the remainder is zero.

**Understanding Mod**
The pattern of a modulus calculation is <number> % <modulus> = <remainder>

The result of using mod is the remainder of a division. To list some examples...

4 % 2 = 0
8 % 3 = 2
55 % 10 = 5

To better understand mod let's look at two examples calculated by hand. First we are given the problem and we recognize the number being divided as the number just before the mod sign. Next set up the numbers for long division and begin to divide as you usually would until you cannot continue without creating a decimal. The number you have leftover is your remainder, and your answer.

*Click on the Modulus.jpeg in the Files menu on the left to see the long division examples.*
