    #18.dinf student totals marks and avereage 


student_no=input("please enter student_no")
student_name=str(input('please enter student_name'))
marks1=int(input('please enter marks1'))
marks2=int(input('please enter marks2'))
marks3=int(input('please enter marks3'))
total_marks=marks1+marks2+marks3
avg_marks=(total_marks/3)
print("total_marks", total_marks)
print("avg_marks",avg_marks)

    #19 swaaping two numbers 
a=input("1st value")
b=input("2nd  value")
print("before swapping",a,b)
a,b=b,a
print("after swapping",a,b)


    #20 find out gross salary
name=str(input('please enter name'))
emp_id=int(input('please enetr emp_id'))
salary=int(input('salary of'))
TDA=int(input('tda of'))
gross_salary=salary+TDA
print("gross_salary of",name,gross_salary)

    #6 what is the type of a
a=1,00,000
print(type(a))

    #7 what is the type of a
a='inf'
print(type(a))

    #8 what the value of a and type of a?
a=~~~~~~~~5

print(a)
print(type(a))

    #24 find the value 
print(3*1**3)


 # If else program

 
     #1.WAP to find biggest number.
 
a = int(input('please enter 1st number'))
b = int(input('please enter 2nd number'))
if a>b:
    print('1st number is greater than 2nd number')
elif a<b:
    print('1st number is less than 2nd number')
else:
    print('all are same')

    #2. WAP input three number and find biggest number

a = int(input('please enter 1st number: '))
b = int(input('please enter 2nd number: '))
c = int(input('please enter 3rd number: '))
if a>b and a>c:
    print(' 1st number is greater ')
elif b>c and b>a:
    print(' 2nd number is greater ')
elif c>a and c>b:
    print(' 3rd number is greater ')
else:
    print('all are same')
   
    #3 check +ve or -ve number

a=int(input('please enter any number')) 
if a>0:
    print('number is +ve')
elif a<0:
    print('number is -ve')
else:
    print('both are same ')
    

