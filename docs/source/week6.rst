Week 6: Basic Functions
=======================

Summary
-------

Functions allow you to chunk code into bigger pieces that make writing programs easier.
In this class, we go over how simple functions work.
Functions are first defined, and then in later code, they are called.
Defining a function is not the same thing as calling or executing the function.

Functions are named.  They use parenthesis at the end of their name to tell the
Python interpreter to execute the function.

We also cover the basics of arguments.  Arguments allow us to send information into the function.
We send the information by putting variables inside the parenthesis.
Multiple arguments are separated by commas.


Homework
--------

1. Write functions for the following turtle abilities:
  - spirals
    - We did these in class, this should give you a good starting point
  - polygons
    - the turning angle should always be 360 / num_sides
    - Sum of exterior angles always equals 360
  - jumping
    - set the turtle’s pen to up (so it doesn’t draw), then do setpos on an x and y coordinate, then put the pen back down
  - drawing each letter of your initials
    - you could do more letters if you want to spell your name
  - a function that uses the letter drawing and jumping to draw both initials or to write a word

Turtle Functions
^^^^^^^^^^^^^^^^

1. spiral
  - the first argument should be the turtle
  - the additional arguments should be the angle and the number loop iterations
2. polygon
  - the first argument should be the turtle
  - the additional arguments should be side length and number of sides
3. jump
  - the first argument should be the turtle
  - the additional arguments should be the new position (x and y)
  - the turtle should not draw while jumping

Reusing old code
^^^^^^^^^^^^^^^^

Turn your code from week 5 into functions
  - Each individual exercise should be a function
  - Doing this, you can change which code runs just by changing which function is called.

Bonus
^^^^^

1. draw_letter
  - the first argument should be the turtle
  - the additional argument could be size, or it could draw one size
  - you should have a different function for different letters
2. draw_word
  - use the draw_letter functions and the jump function to write a word
3. Complete the bonus exercise at the end of the slides.  There are two parts:
    1. Make the functions that it calls so that the code will run
    2. Change the control numbers into variables and turn it into a function



Extra Resources
---------------

Online Books
^^^^^^^^^^^^
1. `Think like a computer scientist. Chapter 4: Functions <http://openbookproject.net/thinkcs/python/english3e/functions.html>`_
2. `Think like a computer scientist: Interactive Edition. <http://interactivepython.org/courselib/static/thinkcspy/Functions/functions.html>`_


Lecture Slides
--------------

.. raw::html

   <iframe src="https://docs.google.com/presentation/d/1FOyskHWtg20Vm0dmNlUPGE8fiqqaH4bOVbLz1srGoGg/embed?start=false&loop=false&delayms=60000" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
