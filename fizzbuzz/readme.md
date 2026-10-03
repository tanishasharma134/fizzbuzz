# FizzBuzz Program 🐍

## 📌 Description

This is a simple Python program that demonstrates the use of **loops, conditional statements, and the modulo (`%`) operator**.

The program prints numbers from **1 to 100** according to the FizzBuzz rules:

* If a number is divisible by **3 and 5**, it prints `FizzBuzz`.
* If a number is divisible by **3**, it prints `Fizz`.
* If a number is divisible by **5**, it prints `Buzz`.
* Otherwise, it prints the number itself.

## 🛠️ Technologies Used

* Python 3
* `for` loop
* `if`, `elif`, and `else`
* Modulo (`%`) operator
* `range()` function

## 💻 Code

```python
for num in range(1, 101):
    if num % 3 == 0 and num % 5 == 0:
        print("FizzBuzz")
    elif num % 3 == 0:
        print("Fizz")
    elif num % 5 == 0:
        print("Buzz")
    else:
        print(num)
```

## ▶️ How to Run

1. Make sure Python is installed on your computer.
2. Create a file named:

```text
fizzbuzz.py
```

3. Add the Python code to the file.
4. Open the terminal in the project folder.
5. Run:

```bash
python fizzbuzz.py
```

## 📤 Example Output

```text
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
...
```

## 🧠 Concepts Practiced

### 1. `for` Loop

The `for` loop is used to repeat the code for every number from 1 to 100.

```python
for num in range(1, 101):
```

### 2. Modulo Operator

The `%` operator gives the remainder after division.

For example:

```python
15 % 3 == 0
15 % 5 == 0
```

Therefore, `15` is printed as:

```text
FizzBuzz
```

### 3. Conditional Statements

The program uses `if`, `elif`, and `else` to check different conditions.

## 🎯 Learning Objective

By completing this project, you will practice:

* Using loops
* Writing conditions
* Using logical operators
* Using the modulo operator
* Understanding divisibility
* Building simple problem-solving logic

**created by**

**Tanisha**

BCA Student | Python Learner
