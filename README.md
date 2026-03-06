# Data-structure-partical-program14
Bubble sort program
marks=[70,85,60,90,75]

n=len(marks)
for i in range(n):
    for j in range(0,n-i-1):
        if marks[j]<marks[j+1]:
            marks[j],marks[j+1]=marks[j+1],marks[j]

print "Ranked Marks:"
for m in marks:
    print m
