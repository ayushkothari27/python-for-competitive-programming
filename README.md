# python-for-competitive-programming
This repo was created just for self revision. There might be cases where some codes may not be optimal.

<br>

### Conversion between different types

Integer to List - ```[int(x) for x in str(num)]``` <br>

Integer to String - ```str(integer)``` <br>

String to Integer - ``` int(string)``` <br>

List to Integer <br>
``` 
integers = [1, 2, 3]
strings = [str(integer) for integer in integers]
a_string = "".join(strings)
an_integer = int(a_string) 
```

List to String - ``` "".join(list_of_strings) ``` <br>

String to List of chars - ```list(string) ``` <br>

### String functions

Lower case - ```string.lower()``` <br>

Upper case - ```string.upper()``` <br>

Reverse - ``` string[::-1] ``` <br>

Replace all occurance of char by other in a string - ```string.replace(old_char,new_char)``` <br>
``` ''.join('new_char if c == old_char else c for c in string)``` <br>
``` new_char.join(address.split(old_char)) ```

Replace one occurance of char by other in a string - ```string.replace(old_char,new_char, 1)``` <br>

Split - ``` string.split(delimiter) ``` <br>

Find index of a char in string - ``` string.find(char) (-1 means char not found) ``` <br>

Count 

### List/Array functions 

Maximum number in array - ```max(array)```  <br>

Minimum number in array - ```min(array)```  <br>

Append value to a list - ```list.append(value)``` <br>

Append one list to lists - ``` list1.extend(list2)``` <br>

Count a number in array - ```array.count(i)``` <br>

Length of a list - ```len(list)``` <br>

Sort numbers in an array - ```sorted(array) ``` <br>

Sum of numbers in an array - ```sum(array)``` <br>

Reverse - ``` list.reverse() ``` <br>

Find index of a element in list - ``` list.index(element)  ``` <br>

Delete element at a certain index - ``` del list[index] ``` <br>

Insert an element at a particular index - ``` list.insert(index,element) ``` <br>

Remove element at particular index - ``` array.pop(index)  ``` <br>

Remove a particular element - ``` array.remove(element)  ``` <br>

### Dictionary functions 
Initialize - ```dict = {}``` <br>

Assign - ``` dict[key] = value ``` <br>

Check if key already exists - ``` if key in dict ``` <br>

Get value from a key ``` dict[key] ``` <br>

List of keys - ``` list(dict.keys()) ``` <br>

List of values - ``` list(dict.values()) ``` <br>

Remove a particular key - ```dict.pop(key) ``` <br>

### Set functions 

Initialize - ``` x = set()  ``` <br>

Add into a set - ``` set.add(element) ``` <br>

Check if element already exists - ``` if ele in set ``` <br>

### ASCII

Int val from char - ```ord(char)``` <br>

Char val from int - ```chr(int)``` <br>


### No of digits in a number

```log10(n) + 1``` <br>

### Binary number of a particular length - 
```
get_bin = lambda x, n: format(x, 'b').zfill(n)
binary_x = get_bin(number,length)
```

### Tips

1. If you want to sort an array seperating even and odd numbers we can use quick sort with time O(N) and space O(1). <br>


