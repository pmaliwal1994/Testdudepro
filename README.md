# Testdudepro
Task for testdude
#task 1
num1=int(input("Enter 1st num "))
num2=int(input("Enter 2nd num "))

print("Addition",num1+num2)
print("subtraction",num1-num2)
print("Multiplication",num1*num2)
if num2 <=0:
    print("can not divide by 0 or less")
else:
    print("Divide", num1 / num2)

#task 2
s1=input("First name ")
s2=input("last name ")
print("Hello",s1,s2,"Welcome to world")

#task 3
# odd even

num=int(input("Enter the number "))

if num % 2 ==0 :
    print(num,"is even")
else :
    print(num,"is odd")

#task 4
# for loop
sum=0
for i in range (1,51):
    sum+=i
print(f"The sum of number from 1 to 50 is {sum}")

