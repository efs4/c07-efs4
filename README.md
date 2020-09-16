# c07 Loops: "Determinate" ~ `for <iterator>` & "Indeterminate" or "Conditional" ~ `while <bool>`

# Review

_Lambert Ch 2 Software Development, Data Types, & Expressions_

0. Types
   1. simple: `bool`, `int`, `float`
   2. collection: `str` (`set`, `tuple`, `list`, `dict`)
   3. others: (`numpy Series`, `pandas DataFrame`, ... using OOP, programmers create classes, which are basically new types!!!:astonished:)

1. Built-in Functions
   1. `print()` (`f-strings`) : writes (returns) the input argument to the console by default
   2. `input()` : writes the input argument to the screen and returns the characters typed at the keyboard as a `str`
   3. `type()`  : returns the type of the input argument
   4. `int()`  : casts `str` to `int`
   5. `float()` : casts `str` to `float`
   
2. Assignment Statement
   1. `strName = 'Alika'`
   2. `strInput = input('What is your name? ')`

3. Operators
   1. `+`
      1.  concatenates `str : '1' + '2' = '12'`
      2. adds numerics:  `1 + 2 = 3 ; 1.0 + 2 = 3.0 ; 1 + 2.0 = 3.0 ; 1.0 + 2.0 = 3.0`
   2. `-` numeric
   3. `*`
      1. numeric
      2. `'Fa' + 4 * '-la' + ' La' + 3 * '-la'` :christmas_tree:
   4. `/` `float` division
   5. `//` `int` division quotient: `23 // 10 --> 2` ; `24 // 10 --> 2` ; `25 // 10 --> 2` ; `29 // 10 --> 2` ; `30 // 10 --> 3`
   6. `%`  `int` division remainder: `23 % 10 --> 3` ; `24 % 10 --> 4` ; `25 % 10 --> 5` ; `29 % 10 --> 9` ; `30 % 10 --> 0`

_Lambert Ch 3 Loops & Selection Statements_

4. Conditional Statement or Selection Statement: `if`
   a. `if <bool>:` Only run the if branch if `<bool>` is `True`
   b. `if <bool>: ... else:`  If `<bool>` is `True` run the if branch, otherwise run the `else` branch
   c. `if <bool0>: ... elif <bool1>:` If `<bool0>` is `True` run the if branch, else if `<bool1>` is `True` run the `elif` branch
   d. `if <bool0>: ... elif <bool1>: ... else:` combination of b & c

5. Conditional Loop: `while <bool>:`
   a. Input validation ~ do __*NOT*__ know how many attempts user will require before produce valid input
   b. Iterative calculations in math where successive steps produce more accurate estimates ~ pi & sqrt(2), etc

## In-class Exercise (ICE) 0. Write a `while` loop that produces the following output:
```
0
1
2
3
```
code for ICE0:
```python
# ICE0

```
   
## ICE 1. Write a `while` loop that produces the following output: 
```
 7
 8
 9
10
```
code for ICE1:
```python
# ICE1
 
```
   
## ICE 2. Write a `while` loop that produces the following output: 
```
10
20
30
40
```
code for ICE2:
```python
# ICE2
 
```
  
# Deterministic loops using `for`
In some sense, the `while <bool>:` loop can handle nearly every loop situation, but "determinate" and "indeterminate"!
However, if we have a determinate loop, it is much easier to use a `for` loop.

# `range([start=0], stop, [step=1])`
* `range(5)` ~ 0, 1, 2, 3, 4
* `range(5, 10) ~ 5, 6, 7, 8, 9
* `range(5, 10, 2) ~ 5, 7, 9


## In-class Exercise (ICE) 3. Write an `if` that produces the following output:
```
0
1
2
3
```
code for ICE3:
```python
# ICE3

```
   
## ICE 4. Write an `if` loop that produces the following output: 
```
 7
 8
 9
10
```
code for ICE4:
```python
# ICE4

```
   
## ICE 5. Write an `if` loop that produces the following output: 
```
10
20
30
40
```
code for ICE5:
```python
# ICE5
 
```
  
## ICE 6. Write an `if` loop that produces the following output:
```
A
l
o
h
a
```
code for ICE6:
```python
# ICE6

```

Link from about to this repo.
