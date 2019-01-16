## Task

* Google 'hello world' in C
* Run GCC - this is the compiler
* Write 'hello world' in C, python and node.js 
* Understanding the basics of these langs will inform a basis of javascript

#####Resources
rosettacode.org
docs.python.org
stackoverflow.com

## Program and Command Invocation

Generally, command implies a command line program that can be executed from a shell. Program implies a more fully fledged or a higher level piece of software e.g. inkscape, gimp etc. 

Programs can be invoked in different ways:

### UI examples

* Double clicking on a desktop shortcut
* Using applications menu of desktop environment e.g. Gnome, Windows, etc.
* Programs can invoke other programs e.g. When opening a live server in VS, it invokes an http server

### Command line examples 

#### `ls`, `lsblk`, `python`
Three examples of command line invocation (execution, running) of these command line programs (sometimes called utilities), with zero arguments.

#### `ls -a`, `python hello.py`
Two examples of single argument command line invocation, of `ls` and `python` respectively.\
`ls` is passed the string `-a`.\
`python` is passed the string `hello.py`

#### `git config --global user.email`, `gcc -o hello hello.c`
`git` is passed the three string arguments `config`, `--global` and `user.email`.\
`gcc` is passed the three string arguments `-o`, `hello` and `hello.c`.\
It is the shell's job to invoke the given program, for example `gcc` or `git`, and to pass the program its string arguments.\
It is the program's job to make sense of the string arguments. For example, in the case of `gcc -o hello hello.c`, the string `hello` is actually a parameter that is being passed to the `-o` argument.

#### `python -c'print("HI")'`

#### `python -c 'print("HI")'` 
#### `history | less` 
#### `LANGUAGE="" chromium-browser`
#### `head -n 5 $(which chromium-browser)`
