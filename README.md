# 10 rules for mission critical Ruby code

> Nasa's 10 rules for mission critical programming rewritten for ruby

Some similar resources:

* https://www.cheatography.com/davidpol/cheat-sheets/applying-nasa-coding-standards-to-javascript/

# The rules

## 1. No function should be longer than what can be printed on a single sheet of paper in a standard reference format with one line per statement and one line per declar­ati­on. Typically, this means no more than about 60 lines of code per function.

## 2. Restrict all code to very simple control flow constructs – do not use goto statements, setjmp or longjmp constructs, and direct or indirect recursion

## 3. Do not use dynamic memory allocation after initialization

## 4. All loops must have a fixed upper-bound

## 5. The assertion density of the code should average to a minimum of two assertions per function

## 6. Data objects must be declared at the smallest possible level of scope

## 7. The return value of non-void functions must be checked by each calling function, and the validity of parameters must be checked inside each function

## 8. The use of the pre-processor must be limited to the inclusion of header files and simple macro definitions

## 9. The use of pointers should be restricted. Specifically, no more than one level of dereferencing is allowed

## 10. All code must be compiled, from the first day of development, with all compiler warnings enabled at the compiler’s most pedantic setting
