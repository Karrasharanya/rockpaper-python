import random
user=input("Enter your choice:")
arr=["rock","paper","scissors"]
computer=random.choice(arr)
print(computer," choosen by computer|||||",user," choosen by user")
if(user=="rock" and computer=="scissors"):
  print("user won")
elif(user==computer):
  print("DRAW MATCH")
elif(user=="paper" and computer=="rock"):
  print("user won")
elif(user=="scissors" and computer=="paper"):
  print("user won")
else:
  print("computer won")