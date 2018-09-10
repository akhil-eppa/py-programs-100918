
import math

#====>(1)program to find refractive index 
#i=int(input("Enter incident angle: "))
#r=int(input("Enter reflecting angle: "))
#i=math.radians(i)
#r=math.radians(r)
#m=math.sin(i)/math.sin(r)
#print("refractive index = ",m)





#====>(2)solve quadratic eq eg:10x2+15x +5=0
#a,b,c=input("Enter a,b,c for a quadratic equation ax^2+bx+c=0 : ").split(',')
#a,b,c=int(a),int(b),int(c)
#x1=(-b+math.sqrt((b**2)-(4*a*c)))/(2*a)
#x2=(-b-math.sqrt((b**2)-(4*a*c)))/(2*a)
#print("Roots of the equation are : ",x1," and ",x2)






#====>(3)find lcm
#x,y=input("Enter 2 numbers for which lcm has to be found : ").split(',')
#x,y=int(x),int(y)
#lcm=(x*y)/math.gcd(x,y)
#print("The lcm is : ",lcm)





#====>(4)interest problem
#p,t,r=input("Enter the principal,time and rate : ").split(',')
#p,t,r=float(p),int(t),float(r)
#interest=(p*(1+(r/100))**t)-p
#interest=round(interest,2)
#temp=int(round(interest,0))
#print("The interest is ",temp," ruppees and ",(interest-temp)*100," paise")




#====>(5)print calendar of august 2018
#import calendar
#print(calendar.month(2018,8))






#====>(6)Take 3 words print with different separator
#a,b,c=input("Enter 3 words: ").split(',')
#print(a,b,sep="*",end=" ")
#print c





'''
import turtle
nbrsides = 4
for weirdname in range(nbrsides) :
    turtle.color("red")
    
    turtle.forward(200)
    turtle.right(360/nbrsides)
    for steps in range(nbrsides) :
        turtle.color("blue")
        turtle.forward(100) 
        turtle.right(360/nbrsides)

'''
#for colour in ['red','green','blue','black'] :
#    turtle.color(colour)
#    turtle.forward(100)
#    turtle.left(90)






#====>(7)take a string with numbers and perform max and min and observe your results
#x=input("Enter numbers")
#print(max(x))
#print(min(x))
#if you enter 12345 it gives 5,1









#====>(8)check type of quadrilateral
#a,b,c,d=input("Enter 4 sides of a quadrilateral: ").split(",")
#d1,d2=input("Enter the 2 diagonals: ").split(",")
#a,b,c,d,d1,d2=int(a),int(b),int(c),int(d),int(d1),int(d2)
#if (a==b==c==d) and (d1==d2):
#    print("Square")
#elif (a==b==c==d) and (d1!=d2):
#    print("rhombus")
#elif (a==c) and (b==d) and (d1==d2):
#    print("rectangle")
#elif (a==c) and (b==d) and (d1!=d2):
#    print("parallelogram")
#elif (a==b) and (c==d) and (d1!=d2):
#    print("kite")
#else:
#    print("general quadrilateral")





#====>(9)Checking for collinearity
#x1,y1=input("Enter first point").split(",")
#x2,y2=input("Enter second point").split(",")
#x3,y3=input("Enter third point").split(",")
#x1,y1,x2,y2,x3,y3=int(x1),int(y1),int(x2),int(y2),int(x3),int(y3)
#m1=(y2-y1)/(x2-x1)
#m2=(y3-y2)/(x3-x2)
#m3=(y1-y3)/(x1-x3)
#if (m1==m2==m3):
#    print("Points are collinear")
#else:
#    print("Centroid is: ",((x1+x2+x3)/3),",",((y1+y2+y3)/3))

    



#====>(10)splitting a list
#a=[12,34,12.5,9.6,25]
#li=[]
#lf=[]
#for i in a:
#    if type(i)==int:
#        li.append(i)
#    elif type(i)==float:
#        lf.append(i)
#print(li)
#print(lf)

    


#=====>(11)Generating lists
#n=int(input("Enter a number"))
#a=[]
#x=n-2
#for i in range(1,n):
#    a.append(i)
#for i in range(1,n-1):
#    a.append(x)
#    x-=1
#print(a)
#b=[]
#for i in range(1,n-1):
#    b.append(i*(i+1))
#print(b)




#=====>(12)combining 2 lists
'''
l1=input("Enter a few values of list 1: ").split(",")
l2=input("Enter a few values of list 2: ").split(",")
l3=[]
if len(l1)<=len(l2):
    i=0
    while i<len(l1):
        l3.append(l1[i])
        l3.append(l2[i])
        i+=1
    for i in range(len(l1),len(l2)):
        l3.append(l2[i])
else:
    i=0
    while i<len(l2):
        l3.append(l2[i])
        l3.append(l1[i])
        i+=1
    for i in range(len(l2),len(l1)):
        l3.append(l1[i])
print(l3)


x=input("Enter a word with lower letters")
l=len(x)
i=0
for j in range(l):
    if x[j]=='a' or x[j]=='e' or x[j]=='i' or x[j]=='o' or x[j]=='u' :
        i=i+1
print("no of vowels : ",i)
'''


'''
i=0
s=0
x="bob"
y="bobobobob"
n=y.find(x)
while n!=-1:
    i=i+1
    s=n+1
    n=y.find(x,s)
print(i)
'''
s="abca"
i=0
t=""
x=len(s)
while i<x-1:
    if ord(s[i])<=ord(s[i+1]):
        t=t+s[i]
    i+=1
print(t)

        
        
        
    
    



















