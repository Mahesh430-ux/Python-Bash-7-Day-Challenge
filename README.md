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