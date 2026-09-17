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
my_dict = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

# Sort keys
keys_sorted = dict(sorted(my_dict.items()))
print("Keys sorted:", keys_sorted)

# Sort values
values_sorted = dict(sorted(my_dict.items(), key=lambda x: x[1]))
print("Values sorted:", values_sorted)

## Sample Output
Keys sorted: {'a': 'apple', 'b': 'banana', 'c': 'cherry'}
Values sorted: {'a': 'apple', 'b': 'banana', 'c': 'cherry'}

## Result
Dictionary keys and values are successfully sorted in alphabetical order.

