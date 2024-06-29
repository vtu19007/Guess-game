Secret_number=9
Guess_count=3
Guess_start=0
while Guess_start<Guess_count:
    Guess=int(input("Guess:"))
    Guess_start +=1
    if Guess == Secret_number:
        print("You won!")
        break
else:
    print("Sorry You Lose!")
