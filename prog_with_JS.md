# Programming with JavaScript
![prog](https://cdn01.alison-static.net/courses/887/alison_courseware_intro_887.jpg)

Earlier on, we briefly introduced some JavaScribt basics [6](https://danaabbadi.github.io/learning_journal/Javascript) 
,in this page we will be exploring deeper into how to write a *script* with JavaScript.

A script is a series of instructions that a computer can follow to achieve a goal.Therefor to write a script, you need to first state your goal and then list the
tasks that need to be completed in order to achieve it. A helpful way to achieve thet is by going through three stages, they are:
 
 1. Define the goal. 
 2. Design your script; by drawing flowcharts and then derive steps out of it.
 3. Code each step.  
## Experissions
An expression evaluates a set of values into a single value.
Expressions rely on things called *operators* ; they allow programmers to create a single value from one or more values. 

 | Operator | Explaination | Example|
|----: |---:| ----:|
| ASSIGNMENT OPERATORS |  Assign a value to a variable  |  color = 'beige';   |
|  ARITHMETIC OPERATORS  |  Perform basic math  |  area = 3 * 2;   |
| STRING OPERATORS   |  Combine two strings  |  greeting= 'Hi 1 + 'Mol ly';   |

* Remark: for string operator only '+' is used, by joining two strings into one, this process is called *concatenation*.

## Functions

A function is a group of statements that together perform a specific task. If different parts of a script repeat the same task, you can
reuse the function. To use the function in your code, you need to "call" it.
Advantages of using functions:
   - Code Re-usability
   - Develop an application in module format.
   - Easily to debug the program.
   - Code optimization: No need to write lot of code.
* A JavaScript function is declared by with the function keyword, followed by a name, followed by parentheses ().
  The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)
  The code to be executed, by the function, is placed inside curly brackets: {}.

![fun](https://www.code-morning.com/wp-content/uploads/2016/09/Function1-300x154.png)

When JavaScript reaches a return statement, the function will stop executing.