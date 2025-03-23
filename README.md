<a id="top"></a>

# Table of contents
- [PCEP-03-02](#PCEP Intro)
- [Python Intro](#Python Intro)
- [Variables](#Variables)
  - [Literals](#Literals)

# PCEP Introduction

# Introduction to Python

* Open Source
* Easy to Code
* High Levek programming language
* Portable and Interpreative
* Dynamically Typed

# Keywords

There is a large list of reserved keywords that cannot be used for variables or functions

A few examples

- while, for, break, continue
- if, elif, else
- True, False, None

A full list of reserved keywords can be found [here](https://docs.python.org/3/reference/lexical_analysis.html#keywords)

# Variables

* Cannot start with numbers
* Must start with a letter from the alphabet or an underscore
* Case sensitive
* No special characters
* No reservers words
* No length limit

## Summary

* Stores data values
* No type required
* Requires an initial value even if empty
* Can assign a value to multiple variables
* Used `del` to delete a variable

```
	a = 100
	b = "Hello"
	c = d = 200

	a,b = 100,"Hello"

	del a
```

## Literals [Top](#top)

```
     a = 3
         ^------> Literal
```

* Number
* Strings
* Boolean
* Collections

### Number

* Integer
* Float
* Complex
* Scientific

#### Integer

- No limit in length
- Type is `<class 'int'>`
- Can be negative

```
	a = 1
	a = -1
```

#### Float

- Numbers with deceimals
- Type is `<class `float`>`

```
	a = 0.2    => 0.2
	a = 3.     => 3.0
```

#### Complex

- x + yj
- Type is `<class 'complex'>`

```
   a = 10 + 11j
```

#### Scientific

- Exponent notation

```
   a = 2e7    => 20000000.0
   a = 2e-7   => 0.00000002
   a = .2e-3  => 0.0002
```

### Strings

- Surrounded by single or double quotes

```
   a = "test"
   a = 'test'
   a = "One"\
       "Two"
   """
   One
   Two
   """
```

### Boolean

- True or False values

```
	a = True
	b = False
```

### None

- No value for a variable
- Keyword
- Variables assigned with `None` still exist in memory and can be deleted

```
	a = None
```

### Collections

* [List](#lists)
* [Dictionary](#dictionary)
* [Tuples](#tuples)
* [Set](#sets)

# Print(ing) [Top](#top)

Built-in functionality to write strings to the console.

## Formatting

# Immutability [Top](#top)

Determines if an object type can be modified in-place. 

Immutible types

Mutible types
- Strings
- Numbers
- Lists
- Dictionary
- Sets

# Arithmetric Operations [Top](#top)

* Addition
* Subtraction
* Multiplcation
* Division
* Modulo
* Floor
* Exponent

# Assignment Operators [Top](#top)

Standalone or combined with arithmetric operators

# Bitwise Operators [Top](#top)

# Boolean Operators [Top](#top)

* And
* Or
* Not

# Comparison Operators [Top](#top)

# Input [Top](#top)

## Type Conversion

# String Access [Top](#top)

## Slicing
## Addition
## Multiplication

# Operator Precedence [Top](#top)

# Flow Control / Loops [Top](#top)

## IF

## FOR

## WHILE

## Break

## Continue

## Pass

# Range Command [Top](#top)

[Back to Top](#top)
# Lists

* Creating
* Accessing
* Slicing
* Appending
* Extending
* Insertion
* Deletion

## Create

## Access

## Slicing

## Traversing

## Comprehension

## Math Operations

## Comparing

## Membership Operators

## Functions

### Append

### Extend

### Insert

### Deletion

* Del
* Remove
* Pop
* Clear

#### Del

#### Remove

#### Pop

#### Clear

### Length

### Count

### Index

### Sort

### Reverse

# Tuples [Top](#top)

## Create

## Access

## Slicing

## Conversion

## Immutability

## Packing/Unpacking

# Dictionary [Top](#top)

## Creating

## Accessing

## Updating

## Insertion

## Deletion

### Pop

### Pop Item

### Del

### Clear

## Membership Operators

## Functions

### Length

### Get

### Keys

### Values

### Items

# Sets [Top](#top)

## Create

## Access

## Modifying

## Update

Include with range

## Copy

## Conversion

## Deletion

* Pop
* Remove
* Discard
* Clear

### Pop

### Remove

### Discard

### Clear

## Math Operations

* Union
* Intersection
* Difference
* Symmetric Distance

### Union

### Intersection

### Difference

### Symmetric Distance

## Membership Operators

# Escape Characters [Top](#top)

# Strings [Top](#top)

## Functions

* Length
* Index
* Count
* Lower
* Upper
* Split

### Length

### Index

### Count

### Lower

### Upper

### Split

# Functions [Top](#top)

## Arguments

### Positional

### Keyword

### Default

### Variable Length

## Recursion

## Return Statement

## Iterators

## Global

# Exceptions [Top](#top)

## Types

* BaseException
* Exception
* SystemExit
* KeyboardInterrupt
* abstract exceptions
* ArithmeticError
* LookupError
* IndexError
* KeyError
* TypeError
* ValueError

## Handling

* Try/Except
* Branch Ordering

