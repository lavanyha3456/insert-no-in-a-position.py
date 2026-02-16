# insert-no-in-a-position.py

numbers = [3,4,1,9,6,2,8]
print(numbers)
x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position: "))
numbers.insert(y,x)
print(numbers)


output:
[3, 4, 1, 9, 6, 2, 8]
Enter the number to be inserted: 10
Enter the position: 4
[3, 4, 1, 9, 10, 6, 2, 8]

