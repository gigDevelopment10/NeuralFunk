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
