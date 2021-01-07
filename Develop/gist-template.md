# Regex Tutorial: Matching HTML Tag

Introductory paragraph (replace this with your text)

## Summary
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

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

### Quantifiers
The HTML matching tag regex has two "*" and two "+" as well as one "?".


### OR Operator
The HTML matching tag regex has one "|" and two "[]".


### Character Classes
The HTML matching regex expression has one character class. It is the "/s" and this is where the regex will match a whitespace character. In this case it would most likely be a break for the closing tag.

### Flags

### Grouping and Capturing
The HTML matching tag has 4 grouping and capturing within the expression, this involves nesting as well. 


### Bracket Expressions
The HTML regex expression has a couple bracket expressions. The first bracket matches a string that has a character from a-z. The second bracket has a negation with in the expression

### Greedy and Lazy Match
The HTML regex expression 

### Boundaries

### Back-references
The HTMl regex expression includes one back reference in the middle of the code. It is denoted as "/1". This back reference is here to match the same group of texted that was denoted in the first capturing group. This would be the way the regex matches its tags - for example <div> and </div> or <article> and </article>.


### Look-ahead and Look-behind
This regex does not contain look-ahead or look-behind.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
