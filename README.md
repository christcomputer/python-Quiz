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

