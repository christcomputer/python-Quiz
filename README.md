# python-Quiz


---

### Flow Control in Python Quiz

#### Question 1:
What is the output of the following code snippet?
```python
x = 10
if x > 5:
    print("Greater")
else:
    print("Smaller")
```
a) `Smaller`  
b) `Greater`  
c) `Greater Smaller`  
d) `No output`  

#### Question 2:
How do you correctly write a `for` loop to iterate over the items in a list named `my_list`?
a) `for item in my_list:`  
b) `for (item: my_list)`  
c) `for item from my_list`  
d) `foreach item in my_list`  

#### Question 3:
What will the following code snippet output?
```python
i = 0
while i < 3:
    print(i)
    i += 1
```
a) `0 1 2`  
b) `1 2 3`  
c) `0 1 2 3`  
d) `0 1 2 3 4`  

#### Question 4:
What is the correct syntax to create an `else` block for a `for` loop in Python?
a) 
```python
for i in range(5):
    print(i)
else:
    print("Done")
```  
b) 
```python
for i in range(5):
    print(i)
else print("Done")
```  
c) 
```python
for i in range(5):
    print(i)
else: print("Done")
```  
d) 
```python
for i in range(5):
    print(i)
finally:
    print("Done")
```  

#### Question 5:
How can you handle exceptions in Python?
a) `try...catch`  
b) `try...except`  
c) `try...finally`  
d) `catch...except`  

#### Question 6:
What will the following code snippet output?
```python
try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Execution complete")
```
a) `Cannot divide by zero` `Execution complete`  
b) `Cannot divide by zero`  
c) `Execution complete`  
d) `Error`  

#### Question 7:
In a `while` loop, what happens if the loop condition is always `False`?
a) The loop will execute once  
b) The loop will execute indefinitely  
c) The loop will not execute at all  
d) The code will result in a syntax error  

#### Question 8:
Which of the following `break` statements is correct for exiting a loop?
a) `break;`  
b) `break`  
c) `exit`  
d) `stop`  

#### Question 9:
What is the result of using the `continue` statement in a loop?
a) It exits the loop  
b) It skips the current iteration and proceeds to the next iteration  
c) It stops the program execution  
d) It breaks out of the loop and executes the `finally` block  

#### Question 10:
How can you define multiple conditions in an `if` statement?
a) `if condition1 or condition2:`  
b) `if (condition1, condition2):`  
c) `if condition1 and condition2:`  
d) `if condition1 then condition2:`  

---

### Answers:
1. b) `Greater`
2. a) `for item in my_list:`
3. a) `0 1 2`
4. a) 
```python
for i in range(5):
    print(i)
else:
    print("Done")
```  
5. b) `try...except`
6. a) `Cannot divide by zero` `Execution complete`
7. c) The loop will not execute at all
8. b) `break`
9. b) It skips the current iteration and proceeds to the next iteration
10. a) `if condition1 or condition2:`


---

### Python Strings Quiz

#### Question 1:
What is the output of the following code?
```python
s = "Hello, World!"
print(s[7:])
```
a) `World!`  
b) `Hello, World!`  
c) `World`  
d) `Hello,`  

#### Question 2:
Which method is used to convert all characters in a string to uppercase?
a) `to_upper()`  
b) `upper()`  
c) `capitalize()`  
d) `uppercase()`  

#### Question 3:
What does the `strip()` method do when called on a string?
a) Removes whitespace from the beginning and end of the string  
b) Removes all occurrences of a specified character  
c) Converts the string to lowercase  
d) Replaces a specified substring with another substring  

#### Question 4:
How can you check if a string contains a substring in Python?
a) `substring in string`  
b) `string.contains(substring)`  
c) `string.has(substring)`  
d) `substring.isin(string)`  

#### Question 5:
What is the result of the following code snippet?
```python
s = "Python"
s = s.replace("P", "J")
print(s)
```
a) `Jython`  
b) `Jython`  
c) `Python`  
d) `PythoJ`  

#### Question 6:
How can you concatenate two strings, `str1` and `str2`, in Python?
a) `str1 + str2`  
b) `str1 & str2`  
c) `str1.concat(str2)`  
d) `str1.append(str2)`  

#### Question 7:
What will be the output of this code?
```python
s = "abc def"
print(s.split())
```
a) `['abc', 'def']`  
b) `'abc', 'def'`  
c) `'abc def'`  
d) `['abc def']`  

#### Question 8:
Which method would you use to find the position of a substring within a string?
a) `index()`  
b) `find()`  
c) `locate()`  
d) `position()`  

#### Question 9:
What is the result of the following code snippet?
```python
s = "hello"
print(s[::2])
```
a) `hlo`  
b) `hello`  
c) `ell`  
d) `heo`  

#### Question 10:
How can you create a string from a list of characters `['a', 'b', 'c']`?
a) `''.join(['a', 'b', 'c'])`  
b) `list.join(['a', 'b', 'c'])`  
c) `str(['a', 'b', 'c'])`  
d) `''.combine(['a', 'b', 'c'])`  

---

### Answers:
1. a) `World!`
2. b) `upper()`
3. a) Removes whitespace from the beginning and end of the string
4. a) `substring in string`
5. a) `Jython`
6. a) `str1 + str2`
7. a) `['abc', 'def']`
8. b) `find()`
9. a) `hlo`
10. a) `''.join(['a', 'b', 'c'])`

---

### Python Lists Quiz

#### Question 1:
What is the output of the following code snippet?
```python
numbers = [1, 2, 3]
numbers.append([4, 5])
print(len(numbers))
```
a) `5`  
b) `4`  
c) `3`  
d) `6`  

#### Question 2:
How do you access the third element of a list named `my_list`?
a) `my_list[3]`  
b) `my_list[2]`  
c) `my_list.get(3)`  
d) `my_list(2)`  

#### Question 3:
What will the following code output?
```python
lst = [10, 20, 30]
lst[1:2] = [25]
print(lst)
```
a) `[10, 25, 30]`  
b) `[10, 25]`  
c) `[25, 30]`  
d) `[10, 20, 30, 25]`  

#### Question 4:
How do you remove the last item from a list named `my_list`?
a) `my_list.remove()`  
b) `my_list.pop()`  
c) `my_list.delete()`  
d) `my_list.clear()`  

#### Question 5:
What is the result of this code?
```python
lst = [1, 2, 3, 4, 5]
lst[1:4] = []
print(lst)
```
a) `[1, 5]`  
b) `[1, 2, 3, 4, 5]`  
c) `[1, 5]`  
d) `[1, 4, 5]`  

#### Question 6:
Which method can be used to sort a list in ascending order?
a) `sort()`  
b) `order()`  
c) `arrange()`  
d) `sort_asc()`  

#### Question 7:
How can you find the index of an element `x` in a list `my_list`?
a) `my_list.index(x)`  
b) `my_list.find(x)`  
c) `my_list.locate(x)`  
d) `my_list.search(x)`  

#### Question 8:
What will the following code produce?
```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
result = list1 + list2
print(result)
```
a) `[1, 2, 3, 4, 5, 6]`  
b) `[4, 5, 6, 1, 2, 3]`  
c) `[1, 2, 3]`  
d) `[4, 5, 6]`  

#### Question 9:
What is the output of this code?
```python
lst = [10, 20, 30, 40]
print(lst[::-1])
```
a) `[40, 30, 20, 10]`  
b) `[10, 20, 30, 40]`  
c) `[20, 30, 40, 10]`  
d) `[30, 40, 10, 20]`  

#### Question 10:
How do you add multiple items `[6, 7, 8]` to a list `my_list`?
a) `my_list.add([6, 7, 8])`  
b) `my_list.extend([6, 7, 8])`  
c) `my_list.append([6, 7, 8])`  
d) `my_list.insert([6, 7, 8])`  

---

### Answers:
1. b) `4`
2. b) `my_list[2]`
3. a) `[10, 25, 30]`
4. b) `my_list.pop()`
5. a) `[1, 5]`
6. a) `sort()`
7. a) `my_list.index(x)`
8. a) `[1, 2, 3, 4, 5, 6]`
9. a) `[40, 30, 20, 10]`
10. b) `my_list.extend([6, 7, 8])`

---

### Python Sets Quiz

#### Question 1:
What is the result of the following code snippet?
```python
s = {1, 2, 2, 3}
print(s)
```
a) `{1, 2, 2, 3}`  
b) `{1, 2, 3}`  
c) `{2, 2, 3}`  
d) `{1, 2}`  

#### Question 2:
Which method is used to add an element to a set?
a) `add()`  
b) `append()`  
c) `insert()`  
d) `push()`  

#### Question 3:
How do you remove an element from a set?
a) `remove(element)`  
b) `delete(element)`  
c) `discard(element)`  
d) `pop(element)`  

#### Question 4:
What is the output of the following code?
```python
s1 = {1, 2, 3}
s2 = {3, 4, 5}
print(s1.union(s2))
```
a) `{1, 2, 3, 4, 5}`  
b) `{1, 2, 3}`  
c) `{3, 4, 5}`  
d) `{1, 2, 3, 4}`  

#### Question 5:
How can you get the common elements between two sets?
a) `s1.intersection(s2)`  
b) `s1.union(s2)`  
c) `s1.difference(s2)`  
d) `s1.symmetric_difference(s2)`  

#### Question 6:
What is the result of the following code snippet?
```python
s = {1, 2, 3}
s.add(4)
print(s)
```
a) `{1, 2, 3, 4}`  
b) `{1, 2, 3}`  
c) `{4, 1, 2, 3}`  
d) `{1, 2, 3, 4, 4}`  

#### Question 7:
What will be the output of this code?
```python
s = {1, 2, 3}
s.discard(2)
print(s)
```
a) `{1, 3}`  
b) `{1, 2, 3}`  
c) `{2, 3}`  
d) `{1, 2}`  

#### Question 8:
How do you find the difference between two sets?
a) `s1.difference(s2)`  
b) `s1.union(s2)`  
c) `s1.intersection(s2)`  
d) `s1.symmetric_difference(s2)`  

#### Question 9:
What will the following code produce?
```python
s = {1, 2, 3, 4}
s.remove(5)
```
a) `KeyError`  
b) `{1, 2, 3, 4}`  
c) `{1, 2, 3, 4, 5}`  
d) `None`  

#### Question 10:
Which method returns a new set with elements that are in either set but not both?
a) `s1.symmetric_difference(s2)`  
b) `s1.intersection(s2)`  
c) `s1.union(s2)`  
d) `s1.difference(s2)`  

---

### Answers:
1. b) `{1, 2, 3}`
2. a) `add()`
3. a) `remove(element)` or c) `discard(element)` (both are valid, but `discard()` does not raise an error if the element is not present)
4. a) `{1, 2, 3, 4, 5}`
5. a) `s1.intersection(s2)`
6. a) `{1, 2, 3, 4}`
7. a) `{1, 3}`
8. a) `s1.difference(s2)`
9. a) `KeyError`
10. a) `s1.symmetric_difference(s2)`

