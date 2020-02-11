## Lists

Lists are good for keeping track of things by their order, especially when that order might change.

* Lists are mutable; you can add new elements, and modify or delete existing ones
* A list is made of zero or more elements separated by commas, and surrounded by square brackets
* The same value can occur more than once in a list
* Lists can contain elements of different types, including other lists
* To create a list you can use `[]` or the `list()` function
```
# returns []

empty_list = []
```
```
# returns []

another_empty_list = list() 
```
```
# returns ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday']

weekdays = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday']
```
## List Type Conversion

To change other Python data types to a list, use the `list()` function. The following example converts a string to a list of one-character strings.
```
# returns  ['s', 'u', 'n', 's', 'h', 'i', 'n', 'e']

list('sunshine')
```
