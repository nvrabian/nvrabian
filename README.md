# Objects-and-Data-Structures-Assessment-Test

Content Copyright by Pierian Data
# Objects and Data Structures Assessment Test
Test your knowledge.
** Answer the following questions **

Write (or just say out loud to yourself) a brief description of all the following Object Types and Data Structures we've learned about. You can edit the cell below by double clicking on it. Really this is just to test if you know the difference between these, so feel free to just think about it, since your answers are self-graded.

Double Click HERE to edit this markdown cell and write answers.

Numbers: any vlaue consisted of integers or float assigned to variables withou quotation marks

Strings: any vlaue consisted of any character, also numbers, and is assigned with quotation marks

Lists: list of values seperated by commas and put in square brackets. it is also mutable.

Tuples: list of vlues seperated by commas and put in parentheses. it is immutable.

Dictionaries: pair of key:vlaue each key must be unique and pairs are seperated by commas. all pairs are put in curly braces.

Numbers
Write an equation that uses multiplication, division, an exponent, addition, and subtraction that is equal to 100.25.

Hint: This is just to test your memory of the basic arithmetic commands, work backwards from 100.25

((50+50)*(5-1)+1)/(2**2)
100.25
Answer these 3 questions without typing code. Then type code to check your answer.

What is the value of the expression 4 * (6 + 5) = 44

What is the value of the expression 4 * 6 + 5 = 29

What is the value of the expression 4 + 6 * 5 = 34
4 * (6 + 5)
44
4 * 6 + 5
29
4 + 6 * 5
34
What is the type of the result of the expression 3 + 1.5 + 4?

float

What would you use to find a number’s square root, as well as its square?

# Square root:
** 0.5
# Square:
** 2
Strings
Given the string 'hello' give an index command that returns 'e'. Enter your code in the cell below:

s = 'hello'
# Print out 'e' using indexing
print(s[1])
​
e
Reverse the string 'hello' using slicing:

s ='hello'
# Reverse the string using slicing
print(s[::-1])
​
​
olleh
Given the string hello, give two methods of producing the letter 'o' using indexing.

s ='hello'
# Print out the 'o'
​
# Method 1:
print(s[len(s)-1])
​
o
# Method 2:
print(s[-1])
​
o
Lists
Build this list [0,0,0] two separate ways.

# Method 1:
list1 = [0,0,0]
list1
[0, 0, 0]
# Method 2:
[0]*3
[0, 0, 0]
Reassign 'hello' in this nested list to say 'goodbye' instead:

list3 = [1,2,[3,4,'hello']]
list3[2][2]= "goodbye"
Sort the list below:

list4 = [5,3,4,6,1]
list4.sort()
Dictionaries
Using keys and indexing, grab the 'hello' from the following dictionaries:

d = {'simple_key':'hello'}
# Grab 'hello'
d["simple_key"]
'hello'
d = {'k1':{'k2':'hello'}}
# Grab 'hello'
d["k1"]["k2"]
'hello'
# Getting a little tricker
d = {'k1':[{'nest_key':['this is deep',['hello']]}]}
​
#Grab hello
d["k1"][0]["nest_key"][1][0]
'hello'
# This will be hard and annoying!
d = {'k1':[1,2,{'k2':['this is tricky',{'tough':[1,2,['hello']]}]}]}
d["k1"][2]["k2"][1]["tough"][2][0]
'hello'
Can you sort a dictionary? Why or why not?

sorting a dictionary is not possible because the is no function sort() for dictionaries. Maybe will be learned later in course :)

Tuples
What is the major difference between tuples and lists?

lists are mutable and tuples are immutable.

How do you create a tuple?

with parentheses.

Sets
What is unique about a set?

each item in a set can be found only one time, and tere are no duplicate items

Use a set to find the unique values of the list below:

list5 = [1,2,2,33,4,4,11,22,3,3,2]
set(list5)
{1, 2, 3, 4, 11, 22, 33}
Booleans
For the following quiz questions, we will get a preview of comparison operators. In the table below, a=3 and b=4.

Operator	Description	Example
==	If the values of two operands are equal, then the condition becomes true.	(a == b) is not true.
!=	If values of two operands are not equal, then condition becomes true.	(a != b) is true.
>	If the value of left operand is greater than the value of right operand, then condition becomes true.	(a > b) is not true.
<	If the value of left operand is less than the value of right operand, then condition becomes true.	(a < b) is true.
>=	If the value of left operand is greater than or equal to the value of right operand, then condition becomes true.	(a >= b) is not true.
<=	If the value of left operand is less than or equal to the value of right operand, then condition becomes true.	(a <= b) is true.
What will be the resulting Boolean of the following pieces of code (answer fist then check by typing it in!)

# Answer before running cell
2 > 3 = False



# Answer before running cell
3 <= 2 = False


# Answer before running cell
3 == 2.0 = False



# Answer before running cell
3.0 == 3 = True
  File "<ipython-input-17-d1af65b61866>", line 2
    3.0 == 3 = True
    ^
SyntaxError: cannot assign to comparison


# Answer before running cell
4**0.5 != 2 = False
  File "<ipython-input-18-5294bf1d4732>", line 2
    4**0.5 != 2 = False
    ^
SyntaxError: cannot assign to comparison


Final Question: What is the boolean output of the cell block below?

# two nested lists
l_one = [1,2,[3,4]]
l_two = [1,2,{'k1':4}]
​
# True or False?
l_one[2][0] >= l_two[2]['k1']
​
​
False
Great Job on your first assessment!¶
