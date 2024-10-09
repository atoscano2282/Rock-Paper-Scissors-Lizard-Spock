#
#        project : Rock, Paper, Scissors, Lizard, Spock.py
#        author : Angela Toscano-Mendez <atoscano2718086@woonsocketschools.com>
#        date written: 10/08/2024
#
#   description: Im creating a Rock, Paper, Scissors, Lizard, Spock Game where yuo can play more than once and it will take score on how many times each player wins / and or loses

print()

# explaning the Rules of the game to the player's

print("""The rules of the game are pretty simple 
you have to choose one of 5 options them being : Rock, Paper, Scissors, Lizard, Spock
and depending on what you choose and what teh other person chooses the out come will be diffrent 
for example if you choose Rock and the other person chooses paper they win because paper wins rock but if you choose Scissors insted you win because they win paper and so on""")

print()

# Getting the name of each player

playerOne = input("Player one what's your name?: ")

print()

playerTwo = input("Player two what's your name?: ")

print()
# Explaning how the game goes / starts
print("""In this game you will have to input 
            [R] for Rock 
            [S] for Scissors
            [P] for Paper
            [L] for Lizard
            [SP] for Spock 
         Please use Captal letters!!!!""")
# Scoring process

score1 = score2 = 0
isPlaying = True

while isPlaying:

    print()

    chooseYourAction1 = input("Player one choose you action: ")
    chooseYourAction2 = input("Player two choose you action: ")
# If player one chooses Rock [R]
    print()

    if chooseYourAction1 == "R":
        if chooseYourAction2 == "R":
            print("Draw")
        elif chooseYourAction2 == "SP":
            print(playerTwo,"Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "P":
            print(playerTwo, "Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "L":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1
        elif chooseYourAction2 == "S":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1

# If player one chooses Paper [P]

    if chooseYourAction1 == "P":
        if chooseYourAction2 == "P":
            print("Draw")
        elif chooseYourAction2 == "L":
            print(playerTwo,"Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "S":
            print(playerTwo, "Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "SP":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1
        elif chooseYourAction2 == "R":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1

# If player one chooses Scissors [S]

    if chooseYourAction1 == "S":
        if chooseYourAction2 == "S":
            print("Draw")
        elif chooseYourAction2 == "R":
            print(playerTwo,"Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "SP":
            print(playerTwo, "Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "P":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1
        elif chooseYourAction2 == "L":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1

# If player one chooses Lizard [L]

    if chooseYourAction1 == "L":
        if chooseYourAction2 == "L":
            print("Draw")
        elif chooseYourAction2 == "S":
            print(playerTwo,"Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "R":
            print(playerTwo, "Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "SP":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1
        elif chooseYourAction2 == "P":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1

# If player one chooses Spock [SP]

    if chooseYourAction1 == "SP":
        if chooseYourAction2 == "SP":
            print("Draw")
        elif chooseYourAction2 == "L":
            print(playerTwo,"Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "P":
            print(playerTwo, "Wins Flawless Victory!!!!")
            score2 = score2 + 1
        elif chooseYourAction2 == "S":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1
        elif chooseYourAction2 == "R":
            print(playerOne, "Wins Flawless Victory!!!!")
            score1 = score1 + 1

# End of round one
            print(playerOne, "scored" ,score1 , "points.")

            print()

            print(playerTwo, "scored", score2, "points.")

    # == Play again?
    ask = input("Would you like another round? : ")
    if ask != "Y" :
        isPlaying = False
#
if score1 > score2:
    print(playerOne, "Wins the duel with" , score1, "points!")
elif score2 > score1:
    print(playerTwo," Wins the duel with" ,score2, "points!")
else:
    print("The duel ended in a draw!")
