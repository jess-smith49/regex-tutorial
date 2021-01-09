# Regex Tutorial: Matching HTML Tag

Introductory paragraph (replace this with your text)
The purpose of this tutorial is to explain what the different parts of a regular expression do and how they work specificaly with Matching an HTML tag.

## Summary
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

The tutorial will describe how the HTML matching tag works. 

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
The HTML matching tag has three anchors in its regular expression. Two of them include "^" and the other is a "$". 

The snippet of code for the "^" component would include the very beginning of the expression. This comes before the first capturing group and is there to match _____

The snippet of code for the "$" component at the end of the regex is

### Quantifiers
The HTML matching tag regex has two "*" and two "+" as well as one "?".

The quanitfier "+" is included in the first capturing group. ([a-z]+) which will match from one to as many times as possible.


### OR Operator
The HTML matching tag regex has one "|" and two "[]". The first set is [a-z] which is matching a string 


### Character Classes
The HTML matching regex expression has one character class. It is the "/s" and this is where the regex will match a whitespace character. In this case it would most likely be a break for the closing tag.

### Flags

### Grouping and Capturing
The HTML matching tag has 4 grouping and capturing within the expression, this involves nesting as well. 

The first grouping ([a-z]+) matches a single character between a-z.

### Bracket Expressions
The HTML regex expression has a couple bracket expressions. 
The first bracket within the code matches a string that has a character from a-z. [a-z].
The second bracket has a negation with in the expression
[^<]

### Greedy and Lazy Match
The HTML regex expression 

### Boundaries

### Back-references
The HTMl regex expression includes one back reference in the middle of the code. It is denoted as "/1". This back reference is here to match the same group of texted that was denoted in the first capturing group. This would be the way the regex matches its tags - for example <div> and </div> or <article> and </article>.


### Look-ahead and Look-behind
This regex does not contain look-ahead or look-behind.

## Author


A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
