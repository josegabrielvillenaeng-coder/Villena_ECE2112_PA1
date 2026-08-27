## **VILLENA_PA2 2ECE-B ECE 2112**

## Intended Learning Outcomes

At the end of this laboratory activity, the student should be able to:
1. use basic Python functions, operators, and string operations;
2. manipulate strings using indexing, slicing, and built-in string methods;
3. apply sequence unpacking to manipulate the elements of a list; and
4. construct simple Python functions that return a specified result.

## Instructions

Write a Python program in a Jupyter Notebook to solve each of the following problems.

• Use the exact function names specified in each problem.

• Place each problem in a separate, clearly labeled section of the notebook.

• Each function must return the required result unless printed output is explicitly requested.

• Do not use external Python libraries.

• Use only basic Python operations, string methods, slicing, and sequence unpacking. Loops and
classes are not required.

• Test each function using the examples provided. Additional valid inputs may be used when grading
the notebook.

## A. WORD ROTATION PROBLEM 

The task in this problem is to be able to move the first character of a word to the very end, while keeping all the other characters in the same order.

The following functions and methods were used in this problem:

• **def**  - This is used to create a function

• **text[0]** - To get the first character of the word

• **text[1;]** - Gets the rest of the letters of the word after the first character

• **+** - To join the two parts of the code used

• **return** - To command give result of the function made




**Explanation of method used:**

String slicing is used to separate the first character from the remaining characters. The remaining characters are then concatenated with the first character at the end.

## B. USERNAME BUILDER PROBLEM

The task is to take a first name and last name and turn them into a username.

The following functions and methods were used in this problem:

• **def**  - This is used to create a function

• **first_name, last_name** - variable used for the two names given to the function

• **.lower()** - To convert the letters of the name to lowercase

• **.replace(" ","")** - to removes spaces from the names

• **"."**  - Add the required period between names

• **+** - To join the two types of names

• **return** - to return the completed username 



 

**Explanation of method used:**

The **".lower()"** method converts the names to lowercase, while **".replace()"** removes spaces. The processed names are then concatenated with a period between them.

## C. BOOKEND SWAP PROBLEM

The task is to swap the first and last elements of a list, while leaving everything in the middle exactly where it was.

The following functions and methods were used in this problem:

• **def**  - This is used to create a function

• **items** - The list given to the function

• **first** - Stores the first element

• ***middle** - Stores all elements between first and last. Also used to put the middle elements back individually

• **last** - Stores the last element

• **[ ]** - Creates a new list

• **last** - Stores the last element

• **return** - Returns the new list


 

**Explanation of method used:**

Extended sequence unpacking separates the list into the first element, middle elements, and last element. A new list is then constructed with the first and last elements exchanged while preserving the middle elements.


 

Thank you for Reading!

 
