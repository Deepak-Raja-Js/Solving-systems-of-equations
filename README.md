# Solving-systems-of-equations

from sympy import *
x,y,z,t = symbols('x y z t')

a= int(input("enter how many variable: "))
if a==1:
    print("you can use x variable only")
    LHS = eval(input('enter the LHS: '))
    RHS = float(input('enter the RHS: '))
    a = Eq(LHS,RHS)
    print('x value is',solve(a))

if a==2:
    print("you can use x,y variable only")
    LHS1 = eval(input('enter the 1st equation LHS: '))
    RHS1 = float(input('enter the 1st equation RHS: '))
    LHS2 = eval(input('enter the 2nd equation LHS: '))
    RHS2 = float(input('enter the 2nd equation RHS: '))
    a = Eq(LHS1,RHS1)
    b = Eq(LHS2,RHS2)
    print('x value is',solve((a,b)))

if a==3:
    print("you can use x,y,z variable only")
    LHS1 = eval(input('enter the 1st equation LHS: '))
    RHS1 = float(input('enter the 1st equation RHS: '))
    LHS2 = eval(input('enter the 2nd equation LHS: '))
    RHS2 = float(input('enter the 2nd equation RHS: '))
    LHS3 = eval(input('enter the 3rd equation LHS: '))
    RHS3 = float(input('enter the 3rd equation RHS: '))
    a = Eq(LHS1,RHS1)
    b = Eq(LHS2,RHS2)
    c = Eq(LHS3,RHS3)
    print('x value is',solve((a,b,c)))

if a==4:
    print("you can use x,y,z variable only")
    LHS1 = eval(input('enter the 1st equation LHS: '))
    RHS1 = float(input('enter the 1st equation RHS: '))
    LHS2 = eval(input('enter the 2nd equation LHS: '))
    RHS2 = float(input('enter the 2nd equation RHS: '))
    LHS3 = eval(input('enter the 3rd equation LHS: '))
    RHS3 = float(input('enter the 3rd equation RHS: '))
    LHS4 = eval(input('enter the 4th equation LHS: '))
    RHS4 = float(input('enter the 4th equation RHS: '))
    a = Eq(LHS1,RHS1)
    b = Eq(LHS2,RHS2)
    c = Eq(LHS3,RHS3)
    d = Eq(LHS4,RHS4)
    print('x value is',solve((a,b,c,d)))

__author__ = "Deepak Raja"
__copyright__ = "Copyright (C) 2021 Deepak Raja"
__license__ = "Common Attribution"
__version__ = "1.0"
