# fun_factorial.py
#write a program using a user defined 
# function calcfact() to calculate and display 
# the factorial of a number num passed as an argument

#reuiremens
#accept one number from user
#calcu factoprial
#display fact
def calcFact(num):
    fact=1
    for i in range(num,0,-1):
        fact=fact*i
    print("factorial of ",num,"is ",fact)
    #function ends here
#ask number from user 
num=int(input("enter the number:"))
calcFact(num)
