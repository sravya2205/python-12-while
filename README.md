#while statement
'''print 1 to 10 natural numbers'''
num=int(input())
while num<=10:
    print(num,end=' ')
    num+=1

    '''print even numbers upto 20 by using while loop'''
num=int(input())
while num<=20:
    if num%2==0:
        print(num,end=' ')
    num+=1

    '''print odd numbers upto 20 by using while loop'''
num=int(input())
while num<=20:
    if num%2!=0:
        print(num,end=' ')
    num+=1

    
    #program to reverse a 4 digit number,i/p=4562 o/p=2654
num=int(input())
rev=0
while num>0:
    digit=num%10
    rev=rev*10+digit
    num//=10
print(rev)
