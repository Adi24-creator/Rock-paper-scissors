
# Rock-paper-scissors
print("Welcome to the rock paper scissor's game")
user_choice = input("Enter the sign: \n") 
import random
random_sign = random.choice(["rock", "scissor","paper"])
if user_choice == "rock":
  if random_sign == "rock":
    print("rock \nDraw")
  elif random_sign == "scissor":
    print("scissor \nYou won")
  else:
    print("paper \nYou lost") 
if user_choice == "paper":
  if random_sign == "rock":
    print("rock \nYou won")
  elif random_sign == "scissor":
    print("scissor \nYou lost")
  else:
    print("paper \nDraw")
if user_choice == "scissor":
  if random_sign == "rock":
    print("rock \nYou lost")
  elif random_sign == "scissor":
    print("scissor \nDraw")
  else:
    print("paper \nYou won")
