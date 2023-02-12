from random import *

def show (A):
    for a in A:
        for s in a:
            print(s, end=" ")
        print()

def row():
    user = int(input("Which row?: "))
    del A[user-1]
    show(A)

def column():
    user = int(input("Which column?: "))
    for i in range(len(A)):
        del A[i][user-1]
    show(A)



user = input("How many rows do you want?: ")
r = int(user)
user = input("How many columns do you want?: ")
c = int(user)

A = [[randint(1,9) for m in range(c)] for n in range(r)]

show(A)

user = input("What do you want to delete a row or a column? ")

if user == "row":
    row()

    user = input("Do you want to delete a colomn too? (yes / no): ")
    if user == "yes":
        column()
        print("The End")
    else:
        print("The End")

if user == "column":
    column()

    user = input("Do you want to delete a row too? (yes / no): ")
    if user == "yes":
        column()
        print("The End")
    else:
        print("The End")
        
