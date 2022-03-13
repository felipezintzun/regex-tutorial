# Regex Tutorial

This gist explains the use of this regular expression and how it can be used to search from a url.  (/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/)

## Summary

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


## Regex 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
Anchors are part of the regex tokens that do not match any specific character, but identify the engine's current position. For example, the beginning or the end of the string. 

The ^ symbol is used to identify the the beginning of a string. 
The $ is used to identify the end of the string. 

### Quantifiers
Quantifiers specify how many times of a character, character class, or group must be in the input for a match to be found. This regex contains two quantifiers listed below.

The + matches 1 or more of the preceding token. 
{2,6} Quantifier. Matches betweeen 2 and 6 of the preceding token.

### Character Classes
The character class is a small sequence of characters that matches a larger sequence of characters. For example, a-z, we could list out the entire alphabet but instead we use a character class. The most basic regex concept after a literal match.

a-z matches a character in the range of a-z, case sensitive.
0-9 matches a character in the range of 0-9, case sensitive.

### Grouping and Capturing
Grouping and capturing is a way to work with multiple characters as a single unit. They are created by placing the characters insided of a set of parentheses. 

() is used to capture groups 1,2, and 3.
[] is used to match character sets.

## Author

Felipe is a full stack developer with experience in graphics and coding. He recently received a certificate from the UT Austin Coding Bootcamp for completing the course. Felipe gradutated from Texas State University with a Bachelor's of Science, majoring in Advertising and minoring in Art & Design. He finds joy in all things but not limited to cutting-edge design, cooking, technology, street tacos, craft cocktails, his maltipoo Lilo, and all things futuristic.
Connect with Felipe on [LinkedIn](https://www.linkedin.com/in/felipe-mendoza-zintzun-40b28a232/) <br>
Connect with Felipe on [Github](https://github.com/felipezintzun)