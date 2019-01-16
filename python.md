`sys.argv` - Sys is a library in the python standard library. Argv stands for argument vector, it's a list. It's a list containing the arguments. The first argument sys.argv[0] is the name of the program. You have to use the name of the program to call it. 
`import sys` - This brings the functions of the sys name space into the scope of the program so they can be called and referred to.

There's a difference between assigning some constant to a name:
`magda = "mrs bear"`

And assigning the result of a function to a name:
`bear = magda.upper()` (OOP approach, valid python, bad)

`bear = upper(magda)` (FP approach, invalid python, good)

(Here `bear` is now `"MRS BEAR"`, since the `upper()` function has been called).