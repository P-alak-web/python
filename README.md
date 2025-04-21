# python
#create a calculator
Num1 = int(input("enter the first number"))
Num2 = int(input("enter the second number"))
print("enter the operator")
operator  = input("enter the operator(+,-,*,/)")
if operator == '+' :
    print( "the sum of the {Num1} + {Num2} =",Num1 + Num2)
elif operator == '-' :
    print( "the differnce of the {Num1} - {Num2} =",Num1 - Num2)
elif operator == '*' :
    print( "the product of the {Num1} * {Num2} =",Num1 * Num2)
elif operator == '//' :
     if Num2 == 0:
         print("error")
     else :    
         print( "the quotient of the {Num1} / {Num2} =",Num1 // Num2)
    
