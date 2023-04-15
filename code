#P03-Homework

#libs
import random

#vars
#colours
red = '\033[91m'
lilac = '\33[95m'
normal = '\033[0m'

#attempt count with initial guess
count = 1

#initial prompt and user input
print(red + "♥" + normal + " Feeling lucky? Guess a number from 0 to 100 " + red + "♥" + normal)
user = input("> ")
#check if integer
while True: 
    if user.isdigit():
        guess = int(user)
        break
    else:
        user = input("Please input a number > ")

#random number determine
correct = random.randrange(0,100)



#does attempt match determined random number
while correct!= guess:
    #higher than random number
    if guess < correct:
        print("\nHigher than that!")
        user = input("Try again? \n> ")
        count += 1
        #check if int
        while True: 
            if user.isdigit():
                guess = int(user)
                break
            else:
                user = input("Please input a number \n> ")
    
    #lower than random number
    elif guess > correct:
        print("\nLower than that!")
        user = input("Try again? \n> ")
        count += 1
        #check if int
        while True: 
            if user.isdigit():
                guess = int(user)
                break
            else:
                user = input("Please input a number > ")
    
    #get out of loop
    else:
        break

#victory
if count == 1:
    print(f"Holy smokes batman! It only took you one try!\nHave a cookie!\n🍪")
else:
    print(f"CORRECT!\nIt took you {count} tries.\nHave a flower!" + lilac + "\n✿" + normal)
