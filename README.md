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

### Aim: To develop a python program to remove the two string values from the rear end  


### Algorithm:

1.Start

2.Read an integer n (number of strings).

3.Initialize an empty deque q.

4.For n times, read a string and append it to q.

5.Remove two elements from the rear of q using pop() (if q is not empty).

6.Print the resulting deque.

7.End


### Program:
### Name:Harinishri S
### Rrg No:212223090008
```
from collections import deque
q=deque()
n=int(input())
for i in range(n):
    q.append(input())
for i in range(2):
    q.popleft()
print(q)    
```
### Output:
![image](https://github.com/user-attachments/assets/6bb8a0dc-a0ac-416b-ae9d-7580a0093c33)

 
### Result: Thus, the given program is implemented and executed successfully .


### EX: 10.4 Types of queue

### Aim: To Develop a python program to display the student details based on rank order (ascending order)

### Algorithm:

1.Start

2.Read an integer n (number of entries).

3.Initialize an empty list l.

4.Repeat n times:

5.Read a string x (in format "item1,item2").

6.Split x by comma into two parts.

7.Append the tuple (item1, item2) to list l.

8.Sort the list l.

9.Print each tuple from the sorted list.

10.End

### Program:
### Name:Harinishri S
### Reg No:212223090008
```
n=int(input())
l=[]
for i in range(n):
    x=input()
    ab=x.split(",")
    l.append((ab[0],ab[1]))
l.sort()    
for i in l:
    print(i)
```
### Output:
 ![image](https://github.com/user-attachments/assets/75ec3413-c09a-4dd0-83e2-3e217730fb68)

 

### Result: Thus, the given program is implemented and executed successfully .
 

