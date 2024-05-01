### Variables & Scoping 

1. Line 12 will output 3 because `var i` is intialized as a `var` and a `var` has no block scope. In the for loop, var i will increase from 0 until it doesn't pass the condition that i < prices.length, which is 3.

2. Line 13 will output 150 because `var discountedPrice` is intialized as a `var` and a `var` has no block scope. At the last iteration of the for loop, `var discountedPrice` = prices[3] * 1 (1 - 0.50). This simplifies to `var discountedPrice` = 300 * 0.5 = 150.

3. Line 14 will output 150 because `var finalPrice` is intialized as a `var` and a `var` has no block scope. At the last iteration of the for loop, `finalPrice` = Math.round(150 * 100) / 100. This simplifies to finalPrice = 150.

4. This function will return `var discounted`, which is an array of the discounted prices of three items. It will return `(3) [50, 100, 150]`.

5. The code causes an error because `i` is intialized using the `let` keyword inside of the for loop, so it cannot be accessed outside of that block and can only be accessed within the loop block."

6. The code causes an error because `discountedPrice` is intialized using the `let` keyword inside of the for loop, so it cannot be accessed outside of that block and can only be accessed within the loop block."

7. The code will give an output of 150 because `finalPrice` is initialized using the `let` keyword insde of the function, so it can be accessed by any block within the function, including the for loop. At the last iteration of the for loop, `finalPrice = Math.round(discountedPrice * 100) / 100`. This simplifies to `finalPrice = Math.round(150 * 100) / 100 = 150`.

8. This function will return `let discounted` because `discounted` is initialized using the `let` keyword insde of the function, so it can be accessed by anything inside of the function. `discounted` is an array of the discounted prices of three items, so the function will return `(3) [50, 100, 150]`.

9. The code causes an error because `i` is initialized in the for loop, so it can only be accessed within the for loop. But line 11 is trying to access `i` from outside the for loop, which is not doable.

10. Line 12 will return `3` because `length` is initialized as a `const` within the function and it can be accessed by anything within the function, as such at line 12.

11. The function will return `(3) [50, 100, 150]` because `discounted` is initialized as a `const` within the function, so it can be accessed by anything within the function, as such at line 14.


### Data Types

12. 
    1. `student.name`
    2. `student["Grad Year"]`
    3. `student.greeting()`
    4. `student["Favorite Teacher"].name`
    5. `student.courseload[0]` 

### Basic Operators & Type Conversion

13. 
    1. '3' + 2 = **'32'** because the `+` operator performs string concatenation when one of the operands is a string, which in this case, '3' is a string and so it concatenates '3' and 2 into the string **'32'**.
    2. '3' - 2 = **-1** because the `-` operator is used and it causes operands that can be converted to numbers and it subtracts the numbers. Therefore, '3' is converted into the number 3 and and 2 is substracted from it.
    3. 3 + null = **3** because the `+` operator converts null into the number 0, so 3 + 0 = 3.
    4. '3' + null = **'3null'** because the `+` operator converts null into the string 'nul' and it adds the two strings together into one string.
    5. true + 3 = **4** because `+` causes true to map to the number 1 and convert to a number, leaving us with the equation 1 + 3 = 4. 
    6. false + null = **0** because `+` causes false to map to the number 0 and null to be the number 0 as well, leaving us with the equation 0 + 0 = 0.
    7. '3' + undefined = **'3undefined** because the `+` operator converts undefined to the string 'undefined' and concatenates it with the string '3'.
    8. '3' - undefined = **NaN** because the `-` operator will try to convert undefined into a number to subtract it from 3, but undefined cannot be converted into a string, so the output is NaN.

### Comparison

14. 
    1. '2' > 1 = **true** because the `>` operator converts the string to a number and outputs the equality
    2. '2' < '12' = **false** because using the `<` with strings compares the two lexicographically and the string '2' comes after the string '12'.
    3. 2 == '2' = **true** because the `==` operator converts the operands to the same type and so it converts '2' into the number 2 and compares the equality.
    4. 2 === '2' = **false** because the `===` operator performs the equality comparison without converting any of the operands and a string and number cannot be compared, so it returns false.
    5. true == 2 = **false** because the `==` operator converts true into the number 1, and 1 does not equal 2, so it outputs false.
    6. true === Boolean(2) = **true** because Boolean(2) = true since it is a non-zero number, and true === true = true. 
  
15. Both operators are used for comparing two operands but the operator `==` is used for comparing operands after type coercion and so it converts the operands before comparing. On the otherhand, the operator `===` is used for comparing operands without performing type coercion and so it performs operators without converting them. 

### Loops

16. Answer in JS file part2-question16.js

### Functions

17.  The function modifyArray takes in two parameters, an array named array and a function named callback. modifyArray will take array and modify it by the function callback. In this case, the array will be [1, 2, 3] and the callback function will muliply each of the elements by 2 and output the resulting array, which is [2, 4, 6]. First, a new array called newArr will be initialized to contain the new elements that are modified. A for loop is created to go through all of the elements in the old array and modifying them while also adding the result to newArr. To be specific, the for loop will go through each element in the array passed through, which is the array [1,2,3] and then it applies the callback function to each element. This callback function is called doSomething and it takes each number in the array and multiples it by two. After performing doSomething to each element in the array, it adds the result to newArr and returns the modified array. 
   
### setinterval(), setTimeout(), clearTimeout()

18. Answer in JS file part2-question18.js

19. The output of the above code is 1 4 3 2. 