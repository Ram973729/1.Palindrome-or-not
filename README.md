# 1.Palindrome-or-not
n=int(input())
a=n
b=0
while a>0:
    b=b*10
    b=b+(a%10)
    a=a//10
    print(a)
    print(b)
if b==n:
    print('Palindrome')
else:
    print('Not a Palindrome')
