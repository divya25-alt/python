# python
 1: Check if a Number is Positive and Negative in Python
num = 12
if num > 0
print('positive')
elif num < 0
print('negative')
else:
print('zero')
2: check the given number is even or odd
num = int(input("Enter a number: "))
 if num % 2 ==0:
print( "is even")
else
print( "is odd")
3:Sum of The First N Natural Numbers in Python
num = 15
sum = 0
for i range (num+1):
sum +=i
print('sum")
4:Sum of the Numbers in a Given Interval in Python 
num1 , num 2, =3,6
sum = 0
for i in range (num1, num2+1):
sum += i
print(num1, num2)
5: Greatest of the Two Numbers in Python
num1 = 2
num2 = 3
if num1 > num2:
print(num1)
else:
print(num2)
6:Sum of N Natural Numbers
num, sum = 6,0
for i in range(num+1)
sum += i
print(sum)
7:Greatest of the Three Numbers in Python 
num1 = 10
num2 = 20
num3 = 30
max = 0
if num1>=num2 and num1>=num3:
elif
num2>=num1 and num2>=num3:
else:
print(max)
8:Whether a Year is a Leap Year or Not
year = 4000
if year%400==0:
print(leap year)
else:
print(not leap year)
9:Find the sum of the Digits of a Number
num = input("Enter a num")
sum = 0
for i in num:
sum = sum + int(i)
print(sum)
10:Reverse of a Number in Python 
num = int(input("Enter a num")
rev = 0
while(n>0):
r = n % 10
rev = rer * 10 + r
n = n // 10
print("revese number: " , rev)
11:Whether a Number is a Prime or Not
count = 0
n = int(input("Enter a number"))
for i in range(1,n+1):
if n % i == 0
count+=1
if count == 2:
print("prime")
else:
print("not prime")
12:Perfect Number in Python
num = int(input("Enter a num")
sum=0
for i in range(1,(n/2)+1):
if(n%i==0)
sum=sum+i
if(sum==num)
print("perfect number")
else:
print("not perfect number")
14:Check for Perfect Square in Python
num = int(input("Enter a num")
flag=0
for i in range(1,n)
if i*i=n
flag=1
break
if flag==1
print("perfectsquare number")
else
print("notperfectsquare  number")
15:Reverse a Number in Python
n= int(input("Enter a num"))
rev=0
while n>0
r=n%10
rev=rev*10+r
n=n//10
print("reverse of n is ",n)
16:palindrome number
n = int(input("Enter a num"))
pal=num
rev=0
while n>0
r=n%10
rev=rev*10+r
n=n//10
if(pal==rev)
print("palindrome number")
else:
print("not palindrome number")
17: Given Number is an Armstrong Number or Not
n = int(input("Enter a num"))
x=len(str(n))
temp=num
sum=0
while n>0
r=n%10
sum=sum+r**x
n=n//10
if(temp==sum)
print("armstrong number")
else:
print("notarmstrong number")
18:Armstrong Numbers in a given Range in Python
for i in range(1,501)
temp=num
sum=0
while n>0
r=n%10
sum=sum+r**x
n=n//10
if(temp==sum)
print("armstrong number")
else:
print("notarmstrong number")
19:Fibonacci Series in Python
n = int(input("Enter a num"))
f1=0
f2=1
print(f1,end'')
print(f2,end'')
f3=f1+f2
while(f3<=n)
print(f3,end'')
f1=f2
f2=f3
f3=f1+f2
20:Factorial of a Number in Python
n = int(input("Enter a num"))
fact=1
for i in range(1,n+1)
fact=fact*i
print("factorial of n is",fact)
21:power of number
base=4
exponent=5
result=1
while exponent!=0
result=result*base
exponent-=1
print("result:",result)
22:factor of number
n = int(input("Enter a num"))
for i in range(1,n+1)
if(n%i==0)
print(i)
23:prime factor of number
n = int(input("Enter a num"))
for i in range(1,n+1):
if(n%i==0):
count=0
for j in range(1,i+1)
if(i%j==0):
count+=1
if(count==2):
print(i)
24:Check Whether or Not the Number is a Strong Number
n = int(input("Enter a num"))
strong=n
sum=0
while n>0
r=n%10
f=1
for i in range(1,n+1)
fact=fact*i
sum=sum+fact
n=n//10
if(strong==num):
print("strong number")
else:
print("not strong number")
25:Automorphic number using Python
n = int(input("Enter a num"))
square=n*n
ifstr(square).endswith(str(n))
print("Automorphic number")
else:
print("not Automorphic number")
26:Checking Whether the Number is Harshad or not 
n = int(input("Enter a num"))
x=n
sum=0
while n>0:
r=n%10
sum=sum+r
n=n//10
if(n%sum==0):
print("Harsad number")
else:
printprint("not Harsad number")
27:Program to check Abundant Number
def



























