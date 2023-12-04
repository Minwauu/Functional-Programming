# Functional-Programming

## Basics of functional programming 

- Programming paradigm: A style or way of computer programming. Different languages support writing programs in different ways.

- Four major programming paradigms exist
   - Procedural
   - Object-orientated
   - Declarative
   - Functional
 
- Main features of Functional Programming:
   - Functions are used as the fundamental building blocks (unlike on other paradigms which allow objects, procedures etc. )
   - Statements are written as a series of functions.
   - Each accepts input data as arguments and returns an output.
   - **Statelessness & immutability**
       - Values of variables can not change
       - Variables are immutable
       - The program is stateless
   - **No side effects**
       - A function can only perform a calculation and return a value.
       - This results in code being much easier to write correctly.
       - Easier for the programmer to understand.
       - Easier to predict how the program will behave.
       - Less prone to bugs.
       - All this aids massively in writing programs which need to take advantage of **parallel processing**.
       - Makes functional programming ideal for processing **Big Data**.
  
    ![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/0f7990f3-fe53-4fd9-ab89-b734dbf08113)


  - In functional programming a function is considered a **first-class object*.
  - A first class object is an object which may:
    - Be assigned to a variable
    - Appear in expression
    - Be assigned as an argument
    - Be returned in a function call
  - First class objects we are already familiar with are:
    - Integers
    - Real/Float/Decimals
    - Characters
    - Strings
   
## Function application 

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/ea612cc1-faed-4044-9078-c49877521d5a)

## Currying 

- All functions in Haskell are curried. This means that function that takes multiple parameteres is actually a sequence of single parameter functions.S

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/9acc3075-3e24-4be9-94ba-aaf807471603)

- This is a function that takes a number that returns a function that takes a number and returns the sum of the two numbers.

## Partial application of functions

- Curring is related to the partial application of functions. Partial application of a function occurs when a function is called with fewer than the total number of parameters.

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/c27bb4e9-c711-4b45-b00a-b6bc0235773c)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/e1eabfb8-7a59-47db-a88e-410610ab2145)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/fd350de5-4a3b-4374-893d-24af94cea0f2)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/1fa547ba-8f81-4b3f-b131-75c0a4218043)










