your_name = 'Desmond'
print(f'Hello, {your_name}! Welcome to Python')

first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")
full_name = first_name + " " + last_name
full_name_upper = full_name.upper()
print("Full name in uppercase:", full_name_upper)

age = int(input("Enter your age: "))
years_left = 100 - age
print(f"You will turn 100 in {years_left} years.")

score = float(input("Enter your test score: "))

# Determine the grade based on the score
if score >= 90:
    grade = 'A'
elif score >= 80:
    grade = 'B'
elif score >= 70:
    grade = 'C'
elif score >= 60:
    grade = 'D'
else:
    grade = 'F'

# Print the grade
print(f"Your grade is: {grade}")

age = int(input("Enter your age: "))

has_license = input("Do you have a driving license? (yes/no): ").strip().lower()

if age >= 18 and has_license == 'yes':
    print("You are allowed to drive.")
else:
    print("You are not allowed to drive.")




import random

dice_roll = random.randint(1, 6) 

print(f"You rolled a {dice_roll}.")


import random

def get_computer_choice():
    """Randomly select rock, paper, or scissors for the computer."""
    choices = ['rock', 'paper', 'scissors']
    return random.choice(choices)

def get_user_choice():
    """Get the user's choice and validate it."""
    while True:
        user_choice = input("Enter your choice (rock, paper, scissors): ").strip().lower()
        if user_choice in ['rock', 'paper', 'scissors']:
            return user_choice
        else:
            print("Invalid choice. Please choose rock, paper, or scissors.")

def determine_winner(user_choice, computer_choice):
    if user_choice == computer_choice:
        return "It's a tie!"
    elif (user_choice == 'rock' and computer_choice == 'paper') or \
         (user_choice == 'paper' and computer_choice == 'scissors') or \
         (user_choice == 'scissors' and computer_choice == 'rock'):
        return "You win!"
    else:
        return "You lose!"

def play_game():
    computer_choice = get_computer_choice()
    user_choice = get_user_choice()
    
    print(f"Computer chose: {computer_choice}")
    print(f"You chose: {user_choice}")
    
    result = determine_winner(user_choice, computer_choice)
    print(result)

if __name__ == "__main__":
    play_game()



    favorite_foods = ['Pizza', 'Burger', 'Sushi', 'Tacos', 'Pasta']

favorite_foods.append('Ice Cream')

favorite_foods.insert(2, 'Salad')

favorite_foods.remove('Tacos')

favorite_foods.sort()

print("Final list of favorite foods:", favorite_foods)




friends = (Anene, Great, Segun, Adefisan, Great)

for i in range(5):
    friend_name = input(f"Enter the name of friend {i+1}: ")
    friends.append(friend_name)
    
print("List of friends:", friends)
# Sir i dont know it is not defining



GitHub is a web-based platform that provides version control and collaborative tools for managing software projects.
# key feature: Team members can comment on and review code changes to ensure quality and consistency.


First you download vs code on your sysem
after the installatin u go to the the extension and download the python extention like pylance 
and that is all


    
