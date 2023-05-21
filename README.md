Marks = int(input("Enter Marks: "))

if Marks >= 80:
    print("Grade: A")
elif (Marks < 80 and Marks >= 60):
    print("Grade: B")
elif Marks < 60 and Marks >= 50:
    print("Grade: C")
elif Marks < 50 and Marks >= 45:
    print("Grade: D")
elif Marks < 45 and Marks > 25:
    print("Grade: E")
elif Marks < 25:
    print("Grade: F")
