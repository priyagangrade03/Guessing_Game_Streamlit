# Guessing_Game_Streamlit
This is a simple and interactive number guessing game built with Python. It was created as part of a beginner-friendly challenge to practice conditional statements, loops, list handling, and user input.

### A Python-based number guessing game where the player has to guess a randomly chosen number between 1 and 100.

### Instead of just saying "Too high" or "Too low", the game gives relative temperature-based feedback:

- "WARM!" – if the first guess is within 10 numbers of the target.

- "COLD!" – if the first guess is more than 10 numbers away.

### For subsequent guesses:

- "WARMER!" – if the new guess is closer to the number than the previous one.

- "COLDER!" – if the new guess is farther from the number than the previous one.

- Keeps track of all previous guesses using a list.

- Counts the number of attempts and displays the total once the correct number is guessed.

### Uses basic Python programming constructs including:

- random.randint() to generate the target number.

- while loop to continue the game until the user guesses correctly.

- input() to receive user guesses.

- abs() to calculate the distance between guesses and the target.

### Beginner-friendly project designed to practice:

- Loops

- Conditionals

- List operations

- User interaction
