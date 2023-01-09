# Assignment-Python-1
# Q1. Why do we call Python as a general purpose and high-level programming language?
# - Python can be used in many tech stacks like web development, AI/ML etc that is why it is known as general
#   purpose. Also, it is very easy to read and understand by human so its a high level programming. As machines
#   can understand low level prgramming i.e 0 and 1

# # Q2. Why is Python called a dynamically typed language?
#  - As python determined the datatypes of the variables by its own hence it is known as dynamically typed language.
#    Since, its a best practice to check the datatype of the variable by using type()

# # Q3. List some pros and cons of Python programming language?
# - Pros are - its very easy to learn and understand the language as its uses simple engish sentence
#   Cons - it is very slow as compare to other programming language like java and C++ as python uses interpretor
#   to convert high level language to combinations of 0 and 1

# Q4. In what all domains can we use Python?
# - Web development, Automation, AI/ML, Deep learning, Data analysis, Data visualisation

# Q5. What are variable and how can we declare them?
# - Variable is like a storage container that contains data and store in a particular allocated memory location

#Q6. How can we take an input from the user in Python?
# - We can take input from user by calling input() inbuit function. For ex - 
# UserName = input('Enter your Username')
# print('Your user name is '+ UserName)

#Q7. What is the default datatype of the value that has been taken as an input using input() function?
# - String

#Q8. What is type casting?
# - Whenever we want to change the datatype of any particular variable we use type casting
# for ex - Phone_Number = '1234567890'
#          print('Your Phone number is '+ int(Phone_Number))
# in above example i had converted string to int by using Int() typecasting to change its datatype

# Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
# Using split() function we can take two inputs at a time for ex - 
# Name, Surname = input('Enter your name and surname').split()
# print('Your name is '+Name,'Your surname is '+Surname)

# Q10. What are keywords?
# - Keywords are built in reserved words for ex- print() we can use to for only printing outputs, we cannot use 
# for any other purpose

# Q11. Can we use keywords as a variable? Support your answer with reason.
# - We cannot use keyword as variable as they predefined for their function except true and false in lowercase

# Q12. What is indentation? What's the use of indentaion in Python?
# indentation is a structure of writing code in python, Python identifies the block of code to execute with the help of indentation
# we use tab to give indentation equivalent to 4 spaces

# Q13. How can we throw some output in Python?
# - using print() function we can print output in the console

# Q14. What are operators in Python?
# - if we want perform any mathematical function in the code we use operators like +,-,%,*,**,/,//

# Q15. What is difference between / and // operators?
# - '/' return value with float and '//' returns integer value only

# Q16. Write a code that gives following as an output.
# ```
# iNeuroniNeuroniNeuroniNeuron
# ```
# a = 'INeuron'
# print(a * 4)

# Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
# a = input('Enter a number to check the number is odd or even')
# if int(a)%2 == 0:
#     print('The number is even')
# else:
#     print('Then number is odd')

# Q18. What are boolean operator?
# Boolean operators are simple words like and , or, not

# Q19. What will the output of the following?
# ```
# 1 or 0
# 1
# 0 and 0
# 0
# True and False and True
# False
# 1 or 0 or 0
# 1
# ```

# Q20. What are conditional statements in Python?
# - Conditional Statements is a decision make statements like if statements is true then return true else false..

# Q21. What is use of 'if', 'elif' and 'else' keywords?
# - We use to match conditions in if,elif keywords. if any condition matches then return the statement, else print else block 


# Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

# a = int( input('Enter your Age') )
# age = 18

# if a>=age:
#     print('I can vote')
# else:
#     print("I can't vote")


# Q23. Write a code that displays the sum of all the even numbers from the given list.
# ```
# numbers = [12, 75, 150, 180, 145, 525, 50]
# ```

# numbers = [12, 75, 150, 180, 145, 525, 50]
# a = 0
# for b in numbers:
#     if b%2 == 0:
#         print('even number is',a)
#         a += b
# print(a) 


# Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

# a = input('Enter the first number')
# b = input('Enter the second number')
# c = input('Enter the third number')

# if a>b and a>c:
#     print('a is greater',a)
# elif b>a and b>c:
#     print('b is greater',b)
# elif c>a and c>b:
#     print('c is greater',c)

# Q25. Write a program to display only those numbers from a list that satisfy the following conditions

# - The number must be divisible by five

# - If the number is greater than 150, then skip it and move to the next number

# - If the number is greater than 500, then stop the loop
# ```
# numbers = [12, 75, 150, 180, 145, 525, 50]
# ```

# numbers = [12, 75, 150, 180, 145, 525, 50]

# for a in numbers:
#     if a%5 == 0:
#         if a>150:
#             if a>=500:
#                 break
#             else:
#                 continue
#         print(a)
