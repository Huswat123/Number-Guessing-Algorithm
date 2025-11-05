#  Number Guessing Game (Python)

A simple Python command-line game where you try to guess a randomly generated number between 1 and 100.

##  How It Works
- Import random number from library which can be between **1** and **100**.
- You enter guesses until you find the correct number.
- After each guess, the program tells you whether your guess is **too high**, **too low**, or **correct**. using WHILE, ELSE , and ELIF
- It also counts the number of attempts you made.
- BREAK at the end of the code breaks the loop after the guess is correct

##  Example
Import random
cl
number = random.randint(1, 100)
attempts = 0

print("Guess a number between 1 and 100")

while True:
    guess = int(input("Enter your guess: "))
    attempts += 1
    if guess < number:
        print("Too low!")
    elif guess > number:
        print("Too high!")
    else:
        print(f"Correct! You guessed it in {attempts} tries.")
        break


##  How to Run

1. Have **Python 3** installed.
2. Save the game code as `guess.py`.
3. Open a terminal (or command prompt) and run:
   ```bash  python guess.py


