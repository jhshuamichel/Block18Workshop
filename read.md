Expectations: (For #1. A function called "multiplication" that returns the product of the two input numbers.)

- expect addition function to return the sum 
- function returns one single product from two input numbers.
- function creates a multiplication formula 
- expect multiplication  input1 ,input2 to be a number
- expect multiplication input 1, input2 to be  x
- expect multitplication input 1, input2 to be an error

Specification: (For #1. A function called "multiplication" that returns the product of the two input numbers.)

- Given two valid numbers, num1 and num2 
-When the multiplication function is called the result should be the product of num1 and num2.
- Given a negative number num1 and negative num2
- When the multiplication function is called the result should be positive product of num1 and num2.
-Given a num1 and a string entered as num2
- when the multiplication function is called the result should be an error.
<!--  -->

Expectations: (For #2)
- Expect the function to return an array as an output
- expect concatOdds([3,2,1], [9,1,1,1,4,15,-1]) should result in [-1, 1, 3, 9, 15]
- Unexpected input like strings entered should result in an error.

Specification: (For #2)
- The function should accept two arrays of integers as arguments
-The function should identify and extract odd numbers from both arrays.
- The odd numbers from both arrays should be combined into a single array.
-The result should be in ascending order.
- duplicate odd numbers should not be repeated and doubled into the array. 
- if input arrays are empty the function should handle it returning an empty array
-should display any amount length array inputs.

<!--  -->

Expectations:(For #3)
-Expect function if guess then create account or log in function
-Expect function logged-in user then no create account.
- Expect if user data entered does not meet requirements to redirect them.

Specification: (For #3)
-If the user checks out as a guest there should be an option to login if they already have an account.
-If the user checks out as a guest there should be a prompt asking to create an account after or not.
- Have the option to stay log in to avoid logging in again 
- Security paramaters to have password saved 