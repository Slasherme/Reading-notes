From the Duckett HTML book:

Chapter 3: “Lists” (pp.62-73)
Chapter 13: “Boxes” (pp.300-329)
From the Duckett JS book:

Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
# Lists:
* Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
* Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
* Definition lists are made up of a set of terms along with the
definitions for each of those terms.
LISTS
## we should know:
There are three t XX ypes of HTML lists: ordered,
unordered, and definition.
XX Ordered lists use numbers.
XX Unordered lists use bullets.
XX Definition lists are used to define terminology.
XX Lists can be nested inside one another.

# Boxes:
- we can add a box by
* in html:
```
<p class="one">Wurlitzer Electric Piano</p>
<p class="two">Wurlitzer Electric Piano</p>
<p class="three">Wurlitzer Electric Piano</p>
<p class="four">Wurlitzer Electric Piano</p>
<p class="five">Wurlitzer Electric Piano</p>
<p class="six">Wurlitzer Electric Piano</p>
<p class="seven">Wurlitzer Electric Piano</p>
<p class="eight">Wurlitzer Electric Piano</p>
```
* in css:
```
p.one {border-style: solid;}
p.two {border-style: dotted;}
p.three {border-style: dashed;}
p.four {border-style: double;}
p.five {border-style: groove;}
p.six {border-style: ridge;}
p.seven {border-style: inset;}
p.eight {border-style: outset;}
```
* we should know:
- CSS treats each HTML e XX lement as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding
for each box with CSS.
- It is possible to hide elements using the display and
visibility properties.
- Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of
boxes containing text and the leading.
- CSS3 has introduced the ability to create image
borders and rounded borders.
# Loops:
* We should know :
1 . Conditional statements allow your code to make
decisions about what to do next.
2. Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
3 . Logical operators allow you to combine more than one
set of comparison operators.
4 . if ... else statements allow you to run one set of code
5 . if a condition is true, and another if it is false.
6 . switch statements allow you to compare a value
1 . against possible outcomes (and also provides a default
option if none match).
1 . Data types can be coerced from one type to another.
1 . All values evaluate to either truthy or falsy.
1 . There are three types of loop: for, while, and
1 . do ... while. Each repeats a set of statements.