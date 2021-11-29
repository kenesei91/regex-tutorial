# Regex Tutorial

Regex by definition stands for regular expression. According to the bootcamp module, it is a sequence of characters that defines a specific search pattern. This tutorial is going to explain how regex functions, by breaking down each component and describing what it does. This tutorial will also provide clarity and understaning of the code written to other developers and non-developers.

## Summary

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

The above code or group of characters is an example of a regex that validates that a user input is a valid email address. A breakdown of each individual code is explained detailing their functions and what they do.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors serve to match a position between characters.

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

The dollar sign `$` matches the last character in the string. For example, in `abc`, c$ matches c in abc, while, a$ don't match.
The caret sign `^` which is the opposite fo the dollar sign, matches the position before the first character of any string. For example, in `abc`, ^a matches a in abc, while, ^c don't match.

### Quantifiers

Quantifiers indicate the number of characters to match

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

The plus `+` repeats the previous item once or more, also known as greedy. 
The `{2,6}` repeats the previous items between 2 and 6 times.

### OR Operator
Unfortunately, there are no `|` operators in my example. However, the OR Operator `|` is used the match characters or expressions either on the left or right side of the `|` operator.

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
