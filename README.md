import random

player = int(input("Chose a number from 1 to 3:(1 for Rock, 2 for Paper, 3 for Scissors): "))
computer = random.randint(1,3)

print(f'computer chose {computer}')

if player == 1 and computer == 3:
    print("You won!")
elif player == 2 and computer == 1:
    print("You won!")
elif player == 3 and computer == 2:
    print("You won!")
elif player == 1 and computer == 2:
    print("You lost!")
elif player == 2 and computer == 2:
    print("It's a tie!")
elif player == 3 and computer == 1:
    print("You lost!")
elif player == 1 and computer == 1:
    print("It's a tie!")
elif player == 2 and computer == 1:
    print("You won!")
elif player == 3 and computer == 3:
    print("It's a tie!")
else:
    print("Chose a number from 1 to 3")
