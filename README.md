# Mastermind Code-Breaking Game

Master Mind is a code-breaking game for two players – a code maker and a code breaker. With four pegs and six colors, there are 6^4 = 1296 different patterns (allowing duplicate colors). Varying the number of colors and the number of holes results in a spectrum of Mastermind games of different levels of difficulty.

In this program, computer plays the role of code maker and user plays the role of code breaker. Code maker (computer) creates a code consisting of 4 or more colors at specific positions, but does not reveal the code to code breaker (user). Code breaker tries to guess the pattern, in both order and color, within 'x' turns, where x is determined based on the difficulty level.

The computer creates a code which has to be quessed by the user. Each guess is made by the user by typing first letter of the colors, for example, G R Y P. Once code is typed, the code maker (computer) provides feedback by displaying m B and n W, where m and n can be a positive integer <= number of positions (for example 1 B, 2 W). B is displayed for each color from the guess which is correct in both color and position. W indicates the existence of a correct color, but placed in the wrong position. Once feedback is provided, another guess is made by the user; guesses and feedback continue to alternate until either the code breaker guesses correctly, or twelve (or ten, or eight) incorrect guesses are made, depending on the difficulty level.

The user can also chose to be code maker and make a secret code and the computer will guess the code in miniumum number of tries. The length of the secret code should be 4. The valid colours are R, O, G, Y, P and V. The secret code can be created with a combination of these colours, with or without repition.
