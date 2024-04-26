---
description: Strings and basic string functions
---

# Strings

Strings are immutable

x = 'ananya'

x\[3] = 'u'  will give immutable error as strings are immutable as an object in themselves though strings can be reassigned to variables repeatedly.

x = 'anauya'  is possible cause we are assigning a new string instead of changing previous one ('ananya')

### String Init

```python
x  =  'ananya'
y  =  "andy"
long_string = '''  wow
you are awsome
;) ;)
'''
```

NOTE:

* if you want ' or " in string use escape sequences '\ '
* \t for tab space
* \n for new line
* \\\ for slash
* \\'  for '
* \\" for "

Operations On Strings

```python
>>>  print(x+y) 
	ananyaandy
>>> print(x*3)
	ananyaananyaananya
>>> print(x + str(100))
	ananya100
```

### String Formatting

```python
>>>x = 'ananya'
>>>age = 55
>>>print(f'hi {x}, you are {age} years old')
	hi ananya, you are 55 years old
>>>print('hi {}, you are {} years old'.format('ananya','55'))
	hi ananya, you are 55 years old
>>>print('hi {0}, you are {1} years old'.format(x,age))
hi ananya, you are 55 years old
```

### String Slicing

```python
>>>x = 'ananya'
>>>print(x[4])
	y
>>>print(x[0:3])
	ana
>>>print(x[0:5:-1])
	ynana
>>>print(x[3:])
	nya
>>>print(x[::2])
	aay
```

### String Methods

&#x20;

| Function                                                                         | Description                                                                                   |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [capitalize()](https://www.w3schools.com/python/ref\_string\_capitalize.asp)     | Converts the first character to upper case                                                    |
| [casefold()](https://www.w3schools.com/python/ref\_string\_casefold.asp)         | Converts string into lower case                                                               |
| [center()](https://www.w3schools.com/python/ref\_string\_center.asp)             | Returns a centered string                                                                     |
| [count()](https://www.w3schools.com/python/ref\_string\_count.asp)               | Returns the number of times a specified value occurs in a string                              |
| [encode()](https://www.w3schools.com/python/ref\_string\_encode.asp)             | Returns an encoded version of the string                                                      |
| [endswith()](https://www.w3schools.com/python/ref\_string\_endswith.asp)         | Returns true if the string ends with the specified value                                      |
| [expandtabs()](https://www.w3schools.com/python/ref\_string\_expandtabs.asp)     | Sets the tab size of the string                                                               |
| [find()](https://www.w3schools.com/python/ref\_string\_find.asp)                 | Searches the string for a specified value and returns the position of where it was found      |
| [format()](https://www.w3schools.com/python/ref\_string\_format.asp)             | Formats specified values in a string                                                          |
| format\_map()                                                                    | Formats specified values in a string                                                          |
| [index()](https://www.w3schools.com/python/ref\_string\_index.asp)               | Searches the string for a specified value and returns the position of where it was found      |
| [isalnum()](https://www.w3schools.com/python/ref\_string\_isalnum.asp)           | Returns True if all characters in the string are alphanumeric                                 |
| [isalpha()](https://www.w3schools.com/python/ref\_string\_isalpha.asp)           | Returns True if all characters in the string are in the alphabet                              |
| [isdecimal()](https://www.w3schools.com/python/ref\_string\_isdecimal.asp)       | Returns True if all characters in the string are decimals                                     |
| [isdigit()](https://www.w3schools.com/python/ref\_string\_isdigit.asp)           | Returns True if all characters in the string are digits                                       |
| [isidentifier()](https://www.w3schools.com/python/ref\_string\_isidentifier.asp) | Returns True if the string is an identifier                                                   |
| [islower()](https://www.w3schools.com/python/ref\_string\_islower.asp)           | Returns True if all characters in the string are lower case                                   |
| [isnumeric()](https://www.w3schools.com/python/ref\_string\_isnumeric.asp)       | Returns True if all characters in the string are numeric                                      |
| [isprintable()](https://www.w3schools.com/python/ref\_string\_isprintable.asp)   | Returns True if all characters in the string are printable                                    |
| [isspace()](https://www.w3schools.com/python/ref\_string\_isspace.asp)           | Returns True if all characters in the string are whitespaces                                  |
| [istitle()](https://www.w3schools.com/python/ref\_string\_istitle.asp)           | Returns True if the string follows the rules of a title                                       |
| [isupper()](https://www.w3schools.com/python/ref\_string\_isupper.asp)           | Returns True if all characters in the string are upper case                                   |
| [join()](https://www.w3schools.com/python/ref\_string\_join.asp)                 | Joins the elements of an iterable to the end of the string                                    |
| [ljust()](https://www.w3schools.com/python/ref\_string\_ljust.asp)               | Returns a left justified version of the string                                                |
| [lower()](https://www.w3schools.com/python/ref\_string\_lower.asp)               | Converts a string into lower case                                                             |
| [lstrip()](https://www.w3schools.com/python/ref\_string\_lstrip.asp)             | Returns a left trim version of the string                                                     |
| maketrans()                                                                      | Returns a translation table to be used in translations                                        |
| [partition()](https://www.w3schools.com/python/ref\_string\_partition.asp)       | Returns a tuple where the string is parted into three parts                                   |
| [replace()](https://www.w3schools.com/python/ref\_string\_replace.asp)           | Returns a string where a specified value is replaced with a specified value                   |
| [rfind()](https://www.w3schools.com/python/ref\_string\_rfind.asp)               | Searches the string for a specified value and returns the last position of where it was found |
| [rindex()](https://www.w3schools.com/python/ref\_string\_rindex.asp)             | Searches the string for a specified value and returns the last position of where it was found |
| [rjust()](https://www.w3schools.com/python/ref\_string\_rjust.asp)               | Returns a right justified version of the string                                               |
| [rpartition()](https://www.w3schools.com/python/ref\_string\_rpartition.asp)     | Returns a tuple where the string is parted into three parts                                   |
| [rsplit()](https://www.w3schools.com/python/ref\_string\_rsplit.asp)             | Splits the string at the specified separator, and returns a list                              |
| [rstrip()](https://www.w3schools.com/python/ref\_string\_rstrip.asp)             | Returns a right trim version of the string                                                    |
| [split()](https://www.w3schools.com/python/ref\_string\_split.asp)               | Splits the string at the specified separator, and returns a list                              |
| [splitlines()](https://www.w3schools.com/python/ref\_string\_splitlines.asp)     | Splits the string at line breaks and returns a list                                           |
| [startswith()](https://www.w3schools.com/python/ref\_string\_startswith.asp)     | Returns true if the string starts with the specified value                                    |
| [strip()](https://www.w3schools.com/python/ref\_string\_strip.asp)               | Returns a trimmed version of the string                                                       |
| [swapcase()](https://www.w3schools.com/python/ref\_string\_swapcase.asp)         | Swaps cases, lower case becomes upper case and vice versa                                     |
| [title()](https://www.w3schools.com/python/ref\_string\_title.asp)               | Converts the first character of each word to upper case                                       |
| translate()                                                                      | Returns a translated string                                                                   |
| [upper()](https://www.w3schools.com/python/ref\_string\_upper.asp)               | Converts a string into upper case                                                             |
| [zfill()](https://www.w3schools.com/python/ref\_string\_zfill.asp)               | Fills the string with a specified number of 0 values at the beginning                         |

&#x20;

&#x20;
