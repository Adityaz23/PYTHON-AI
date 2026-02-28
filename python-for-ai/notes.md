# In Python the code run from top to bottom and from left to right. Pretty much same as reading the book.
### The problem with the python in the real world you work with so many projects side to side (we even work with lot of packages so these packages also have versions ) :-
## Project A : needs version 1.0 of the tool.
## Project B : needs version 2.0 of the tool.
>>
### If we install the version 2.0 congrats you just broke the version 1.0 project A
## This is where we need the virtual environemt helps us to get rid of these errors.
>>
### Q. What are virtual environments ?
### A virtual environment is like a private copy of python for each project. Think of them as the :-
1. A seprate folder for each project.
2. It's own Python installation.
3. It's own place to install packages.
4. Complete isolation from other projects.
>>
### Understand the Packages :-
### Packages are pre-written code that others have created for us to use in the code. Instead of writing everything from scratch we can use them by installing them in our project. We can import these packages. Ex:-
1. requests -> for downloading the web pages.
2. pandas -> for working with data.
3. openai -> for using AI models
>>
## To create the new environment there are two ways :-
 Method 1 :- VS Code command pallete (easier).
 >>
        1. Open your vs code project.
>>
        2. Press Cmd+Shift+P.
>>
        3. Type: "Python: Create Environment".
>> 
        4. Select "VENV".
>>
        5. Select your python installation.
>>
        6. VS code creates and activates everything for you.
>>
 Method 2 :- Terminal Commnad :-
>>
        1. Open the terminal in VS code.
>>
        2. Make sure you are in the right project
>>
        3. Run this command. (python3 -m venv .venv)
>>

### When we working on different projects we really need to isolate everything and this is the way of doing that.

### Q. What about anaconda ?
### Ans. It is another tool that manages the environment and packages. It is popular because it comes pre-loaded with the many data science packages.

#### When you are learning AI then go with the built-in environment.
>>

# Packages and Pip :-
### Standing on the shoulders of the giant 
One of python's superpower is its massive collection of packages.Instead of writing everything from scratch,you can use the code of the others which they have written, tested and shared.

### Q. What are packages?
### Ans. Packages are those which others have written and shared to the others so we do not need to write everything from the scratch.
* Each package is like a toolbox with specialized tools for a specific task.
>>

# Meet PIP :-
### PIP (Pip install packages) is python's package manager just like npx for js,react etc..
* Download packages from the internet.
* Install them in your environment.
* Manages versions and dependencies.

# Variables :-
* name = "Aditya" 
* age = 23

### Python naming convention :-
        We use lowercase letters with the underscore between wrods. This is called the "snake_case" and its the sandard way of writing the names to the variables in the python.
>>
# Data Types :-
        Q. What are data types ?
        Ans. You cannot add the name to the age they both are different data that is why you need the data types to define the value of the different data.
>>
#### Python has main 4 types of data types :-
* Numbers -> for counting and calculations.
* Text -> for the words and messages.
* True/False -> for decisions

### Numbers :-
Under the hood there are two types of numebrs Integers and Float
* Int -> age = 10 , score = 1 ,
 whole numbers without decimals.
* Float -> price = 12.32, temprature = -4.4, pi = 3.14,
 numbers with decimal points.
