# Python-Bash-7-Day-Challange

Day 1 : PYTHON BASICS :-

1) A Variable is a container that stores data in a memory so that when it needed we can use it 

example of variables in python :- name ="mahesh"  ( here the name is the variable and the mahesh is the information that store in  name(variable))

lets take an example of variable in cloud infrastructute suppose the example is :-
server=web-server-01
region=us-east-1

print(server)
print(region)


2) Data type:- A data type tells Python what kind of data is stored in a variable , so now lets discuss the type of data types  and those are string ,integer,float,boolean .

let us take example of each types of data types oky :- 
1) string :name = "Mahesh" - these indicates the text  data and those which are written in double notaion 
2) integer :age = 19       - these indicates that the variable is assign a numeric value 
3) float : salary = 1500.50  - these indicates that the numbers are written in decimal form 
4) boolean : is_server_running = True   
             logged_in = False     - these indicates that whether the statement is true or false .

output: true 
        false


3) Input and output:- 
example of input :-  name =input("My name is Mahesh")
                     print ("Good Morning" , name)
                    
output :-Good morning My name is Mahesh


4) Arithmetic operations:-
  4.1  Additon:- a = 63
                 b = 56
                 c = a + b
                 print(c) 

output :- c = 119 

 4.2   Substraction :- 
       print (a - b )

output :- 7 

4.3   Multiplication :
      print ( a * b )

output : 3528


4.4  Division :
print(a / b)

Output: 2.0


4.5 Modulus (%)  :- Returns remainder and Useful for checking even/odd numbers. 

print(10 % 3)

Output: 1 



5 Comparison Operators :- Used for comparisons between two numbers 


5.1 Equal To :- 
print(10 == 10)

Output: True 


5.2 Not Equal
print(10 != 5)

Output: True 


5.3 Greater Than
print(20 > 10)

Output: True 


5.4 Less Than
print(5 < 10)

Output: True 


6 Logical Operators :- logical operators operates the code logically it means that whether the code is logically coreect or not 
6.1 AND
print(True and True)

Output: True 


6.2 OR
print(True or False)

Output:True 


6.3 NOT
print(not True) 

7 Type conversion :-  Type converison changes on data type to another so why it is needed ? because input always return a string 

7.1 convert string into integer :-
example : age =int(input("Enter Age :" )) 
output:- 19 is stored as an integer 

7.2 convert string to float 
example :- price = float(input("Enter Price: "))
input 99.99 
output 99.99 

7.3 convert number to string :- 
example :- age = 19
print("Age is" +str(age) )
output :- Age is 19 

Day 2 :-Python Control Flow(Conditions & Loops)

1) comparsion operators :- 
1.1 Equal to (==)
1.2 != (Not equal to)
1.3 > (Greater than)
1.4 < (Less than)
1.5 >= (Greater than or equal to)
1.6 <= (Less than or equal to)

Example of all :
age  =int(input("Enter your age : 3"))
if age ==18:
    print("You are eligible to vote and for applying for a driving license")
elif age >=18:
    print("You are eligible to apply for voting ")
elif age <= 18:
    print("You are not eligible to vote")
elif age > 21:
    print("You are eligible to drive")
elif age < 21:
    print("You are not eligible to drive")


2.Logical Operators:- Logical operators combine two or more conditions into a single expression. They are useful when making complex decisions.

Types of Logical Operators

2.1 AND :- Returns True only if both conditions are true.

example :- 
age = 20
has_id = True

print(age >= 18 and has_id)

Output :-true

2.2 OR 

Returns True if **at least one condition** is true.

python
print(True or False)


Output  :- true 


2.3 NOT :- Reverse the result of a condition.
example :-  
print(not True)

Output:- False

3. Conditional Statements :- Conditional statements allow a program to make decisions based on conditions.



3.1 if Statement :-Executes a block of code only if the condition is true.

age = 20

if age >= 18:
    print("Eligible to Vote")

Output :- Eligible to Vote


3.2 if...else Statement :- Executes one block if the condition is true and another block if it is false.

age = 15

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")

Output :- Not Eligible


3.3 if...elif...else Statement :-Checks multiple conditions in order.

example :- 

marks = 82

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
else:
    print("Grade D")

Output :- Grade B

3.4. for Loop :- A for loop repeats a block of code for each item in a sequence or for a specified number of times.

example :-
for i in range(1, 6):
    print(i)


Output
1 2 3 4 5 








 Day 3 - Python 7 Days Challenge

 Topic: Conditional Statements (Decision Making)

Today I learned how Python makes decisions using conditional statements. These statements allow a program to execute different blocks of code depending on whether a condition is True or False.




What is a Conditional Statement?

A conditional statement is used to perform different actions based on different conditions.

Python evaluates a condition and executes the appropriate block of code.

Syntax

if condition:
    # code




1. if Statement

Definition :-The if statement executes a block of code only when the given condition is True.

Example :- 

age = 20
if age >= 18:
    print("You are eligible to vote.")

Output :- You are eligible to vote.



2. if-else Statement

Definition :- The if-else statement executes one block of code if the condition is True, otherwise it executes another block.

Example

age = 15

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")

Output

Not Eligible




3. if-elif-else Statement

Definition :-The elif keyword allows Python to check multiple conditions one after another if  none of the conditions are True, the else block is executed.

Example:-  

marks = 82
if marks >= 90:
    print("Grade A")
elif marks >= 80:
    print("Grade B")
elif marks >= 70:
    print("Grade C")
else:
    print("Grade D")

Output :- Grade B




4. Nested if Statement

Definition :- A Nested if means writing an if statement inside another if statement.It is used when one condition depends on another.

Example :- 

age = 22
has_license = True

if age >= 18:
    if has_license:
        print("You can drive.")

Output :- You can drive.



5. Comparison Operators

Definition :- Comparison operators compare two values and always return either True or False.

Operator	Meaning	Example

==	Equal to	5 == 5
!=	Not Equal to	5 != 4
>	Greater than	8 > 5
<	Less than	3 < 7
>=	Greater than or Equal to	10 >= 10
<=	Less than or Equal to	7 <= 9


Example :-
a = 15
b = 10

print(a > b)
print(a == b)

Output

True
False




6. Logical Operators

Definition :- Logical operators combine multiple conditions.

6.1 AND Operator (and) :- Returns True only if both conditions are True.

Example :-

age = 20
citizen = True

if age >= 18 and citizen:
    print("Eligible to vote")


---

6.2 OR Operator (or) :- Returns True if at least one condition is True.

Example:- 

rain = False
holiday = True

if rain or holiday:
    print("Stay at home")



6.3 NOT Operator (not) :- Reverses the result.

Example :- 
is_logged_in = False

if not is_logged_in:
    print("Please log in.")


7. Boolean Values

Definition :- A Boolean value has only two possible values:
                                True
                                False

Booleans are used to make decisions in programs.

Example :- 

is_student = True

print(is_student)

Output :- True


---

8. Indentation

Definition :- Indentation refers to the spaces before a line of code.

Python uses indentation to define blocks of code. Unlike many programming languages, Python does not use curly braces {}.

Correct Example:- 

age = 18

if age >= 18:
    print("Adult")

Incorrect Example

age = 18

if age >= 18:
print("Adult")

This will produce an IndentationError.




9. Pass Statement

Definition :- The pass statement is a placeholder. It allows you to write empty code blocks without causing an error.

Example :- 

age = 18

if age >= 18:
    pass




10. Ternary Operator (Conditional Expression)

Definition:- The ternary operator allows you to write an if-else statement in a single line.

Syntax

value_if_true if condition else value_if_false

Example :- 

age = 19

result = "Adult" if age >= 18 else "Minor"

print(result)

Output :- Adult




Mini Practice Programs

Program 1: Even or Odd

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")




Program 2: Largest Number

a = 20
b = 35

if a > b:
    print(a)
else:
    print(b)



Program 3: Positive, Negative, or Zero

num = int(input("Enter a number: "))

if num > 0:
    print("Positive")
elif num < 0:
    print("Negative")
else:
    print("Zero")


---

Program 4: Password Check

password = input("Enter password: ")

if password == "python123":
    print("Access Granted")
else:
    print("Access Denied")





🐍 Day 4: Python Loops :- 

Topics to Cover

1. What is a Loop?

Definition: A loop is used to execute a block of code repeatedly until a condition is met.

Example:

for i in range(5):
    print(i)

Output

0
1
2
3
4


---

2. for Loop

Definition: A for loop iterates over a sequence such as a list, tuple, string, or range.

Syntax

for variable in sequence:
    # code

Example

fruits = ["Apple", "Banana", "Mango"]

for fruit in fruits:
    print(fruit)


---

3. range() Function

Definition: The range() function generates a sequence of numbers.

Examples

for i in range(5):
    print(i)

for i in range(2, 8):
    print(i)

for i in range(1, 11, 2):
    print(i)


---

4. while Loop

Definition: A while loop executes as long as the given condition is True.

Example

count = 1

while count <= 5:
    print(count)
    count += 1


---

5. Infinite Loop

Definition: An infinite loop occurs when the loop condition never becomes False.

Example

while True:
    print("Hello")

> ⚠️ Stop the program manually using Ctrl + C.




---

6. break

Definition: The break statement immediately exits the loop.

Example

for i in range(10):
    if i == 5:
        break
    print(i)


---

7. continue

Definition: The continue statement skips the current iteration and moves to the next one.

Example

for i in range(6):
    if i == 3:
        continue
    print(i)


---

8. pass

Definition: The pass statement is a placeholder that does nothing.

Example

for i in range(5):
    if i == 2:
        pass
    print(i)


---

9. Nested Loops

Definition: A loop inside another loop is called a nested loop.

Example

for i in range(3):
    for j in range(3):
        print(i, j)


---

💻 Practice Programs

1. Print numbers from 1 to 20.
solution :- for i in range(20)
print(i)


2. Print even numbers from 1 to 50.
for i in range(50):
    str =int(input("Enter a number :"))
    if i % 2== 0:
        print("The number is even : {i}")
    else:
        print(" the number is odd :  {i}")


3. Print odd numbers from 1 to 50.

for number in range(1, 21):
    if number % 2 == 1:
        print(number)


4. Calculate the sum of numbers from 1 to 100.

total = 0;
for number in range (1 , 100):
    total = total + number 
print (" sum =" , total)

5. Print the multiplication table of any number.

number = int(input("Enter a number: "))

for i in range(1, 11):
    print(number, "x", i, "=", number * i)

Great idea. Since you're posting this on GitHub, it's better to explain **every List method** with its definition, syntax, example, and output. This makes your Day 5 repository much more valuable.


🐍 Day 5: Python Lists

 📌 5.1 What is a List?

A List is an ordered, mutable (changeable) collection that can store multiple items of different data types.

 Features

* ✅ Ordered
* ✅ Mutable
* ✅ Allows duplicate values
* ✅ Supports indexing and slicing
* ✅ Can contain different data types

---

 Creating a List :- 
 Example

python
fruits = ["Apple", "Mango", "Orange", "Banana"]

print(fruits)

 Output :- 
```
['Apple', 'Mango', 'Orange', 'Banana']
```

5.2 Indexing :- 

Lists start from 0.

python
fruits = ["Apple", "Mango", "Orange", "Banana"]

print(fruits[0])

print(fruits[2])

print(fruits[-1])


 Output :- 


Apple
Orange
Banana




 5.3 Slicing

python
numbers = [10,20,30,40,50]

print(numbers[1:4])

print(numbers[:3])

print(numbers[2:])


 Output


[20,30,40]
[10,20,30]
[30,40,50]



 ⭐ List Methods

---

1. append()

Definition :- 

Adds one item mto the end of the list.

 Syntax :- 

python
list.append(item)


 Example

python
languages = ["Python","Java"]

languages.append("Go")

print(languages)


 Output :- 


['Python', 'Java', 'Go']


---

2. insert()

 Definition :-- 

Inserts an element at a specified position.

Syntax :- 

python
list.insert(index, item)


 Example :-

python
languages = ["Python","Java"]

languages.insert(1,"C++")

print(languages)

 Output :-


['Python', 'C++', 'Java']


3. extend()

 Defination :- 

Adds all elements from another iterable (such as a list or tuple) to the end of the list.

 Syntax

python
list.extend(iterable)


 Example :- 

python
numbers = [1,2,3]

numbers.extend([4,5,6])

print(numbers)


 Output

[1,2,3,4,5,6]




 4. remove()

 Definition

Removes the **first occurrence** of the specified value.

 Syntax

python
list.remove(value)


 Example

python
fruits = ["Apple","Mango","Orange"]

fruits.remove("Mango")

print(fruits)


 Output


['Apple', 'Orange']




 5. pop()

 Definition :- 

Removes and returns an item at the specified index. If no index is given, it removes the last item.

 Syntax

python
list.pop(index)


 Example :- 

python
numbers = [10,20,30,40]

numbers.pop()

print(numbers)


 Output


[10,20,30]


6 . Pop by Index


numbers = [10,20,30,40]

numbers.pop(1)

print(numbers)


 Output


[10,30,40]




 6. clear()

Definition ;- 

Removes all items from the list.

 Example


numbers = [1,2,3]

numbers.clear()

print(numbers)


 Output : []

---

7. index()

 Definition :- 

Returns the index of the first occurrence of a value.

 Example


fruits = ["Apple","Mango","Orange"]

print(fruits.index("Orange"))


 Output :- 2


2



 8. count()

 Definition :- 

Counts how many times a value appears in the list.

Example

numbers = [1,2,2,3,2]

print(numbers.count(2))


 Output


3




 9. sort()

 Definition :- 

Sorts the list in ascending order by default.

 Example :- 


numbers = [5,2,8,1]

numbers.sort()

print(numbers)

 Output


[1,2,5,8]



 Descending Order

python
numbers = [5,2,8,1]

numbers.sort(reverse=True)

print(numbers)

 Output:- 


[8,5,2,1]




 10. reverse()

 Definition :-

Reverses the order of the list.

 Example :- 

numbers = [1,2,3,4]

numbers.reverse()

print(numbers)


 Output :-

[4,3,2,1]


 11. copy()

 Definition

Creates a shallow copy of the list.

 Example


list1 = [10,20,30]

list2 = list1.copy()

print(list2)


 Output :-


[10,20,30]

# ⭐ Built-in Functions Used with Lists

 len()

Returns the number of elements.

```python
fruits = ["Apple","Mango","Orange"]

print(len(fruits))

Output :- 3  


max()

Returns the largest value.


numbers = [5,10,20]

print(max(numbers))


Output


20



 min()

Returns the smallest value.


numbers = [5,10,20]

print(min(numbers))


Output :- 5 


sum()

Returns the total of all numbers.


numbers = [10,20,30]

print(sum(numbers))


Output


60

 sorted()

Returns a new sorted list without modifying the original.

numbers = [5,2,8,1]

print(sorted(numbers))

print(numbers)


Output


[1,2,5,8]
[5,2,8,1]
```



# List vs Tuple

| Feature     | List            | Tuple  |
| ----------- | --------------- | ------ |
| Mutable     | ✅ Yes           | ❌ No   |
| Ordered     | ✅ Yes           | ✅ Yes  |
| Duplicates  | ✅ Yes           | ✅ Yes  |
| Indexing    | ✅ Yes           | ✅ Yes  |
| Performance | Slightly slower | Faster |


