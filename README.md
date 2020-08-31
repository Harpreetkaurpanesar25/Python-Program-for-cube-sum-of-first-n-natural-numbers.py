# Python-Program-for-cube-sum-of-first-n-natural-numbers.py
# for simple program you can go with this code
n=int(input())
sum = 0
for i in range(1, n+1):
    sum +=i*i*i
    print(sum)
    
    
# to reduce complexity we can go with the formula i.e.  (n ( n + 1 ) / 2) ^ 2

n= int(input("Enter the number: "))
x = (n * (n + 1)  / 2)
# squaring the value seperately
v=(int)(x * x)
print(v)

