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
27:Program to check friendly pairs
n1=int(input("enter first number:"))
n2=int(input("enter second number:"))
def sum_of_divisors(n):
total=0
for i in range(1,n+1):
   if(n%i==0):
   total=total+i
abudancy1=sum of divisors/n1
abudancy2=sum of divisors/n2
if abudancy1==abundancy2
print("friendly pairs")
else:
print("not friendly pairs")
28:Check Whether or Not the Number is an Abundant Number
def get_divisor_sum(n):
    total = 0
    for i in range(1, n):
        if n % i == 0:
            total += i
    return total
def are_friendly_pairs(a, b):
    sum1 = get_divisor_sum(a)
    sum2 = get_divisor_sum(b)
   return (sum1 / a) == (sum2 / b)
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
if are_friendly_pairs(num1, num2):
    print(f"{num1} and {num2} are Friendly Pairs.")
else:
    print(f"{num1} and {num2} are not Friendly Pairs.")
29:Python program to find HCF of Two Numbers
def computeHCF(x,y)
   smaller=0
if(x<y)
   smaller=x
  else:
  smaller=y
hcf=0
for i in range(1,n+1)
   if(x%i==0) and (y%i==0)
   hcf=i
   return hcf
 n1=12
 n2=14
 print("HCF of Two Numbers {} and {} is{}.format(n1,n2, computeHCF(n1,n2))
30:Find Largest element in an array 
arr=[4,8,2,7,16,9]
l=arr[0]
for i in range(1,len(arr))
if arr[i]>l
   l=arr[i]
   else:
   continue
print("largest is",l)
31:Find Smallest element in an array 
arr = [4, 8, 2, 7, 16, 9]
smallest = arr[0] 
for i in range(1, len(arr)):
    if arr[i] < smallest:
        smallest = arr[i]
print("Smallest element is", smallest)
32: Smallest and largest element in an array
arr=[4,8,2,7,16,9]
smallest = arr[0]
largest = arr[0] 
for i in range(1, len(arr)):
  if arr[i] < smallest:
        smallest = arr[i]
          if arr[i] <largest:
        largest = arr[i]
   print("Smallest element is" smallest)
   print("largest elsemnet is",largest)
 33:Find Second Smallest Element in an Array
   arr=[4,8,2,7,16,9]
   if len(arr)<2:
   print"Array must at least two numbers")
   for num in arr:
   if num<smallest:
   second_smalllest=smallest
   elif num<second_smallest and num!=smallest
   second_smalllest=num
   if second_smallest == float('inf'):
    print("No second smallest element found (all elements may be equal).")
    else:
    print("Second smallest element is:", second_smallest)
  34:Calculate the sum of elements in an array
   arr=[32,45,65,80,98]
    total=0
  for i in range(len(arr)):
    total=total+arr[i]
    print("total sum is",total)
 35:Python Code for Reverse an Array suing slicing
 arr=[12,3,5,8,9]
 reversed_arr=arr[::-1]
 print("original array:",arr)
  print("reversed array:",reversed_arr)
 36:Python Program to convert temperature from Celsius to Fahrenheit and Fahrenheit to Celsius.
 print("choose conversion:")
 print("1.celsius to fahrenheit")
 print("2.fahrenheit to celsius")
 choice=input("Enter 1 or 2:")
 if choice=='1':
    c=float(input("Enter temparature in Celsius"))
    f=(c*9/5)+32
    print("Temparature  in fahrenheit:",f)
 elif choice=='2':
   f=float(input("Enter temparature in fahrenheit"))
   c=(f-32)+5/9
   print("Temparature in celsius:",c)
 else:
   print("Invalid choice")
37 to check whether a character is vowel or consonant.
ch=input("Enter a single character:").lower()
if len(ch)==1 and ch.isalpha():
   if ch is 'aeiou'
     print(ch,"is vowel")
   else
     print(ch,"is constant")
 else:
     print("Enter a valid alphabet")
38:to check whether a character is vowel or consonant or special character.
ch=input("Enter a single character:").lower()
if len(ch)==1: 
    if ch.isalpha():
       if ch in 'aeiou':
          print(ch,"is vowel")
        else
          print(ch,"is consonant")
     else
       print(ch,"is special character")
else
       print(" please enter only one character") 
39:Python Program to print all alphabets from a to z using while loop
ch='a'
  while ch<='z':
      print(ch,end='')
      ch=ch(ord(chr)+1))
40:Python Program to print all uppercase alphabets using while loop.
ch='A'
  while ch<='Z':
      print(ch,end='')
      ch=ch(ord(chr)+1))
41: to print LCM of two numbers using while loop
n1=int(input("Enter first number:")
n2=int(input("Enter second number:")
if n1>n2:
  greater=n1
  else
  greater=n2
while True:
if greater%n1==0 and greater%n2==0
print("LCM of", num1, "and", num2, "is", greater)
        break
    greater +=1
42:Python Program to print the length of given string.
s=input("Enter a string:")
print("length of string is:",len(s))
43:Python Program to concatenate two strings
s1=input("Enter first string:")
s2=input("Enter second string:")
result=s+s2
print("concatenated of sting"",result)
44 to compare two strings.
s1=input("Enter first string:")
s2=input("Enter second string:")
if s1==s2:
print("strings are equal.")
else
print("strings not equal.")
45.to perform copy of one string to another string.
s1=input("Enter first string:")
s2=s1
print("original sring:",s1)
print("copied string:",s2)
46: to convert lowercase string to uppercase.
text=input("Enter a lowercase string: ")
uppercase_text=text.upper()
print("Uppercase string:", uppercase_text)
47:to convert uppercase string to lowercase.
text=input("Enter a uppercase string: ")
lowercase_text=text.lower()
print("lowercase string:", lowercase_text)
48:to insert an element in an array at end.
arr=[1,2,3,4]
element=5
arr.append(element)
print("updated array:",arr)
49: to insert an element in an array at first.
arr=[1,2,3,4]
element=5
arr.insert(0,element)
print("updated array:",arr)
50: to delete an element in an array at end.
arr=[1,2,3,4]
arr.pop()
print("updated array:",arr)
51: to delete an element in an array at first
arr=[1,2,3,4]
arr.pop(0)
print("updated array:",arr)
52:to print all unique elements in the array
arr=[1,2,3,4]
unique_elements=set(arr)
print("unique elemnts in the array:",arr)
53:to Sort first half in ascending order and second half in descending order in an array
arr = [10,50,20,40,60,30,70,80]
mid=len(arry)/2
first_half=sorted(arr,[:mid])
second_half=sorted(arr,[mid:]) reverse=True
result=first_half+second+half
print("Modified array:",result)
54: to sort the elements of an array
arr = [10,50,20,40,60,30]
arr.sort()
print("sorted element:",arr)
55:Finding the frequency of element Frequency of elements in an array
arr = [10,50,20,40,60,30,10,20,40]
frequency={}
for elements in arr:
    if elements in frequency:
     frequency(elements)=+1
     else:
     frequency(element)=1
print("frequency element:",element)
56: for sorting elements of an Array by Frequency
arr = [10,50,20,40,60,30,10,20,40]
frequency={}
for elements in arr:
    if num in frequency:
     frequency(elements)=+1
     else:
     frequency(element)=1
sorted_arr=sorted(arr,key=lambda,x:frequency[x])
print("sorted elements by frequency:",sorted_arr)
57:Find the Longest Palindrome in an Array
def count_distinct_elements(arr)
    result=len(set(arr)))
    return result
numbers=[10,50,20,40,60,30,10,20,40] 
print("number of distinct elements:", count_distinct_elements(arr))
58:Finding Repeating elements in an Array
def find_repeating_element(arr):
    seen=set()
    repeats=set()
    for item in arr:
        if item in seen:
           repeats.add(item)
       else:
           seen.add(item)
     return list(repeats)   
   arr=[10,50,20,40,60,30,10,20,40]
   print("number of elements:",find_repeating_element(arr))
59:Removing Duplicates elements from an array
def remove_duplicates(arr)
    return list(set(arr))
arr=[10,50,20,40,60,30,10,20,40]
print("Remove without duplicates:",remove_duplicates(arr))
60:finding minimum scalar of two products 
def min_scalar_product(arr1,arr2):
    arr1.sort()
    arr2.sort(return= True)
    return sum(a*b for a,b zip(arr1,arr2))
arr1=[1,8,-8]
arr2=[3,-2,6]
print("Minimum scalar product:", min_scalar_product(arr1,arr2))
61:Find non-repeating elements in an array 
from collections import counter
arr=[1,1,2,2,3,4,4,4,5,5]
count=counter(arr)
non_repeating=(num for num,count in count.items if count==1)
print("non_repeating)
62:def max_scalar_product(v1,v2):
      v1.sort(reverse=True)
      v2.sort(reverse=True)
      return sum(a*b for a,b in zip(v1,v2))
  v1=[2,5,1]
  v2=[0,7,1]
  print("Maximum scalar product:",max_scalar_product(v1,v2))
63:to count numbers of even and odd elements in an array
arr=[1,2,3,4,5,6,7,8]
even_count=0
odd_count=0
for num in in arr:
    if num%2==0
       even_count+=1
    else:
       odd_count+=1
 print("Even numbers:",even_count)
  print("odd numbers:",odd_count)
64:GCD of Two Numbers 
import math
a=76
b=2
gcd=gcd.mat(a,b)
print("GCD of a and b ",is gcd)
65:for Binary To Decimal Conversion
binary="1011"
decimal=int(binary,2)
print("Decimal number:",decimal)
66:hexadecimal to decimal
hex_num=input("Enter a hexadecimal number:")
dec=int(hex_num,16)
print("decimal number:",decimal)
67:decimal to binary
dec=int(input("Enter a dec number:")
binary=bin(dec)[:2]
print("Binary number:",binary)
68: to find out the quadrant in which the given co-ordinate lie
def find_quadrant(x, y):
    if x > 0 and y > 0:
        return "Quadrant I"
    elif x < 0 and y > 0:
        return "Quadrant II"
    elif x < 0 and y < 0:
        return "Quadrant III"
    elif x > 0 and y < 0:
        return "Quadrant IV"
    elif x == 0 and y == 0:
        return "Origin"
    elif x == 0:
        return "On the Y-axis"
    elif y == 0:
        return "On the X-axis"
x = float(input("Enter the x-coordinate: "))
y = float(input("Enter the y-coordinate: "))
print("The point lies in:", find_quadrant(x, y))
69: for Permutations In Which N People Can Occupy R Seats In A Classroom
de factorial(num)
   fact=1
   for i in range(num,1,-1)
   fact=fact*i
p=int(input("Enter number of people:")
r=int(input("Enter number of seats:")
p=factorial(n)/factorial(n-r)
print("total possible arrangements:,"p)
70:for Finding Maximum Number Of Handshakes
N=30
no_of_handshakes=int(N*(N-1)/2)
print("Max number of handshakes possible for" N, "pepople are:",no_of_handshakes)
71:Python Program for Addition of two fractions
num1 = int(input("Enter numerator of first fraction: "))
den1 = int(input("Enter denominator of first fraction: "))
num2 = int(input("Enter numerator of second fraction: "))
den2 = int(input("Enter denominator of second fraction: "))
f1 = Fraction(num1, den1)
f2 = Fraction(num2, den2)
result = f1 + f2
print("The sum of the two fractions is:", result)
72:Replace all 0’s with 1 in a given integer 
def replace_zeros_with_ones(n):
    return int(str(n).replace('0',1)
number=1011
result= replace_zeros_with_ones(number) 
print(result)
73: Calculate the area of a circle
def area_of_circle(radius):
    return math.pi*radius**2
r=5
print( f"area of circle with radius {r} is { area_of_circle(r):2f}")
74:







 



 
       
 
       



      
    
   
    

   
       

 



        




























   
 


       
   
    


   


 
 
 
 

 




   
       
   






     
   



  



































