# Guess-The-Number
Guess the number game

import random

randomNumber = random.randint(0, 10)
chooseNumber = 0

while chooseNumber != randomNumber:

    chooseNumber = int(input("Guess the number between 0 and 10: "))

    if (chooseNumber > randomNumber):
        print("To high")
    elif (chooseNumber < randomNumber):
        print("To low")
    else:
        print("Bravo")
