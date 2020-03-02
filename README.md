# python-for-competitive-programming
This repo was created just for self revision. There might be cases where some codes may not be optimal.

<br>

### Replace char by other in a string

All occurance <br>
```string.replace(old_char,new_char)``` <br>

One occurance <br>
```string.replace(old_char,new_char, 1)``` <br>

### Conversion between different types

Integer to List <br>
```[int(x) for x in str(num)]``` <br>

Integer to String <br>
```str(integer)```

String to Integer <br>
``` int(string)```

List to Integer <br>
``` 
integers = [1, 2, 3]
strings = [str(integer) for integer in integers]
a_string = "".join(strings)
an_integer = int(a_string) 
```

List to String <br>
``` a_string = "".join(strings) ```

String to List of chars <br>
```list(word) ```



