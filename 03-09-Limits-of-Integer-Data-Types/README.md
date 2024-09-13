All variable types have a minimum and a maximum value. For integers, that minimum is  -2,147,483,648 and the maximum is 2,147,483,647. 

Why is knowing the min and max value of a variable type important?
For designing and debugging a program, we need to know the limits of our variables. If we go over the maximums or under the minimums of variable types they can give us unexpected results.

Feel free to test out these limits in your code! Check out the code in [Main.java](Main.java) and click "run" to see the results.

Why was the result negative when 1 was added to the maximum integer value?
Since the boundaries are -2,147,483,648 to 2,147,483,647, for an integer, we cannot store the value 2,147,483,648. So, instead of giving an error, a wrapping technique is used; when the maximum number is reached and an attempt to increase that number is made, it simply starts from the lowest possible value (-2,147,483,648) and increases from there. It loops, or wraps, around these values, never going past its max and min values.