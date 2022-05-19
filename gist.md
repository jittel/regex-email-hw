# Regex Tutorial

Regular expressions (or regex for short) are used for finding and replacing text, and text validation.

## Summary

This is the regular expression to validate a matching email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This can help in any website where users will have to pass through an email validation check.

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
`^` is our starting anchor, and `$` is our ending anchor. These show the beginning and end of a string.

### Quantifiers
`([a-z\.]{2,6})` is showing that we are taking in the characters a-z, and limiting the length to between 2 and 6 characters. The `+` is adding seperate parts of the string together.

### Grouping Constructs
All instances of things held inside parentheses `(` and `)` are considered part of a group, and allows you to treat that piece as a single unit.

### Bracket Expressions
Brackets `[` and `]` show that certain characters are part of a set.

### Character Classes
`a-z0-9_` denotes that the characters coming in are a-z and 0-9.

### The OR Operator
There is no OR operator in this expression.

### Flags
There are no flags in this expression.

### Character Escapes
`\d` matches any single digit [0-9], but will not match double digits.

## Author

Nate is a web developer working mostly with the MERN stack, check out his [github](https://github.com/jittel)
