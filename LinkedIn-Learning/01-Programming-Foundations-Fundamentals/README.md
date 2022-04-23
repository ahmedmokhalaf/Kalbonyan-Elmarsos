# Goal Sections

## 1. Programming Basics

### Software Lingo

[Software Lingo.pdf](Software%20Lingo.pdf)
---

## 2. Programming Syntax

### Basic statements and expressions

🛠 Operators are symbols that tell the computer to perform an action with some input.

> Expression = input And Operator And  Operands.
> Expression = 10 + 20

| Symbol | Operation | Usage |
| :----: | :----: | :----: |
| + | Addition | 10 + 2 |
| - | Subtraction  | 10 - 2 |
| × | Multiplication  | 10 * 2 |
| ÷ | Division | 10 / 2  |


### The order of operations “ PEMDAS ’’

- For more information.
    [Order of Operations - PEMDAS (mathsisfun.com)](https://www.mathsisfun.com/operation-order-pemdas.html)

   ![The order of operations “ PEMDAS ’’](https://cdn-academy.pressidium.com/academy/wp-content/uploads/2022/02/PEMDAS.png)

- 🛠 PEMDAS

        2 + 5 × 3 = 2 + 15 = 17 ☑️ This is right
        2 + 5 × 3 = 7 × 3  = 21 ❌ This is wrong

---

### **Troubleshooting issues**

      🐞 There are three different types of error

### **_Syntax errors_**

- A syntax error occurs when the code given does not follow the syntax rules of the programming language. Examples include:

  - misspelling a statement, eg writing `pint` instead of `print`
  - using a **variable** before it has been declared
  - missing brackets, eg opening a bracket, but not closing it

> A  program cannot run if it has syntax errors. Any such errors must be fixed first. A good **integrated development environment (IDE)** usually points out any syntax errors to the programmer.

### **_Logic errors_**

- A logic error is an error in the way a program works. The program can run but does not do what it is expected to do.

- Logic errors can be caused by the programmer:

  - incorrectly using logical operators, eg expecting a program to stop when the value of a variable reaches 5, but using <5 instead of <=5
  - incorrectly using **Boolean operators**
  - unintentionally creating a situation where an **infinite loop** may occur
  - incorrectly using brackets in calculations
  - unintentionally using the same variable name at different points in the program for different purposes
  - using incorrect program design

> Unlike a syntax error, a logic error does not usually stop a program from running. The program will run, but not function as expected.

**A program with a syntax error will not run. A program with a logic error will run but it will not perform as expected.**

### **_Runtime errors_**

- A **runtime error** is an error that takes place during the running of a program.

- An example is writing a program that tries to access the sixth item in an **array** that only contains five items. A runtime error is likely to crash the program.

---

## 3. Variables and Data Types

### Python Data Type

  ![Python Data Type](https://pynative.com/wp-content/uploads/2021/02/python-data-types.jpg)

---

### Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)

---

### Python Keywords

![Python Keywords](https://cdn.educba.com/academy/wp-content/uploads/2019/11/Python-Keywords.png)

---

### **Working with numbers**

![Untitled](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/ae506946-a9db-49a2-ba83-8e7967a413d3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220423%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220423T142200Z&X-Amz-Expires=86400&X-Amz-Signature=3d4e695a16b531a02173ea8e3597b002900a912620ae2a64311f8a25c4fee708&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

---

### Comments

```python
Single Comment
    # This is a comment
    # written in
    # more than just one line
    
Multi Line Comments
    """
    This is a comment
    written in
    more than just one line
    """
```

## 4. Conditional Code

### Relational Operators

![Relational Operators](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4e412444-ebcc-4f66-bfa3-027984af1792/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220423%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220423T142328Z&X-Amz-Expires=86400&X-Amz-Signature=7dcd496b2e322bf47c91a05f2a6e988518b38320b32de1a6183b7d100845b81b&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

### If In Python , Java && Ruby

   ![If In Python , Java && Ruby](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/640cc2f0-25f9-40ce-8efd-a19bdce3d383/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220423%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220423T142506Z&X-Amz-Expires=86400&X-Amz-Signature=64f4a339dab2961e74af5faf1232fba9db983446ec372e9e4f23daf8661a8146&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

## 5. Modular Code

### Creating and calling functions

- Creating a Function
    In Python a function is defined using the def keyword:

    ```python
    def say_hello():
        print("Hello from a function")
    ```

### Calling a Function

- To call a function, use the function name followed by parenthesis:

    ```python
    def say_hello():
        print("Hello from a function")
    say_hello()
    ```

### Parameters or Arguments?

  - The terms _parameter_ and _argument_ can be used for the same thing: information that are passed into a function.
    From a function's perspective:
    A parameter is the variable listed inside the parentheses in the function definition.
    An argument is the value that is sent to the function when it is called.

        ```python
        def my_function(fname):
        print(fname + " Refsnes")
        
        my_function("Emil")
        my_function("Tobias")
        my_function("Linus")
        ```
###  Return Values
  - To let a function return a value, use the `return` statement:

    ```python
    def my_function(x):
        return 5 * x

    print(my_function(3))
    print(my_function(5))
    print(my_function(9))
    ```
---
## Certificate of Programming Foundations: Fundamentals

![Certificate of Programming Foundations: Fundamentals](https://media-exp1.licdn.com/dms/image/C4E1FAQGSQRIV8wC1jw/feedshare-document-cover-images_1280/0/1650665925959?e=2147483647&v=beta&t=uiDq6xkFnEbsC86j8tE87DuoUFgsPKjnm72CbfjoZwQ)
