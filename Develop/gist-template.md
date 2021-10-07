# Matching an Email Address

<!-- Introductory paragraph (replace this with your text) -->
I will take you through the steps of determining the componants of an email address using Regex.  You will learn how to find all the Quantifiers that makes up an email address.

## Summary

<!-- Briefly summarize the regex you will be describing and what you will explain.  -->

Matching an Email –
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

dm-tuominen@adacounty.id.gov

The fisrt Regex Components is dm-tuominen,  the plus +) after the ending bracket is telling it to run through each character until it gets the the end.  It will know it is at the end of the string when it reaches the @ symbol, you can use as may characters in in this component as you liek there is no limit.  The @ symbol is the second component of the emall address and the only character in this component. The third component of the email address is the adacounty, again it will run through the string until it get to the . which is the next component.  This component can be as long as you wonat there is no limit. The plus +) tells it to run through the string until it gets to the end. the forth component is the id.gov, this component can be either 2 characters or up to 6 characters.  It can not have any more characters than that.

That breaks down how you would find each of these components.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Author](#author)



## Regex Components
Regex Components are Building blocks to create a pattern

### Anchors 
^  is put in the begining  of a string and $  is at the end of the string

### Quantifiers
Related to the quinity of characted in the componant like {2, 6} means it can be at least 2 and no more than 6 characters

### Character Classes
Character Classes are the brackets and the items in the brackets are the characters

### Grouping and Capturing
Parentheses are the basic grouping  of  a regex expressions
### Bracket Expressions
Character class is an example of a bracket.

## Author

  Denise Tuominen
  dmtuominen@gmail.com
   [dmtuomine22](https://github.com/dmtuominen22)
