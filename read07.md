# Javascript and JQuery
### This page  summarize  how JavaScript can be used in browsers to make websites more interactive, nteresting, and user-friendly. You will also learn about jQuery because it makes writing JavaScript a lot easier. 

## Introduction:
#### What is script and how do i create one ?
* A script is a series of instructions that the computer
can follow in order to achieve a goal.
* Each time the script runs, it might only use a subset of
all the instructions.
* Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
* To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help).  

## EXPRESSIONS :
An expression evaluates into (results in) a single value. Broadly speaking
there are two types of expressions. 
1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE : In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using
the assignment operator (the equals sign).
var color = 'beige';
The value of co 1 or is now beige. 

2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE :You can perform operations on any number of individual values (see next page) to determine asingle value.
 For example: var area = 3 * 2; 
The value of area is now 6. 

## OPERATORS :
Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 

* ASSIGNMENT OPERATORS
Assign a value to a variable
color = 'beige';
The value of co 1 or is now beige.
(See p61)
* ARITHMETIC OPERATORS
Perform basic math
area = 3 * 2;
The value of area is now 6.
(See p76)
STRING OPERATORS
Combine two strings
greeting= 'Hi 1 + 'Mol ly';
The value of greeting is now Hi Molly. 
##### there a many other arithmetic operator:
1. addition (+),Adds one value to another
2. subtraction (-) Subtracts one value from another
3. divison (/),Divides two values 
4. multiplication (*),Multiplies two values using an asterisk
(Note that this is not the letter x) 
5. increment (++), Adds one to the current number 
6. decrement (--), Subtracts one from the current number 
7. modulus (%), Divides two values and returns the
remainder 

* COMPARISON OPERATORS
Compare two values and return true or fa 1 se
buy = 3 > 5;
The value of buy is fa 1 se.
(See p150)
LOGICAL OPERATORS
Combine expressions and return true or fa 1 se
buy= (5 > 3) && (2 < 4);
The value of buy is now true

* STRING OPERATOR
There is just one string operator: the+ symbol.
It is used to join the strings on either side of it. 
 For example:
 var firstName = 'Ivy ' ;
var lastName = ' Stone' ;
var ful l Name = f irstName + l astName ; 


## WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements).

#### For example:
this is the declaring of  a basic function :

## function sayHello() {document.write ('Hello!');}
 
 to call that function :

 you should write this line:
 ## sayHello();

 #### Declaring functions that need information :
 ## function getArea( width, height) 
 ## {return width * height;}

 #### Calling  functions that need information:
 *write this line whenn you want to call that*
 you should enter the a value fpr the argument to that function 
 and you have to ways for that 
 1. Argument vs Values : when the function below is called , the number 3 will be used for the width of the wall, and 5 will be used for its height 

   ## getArea(3,5);

2. Argument vs variables : You dont have to specify actual values when calling a function - you can use variables in their place . So the the followingdoes the same thing .
 
 ## wallWidth=3;
 ## wallHeight=5;
 ## getArea(wallWidth , wallHeight );

So Now we are good enough to go writting a function.
