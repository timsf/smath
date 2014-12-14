smath
==========

This is a collection of LaTeX macros that automates and centralizes most of the formatting in math mode. Instead, you declare a variable to belong to some class of mathematical objects (i.e. a vector) and the package defines the appropriate formatting for that class. The overall goal is to let you focus on the meaning of your writing, just as outside of math mode.

Place smath.sty in the same folder as your .tex file and add \usepackage[options]{smath} to your preamble. Smath requires the mathtools package to be installed. You can now use any macro defined in smath.sty. Consult the file for macro definitions. You can easily extend the package by adding your own macros to the file. Consult your favorite LaTeX documentation on how to define macros. 

The goal is to have a set of options to choose from to extend functionality. Currently, there is a stats option that mostly provides macros for density functions.