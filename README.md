# evaluvation
marks = []
for i in range(5):
    mark = int(input(f"Enter marks for subject {i+1}: "))
    marks.append(mark)

average = sum(marks) / 5

if average >= 90:
    grade = 'A'
elif average >= 80:
    grade = 'B'
elif average >= 70:
    grade = 'C'
elif average >= 60:
    grade = 'D'
else:
    grade = 'Fail'

print(f"Average Marks: {average}")
print(f"Grade: {grade}")

