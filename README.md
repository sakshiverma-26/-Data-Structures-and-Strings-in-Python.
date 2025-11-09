# -Data-Structures-and-Strings-in-Python.
# task 1
students_marks = {
    "Alice": 85,
    "Bob": 92,
    "Charlie": 78,
    "David": 90,
    "Eva": 88
}

student_name = input("Enter the student's name: ")

if student_name in students_marks:
    print(f"{student_name}'s marks are: {students_marks[student_name]}")
else:
    print(f"Sorry, no record found for student '{student_name}'.")

   # task 2
numbers = list(range(1, 11))
print("Original list:", numbers)

first_five = numbers[:5]
print("First five elements:", first_five)

reversed_first_five = first_five[::-1]
print("Reversed first five elements:", reversed_first_five)
