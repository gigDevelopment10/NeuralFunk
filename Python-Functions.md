# Python In built funtions 

**id()**

* The id() function returns a unique id for the specified object. 
* All objects in Python has its own unique id. The id is assigned to the object when it is created. 
```
n = 3
uid = str(id(n))
# output = '9793152'
```
**set()**

* The set() function returns unique elements of an array. 
* However the order is not preserved but here is an alternative way
```
def set(sub_string):
    uniue_char = []
    for c in sub_string:
        if not c in uniue_char:
            uniue_char.append(c)
    return ''.join(uniue_char)
```

**Python magic funtion**
Python __add__() function is one of the magic methods in Python that returns a new object(third) i.e. the addition of the other two objects. It implements the addition operator “+” in Python.
```
class Pyth:
  
    def __init__(self, val):
        self.val = val
  
obj1 = Pyth("Geeks")
obj2 = Pyth("ForGeeks")
obj3 = obj1 + obj2
print(obj3.val)
```

Python __call__ is a built-in function. The __call__ method enables Python programmers to write classes where the instances behave like functions and can be called like a function. When the instance is called as a function; if this method is defined, x(arg1, arg2, ...) is a shorthand for x.__call__(arg1, arg2, ...).

```
object() is shorthand for object.__call__()
```
