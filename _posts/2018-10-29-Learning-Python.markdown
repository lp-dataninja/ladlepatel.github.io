---
title: "Learning Python - Getting Started | Blog"
layout: post
date: 2018-10-29 22:44
tag:
- python
- programming
category: blog
author: Ladle Patel
description: Markdown summary with different options
---

HELLO WORLD PROGRAM.
print ‘Hello World!’

CREATE SOME VARIABLES IN PYTHON
i = 4 int

type(i)

f = 4.1 float

type(f)

b = True boolean variable

s = “This is a string!”

print s

my_list = []
list of integers
my_list = [1, 2, 3]
print my_list
for i in my_list:
addition = i+i
print addition

list with mixed datatypes
my_list = [1, “Hello”, 3.4]
print my_list

my_list = [“mouse”, [8, 4, 6], [‘a’]]
print my_list

my_list = [‘p’,’r’,’o’,’b’,’e’]

print(my_list[0])
print(my_list[2])

empty set()
a = set()

set of integers
my_set = {1, 2, 3}
print(my_set)

for s in my_set:
print s

set of mixed datatypes
my_set = {1.0, “Hello”, (1, 2, 3)}
print(my_set)

set do not have duplicates
Output: {1, 2, 3, 4}
my_set = {1,2,3,4,3,2}
print(my_set)

empty dictionary
my_dict = {}
dictionary with integer keys
my_dict = {1: ‘apple’, 2: ‘ball’}
for key, value in my_dict.iteritems():
print “key =”,key,”value =”,value

dictionary with mixed keys
my_dict = {‘name’: ‘John’, 1: [2, 4, 3]}
print my_dict

num = 3
if num > 0:
print(num, “is a positive number.”)

num = -1
if num > 0:
print(num, “is a positive number.”)

num = -5
num = 0
if num >= 0:
print(“Positive or Zero”)
else:
print(“Negative number”)

if num > 0:
print(“Positive number”)
elif num == 0:
print(“Zero”)
else:
print(“Negative number”)
def addition(x):
y = x + 2
return y
i = 5
addition(i)

square = lambda x: x*x
square(2)

class Arithmetic_operations:

def addition(self,a,b):
print ‘additon method’,a+b

def sub(self,a,b):
print ‘sub method’,a-b

obj1 =Arithmetic_operations()
obj1.addition(10,20)
obj1.sub(40,20)
