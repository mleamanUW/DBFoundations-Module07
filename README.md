# DBFoundations-Module07

Matthew Leaman
February 28, 2024
IT FDN 130A
Winter 2024
Assignment 07
https://github.com/mleamanUW/DBFoundations-Module07

Assignment 07 Writeup

Introduction
There are many ways to build more robust and useful reports. User Defined Functions can be used to save specific functions and queries to the database to be called upon in the future, instead of having to rewrite the code each time someone wants to create a similar report.

SQL User Defined Functions Use
User Defined Functions (UDFs) are custom functions that can be used to either return a table of values or return a single value. They are helpful, because code can be written once and then reused based on a given parameter as defined by the person who creates the function. 

Scalar, Inline, and Multi-Statement Functions

Scalar functions return a single value based on an expression. These functions can be used for a simple calculation, and then can be used within other statements to return a value in a new column for each record returned. An example would be to create a scalar function that multiples two values, then using that within a new statement that would multiple the number of units sold by the unit price to calculate an extended price. This 

Inline and multi-statement functions are both types of Table Valued Functions and can call upon scalar functions. An inline statement contains only a single statement, which must be a Select Statement. will return a table as a result and can then be used in a query like any other table. A multi-statement function is like a multi-statement function, but the results can be joined with data from other tables to create a more robust report.

Summary
 
User Defined Functions are used to create more robust and useful reports, which are saved within a database to be called upon again. Instead of rewriting complex code continually, functions can be used to create reports which involve calculations, and can be combined with data from one or more tables.
![image](https://github.com/mleamanUW/DBFoundations-Module07/assets/160677974/bd75edd8-fbf6-4483-9fb5-0d33090d303e)
