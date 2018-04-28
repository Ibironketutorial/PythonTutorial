Python 3.6.5 (v3.6.5:f59c0932b4, Mar 28 2018, 16:07:46) [MSC v.1900 32 bit (Intel)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> print
<built-in function print>
>>> print('welcome')
welcome
>>> print 'welcome'
SyntaxError: Missing parentheses in call to 'print'. Did you mean print('welcome')?
>>> print('Algorithm and Data Structure')
Algorithm and Data Structure
>>> type(2)
<class 'int'>
>>> type(2.3)
<class 'float'>
>>> type(true)
Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    type(true)
NameError: name 'true' is not defined
>>> type(True)
<class 'bool'>
>>> type('a')
<class 'str'>
>>> number =2
>>> rea=2.2
>>> word="word"
>>> print(word)
word
>>> type(word)
<class 'str'>
>>> a=b=c=1.5
>>> print a
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(a)?
>>> print(a)
1.5
>>> print (b)
1.5
>>> print (c)
1.5
>>> one, two, three = 1, 'two', 3.0
>>> print (one)
1
>>> print (two)
two
>>> print (three)
3.0
>>> number = 1
>>> str = 'string'
>>> number = str
>>> print (number)
string
>>> import keyword
>>> keyword.kwlists
Traceback (most recent call last):
  File "<pyshell#28>", line 1, in <module>
    keyword.kwlists
AttributeError: module 'keyword' has no attribute 'kwlists'
>>> keyword.kwlist
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
>>> def test():
	statement1
	statement2
	statement3

	
>>> 
>>> def test2():
	statement4
	statement5
	statement6

	
>>> import os
>>> clear=lambda:os
>>> clear
