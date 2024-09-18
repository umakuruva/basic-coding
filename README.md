@@<a>@@ #Python program for reverse of a number
   #python code to reverse a number
n=int(input())
temp=n 
rev=0
while(n>0):
    rem=n%10 
    rev=(rev*10)+rem
    n=n//10

print(rev)
@@<b>@@ pytho code to find the fibonacci series
n1=0
n2=1 
n=int(input())
print(n1,n2,end=" ")
for i in range(n):
    n3=n1+n2
    print(n3,end=" ")
    n1=n2
    n2=n3
   @@ <c> @@ python program to check perfect number or not
    n=int(input())
l1=[]
for i in range(1,n):
    if (n%i==0):
        l1.append(i)
print(l1)
a=sum(l1)
if(a==n):
    print("Given number is a perfect number")
else:
    print("Given number is not a perfect number")
  @@ <d> @@ Python program to check given two strings are an anagram or not
  s1=input()
s2=input()
s1=s1.lower()
s2=s2.lower()
if(len(s1)==len(s2)):
    s3=sorted(s1)
    s4=sorted(s2)
    if(s3==s4):
        print("The given two strings are anagram")
    else:
        print("Given two strings are not an anagram")
else:
    print("Not an anagram")
    @@<e>@@ Python program to check given string is palindrome or not

    #python program to check given strings are palindrome or not
s1=input()
n=len(s1)
s2=""
for i in range(n-1,-1,-1):
    s2+=s1[i]
if(s1==s2):
    print("Given  strings are palindrome")
else:
    print("Given strings are not palindrome")
    
    @@<f>>@@ Python program to check given year is leap year otr not
      year=int(input())
if(year%4==0 or year%400==0):
    print("Given year is a leap year")
else:
    print("Given year is not a leap year")
 @@<g> python program to find the prime numbers in a given range
 

