# 
## About HTML:
* heading:Browsers display the contents of
headings at different sizes. The
contents of an ```<h1>``` element is
the largest, and the contents of
an ```<h6>``` element is the smallest.
* paragraph:
To create a paragraph, surround
the words that make up the
paragraph with an opening ``` <p>```
tag and closing ```</p> ```tag .
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.
* Bold & Italic:
- Bold by 
```<b></b>```.
- italic by ``` <i></i>```.
- "```<br /> and <hr /> ```"for vertical and horizantal lines.
### HTML elements are used to describe 
the structure of
the page (e.g. headings, subheadings, paragraphs).
They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).
# CSS works by :
associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
* it could be inline outline and external:
```
<!DOCTYPE html>
<html>
<head>
<title>Using Internal CSS</title>
<style type="text/css">
body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}
</style>
</head>
<body>
<h1>Potatoes</h1>
<p>There are dozens of different potato
varieties. They are usually described as
early, second early and maincrop.</p>
</body>
</html>
```
- the best one is in an external sheet because it makes every thing easier to handle.
# CSS treats 
each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
- Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
- Different types of selectors allow you to target your
rules at different elements.
- Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document,
although they may appear within an HTML page.
## colors on css:
Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
# About javascript:
- its the thing that create the interaction between the site components;
** A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.
- A script is made up of a series of statements. Each
statement is like a step in a recipe.
Scripts contain very precise instructions. For example,
- you might specify that a value must be remembered
before creating a calculation using that value.
Variables are used to temporarily store pieces of
information used in the script.
- Arrays are special types of variables that store more
than one piece of related information.
- JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
Expressions evaluate into a single value.
- Expressions rely on operators to calculate a value.
- A script is made up of a series of statements. Each
statement is like a step in a recipe.
- Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.
- Variables are used to temporarily store pieces of
information used in the script.
Arrays are special types of variables that store more
than one piece of related information.
JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
- Expressions evaluate into a single value.
Expressions rely on operators to calculate a value.
. .
## Loops and operators:
- Conditional statements allow your code to make
decisions about what to do next.
- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
- Logical operators allow you to combine more than one
set of comparison operators.
if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.
- switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
- Data types can be coerced from one type to another.
- All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and
- do ... while. Each repeats a set of statements
