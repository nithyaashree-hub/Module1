## EX 01:Conditional Statements in Python: Even or Odd Checker


## 🎯 Aim:

To write a Python program to check whether the given number is even or odd using if...else statements.

## 🧠 Algorithm:

Get an input from the user.

Convert the input to an integer and store it in a variable a.

Use the modulo operator % to check if a % 2 == 0.

If true, print "EVEN".

Else, print "ODD".

End the program.

## 🧾 Program:
~~~
a=int(input())
if(a%2==0):
    print("EVEN")
else:
    print("ODD")
~~~
## Output:

<img width="390" height="315" alt="image" src="https://github.com/user-attachments/assets/06e81011-2fa6-4c87-b213-bab7cc54ce10" />

## Result:

Thus,the Python program to check whether the given number is even or odd using if...else statements is created successfully.


# Ex 02:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim:

To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm:

1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program:
~~~
a = (False == True)
b = (False== 0)
c = False + True
d = False + 5
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
~~~

## Output:

<img width="392" height="356" alt="image" src="https://github.com/user-attachments/assets/7df17000-cab9-47b0-8dbb-110b3ff174b8" />



# EX 03:Datatypes-Character Literal in Python

## 🎯 Aim:
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm:
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program:
~~~
a='T'
b='a'
print(a)
print(b)
~~~
## Output:

<img width="367" height="311" alt="image" src="https://github.com/user-attachments/assets/c267ed6b-fa38-4b13-a7da-db746651f2a8" />

## Result:
Thus,the Python program that prints the characters 'T' and 'a' using character literals is created successfully.


# EX 04:🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output
![image](https://github.com/user-attachments/assets/cfb21d8d-f166-463c-9763-1553bb104556)

## Result
Thus,the Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is created successfully.



# EX 05:Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```
## Output
![image](https://github.com/user-attachments/assets/4f908af4-3ede-436b-ab3a-ce1aa9a7adc4)


## Result
Thus,the Python program to read a string from the user and then print it is created successfully.
