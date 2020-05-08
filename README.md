# python
#Assignment 1 - 

marks = int(input("Enter your marks - "))

print('|--------|')
if(marks >= 85):
    print("|   A    |")
elif (marks>=75 and marks <= 84):
    print("|   B    |")
elif (marks>=65 and marks <= 74):
    print("|   C    |")
elif (marks>=55 and marks <= 64):
    print("|   D    |")
elif (marks>=45 and marks <= 54):
    print("|   E    |")
else:
    print("Need imporvement")
    
print('|--------|')
