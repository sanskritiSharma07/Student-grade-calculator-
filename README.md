# Student Grade Calculator

print("===== Student Grade Calculator =====")

name = input("Enter Student Name: ")

subjects = int(input("Enter Number of Subjects: "))

total = 0

for i in range(subjects):
    marks = float(input(f"Enter Marks for Subject {i+1}: "))
    total += marks

percentage = total / subjects

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 50:
    grade = "D"
else:
    grade = "F"

print("\n===== Result =====")
print("Student Name :", name)
print("Total Marks :", total)
print("Percentage :", round(percentage, 2), "%")
print("Grade :", grade)# Student Grade Calculator

print("===== Student Grade Calculator =====")

name = input("Enter Student Name: ")

subjects = int(input("Enter Number of Subjects: "))

total = 0

for i in range(subjects):
    marks = float(input(f"Enter Marks for Subject {i+1}: "))
    total += marks

percentage = total / subjects

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 50:
    grade = "D"
else:
    grade = "F"

print("\n===== Result =====")
print("Student Name :", name)
print("Total Marks :", total)
print("Percentage :", round(percentage, 2), "%")
print("Grade :", grade)
