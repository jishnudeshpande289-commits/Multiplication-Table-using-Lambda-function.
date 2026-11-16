# Multiplication-Table-using-Lambda-function.
A simple Python code to print the multiplication of an entered number.
#input integer from user
n=int(input("Enter a number:"))
print('The multiplication table of',n,'is:\n')
#starting a loop by specifying range
for i in range(1,11):
    f=lambda n : n*i
    print(n,"x",i,"=",f(n))#f(n)-lambda function is called

