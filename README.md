# Magic-8-Ball
The Magic 8 game, also known as the Magic 8-Ball, is a toy used for fortune-telling or seeking advice. The game consists of a black ball resembling a pool ball, with a white number 8 printed on it. Inside the ball, there is a 20-sided polyhedron, with each side displaying a different answer to a yes-or-no question. To use the Magic 8 game, the user must hold the ball and ask a yes-or-no question, then shake it to reveal an answer. The answers range from positive ("It is certain") to negative ("Don't count on it") to neutral ("Reply hazy, try again"). The Magic 8 game has been popular since its introduction in the 1950s and remains a classic toy for both children and adults.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python magic8.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first line imports the random module.

* The ```magic8ball()``` function is defined to generate responses to user input.

* The user is prompted for a question input, which is stored in the response variable.

* A list of 8 possible answers is defined in the ```Eightball_answers``` variable.

* If the user enters "quit" in response to the prompt, the program ends.

* Otherwise, a randomly selected answer is printed from the ```Eightball_answers``` list using the ```random.choice()``` function.

* A new line is printed for spacing.

* The ```magic8ball()``` function is called again, which prompts the user for another question.

* The ```magic8ball()``` function is called one final time at the end of the code to start the program.
