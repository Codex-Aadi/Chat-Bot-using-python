# Chat-Bot-using-python
I have made this chat Bot project to learn f strings and basic if/else statements

name = input("Hello! What is your name? ")

print(f"Nice to meet you, {name}!")
age_input = input("How old are you? ")

age = int(age_input)

bot_age = 3

age_difference = age - bot_age

print(f"You are {age_difference} years older than me. I'm only {bot_age} years old!")

color = input("What's your favourite color? ")

print(f"Oh, {color} is a beautiful color!")

user_input = input("who is your favourite bollywood actor?")

print(f"Lol, {user_input} is trash! Actually whole Bollywood is trash")

joke = input("BTW wanna hear a joke?")

if joke == "Yes":
    print("Your Life")
    
else:
    print ("Baaakaaaaa")
