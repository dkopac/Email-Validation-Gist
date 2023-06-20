# Validating an Email using regex

In this tutorial we will breakdown how to validate an email using regex.

## Summary

The Regex we are examining is ^[a-z0-9]+@[a-z]+\.[a-z]{2,3}$

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

^ and $ are the anchors in this snippet. ^ represents the begining of the string while $ ends the string

### Quantifiers

{2,3} are the quantifiers as they will match any string that contains a squence of 2 to 3 characters

### Character Classes

[a-z0-9] is any character between a to z and 0 to 9 to start the string \. is used as the email with characters following the @ character

### Grouping and Capturing

The () will validate the characters inside the string for the valid email

### Bracket Expressions

[a-z] and [0-9] will find and character between the brackets while either of those expressions that start with ^ will find any character outside of the brackets.

### Greedy and Lazy Match

[a-z] Greedy will return a wide variety of strings while [0-9] Lazy will return a small string

Created By https://github.com/dkopac
