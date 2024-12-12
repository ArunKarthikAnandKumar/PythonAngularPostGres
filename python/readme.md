# Printing in python 
for numbers just add comma and type the number.
print('Hello World',100)

Conat doesnt work with int type use comma for printing
```
name='Arun'
age=18
print('The name is '+name+' Age is',age)
```

\n new line character
for string ypu can do slicing 
str="Arun"
str[0]

in print(1+2)
it gives the output.

# int to str
num1=str(num2)

abs(-1) gives the absolute value.
max(4,1)
min(4,1)
sum(1,2,3)
round(3.51)
bin(3) to binary string.

# Importing
from math import *
functions like 
sqrt

# User Input
input('Name') 
default any input is taken as string

for taking only int
age=int(input('Enter your name))

sentence.replace(w1,w2)
w1 replaced with w2

# List In Python
in this we can use double slicing
print(countries[1:])
for 1 to end all wil be printed.

# printing Type
print(type(var))

reverse indexing
from last -1

List can store multiple types without explicitly specifying.

Constructors
countries=list(('Nigeria',34,False))

Normaly list
count=[1,2,3]

# List Methods
for adding 1 to 2
l1.extend(l2)
l1.append()
len(l1)
l1.insert(index,'name')
l1.remove(index,'name')
l1.count('mango')
l1.sort()
l1.reverse()
l2=l1.copy()
l1.pop()
l1.remove(index,or value)
del list1[1]

# Tuples
they are immutable
() brackets are used
once created cannot be modified.
allows repetation of value
it allows various dataTypes in it.
### tuple constructor
tp=tuple((1,'homw'))

# Functions in python
def greetings():
 print('helo')

one single indentation is 4 spaces

in function if not sure about len 
paramater as fun(*name)
print usig index name[1]

Name arguments
fun(name='john',age=17)

# Conditional
if ():
elif():
else

checking condition we can use 'and' 'or'

while taking input general input means it can be of any type.

# Dictioanaries
Key Value Pairs
```

my_dict={"name":'Arun',"age":18,"number":'9099000'}
print(my_dict['name'])
```
Duplicates are not allowed

# For loop
we can use it to iterate through any dataType.
```
for i in range(10):
    print(i)
```
loop prints from 0

for i in range(1,10,2)
start 1 , 2 is step value.

# Comments
single line use #
for multi line
use 3 inverted commas.

# Try Except in Python 

```
try:
    age=int(input('Enter age:'))
except:
    print('Invalid value Entered')

```
if we specify type of error in except only for that error will be thrown.

we can also use finally
even if error or not it will execute.

# File Handling in Python

###### Reading
```
count_file=open('hello.txt','r')
if count_file.readable():
    print(count_file.readline())
count_file.close()
```
if we use readLines all will be printed.
a file openend must be closed

##### writing
```
count_file=open('hello.txt','w')
count_file.write('This is the current value')
count_file.close()

count_file=open('hello.txt','r')
if count_file.readable():
    print(count_file.readline())
count_file.close()

```


# Classes and Objects in python
python is a object oriented program
```
class Myclass:
    x=5

p1=Myclass()
print(p1.x)
```
init function allows initialization of different value in class.
```
class Person:
    def __init__(self,name,age):
        self.name=name
        self.age=age

p1=Person('John',22)
print("name is",p1.name,'age is',p1.age)
```
for deleting initialized value
del p1.age()

# Inheritance in pythonn
from new import student

class Person(student):
    pass

p1=Person()
print(p1.name)

# Modules in python
using function in another file in current one

# Pip
for installing external modules from WEB.