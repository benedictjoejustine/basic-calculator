# basic-calculator
A basic calculator whic can be used for addition, subtraction, division &amp; multiplication.

Code:-
num1=float(input("enter the first number:"))
print("1.addition\n2.subtraction\n3.multiplication\n4.division")
check=float (input("enter your selection:"))
num2=float(input("enter the second number:"))
if(check==1):
    result=num1+num2
    print("result=",result)
elif(check==2):
    result=num1-num2
    print("result=",result)
elif(check==3):
    result=num1*num2
    print("result=",result)
elif(check==4):
    result=num1/num2
    print("result=",result)
else:
    print("cant do it")
