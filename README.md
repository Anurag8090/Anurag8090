#A simple calculator in python
print("please select the operation of your choice\n" \
"1.Additionn\n"  \
"2.Subtraction\n" \
"3.Multiply\n" \
"4.Divide\n" \
"5.Remainder")
select=input("Choose the operation ")
input1=int(input("enter first number "))
input2=int(input("enter second number "))
swap=input("Do you want to swap numbers in operation")
def sum_numbers(input1,input2):           print(input1+input2)
def dif_numbers(input1,input2):
    print(input1-input2)
def pro_numbers(input1,input2):
        print( input1*input2)
def div_numbers(input1,input2):
       print(input1/input2)
def rem_numbers(input1,input2):
           print(input1%input2)
if swap=='yes':                sum_numbers(input1input2)   
elif select=='2':
    dif_numbers(input2,input1)
elif select=='3':
    pro_numbers(input2,input21)
elif select=='4':
       div_numbers(input2,input1)
elif select=='5':
     rem_numbers(input2,input1)
else:
         print('Restart the program')
if select=='1':
    sum_numbers(input1,input2)   
elif select=='2':
    dif_numbers(input1,input2)
elif select=='3':
    pro_numbers(input1,input2)
elif select=='4':
        div_numbers(input1,input2)
elif select=='5':
     rem_numbers(input1,input2) 
else:
        print("Invalid operation!")
     
