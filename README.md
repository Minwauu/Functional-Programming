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


## Haskell 

### List processing 

- As with all languages, Haskell comes with a range of standard library functions, some of which we will introduce below.

- The *head* funcion returns the first element in a list:

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/8155288d-f887-4c9f-a55f-23c33c940702)

- Conversely, *tail* returns all but the first element in a list:

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/43de337e-cbc3-4d47-8391-922584c18589)

Return an element from the list (starting from 0)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/3b6c6029-012d-48f8-ab3b-6e8e488b65bb)

Select the first number of elements from a list:

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/1afca90b-72f1-40b1-b2e1-454872761b78)

Remove the first number of elements from a list

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/3979805e-4224-4af3-aa25-ec9cc02fbd6f)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/f642c90a-553a-4928-aff4-2009597ba596) !

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/4a4868c4-a7d3-433c-85b6-c8ca4c23d9cd)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/f5bb20d1-a01c-4e6b-a48a-25f1e23efe5c)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/4e14b5f0-6cbb-48ce-9a8a-93ca16502ed5)

### Writing programs

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/2baa29e7-b9dd-43fc-adb8-bc548891f76d)

### Higher order functions

- Higher-order functions are functions that can take a function as an argument and/or return a function as a result. The higher order functions that we need to know about are:
  - map
  - filter
  - fold

### Map

- Map applies a function to each element of a list and returns the results in a list. It works by applying the function to the head of the list and makes recursive calls to each element in the tail.

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/5fab2441-e258-4ff4-9d34-f728021a7443)

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/deacc176-d31c-40f5-80f7-adebd6865cbc)

### Filter

- Filter applies a function to a list to select items from a list:

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/15ba6972-85a2-4cf5-abc1-d43c62b9a0a2)

### Fold

![image](https://github.com/Minwauu/Functional-Programming/assets/110039102/41e26c1e-6abd-4214-9756-dee5915aaec5)






















