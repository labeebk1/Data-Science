# Phase 1 - Week 1 - Day 1

## Outline

* What is a computer
  * A computer at its most fundamental just contains **memory** (harddrive, ram, cache) and **logic unit** (CPU, GPU) that manipulates the memory
    * The memory is just numbers (really just 1s and 0s) and the logic unit just adds and subtracts these numbers
    * Doing over 100,000 of these computations each second results in the sophisticated programs you see on your computer

* What is a programming language
  * A human-friendly way to instruct the computer how to use its **logic unit** to manipulate its **memory**
  * A programming language simply provides us with a human-friendly abstraction of computer memory and how to manipulate it
  * The programming language we will use is Python
  
* Why Python
  * Easy to learn
  * One of the most popular overall
  * Most popular for data science
  * Extensive library - don't need to reinvent the wheel everytime

* What is Python
  * Specification (docs.python.org) vs Implementation (github.com/python)
  * Rules of the language specified abstractly. Can be implemented in any language
  * Most popular implementation is in C (due to performance benefits of C)

* How to develop in Python
  * Set up programming environment (BASH)
    * ls/cd
    * jupyter notebook
    * mkdir/rmdir
  * Set up Git 
    * init
    * add/commit
    * push/pull
    
 * Python memory abstraction model (formally defined as **data types**)
   * Atomic data types
     * Numbers (int, float)
     * Booleans (bool)
       * short-circuiting
       * 
     * Strings (str)
       * len
       * indexing
       * slicing
       * adding
       * f-strings
   * Compound data types
     * Lists (list)/ Tuples (tuple)
       * len
       * indexing
       * slicing
       * appending/adding (only to list)
     * Dictionary (dict)
       * len
       * selecting
   * Python memory model
```Python
x = 1234; id(x)
y = 1234; id(y)

lst1 = [x, y]
id(lst1)
id(lst1[0])
```
 * Python logic unit abstraction model (formally defined as **functions**)
   * Formally define: keywords, function name/parameters/arguments/body
   * Scope (LEGB)
   * Conditionals
     * several if vs if/elif/else
   * Iteration
     * while vs for
     * for i in range() vs for i in X
   * Leaky scope
   * Functions are first class citizens
```Python
def adder(n):
 def add_n(x):
  return n+x
 return add_n
add5 = adder(5)
add10 = adder(10)
print(add5(3)); print(add5(10))
print(add10(3)); print(add10(3))
```
 
## Current
* Setting up environment
  * Bash
  * Github
  * Hackerrank
  * Python
  
 * Python
   * Basic types
   * Functions & loops
   * Basic type methods 
   
## Additions
* Theory of bash and github (Apart of setting up environment)
  * git add/commit/push/pull/checkout/branch
  * ls/cd/pwd/echo/vim or emacs/rm and rmdir
  
* What is CS? (After setting up environment, before python)
  * Compilers/Distributed computing/concurrency/AI
  * A computer stores memory and does logic, so does a programming language
* What is Python? (After setting up environment, before python)
  * Specificaiton vs implementation
* Python memory storage - basic types (After setting up environment, apart of python)
* Python logic - functions (After setting up environment, apart of python)

  
 
