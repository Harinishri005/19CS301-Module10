# 19CS301-Module10
###EX: 10.a  STACK
### Aim:Write a python program to get the integer values from the user and push only the even number into the stack and later pop the last 3 elements

### Algorithm:
1.Initialize an empty stack.

2.Repeat until the user enters 'done':

3.Take integer input from the user.

4.If the input is even, push it into the stack.

5.Display the current stack.

6.Initialize a counter to 0.

7.While the stack is not empty and the counter is less than 3:

8.Pop the top element from the stack.

9.Increment the counter.

10.Display the stack after popping the last 3 elements.

### Program:
### Name:Harinishri S
### Reg no:212223090008
```
L=[]
n=int(input())
for i in range(n):
    value=int(input())
    if value%2==0:
        L.append(value)
print(L)        
for i in range(3):
    L.pop()
print(L)    
    
```
### Output:
 ![image](https://github.com/user-attachments/assets/4cffe6e6-527a-4b54-bb2e-660972a9cba9)


### Result: Thus, the given program is implemented and executed successfully .
 


### EX: 10.2 IMPLEMENTATION OF STACK
### Aim: To Write a python program to implement the stack using deque method for rotating the stack.
### Algorithm:

STEP 1: Start.

STEP 2: Import collections and import deque.

STEP 3: Create a list and get the input from user.

STEP 4: Create a variable n and get number of inputs from user.

STEP 5 : Using a loop get the inputs from user and append in deque.

STEP 6: Using rotate function rotate the stack.

STEP 7 : Print the result. 

STEP 8 : Stop.
### Program: 
### Name:Harinishri S
### Reg No:212223090008
```
import collections
def fun(n):
   stack = collections.deque([])
   a=int(input())
   for i in range (a):
         x=stack.append(int(input()))
     print(f"Stack before rotation {stack}") stack.rotate(n)
print(f"Stack after rotation {stack}")
```
### Output:
![image](https://github.com/user-attachments/assets/f42c4ec6-578c-418a-8f66-cf70abe7dc54)

### Result: Thus, the given program is implemented and executed successfully .
 


EX: 10.3 QUEUE
### Aim: To Write a python program to implement the stack using deque method for rotating the stack.
### Algorithm:

STEP 1: Start.

STEP 2: Import collections and import deque.

STEP 3: Create a stack and a variable n.

STEP 4: Get the number of inputs from user.

STEP 5: Using a loop get the inputs from user.

STEP 6: Append the even and unique elements in the stack.

STEP 7: Print the result.
### Program:
```
import collections
stack = collections.deque([])
n = int(input())
for i in range(n):
       x = int(input())
        if x not in stack:
          if x%2==0:
             stack.appendleft(x)
print(stack)
```
### Output:
![image](https://github.com/user-attachments/assets/de6e3e09-b10b-42d4-9faf-32fcf990f29a)
 
### Result: Thus, the given program is implemented and executed successfully .


### EX: 10.4 IMPLEMENTATION OF QUEUE
### Aim: To Develop a python program to get the 4 integer values from user and display the values using multiprocessing library
### Algorithm:

STEP 1: Start.

STEP 2: From Multiprocessing Import Queue.

STEP 3: Create a list and get the input from user.

STEP 4 : Append the elements in the list.

STEP 5: Using 'get' built-in function print the list.

STEP 6 : Print the result.

STEP 7 : Stop.
### Program:
```
from multiprocessing import Queue
queue = Queue()
for i in range(4):
    queue.put(int(input()))
for i in range(4):
     print(queue.get())
```
### Output:
 ![image](https://github.com/user-attachments/assets/26a380ff-118e-43f4-8178-83a5417262b5)
 

### Result: Thus, the given program is implemented and executed successfully .
 

