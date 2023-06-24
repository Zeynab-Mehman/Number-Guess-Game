# Number-Guess-Game
Number Guessing Game
Simple number guessing game using JavaScript is presented here. The player must submit their guess to see if it matches the randomly generated number, which is between 1 and 15. The game gives comments on whether the guess was accurate, too high, or too low.

Game Rules
The game generates a random number between 1 and 15.
The player enters their guess in the input field and clicks the "Check" button.
If the guess is correct, the game displays a success message along with the number of attempts made by the player.
If the guess is incorrect, the game provides feedback on whether the guess is too high or too low.
The player can continue guessing until they correctly guess the number.
The game keeps track of the number of attempts made by the player.
Code Explanation
The code is structured as follows:
It defines variables to store references to HTML elements such as the input field, check button, result box, guess number display, attempts display, and response display.
The game generates a random number between 1 and 15 using the Math.random() and Math.floor() functions.
An event listener is added to the check button, which triggers when the button is clicked.
Inside the event listener, the player's guess is compared with the randomly generated number.
If the guess is correct, a success message is displayed with the number of attempts made.
If the guess is incorrect, feedback is provided on whether the guess is too high or too low.
The number of attempts is updated and displayed in the guess number display and attempts display elements.
The result box is updated to show the current guess value and the number of attempts made.
