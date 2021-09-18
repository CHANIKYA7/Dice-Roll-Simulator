# Dice-Roll-Simulator
Rolling of one or more dice using the random module and rolling of single dice  using the For loop

# Rolling of single dice


import random

min = 1
max = 6
s = random.randint(min,max)
print("rolling the dice")
print(".......")
print(f" the value is :{s}")




# Rolling two dice at a time

import random
min = 1
max = 6
print("rolling the dices")
print(".......")
s1 = random.randint(min, max)
s2 = random.randint(min, max)
print("the values are :")
print(f"{s1} {s2}")



# using loop

import random

min = 1
max = 6
roll_again = 'yes'
while roll_again == 'yes' or roll_again =='y':
    print("rolling the dices")
    print("......")
    print("......")
    print(random.randint(min,max))
    print(random.randint(min,max))
roll_again = input("roll dices?")












