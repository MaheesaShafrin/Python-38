# Python-38
Write a Python program to insert a number to any position in a list
numbers = [3,4,1,9,6,2,8]
print(numbers)
x= int(input("Enter the numbers to be inserted:"))
y=int(input("Enter the position:"))
numbers.insert(y,x)
print(numbers)

Output:
[3, 4, 1, 9, 6, 2, 8]
Enter the numbers to be inserted:5
Enter the position:2
[3, 4, 5, 1, 9, 6, 2, 8]
