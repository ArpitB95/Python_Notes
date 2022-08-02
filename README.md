# Data types & operators
## 2 types operators

## Arithmetic operators
#- '+ - * /'
#- '+' adds two operands (var) together
#- '-' substract
#- '*' multiply
#- '/' divide


## Comparison operators
#- '>' greater than

#- '<' less than

#- '==' equal to

#- '!=' not equal to

#- '>=' greater and equal

#- '<=' less and equal

````
a= 4
b= 2
print(a>b) #true
print(a<b) # false
print(a==b) #true
print(a != b) #true

print(a+b) #6
````

# Functions methods builtin python

### what options are available in python's builtin library
- greeting = "Hello world"
- print(greeting)

## if we need to check if the letters are in string

- print(greeting.isalpha()) #true or false

### Is it in lower case or upper case
- print(greeting.islower())    #boolean
- print(greeting.isdigit())    #boolean
- print(greeting.endswith("!"))    #boolean
- print(greeting.startswith("H"))   #boolean and case sensitive


# String Concatenation Casting

##string indexing
 'Hello world!'
 index in python starts with 0 

- hello world!
- 0123456789101112 (h is 0, e is 1, l is 2 ...)

- greeting= "Hello World"
        - 01234567891011
        -             -1 (d is -1, reverse starts with -1)
-print(len(greeting))
-print(greeting[-5]) # output o
-print(greeting[:5]) # output hello

##print only world in a print statement using slicing
- print 4th letter from left to right
- print 7 letter from right to left
- print 6 letter from left to right


- greetings = "Hello World!"

- print(greetings[0])
#
## strip() is used to remove spaces
````
example_string = "James       "
print(example_string)
print(len(example_string))
print(len(example_string.strip()))
````
#
#
## - welcome user with their name and welcome message - name & message must start with capital
#
- example_text = "here's some text with lot's of text"
- print(example_text.count("text"))
#
## find a method to bring the statement in capital letter
#
- print(example_text.capitalize())
- print(example_text.islower())  # to find if statement is in lower case
#
## how to replace text within the string
- print(example_text.replace("with ", "t "))   # replace() is used to replace characters


# concatenation & casting
## You can concatenation (join) strings together but you can not join string and integer,for that you need to convert integer into string
````
first_name = "James"
mid_name = "Bond"
last_name = "007"
age = 47
address= 33


 

print(first_name + " " + mid_name + " " +  last_name + " " + str(age))
````

 # select all lines that you want to comment and then press control plus /

# DOR (Definition of Ready)
- It is a set of agreements that tells you when something is ready to begin. More correctly, “if something is good to begin”. E.g., when a user story is ready to be taken into a sprint, or when all the conditions are right for a team to begin a sprint.

# DOD (Definition of Done)
-  The Definition of Done is an agreed-upon set of items that must be completed before a project or user story can be considered complete


# Data collections
## Lists, Tuples & Dictionary

### Lists
 - What are lists ?
 - correct syntax for list is []
 - Lists are mutable (they can be changed)
 - Indexing same concept applies

- shopping_list = ["bat", "milk", "bread"]
-    indexing        0        1        2  (Here 0 =bat, 1 = milk and 2 = bread)

  print(shopping_list)

- Find out the type of shopping list
  print(type(shopping_list))  # output would be class list

- Find out the len of shopping list
  print(len(shopping_list)) # to find the length of the list

- How to add an item to shopping list 
  ```
  shopping_list.append("oreos")  # append() adds an item at the end of the list
  print(shopping_list)
  ```
  
-  How to delete an item from our shopping list
   ```
   shopping_list.remove("milk")   # remove() removes the item given
   print(shopping_list)
   ```
   
### Find out how to replace an item from the list and replace bat with milk

- mixed_list = [1,2,3,"one","two","three"]  (Indexing : 0,1,2,3,4,5)
              
               
  print(mixed_list)

- print 2 & 3 from the above list

- print(mixed_list[1])   # output would be 2
 
- print(mixed_list[3])   # output would be one

- print(mixed_list[1:3])  # outcome would be 2,3
