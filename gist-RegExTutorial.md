# Reg Ex Tutorial

Reg Ex stands for regular expression.  Regular expression is a way to search through a string of text.  We can use this functionality to do things such as validation and replace text, among many other things.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.  In general; it allows us to search through text in an advanced way. Here is an example of regular expression below.

```
/ MellowMoo /g
```

We first start of the reg ex with a forward slash ( / ).  We also close it with one.  Inside the forward slashes is the string that we are searching for.  Outside of the closing forward slash is a single letter.  This is an expression tag.  There are many ways to write reg ex for different use cases.  Below is a table of contents with explainations of different parts of reg ex.  I hope you find this useful.



## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

Anchors are used to match strings that either start with, begin with, or end with the characters defined by the reg ex.

Below are examples

* `$` - will find a string that ends with the word before this character
```
Name$       This will find any string ending with `Name`
```

* `^` - will find any string that starts with the word after this character
```
^Name       This will find any string starting with `Name`
```

Anchors can also be used in combination for different outcomes.
```
^Name$      This will find the exact string

Name        This will find any string that has `Name` in it
```

### Quantifiers
Quantifiers allow us to specify how many instances must be represented in the input to be matched.

Below are examples of quantifiers.

* `*` - matches a string that is followed by zero or more of its last character
* `+` - matches a string that is followed by one or more its last character
* `?` - matches a string that is follwoed by zero or one of its last character
* `{}` -  matches a string that is followed by the amount of the number in the brackets of the last character in the string
* `()*` - matches a string that is followed by zero or more copies of the string within the brackets
* Examples:
```
123*        will find a string that has 12 followed by zero or more 3
xyz+        will find a string that has 12 followed by one or more 3
xyz?        will find a string that has 12 followed by zero or one 3
xyz{2}      will find a string that has 12 followed by 2 3
xyz{2,}     will find a string that has 12 followed by 2 or more 3
xyz{2,5}    will find a string that has 12 followed by 2 up to 5 3
x(yz)*      will find a string that has 12 followed by zero or more copies of the sequence 23
x(yz){2,5}  finds a string that has 12 followed by 2 up to 5 copies of the sequence 23
```

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)