# hw-lesson-2
Excersize 1:
number=input('')
actual_number=int(number)
calculation=actual_number%2
if calculation==0:
    print("This number is even!")
else:
    print("This number is odd!")

Excersize 2:
number=input('')
actual_number=int(number)
calculation=actual_number%2
if calculation==0 and actual_number>=100:
    print("This number is even and its over 100!")
else:
    print("This number might have been over 100 but it wasn't even or this number was less than 100!")
    
    
Excersize 3:
username=input("Your name is: ")
if username=='joe':
    print("your name is joe")
else:
    print("your name is", username)
    
    
Excersize 4:
score=input("Your score is: ")
real_score=int(score)
if real_score>=90:
    print("Your grade is an A!")
elif real_score>=80 and 89:
    print("Your grade is a B!")
elif real_score>=70 and 79:
    print("Your grade is a C!")
elif real_score>=60 and 69:
    print("Your grade is a D!")
elif real_score<60:
    print("Your grade is a F!")
