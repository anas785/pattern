# pattern


name=input("Enter the name: ")
n=len(name)

for i in range(n):
    for j in range(i+1):
        print(name[j],end="")
    print()




str1=input("enter the name: ")
length=len(str1)
for i in range(length):
    for j in range(length-i):
        print(str1[j],end='')
    print()
