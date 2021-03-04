# welcome to read 4 ^.^
JAVASCRIPT
IN THE BROWSER
Each version of a web browser adds new features.
Often these new features make tasks easier, or are
considered better, than using older techniques.
Online, you will find alternatives available for
each example that does not work in IE8.
But please check the comments in those code
samples to make sure you know about the about
issues involved in using them.
# the basics:
1. What is a script and how do Icreate one?
2.  How do computers fit in with the world around them?
3.  How do I write a script for aweb page?
**INSTRUCTIONS:**
A script is a series of instructions that a
computer can follow to achieve a goal.
# WRITING A SCRIPT:
To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
Start with the big picture of whatyou want to achieve, and breakthat down into smaller steps.
1: DEFINE THE GOAL
2: DESIGN THE SCRIPT
3: CODE EACH STEP
# EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.
1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
In order for a variable to be useful, it needs to be
given a value. As you have seen, this is done using
the assignment operator (the equals sign).
var color = 'beige';
3. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
individual values (see next page) to determine a
single value. For example:
var area = 3 * 2;
# OPERATORS
1. ASSIGNMENT OPERATORS
color = 'beige';
The value of co 1 or is now beige
2. ARITHMETIC OPERATORS
 Perform basic math
area = 3 * 2;
The value of area is now 6
3. STRING OPERATORS
Combine two strings
greeting= 'Hi 1 + 'Mol ly';
The value of greeting is now Hi Molly.
4.  COMPARISON OPERATORS
 Compare two values and return true or fa1se
buy = 3 > 5;
The value of buy is fa1se.
5. LOGICAL OPERATORS
Combine expressions and return true or fa1se
buy= (5 > 3) && (2 < 4);
The value of buy is now true.
# WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
**heres a example of HTML coding**
<!DOCTYPE html>
<html>
<head>
Before the closing </body>
tag, you can see the link to the
JavaScript file. The JavaScript
file starts with a variable used
to hold a new message, and is
followed by a function called
updateMessage().
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="css/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></script>
</ body>
</ html>
**heres a example ofJAVASCRIPT coding**
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};


End of read 4 