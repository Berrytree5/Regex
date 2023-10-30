
# Regex Tutorial: Mastering Regular Expressions

## Introduction
Welcome to my comprehensive regex tutorial on matching and validating email addresses. Email addresses come in various formats, and regex is a powerful tool to ensure their validity. In this tutorial, we'll explore a regex pattern for matching and validating email addresses and provide explanations and examples.

## Summary
In this tutorial, we'll focus on a specific regex: `^(\d{3}-\d{2}-\d{4})$`. 

This regex matches a wide range of valid email addresses.

## Table of Contents
- [Understanding the `^` Anchor](#understanding-the--anchor)
- [Matching Characters with `[\w\.-]`](#matching-characters-with-w-)
- [The `+` Quantifier](#the--quantifier)
- [Matching the `@` Symbol](#matching-the--symbol)
- [Matching Domain Components with `[\w\.-]+`](#matching-domain-components-with-w-)
- [Matching the Dot `.`](#matching-the-dot-)
- [Matching the Top-Level Domain (TLD) with `\w+`](#matching-the-top-level-domain-tld-with-w)
- [The `$` Anchor and Conclusion](#the--anchor-and-conclusion)

## Understanding the `^` Anchor
### Explanation: 
The `^` anchor matches the start of a line. In our regex, it marks the beginning of the email address.
### Exmample: 
The regex ^[\w\.-]+ matches the characters at the beginning of an email address.

## Matching Characters with `[\w\.-]`

### Explanation: 
The character class `[\w\.-]` matches word characters, dots, and hyphens in the email username and domain.
### Example:
 The regex [a-zA-Z0-9\.-]+ matches characters in the username part of an email address.

## The `+` Quantifier
### Explanation:
 The `+` quantifier allows one or more occurrences of the preceding pattern. It's used to match one or more characters in the email username and domain.
### Example:
 The regex [a-zA-Z0-9\.-]+ matches one or more characters in the username.

## Matching the `@` Symbol
### Explanation:
 The `@` symbol is a literal match for the at symbol in the email.
### Example : 
The regex @ matches the at symbol in an email address.

## Matching Domain Components with `[\w\.-]+`
### Explanation: 
We use `[\w\.-]+` to match the domain components (e.g., google in `google.com`) in the email address.
### 
Example: The regex [\w\.-]+ matches domain components in email addresses.
## Matching the Dot `.`
### Explanation 
The dot `.` is a literal match for the dot in the email domain.
### Example: 
The regex . matches the dot in an email address.
## Matching the Top-Level Domain (TLD) with `\w+`
### Explanation: 
`\w+` matches the top-level domain (TLD), such as com in `google.com`.
### Example :
The regex \w+ matches the TLD in email addresses.

## The `$` Anchor and Conclusion
### Explanation: 
The `$` anchor matches the end of a line, signifying the end of the email address. In this section, we summarize what we've learned and provide additional resources.
### Conclusion : 
This tutorial has explored the components of an email address regex pattern. We've covered the ^ anchor, character classes, quantifiers, and anchors. Using these components, you can match and validate email addresses effectively.


## About the Author
This tutorial was written by [Drew Berry](https://github.com/Berrytree5). Feel free to check out my GitHub profile for more resources and tutorials.
## Sourcees : https://github.com/pengbo-learn/books/blob/master/Mastering%20Regular%20Expressions%203rd%20(Friedl-2006).pdf
