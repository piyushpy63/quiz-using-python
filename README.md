# quiz-using-python

#code starts here

print("welcome to amazing quiz:")

play=input("Do you want to play? \n")
if play.lower()!="yes":
    quit()
score=0

answer=input("what is full form of cpu?")
if answer.lower()=="central processing unit":
    print("correct!")
    score+=1
else:
    print("oops incorrect")

answer=input("what is tws  ?\n")
if answer.lower()=="truly wireless earbuds":
    print("correct!")
    score += 1
else:
    print("oops incorrect")

answer=input("what is the full form of WHO?  \n")
if answer.lower()=="world health organisation":
    print("correct!")
    score += 1
else:
    print("oops incorrect")
print("your got " + str(score) + " questions correct:")
