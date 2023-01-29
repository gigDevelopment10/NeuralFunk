**Slice a string in equal parts in array**
* string = 'aabcdefcn' k = 3
* output = ['aab', 'cde', 'fcn']
```
List = list(map(''.join, zip(*[iter(string)]*k)))
```
