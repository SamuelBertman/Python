print() = computer states what in ()

VARIABLE
Message_string = store of info e.g. "hello world!"
# so now we can use that message string in other code e.g. print(message_string)
# message_string can be anythign e.g. meal = "lunch" (message_string is meal)
Meal = store of info e.g. "hellow world!"

# Syntax error - written wrong code
# Name error - does not recognise word e.g. printe("")

int = integer  e.g. 2
float = decimal point  e.g. 2.5

an_int = 2
a_float = 2.5
print(an_int + 2) - with int/float, no quotation marks needed 

# ** = to the power of (indicies) e.g. 2 ** 10 = 2 to the power of 10

# % gives only the remainder of the calculation e.g. 5 / 2 = 2.5 but 5 % 2 = 5 cause 5 is the remainder

# strings can be added e.g. full_text = first_text + second_text 
# If want to add a number to added strings, str(), e.g. 
string1 = str(2)
string2 = " I am"
message = string1 + string2
print(message) = 2 I am

# adding to a current set variable is done via += e.g.
miles = 2
miles += 2
print(miles) = 4
# if the value being added to miles is a separate varialbe you can replace the number with it e.g.
miles += kilometers 

# when code goes across 2 or more lines, """ triple are used to signal that until another """, it should not stop reading the code e.g.
"""hello world my name is ... and I am  up to
many things including"""

for user input, we use input() e.g.
likes_snakes = input("do you like snakes?")

# Boolean expressions are statements with a true or false answer
1 == 1 results in a true
1 != 1 results in a false
1 == 2 results in a false
1 != 2 results in a true
'1' == 1 results in a false (different formats)
first_expression = True/False

if ... == ... : 
print(....)
# conditional statement, colon needed after if statement, the == means if this what is stated is equal is true then do such action

> greater than
>= greater than or equal to
< less than
<= less than or equal to
# can be used in if statements e.g.
if temperature >= 30
  print("...")

# in if statements, and can be used to connect statemenets e.g.
if ... and ... : 
# or can also be used in if statements, and, or, not
if not .... - is how it is used

# else is used in conjunction to if statements
if .... :
print("yes")
else:
print("no")

# elif is used in conjunction to if statements
if x < 500 :
print("gold")
elif x < 100
print("silver")
elif x < 50
print("bronze")

listing is done via [] square brackets
numbers = [1, 2, "three"]

# you can remove from a list via remove e.g.
list = [1, 2, 3]
list.remove(1)
print(list) = [2, 3]

# you can add to the end of a list via append e.g.
list = [1, 2, 3]
list.append(1)
print(list) = [1, 2, 3, 1]

# in a list, all things have an index number starting at 0
print(x[3]) will print the 4th item in the list

# square brackets link to index number of a list so you can assign a variable to a list item
employee_four = employees[3]

# to access the last item in a list with ease you can use [-1]

# you can change any word in a list using []
garden = [1, 2, 3]
garden[1] = "strawberry"
print(garden) = [1, "strawberry", 3]
# works with negative indices 

# [2][1] = 3rd in the list, 2nd item

variable.insert(2, "") 
# .insert inserts a new item into a list with the number stating where in the list

removed_element = variable.pop(2)
print(removed_element) 
2
# .pop removes an element from a list and can be attatched to a variable e.g. removed_element, to then be printed separately

# range() when printed print(range) will give the range, then if print(list(range)) that will print all numbers within the range, 
- HOWEVER, the integer in the range will not be in the list e.g. 
range(3) = [0, 1, 2]
# range can start from different number via range(2, 8) comma, the 1st number will be in the range, the last will not
# sequence can be made via range(2,8) and then adding a 3rd integer range(2, 8, 2) which will in this case will be 2 greater than the last in the sequence between the range

# print(len(list)), len will state the number of integers within the list

# a set of elements in a range can be selected and put on a variable via colon e.g.
start = variable[:] 
