# simple gradding-system with python
import math
print("*******************************")
print("=======GRADDING SYSTEM========")
print("-------------------------------")
x=int(input("ENTER THE ENG MARKS:"))
x1=int(input("ENTER THE KISW MARKS:"))
x2=int(input("ENTER THE MATH MARKS:"))
x3=int(input("ENTER THE IRE MARKS:"))
x4=int(input("ENTER THE ARABIC MARKS:"))
total_marks=x+x1+x2+x3+x4
average=total_marks/5



print("-----------------------------------------")
print("ENG:\t KISW:\t MATH:\t IRE:\t ARABIC:\t")
print(str(x),"\t\t",str(x1),"\t",str(x2),"\t",str(x3),"\t\t",str(x4))
print("----------------------------------------")
print("TOTAL MARKS:",total_marks)
print("MEANS SCORE:",average)
print("MEAN GRADE:")

if average>=70: print("A")
if average>=60 and average<=69: print("B")
if average>=50 and average<=59: print("C")
if average>=40 and average<=49: print("D")
if average<=39: print("E")
