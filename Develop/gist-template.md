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
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
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
Cahracter Classes is also known as 'character set'. It matches only one of several characters in a group of characters.

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

For example, matching an a or e, use `[ae]`. You could use this in `gr[ae]y` to match either gray or grey.


### Grouping and Capturing
Groups allow a group of characters to be combined to be used as a single unit.

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Capturing groups aim to treat multiple characters as a single unit. This can be achieved by placing the characters to be grouped inside of a parentheses. For example, `([a-z0-9_\.-]+)` createsa single group containing the letters 'a', 'z', and symbols '-', '\' and so on.

### Greedy and Lazy Match
Quantifiers can be either greedy or lazy. A greedy quantifier tends to match as many characters as possible, while a lazy quantifier tends to match few characters as possible.

### Look-ahead and Look-behind
Unfortunately, my examples do not contain lookarounds. However, Lookahead and lookbehind, aslo known as 'lookaround', matches cahracters, but drops the match, and then returns only the result of a 'match or no match' status. 
## Author

Kenechukwu is an aspiring full stack web developer with seeking opportunities in field of technology with interest in wed design and creation. You can contact me at - [Github Repository](https://github.com/kenesei91/regex-tutorial)
