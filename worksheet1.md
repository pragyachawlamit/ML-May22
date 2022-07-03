## Q1)


```python
num=int(input('Enter a number: '))
def fact(num):
    factorial=1
    if num<0:
        print('Factorial of negative number does not exist!!')
    elif num ==0:
        print('Factorial of 0 is 1')
    else:
        for i in range(1,num+1):
            factorial=factorial*i
        return(factorial)
fact(num)
```

    Enter a number: 5





    120



## Q2)


```python
name=input('Enter a name: ')
if name=='Darth Vader':
    print('Luke, I am your father')
elif name=='Leia':
    print('Luke, I am your sister')
elif name=='Han':
    print('Luke, I am your brother in law')
elif name=='R2D2':
    print('Luke, I am your droid')
else:
    print('Enter a valid name')
```

    Enter a name: Darth Vader
    Luke, I am your father


## Q3)


```python
num=int(input('Enter a number: '))
def nod(num):
    count=0
    while num>10:
        num=num/10
        count=count+1
    count+=1
    print(count)
nod(num)
```

    Enter a number: 3456
    4


## Q4)


```python
num=int(input('Enter a number: '))
def mul(num):
    ans=1
    while num>0:
        p=fact(num)
        ans=ans*p
        num-=1
    print(ans)
mul(num)
```

    Enter a number: 5
    34560


## Q5)


```python
def sm(n):
    n=int(input('Enter number of arguments: '))
    s=0
    for i in range(1,n+1):
        s=s+i*i
    print(s)
sm(n)
```

    Enter number of arguments: 3
    14


## Q6)


```python
def calc(num1,num2,c):
    num1=int(input('Enter first number: '))
    num2=int(input('Enter second number: '))
    c=input('Enter the operation you want to perform: ')
    if c=='+':
        print(num1+num2)
    elif c=='-':
        if num1>num2:
            print(num1-num2)
        else:
            print(num2-num1)
    elif c=='*':
        print(num1*num2)
    elif c=='/':
        print(num1/num2)
    else:
        print('Enter a valid operation!!')
calc(num1,num2,c)
```

    Enter first number: 3
    Enter second number: 2
    Enter the operation you want to perform: +
    5


## Q7)


```python
def I(num):
    num=int(input('Enter a positive number: '))
    for i in range(1,num+1):
        if i%2==0:
            print('I WILL')
        else:
            print('I CAN')
I(num)
```

    Enter a positive number: 4
    I CAN
    I WILL
    I CAN
    I WILL


## Q8)


```python
l=(1,2,1,3,2)
count=0
for i in l:
    for j in range(i+1,len(l)):
        if l[i]==l[j]:
            count+=1
        continue
print(count)
```

    2


## Q9)


```python

```

## Q10)


```python

```
