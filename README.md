# practice
for i in range(0,5):
    for j in range(0,i+1):
           print("*",end="")

    print()
for i in range(0,4):
    for j in range(0,4):
        print("#", end="")
    print("")

for i in range(0,5):
    for j in range(5,i-1):
        print("%",end="")

x=int(input("x is:"))
if x%4==0 and x%100!=0 or x%400==0:
    print("enter year  leap year")
else:
    print(" not leap year")