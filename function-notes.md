# Java Script Reading 7
+ JS allows you to
    1. *Access* the content of the page
    1. *Modify* that content
    1. *Program* rules or instructions the browser can follow
    1. *React* to events triggered by the user or browser

+ With JS, we're writing a script. A script is a series of instructions that the computer can follow in order to achieve a goal
+ To write a script:
    1. Define the goal
    1. Design the script
    1. Code each step

+ Expressions
    + There are two types of expressions:
        1. Expressions that assign a single value to a variable
            + ex. var color = 'beige';
            + The value here would be beige
        1. Expressions that use two or more values to return a single value
            + ex. var area = 3 * 2;
            + The value here would be 6

+ Operators
    + Expressions rely on operators. Operators allow programmers to create a single value from one or more values. Here are some different operators:
        + Assignment operators
        + Arithmetic operators
        + String operators
        + Comparison operators
        + Logical operators

+ Functions
    + Functions let you group a series of statements together to perform a specific task
    + Great for re-using code!!
    + Function name should be an intuitive name so you can look back on it months later to immediately recognize what that function is meant to do
    + How to write a function:
        - function ryansFaveColor(){
            console.log('Ryan's favorite color is: turquoise');
        }
        - And then to run that function, you would write: ryansFaveColor();
            - And then it would return 'Ryan's favorite color is: turquoise'
        - another function example:
            - function personsFaveColor( name, color){
                console.log(name + '\'s fave color is: ' + color);
            }
            - So if you entered 'personsFaveColor( 'Ryan', 'Turquoise');
                - you will get 'Ryan's fave color is: Turquoise'
1. Receive input -> Process -> Return output