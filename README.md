UBAH KOSISO ODINAKA
REG NO: 2024714075 
ASSIGNMENT: USING CONDITIONAL STATEMENTS IN PYTHON TO CREATE A GRADING SYSTEM
# Python Grading System using Conditional Statements
score = int(input("Enter your score: "))

if 70 <= score <= 100:
    print("Grade: A")
elif 60 <= score <= 69:
    print("Grade: B")
elif 50 <= score <= 59:
    print("Grade: C")
elif 45 <= score <= 49:
    print("Grade: D")
elif 40 <= score <= 44:
    print("Grade: E")
elif 0 <= score <= 39:
    print("Grade: F")
else:
    print("Invalid score. Please enter a number between 0 and 100.")
