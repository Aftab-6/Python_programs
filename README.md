# Python_programs

#OPERATORS PROGRAMS USING PYTHON

1.Write a python program to get 2 numbers from the user and calculate their sum and difference using '+' and '-' operators respectively. Print the corresponding sum and difference of the numbers as output in the console.

code:

a=int(input())

b=int(input())

print(a+b)

print(a-b)

2.Write a python program to get 2 numbers from the user and calculate their product, quotient and remainder using '*', '/' and '%' operators respectively. Print the corresponding product, quotient and remainder of the numbers as output in the console. 

code:

a=int(input())

b=int(input())

print(a*b)

print(a//b)

print(a%b)

3.Write a python program to get 2 numbers from the user and swap their values without any loss of data. You can make use of additional 3rdvariable for swapping. Print the corresponding swapped values of the two numbers as output in the console. 

code:

a=int(input())

b=int(input())

temp=a

a=b

b=temp

print(a)

print(b)

4.Write a python program to swap two values without the use of 3rd variable. 

code:

a=int(input())

b=int(input())

a=a+b

b=a-b

a=a-b
print(a)

print(b)

5.A teacher wants to compute the average of 5 students in her class. Write a program to help her to find the average. The average is the sum of all the numbers, then divided by the total numbers. 

code:

a=float(input())

b=float(input())

c=float(input())

d=float(input())

e=float(input())

res=(a+b+c+d+e)/5

print(res)

6.Alice was bored that day,so she was sitting on the riverbank .Suddenly she notices a talking, White Rabbit with a pocket watch .It ran fast,and she followed it, down a rabbit hole .She fell into the hole and found a magical wonderland with dark trees, beautiful flowers.She found many ways numbered from 1,2,3,........18.she was confused which is the right way that will lead her to her home. She found a cute bird, standing in one of the tree. Alice asked the bird the way to go back to her home.The bird said a two digit number( say 23 ) and asked her to find the sum of its digits (2+3=5) and that numbered way will lead her to her home.Alice was already confused, so pls help Alice in finding the route to her home.... 

code:

n=int(input("Enter any integer:"))

sum=0

i=0

while n!=0:

    sum=sum+n%10
    
    n=n//10
    
print(sum)

7.Sheela has three things in her bag. She wants to compute the area of 3 things but 3 things are in different shapes. The three things are in square shape, rectangular shape, and circular shape respectively. Write a program to help Sheela to calculate the area of different shapes. 

code:

a=int(input())

b=int(input())


c=int(input())

e=float(input())

print(a*a)

print(b*c)

f=3.14*e*e

print('%.2f'%f)

8.The college ground is rectangular in shape. The Management decides to build a fence around the ground. In order to help the construction workers to build a straight fence, they planned to place a thick rope around the ground. They wanted to buy only the exact length of the rope that is needed. They also wanted to cover the entire ground with a thick carpet during rainy season. They wanted to buy only the exact quantity of carpet that is needed. They requested your help. Can you please help them by writing a program to find the exact length of the rope and the exact quantity of carper that is required? 

code:

a=int(input())

b=int(input())

print('Required length is %d m'%(2*(a+b)))

print('Required quantity of carpet is %d sqm'%(a*b))

9.pow() function is used to calculate the power of any base and it is defined in math header file. Write a program to read X as the base and N as the power and calculate the result (X^N - X to the power of N)

code:

a=int(input())

b=int(input())

c=a**b

print(c)

10.Sara wished to build a new house but she didn't have a sufficient amount. So, she is planning to borrow some money from the bank on simple interest. When she is borrowing some money from the bank, she has to pay back the original amount accompanied by a certain amount of interest on that amount. She wants to find the interest for borrowed money within a certain period. Help her to find the simple interest. 

code:

a=int(input())

b=int(input())

c=float(input())

d=(a*b*c)/100

print('%.2f'%d)

11.During the Physical Education hour, PET sir has decided to conduct some team games. He wants to split the students in the class into equal sized teams. In some cases, there may be some students who are left out from teams and he wanted to use the left out students to assist him in conducting the team games. For instance, if there are 50 students in the class and if the class has to be divided into 7 equal sized teams, 7 students will be there in each team and 1 student will be left out. PET sir asks your help to automate this team splitting task. Can you please help him out? 

code:

a=int(input())

b=int(input())

print("The number of students in each team is ",a//b,"and left out is ",a%b)

12.Ajay, Binoy and Chandru were very close friends at school. They were very good in Mathematics and they were the pet students of Emily Mam. Their gang was known as 3-idiots. Ajay, Binoy and Chandru live in the same locality. A new student Dinesh joins their class and he wanted to be friends with them. He asked Binoy about his house address. Binoy wanted to test Dinesh's mathematical skills. Binoy told Dinesh that his house is at the midpoint of the line joining Ajay's house and Chandru's house. Dinesh was puzzled. Can you help Dinesh out? Given the coordinates of the 2 end points of a line (x1,y1) and (x2,y2), write a python program to find the midpoint of the line. 

code:

x1=int(input())

y1=int(input())

x2=int(input())

y2=int(input())

c=(x1+x2)/2

d=(y1+y2)/2

print("Binoy's house is located at"+'('+str(c)+','+str(d)+')')





