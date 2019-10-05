glob = 7
notglo = 5
#using a for loop 
for i in range(1999,3201):
    #print(i)
    if i % glob == 0 and i%notglo !=0:
            print(i) 
    
   
#using a a funtion and a while loop   
def divisibvle():
    i = 1999
    while i <3201:
        if i % glob == 0 and i%notglo !=0:
            print(i) 
        i = i+1
    return i
divisibvle()

'''Write a program which can compute the factorial of a given numbers.
The results should be printed in a comma-separated sequence on a single line.
Suppose the following input is supplied to the program:
8
Then, the output should be:
40320'''

def factorial(b):
    if b == 0:
        return 1
    else:
        return b * factorial(b- 1)
print(factorial(b = int(input('please enter a numbers : '))))


#appending keys and values from a user input by starting from 1 and incrementing that (WE PLACCING THE SQUARE OF EACH VALUE)
def creating_dic(n):
    d=dict()
    for i in range(1,n+1):
        d[i]=i*i
    
    return d
print(creating_dic(n =int(input('enter a number'))))

#the aove can also be done the below way 
d = dict()
n = int(input('enter a number : '))
for i in range(1, n+1):
    d[i] = i*i
print(d)

#printing tuples and a list from the user input 
f = input('enteres numbers separated by comas')
e = []
i_s = f.split(',')
e.append(i_s)
t = tuple(i_s)
print(e)
print(t)
