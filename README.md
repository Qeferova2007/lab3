# lab3-10
import math 
eps=0.001
x=0.9
sum_s=term=math.sin(x)
n=2
while abs(term/n)>=eps:
    term*=math.sin(x)
    sum_s+=term/n
    n+=1
    
print(sum_s)
