# HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER 
HTML: content layer
CSS: presentaion layer
javascript(): behavior layer

### JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day. 

Here is a small simple script :
var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3> '); 

### LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE :
When you want to use JavaScript with a web page, you use the HTML
(<script>) element to tell the browser it is coming across a script.
Its s re attribute tells people where the JavaScript file is stored. 


### PLACING THE SCRIPT
IN THE PAGE
You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files). 

### How to use object & methods:
here is an example :
(document.write('Good afternoon!');)
the document object represents the entire web page . all web browsers implement this object, and you can use it just by giving its name.

the (.) member operator 
('Good afternoon!') is the parameter

## If you view the source code of the page in the browser, the JavaScript will not have changed the HTML,because the script works with the model of the web page that the browser has created.


## Basic javascript instruction:
- A script is made up of a series of statements. Each
statement is like a step in a recipe.
 - Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.

 - You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.
/* Th i s script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuer y book */


- Variables are used to temporarily store pieces of information used in the script.

#### You can declare a variable using the variable keyword + the variable:
and you must follow some rules when you choose the variable name , which are:
1. The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number
2. The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name. 
 
 3. ou cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.
ONLINE EXTRA
View a full list of keywords and
reserved words in JavaScript.

4. All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.

5. Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age
 6. If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash)






