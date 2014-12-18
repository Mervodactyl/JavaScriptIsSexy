#DATATYPES & VARIABLES

JS is a weakly typed language and is more fogiving of how one can use different types of data (numbers, text, etc). JS is very good at figuring out what kind of data it is dealing with, but will still need the user to be explicit at times.

Nnmbers:
  * Whole = 123, 9, -9686, -12
  * Floating = 2.3683, 1.233, 9.8562

String:
  * Text
  * individual characters can be repreented by their character number in Latin, eg ```\xA9``` produces the copyright symbol, or their unicode number: ```\u00A9```.


This is an expression: 13 + 4 + 7
which JS will calculate, and then store as a variable.
 exampleVariable + 1 / exampleVariable++
 exampleVariable - 1 / exampleVariable--

The operator precedence goes x | / above + | -. However, + | - have equal value, as does x | / so JS reads from left to right for precedence when solving an expression.
