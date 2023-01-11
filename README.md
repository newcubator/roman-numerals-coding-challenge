# Roman Numeral Converter - Coding Interview

Roman numerals are a numeral system used in ancient Rome and are still used today, mainly for numbering the pages of some books, such as the preface, and for numbering the hours on some clocks.

The basic symbols used in Roman numerals are:

* I (1)
* V (5)
* X (10)
* L (50)
* C (100)
* D (500)
* M (1000)

To create larger numbers, these symbols are combined. For example:

* VIII (8) is created by combining V (5) and III (3).
* LXIV (64) is created by combining L (50), X (10), and IV (4).
* MCDXLIV (1444) is created by combining M (1000), CD (400), XL (40), and IV (4).

There are a few rules to follow when using Roman numerals:

* A symbol placed after another of equal or greater value adds its value. For example, VI is 6 (5 + 1).
* A symbol placed before another of greater value subtracts its value. For example, IV is 4 (5 - 1).
* When a symbol appears after one of greater value, the two symbols are added, regardless of the order in which they appear. For example, LX is 60 (50 + 10).


## Challenge

Create a website using React that allows a user to either enter an arabic or roman number and converts it to the other format. The website should offer a good UX including some nice convenience features. Useful test cases should make sure everything works and will work in the future.
The input range should be limited from 1-3999.
