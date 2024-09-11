In this exercise we are going to create integer variables, assign them values, and then learn how to divide them and store the result in another integer variable.

First, initialize an integer variable named num1 and assign it the value 50.

Remember, first we indicate the data type (int), then comes the variable name, then we use the assignment operator (the = sign) and finally provide the value:
```
int num1 = 50;
```
Next, initialize another integer variable named num2 and assign it the value 40.

Then, initialize integer variable named  answer to store the quotient of num1 divided by num2.
```
int answer = 40;
```
Finally, display the answer variable in the console, using a print statement. 

Notice
The exact answer to 50 divided by 40 is 1.25, but since we are storing that number in an integer variable that number gets truncated. When a value is truncated this means that it is not rounded, instead, it is simply stripped of its decimal point and decimal values. This is why our program gives us 1 instead of 1.25.