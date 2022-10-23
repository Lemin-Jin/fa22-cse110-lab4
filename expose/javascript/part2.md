# Part 2 Answers
1. We are printing the loop variable. After the loop at its third round (i = 3), it is not less than the length of the array, hence the for loop terminates and we print out the final value of i = 3;
2. It is printing out ```price[2]*(1-discount)``` which is 300 * (1-0.5) = 150, the last price it is calculated at for loop round 3.
3. It is printing out the same thing as line 13 did which is 150. It is rounding the discounted price to the 2 decimal values. But since in current cases, the value is a integer, there is nothing to round.
4. It will return a list of discounted price given the original price and discount, and the output of discounted price will be rounded to 2 decimal values.
5. error, since we are using i outside of its block(for loop). Nothing is available for printing.
6. error, same reason above. We are calling discounted price outside of its block(for loop), hence we are not getting any answer.
7. It is printing out ```price[2]*(1-discount)``` which is 300 * (1-0.5) = 150, but with a rounded value of 2 decimal places. But in this particular case, we have nothing to round. The block of this variable is the entire function, not just the for loop, hence we are able to print it inside the function
8. It will return a list of discounted price given the original price and discount, and the output of discounted price will be rounded to 2 decimal values. The scope of discounted is the entire function, and the value of discountedPrice has passed its value to finalPrice before its scope ended, the final result is not compromised.
9. error, since we are using i outside of its scope.
10. It will print 3. The scope of length is the entire function. Hence we are able to use it in the entire function
11. It will return a list of discounted price given the original price and discount. const means we cannot reassign values to the variable, but we can change the content within it. Hence pushing to the array can be executed and produce a normal output.
12. - student.name;
    - student['Grad Year'];
    - student.greeting();
    - student['Favorite Teacher'].name;
    - student.courseLoad[0];
13. - 2 is appended behind 3 since '3' is a string type
    - 3 - 2 = 1. There is no subtraction operation for string type, therefore this operation can be interpret as subtraction between two int,
    - 3 No operand is integer, hence perform numeric operation
    - 3null, one of the operand is string, perform concatnation
    - 4, no operand is string, and true regard as 1, hence an addition provides an output of 3
    - 1, no operand is string, and true regard as 1, null regarded as empty object. hence an outcome of 1
    - 3undefined, one operand as string, hence regard + as a concatenation operation
    - NaN, first, '3' is a string, hence try string operation, but undefined is not '3', hence cannot perform a string operation, then we try subtraction, since undefined is not a number, therefore a subtraction of a NaN is a NaN.
14. - true, string will be converted to number, since 2 > 1 produce a true value
    - false, since the first character is greater than the second
    - true, type conversion, 2==2
    - false, since 2 operands are not the same type
    - false, true will be converted to 1 in a type converted comparison
    - true, since for function Boolean(x), any non-empty/undefined value will provide a true boolean value. Hence true === true return true
15. == can compare after type conversion, === will return false if encounter different type operand
16. see .js file
17. the result is doubling every numeber in the initial array. Since the callback is used to bring other function to be used in the current function, the for loop in the modified array is keep calling dosomething with its parameter and collect its return value.
18. see .js file
19. First the program the 2 lines without time out, then it will print the line with 0 timeout, finally display the value with 1000ms timeout. Hence the order is {1 4 3 2}.
