How to Write a Git Commit Message
ontributors to these repositories know that a well-crafted Git commit message is the best way to communicate context about a change to fellow developers (and indeed to their future selves). A diff will tell you what changed, but only the commit message can properly tell you why.

If you haven’t given much thought to what makes a great Git commit message, it may be the case that you haven’t spent much time using git log and related tools. There is a vicious cycle here: because the commit history is unstructured and inconsistent, one doesn’t spend much time using or taking care of it. And because it doesn’t get used or taken care of, it remains unstructured and inconsistent.

But a well-cared for log is a beautiful and useful thing. git blame, revert, rebase, log, shortlog and other subcommands come to life. Reviewing others’ commits and pull requests becomes something worth doing, and suddenly can be done independently. Understanding why something happened months or years ago becomes not only possible but efficient.
The seven rules of a great Git commit message
Keep in mind: This has all been said before.
Separate subject from body with a blank line
Limit the subject line to 50 characters
Capitalize the subject line
Do not end the subject line with a period
Use the imperative mood in the subject line
Wrap the body at 72 characters
Use the body to explain what and why vs. how

type	use
< strong>	The use of the < strong> element indicates that its content has strong importance.
< em>	By default browsers will show the contents of an < em> element in italic
< blockqoute>	used for longer quotes that take up an entire paragraph
< q>	used for shorter quotes that sit within a paragraph.
< abbr>	to use an abbreviation or an acronym, like Prof ..
< cite >	When you are referencing a piece of work such as a book, film or research paper
< dfn>	The first time you explain some new terminology
< address>	to contain contact details for the author of the page , it may appear in Italic
< ins> & < del>	The < ins> element can be used to show content that has been inserted into a document, while the < del> element can show text that has been deleted from it.
< s>	The < s> element indicates something that is no longer accurate or relevant (but that should not be deleted).
Introducing CSS
what is CSS ?
CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

Data Type
type	exaple
string	anything goes between ' ' or " "
Numbers	1, -2 , 2.5
boolean	True or False
changing the value of a Var
Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script. Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign (also known as the assignment operator), and the new value for that attribute.

Rules of Naming Var
The name must begin with a letter, dollar sign ($),or an underscore (_)It must not start with a number.
can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name
use keywords or reserved words. Keywords are special words.
All variables are case sensitive
Use a name that describes the kind of information that the variable stores.
If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.

Javascript Loops
Loops are used to do some task or execute some statements or block of code number of times as specified

Javascript has 4 different types of loops

For Loop
While Loop
DoWhile Loop
For..in Loop
For Loop

For loop is used where when we know the number of time we want to execute the code.

Syntax
for (initialization; condition; increment) { code to be executed; }

Code Explanation

Initializing value is the starting value of the counter Condition is the conditional used to stop the loop execution Increment is the increment of the initializing value

Example of For Loop

var a = 0; var b = 0;

for( var i=0; i<5; i ) { a ; b ; } document.write (“At the end of the loop a=5 and b=5” );

While Loop

While loop is used where we want to execute the code as long as the condition is true.

Syntax
while (condition) { code to be executed; }

Code Explanation

Condition is the conditional used to stop the loop execution


