# iNeuron-FSDS-Assignment2
1.What are the two values of the Boolean data type? How do you write them?

Ans: It has two possible values: true and false. Bool is not interchangeable with Int and must be converted explicitly if needed.


2. What are the three different types of Boolean operators?

Ans: AND, OR and NOT


3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ).

Ans: 
== Truth Table:

True	==	True	True
True	==	False	False
False	==	True	False
False	==	False	True

AND Truth Table:

True	and	True	True
True	and	False	False
False	and	True	False
False	and	False	False

OR Truth Table:

True	or	True	True
True	or	False	True
False	or	True	True
False	or	False	False

NOT Truth Table:

not	True	False
not	False	True


4. What are the values of the following expressions?

Ans:
(5 > 4) and (3 == 5)  Output: False
not (5 > 4)  Output: False
(5 > 4) or (3 == 5)  Output: True
not ((5 > 4) or (3 == 5))  Output: False
(True and True) and (True == False) Output: False
(not False) or (not True)   Output: True


5. What are the six comparison operators?

Ans : equal to, not equal to, greater than, greater than or equal to, less than, and less than or equal to


6. How do you tell the difference between the equal to and assignment operators? Describe a condition and when you would use one.

Ans: The “=” is an assignment operator is used to assign the value on the right to the variable on the left. The '==' operator checks whether the two given operands are equal or not. If so, it returns true


7. Identify the three blocks in this code:
spam = 0
if spam == 10:
print('eggs')
if spam > 5:
print('bacon')
else:
print('ham')
print('spam')
print('spam')

Ans:
Ham
Spam
spam


8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.

Ans: 
spam=3
if spam==1:
print(“Hello”)
if spam==2:
	print(“Howdy”)
else:
	print(“Greetings!”)


9.If your programme is stuck in an endless loop, what keys you’ll press?

Ans: Ctrl+C


10. How can you tell the difference between break and continue?

Ans: 
Break-The Python break statement stops the loop in which the statement is placed
Continue -A Python continue statement skips a single iteration in a loop.


11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?

Ans: All three will give same output as 0,1,2,3,4,5,6,7,8,9


12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.

Ans:
for i in range(1,11):
    print(i)

i=1
while i<=10:
    print(i)
    i+=1


13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?

Ans: We can use the functions inside a module by using a dot(.) operator along with the module name.
