# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def __init__(self,area):
        area=3.1416*r*r
        self.area=area
    def mech(self):
        print("Area of circle:",round(self.area,2))
r=eval(input())
boo=cse(r)
boo.mech()
```
## Output
![4 1](https://github.com/user-attachments/assets/a0614c3c-1123-4a92-bae8-d34ed535f11b)

## Result
Thus,the program has been executed successfully
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```
## Output
![4 2](https://github.com/user-attachments/assets/43b8a173-183e-4b9b-8905-12a84b619318)

## Result
Thus,the program has been executed successfully.

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def dictionairy(): 
# Declaring hash function      
key_value ={}    
# Initializing the value 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted", 
"in alphabetical order by the value") 
print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))

```
## Sample Output
![4 3](https://github.com/user-attachments/assets/626c9945-2a4c-4b80-a6a3-e6d441c1b60d)

## Result
Thus,the program has been executed successfully.
