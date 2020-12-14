import random

def guess(x):

    random_number=random.randint(1,x)
    guess=0
    while guess!=random_number:
        guess=int(input(f'Guess a number between 1 and{x}:'))
        if guess<random_number:
            print("Guess is too low")
        elif guess>random_number:
            print("Guess is too High")

    print(f'Yay congrats you have guessed correctle and your number is {random_number}:')

guess(10)
