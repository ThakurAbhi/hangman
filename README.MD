This implements a hangman game.

Rules for the game:
i. Use the list of movie names provided below,out of which the computer (interpreter) will choose 1 random word.
Movie list:{ Lagaan , Highway ,Thor, Dangal,Newton}

ii.The word should be displayed  in encrypted form and then the user is asked to guess the letters in the word.

iii. The initial score of the player will be 10 points.

iv. If the correct letter is guessed ,display the letter(with correct placement) and 3 points will be awarded else 2 points will be deducted for each wrong guess.

v.The user is allowed  to make further guesses only if the score is greater than 0.If the score is not greater than zero than the game is over and the player loses  the game.

vi. If all the letters are guessed  correctly  then the player wins the game and thus you need to display the score.

 Sample input/output: 

*
score:10
guess a letter: R

correct guess
**R
score:13
guess a letter: Y

incorrect guess
**R
score:11
guess a letter: A

correct guess
*AR
score:14
guess a letter: W

correct guess
WAR
score:17

You win
