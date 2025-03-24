<a id="top"></a>

- [PCEP Introduction](#pcep-introduction)
- [Introduction to Python](#introduction-to-python)
- [Keywords](#keywords)
- [Variables](#variables)
  * [Summary](#summary)
  * [Literals](#literals)
    + [Number](#number)
      - [Integer](#integer)
      - [Float](#float)
      - [Complex](#complex)
      - [Scientific](#scientific)
    + [Strings](#strings)
    + [Boolean](#boolean)
    + [None](#none)
    + [Collections](#collections)
- [Print(ing)](#print-ing-)
  * [Formatting](#formatting)
- [Immutability](#immutability)
- [Arithmetric Operations](#arithmetric-operations)
- [Assignment Operators](#assignment-operators)
- [Bitwise Operators](#bitwise-operators)
- [Boolean Operators](#boolean-operators)
- [Comparison Operators](#comparison-operators)
- [Input](#input)
  * [Type Conversion](#type-conversion)
- [String Access](#string-access)
  * [Slicing](#slicing)
  * [Addition](#addition)
  * [Multiplication](#multiplication)
- [Operator Precedence](#operator-precedence)
- [Flow Control / Loops](#flow-control---loops)
  * [IF](#if)
  * [FOR](#for)
  * [WHILE](#while)
  * [Break](#break)
  * [Continue](#continue)
  * [Pass](#pass)
- [Range Command](#range-command)
- [Lists](#lists)
  * [Create](#create)
  * [Access](#access)
  * [Slicing](#slicing-1)
  * [Traversing](#traversing)
  * [Comprehension](#comprehension)
  * [Math Operations](#math-operations)
  * [Comparing](#comparing)
  * [Membership Operators](#membership-operators)
  * [Functions](#functions)
    + [Append](#append)
    + [Extend](#extend)
    + [Insert](#insert)
    + [Deletion](#deletion)
      - [Del](#del)
      - [Remove](#remove)
      - [Pop](#pop)
      - [Clear](#clear)
    + [Length](#length)
    + [Count](#count)
    + [Index](#index)
    + [Sort](#sort)
    + [Reverse](#reverse)
- [Tuples](#tuples)
  * [Create](#create-1)
  * [Access](#access-1)
  * [Slicing](#slicing-2)
  * [Conversion](#conversion)
  * [Immutability](#immutability-1)
  * [Packing/Unpacking](#packing-unpacking)
- [Dictionary](#dictionary)
  * [Creating](#creating)
  * [Accessing](#accessing)
  * [Updating](#updating)
  * [Insertion](#insertion)
  * [Deletion](#deletion-1)
    + [Pop](#pop-1)
    + [Pop Item](#pop-item)
    + [Del](#del-1)
    + [Clear](#clear-1)
  * [Membership Operators](#membership-operators-1)
  * [Functions](#functions-1)
    + [Length](#length-1)
    + [Get](#get)
    + [Keys](#keys)
    + [Values](#values)
    + [Items](#items)
- [Sets](#sets)
  * [Create](#create-2)
  * [Access](#access-2)
  * [Modifying](#modifying)
  * [Update](#update)
  * [Copy](#copy)
  * [Conversion](#conversion-1)
  * [Deletion](#deletion-2)
    + [Pop](#pop-2)
    + [Remove](#remove-1)
    + [Discard](#discard)
    + [Clear](#clear-2)
  * [Math Operations](#math-operations-1)
    + [Union](#union)
    + [Intersection](#intersection)
    + [Difference](#difference)
    + [Symmetric Distance](#symmetric-distance)
  * [Membership Operators](#membership-operators-2)
- [Escape Characters](#escape-characters)
- [Strings](#strings-1)
  * [Functions](#functions-2)
    + [Length](#length-2)
    + [Index](#index-1)
    + [Count](#count-1)
    + [Lower](#lower)
    + [Upper](#upper)
    + [Split](#split)
- [Functions](#functions-3)
  * [Arguments](#arguments)
    + [Positional](#positional)
    + [Keyword](#keyword)
    + [Default](#default)
    + [Variable Length](#variable-length)
  * [Recursion](#recursion)
  * [Return Statement](#return-statement)
  * [Iterators](#iterators)
  * [Global](#global)
- [Exceptions](#exceptions)
  * [Types](#types)
  * [Handling](#handling)

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

## Literals

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

# Print(ing)

Built-in functionality to write strings to the console.

## Formatting

# Immutability

Determines if an object type can be modified in-place. 

Immutible types

Mutible types
- Strings
- Numbers
- Lists
- Dictionary
- Sets

# Arithmetric Operations

* Addition
* Subtraction
* Multiplcation
* Division
* Modulo
* Floor
* Exponent

# Assignment Operators

Standalone or combined with arithmetric operators

# Bitwise Operators

# Boolean Operators

* And
* Or
* Not

# Comparison Operators

# Input

## Type Conversion

# String Access

## Slicing
## Addition
## Multiplication

# Operator Precedence

# Flow Control / Loops

## IF

## FOR

## WHILE

## Break

## Continue

## Pass

# Range Command


# Lists
([Back to Top](#top))

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

# Tuples

## Create

## Access

## Slicing

## Conversion

## Immutability

## Packing/Unpacking

# Dictionary

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

# Sets

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

# Escape Characters

# Strings

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

# Functions

## Arguments

### Positional

### Keyword

### Default

### Variable Length

## Recursion

## Return Statement

## Iterators

## Global

# Exceptions

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

