# Regex Tutorial: Understanding Regular Expressions

Welcome to my Regex Tutorial. Here, we'll explore the world of regular expressions, often called Regex. Regex is a powerful tool for finding and manipulating patterns in text. This tutorial aims to teach you the basics of regex and how to use it effectively in your projects.

## Summary

In this tutorial, we'll focus on a regex pattern used to validate email addresses. Here's the regex pattern we'll discuss:

```javascript
/^[\w\.-]+@[\w\.-]+\.\w+$/
```
This regex pattern validates email addresses by ensuring they have the format username@domain.com.

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

Anchors in regex help define where a pattern should appear within the text. Here are two common anchors:

``^`` : The caret symbol denotes the start of a line or string.

``$`` : The dollar sign represents the end of a line or string.

Anchors are essential for ensuring that patterns match specific positions within the text.

### Quantifiers

Quantifiers allow us to specify how many times a character or group should appear. Here are three fundamental quantifiers:

``+`` : Matches one or more occurrences of the preceding character or group.

``*`` : Matches zero or more occurrences of the preceding character or group.

``?`` : Matches zero or one occurrence of the preceding character or group.

Quantifiers are crucial when dealing with patterns of variable length.


### Grouping Constructs

Grouping constructs help organize and capture parts of a regex pattern. They are handy when you want to extract specific information from a string. For example, you can use parentheses ``()`` to capture both the username and domain separately from an email address.

### Bracket Expressions

Bracket expressions, also known as character classes, allow us to specify a set of characters to match. Character classes add flexibility to pattern matching. For instance, you can use ``[0-9]`` to match any digit or ``[aeiou]`` to match any vowel in a word.
### Character Classes

Character classes are predefined sets of characters that simplify regex. Here are three common character classes:

``\d`` : Matches any digit character.

``\w`` : Matches any word character (alphanumeric characters and underscores).

``\s`` : Matches any whitespace character (spaces, tabs, newlines).

Character classes simplify common pattern matches. For instance, ``\d`` can replace ``[0-9]`` to match any digit character.

### The OR Operator

The OR operator ``|`` allows us to match multiple patterns. The OR operator is excellent for scenarios with multiple possible patterns. For example, you can use ``cat`` ``|`` ``dog`` to match either ``"cat" or "dog"`` in a text.

### Flags

Flags modify how regex patterns behave. Here are two common flags:

``i``: Performs case-insensitive matching.

``g``: Performs global matching (finds all matches, not just the first).

Flags give regex expressions versatility. The ``i`` flag, for instance, makes pattern matching case-insensitive, so "apple" matches "Apple."

### Character Escapes

Character escapes enable us to match special characters. Character escapes are essential when you need to match characters with special meanings in regex. For example, `\\` matches a backslash character, and `\.` matches a dot.

## Author

This tutorial was made by Cody Anderson [@cody-and](https://github.com/cody-and)
