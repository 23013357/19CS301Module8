# 19CS301Module8
EXPTNO.8a Program to find Find the time.

### Aim: To Write a python program to find the time taken to cross an electric pole? [Distance = speed*time]
### Algorithm:

STEP 1: Start.

STEP 2:Assign the value 75 to the variable dis.

STEP 3:Multiply 54 by (5 / 18) and store the result in speed.

STEP 4: time = dis / speed

STEP 5: Print the value of time.

STEP 6: Stop.

### Program:
```
dis=75
speed=54*(5/18)
print(dis/speed)
```
### Output:
![image](https://github.com/23013357/19CS301Module8/blob/main/nn.png)





### Result: Thus, the given program is implemented and executed successfully .

EXPTNo.8b program to  print the numbers in reverse order.

### Aim: To Write a python program to  print the numbers in reverse order
### Algorithm:

STEP 1: Start.

STEP 2: Get the input of a from user.

STEP 3: Using while loop .

STEP 4: get the unit digit.

STEP 5:print modulo 10

STEP 6: Stop.

### Program:
```
n=int(input())
while(n>0):
    print(n%10,end="")
    n=n//10
```
### Output:
![image](https://github.com/23013357/19CS301Module8/blob/main/mm.png)

### Result: Thus, the given program is implemented and executed successfully .
 

EXPT NO 8C To Write a python program to Given the participants'	score sheet for your University Sports Day, you are required to find the runner-up score
### Aim: To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them 
         in a list and find the score of the runner-up.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```if  name	== '   main    ':
          n = int(input())
          arr = map(int, input().split())
          arr2 = list(set(arr))
          arr2.sort()
print(arr2[-2])

### Output:
 
![image](https://github.com/user-attachments/assets/032939c0-f500-4bbb-9b19-87b3c54d8454)

 

### Result: Thus, the given program is implemented and executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
     l1=[]
     for i in range(f,l+1):
           l1.append(i)
      return l1
f,l = int(input()),int(input())

```
### Output:
![image](https://github.com/user-attachments/assets/4a9076d8-a2cf-44e1-b7d1-e638b7edf12f)



### Result: Thus, the given program is implemented and executed successfully .
 


