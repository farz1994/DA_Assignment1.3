>What are the different methods to call a function in R? 
First, you use () as usual, to denote a call to a function, immediately after the keyword function : this can specify the argument, in the example x ;

Secondly, a () couple encircles the function(x) declaration and body;

call(name, …)

is.call(x)

as.call(x)

call returns an unevaluated function call, that is, an unevaluated expression which consists of the named function applied to the given arguments (name must be a quoted string which gives the name of a function to be called).

Note that although the call is unevaluated, the arguments … are evaluated.

call is a primitive, so the first argument is taken as name and the remaining arguments as arguments for the constructed call: if the first argument is named the name must partially match name.

>The lazy evaluation of a function means, the argument is evaluated only if it is used inside the body of the function. Say True or False. 
True

>State True or False:
a. Insights driven from descriptive analytics is not meaningful. (False)
b. The number of values in each Elements of a list, should be equal. (False)
c. The datasets are not stored in memory of the computer using R. (False)
d. Data frames and matrices are two dimensional however the array is multidimensional. (True)
