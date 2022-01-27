# Regex Tutorial

Regex refers to Regular Expressions, regex is used in many programing languages so developers can find specific combination of characters. Regular Expressions allows a programmer to search  for variations of string matching a specific pattern rather than being limited to a query. Having this in mind think about a large database with 100,000 users (with name, last name,  email) and you need to find someone by their email. 

## Summary

In this tutorial we will learn how use regex(Regular Expression) to match an email. Below you'll see an example of what is used to verify user input is a vaild email address.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Let's get started.

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
To start off, regular expressions begin and end with foward slash "/", In regular expression for matching an email address, we have surrounded our RegEx search with the anchors ^ and $ to identify that the enclosed search pattern should not have any other characters, including spaces, before or after it. Within the foward slash we encounter a caret (^) anchor which identefies the beginning of a string and the dolllar sign ($) identefies as the end of the string. The metacharacter (/b) is used to identify the begining or end of a word.

lets think about this for a second, if you use RegEx to search for /book/ it'll return "book" wherever its located because it does not care about the positioning within the string. if we plug in "$" we get /book$/ and will only find "book" located at the end of the string. if we use /^book/ it wont return any matches, since there are no instances that start with "book" in the begining of a string. lastly if we want to only look for the word book we enclose the RegEx search. (/\bbook\b/).


### Quantifiers
Quantifiers are instances of a character, group, class must be present in the input to find a match.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Written by Alexis Velasquez a full stack developer. for more information on the author checkout his github 
Github: https://github.com/alexzoo0
