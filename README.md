# python-project

snake water gun game

Snake Water Gun is one of the famous two-player game played by many people.
It is a hand game in which the player randomly chooses any of the three forms i.e. snake, water, and gun.
Here, we are going to implement this game using python.

The code starts by importing the random module.
This module provides a random number generator, which is used in this program to generate different types of objects (snake, water, gun) on each round of the game.
Next, the code sets up some variables: n (the number of rounds in the game), rounds (the number of rounds played so far), and options (a list containing snake, water, and gun objects).
The next line calculates user_win and comp_win.
These are two counters that will keep track of how many computers wins and player wins have been achieved so far in the game.
Next, the code loops through all the possible combinations of snake, water, and gun objects.
For each combination, it calculates how many computers wins or player wins would be achieved if that particular object was chosen as part of the strategy for that round.
Finally, it stores these values in variables named rounds_with_object1(), rounds_with_object2(), and so on.
This way, when a particular object is chosen during a round of play (by either player), the program can easily determine how many more rounds need to be played before that object can be used again.
The code will create a game of Snake where each round is divided into two parts.
In the first part, the snake will move on the screen and water will be randomly placed below it.
The gun can be used to shoot the snake and if it hits, the snake will die.
In the second part, the player has to guess which direction the snake is going in order to avoid getting hit by the gun.
If they get it right, they win; if not, they lose.
The code begins by checking to see if the user has inputted a valid option.
If not, the user is prompted for an option and given a chance to correct any errors.
If the user has inputted a valid option, the code checks to see if that option is one of the three required options.
If it isn’t, then the code randomly chooses an option from those three and continues processing.
If the user has inputted one of the required options, then the code uses random.choice() to choose an action from among those three: round, snake, or water.
The code will print out the following: Round : 3 Snake – ‘s’ Water – ‘w’ Gun – ‘g’
The code starts by assigning the value of the computer to a random variable.
This variable will be used to determine the winner of each round.
Next, the code checks to see if the player is playing as either w or g. If so, then different variables are updated based on which player is chosen.
If the player is not playing as either w or g, then another check is made to see if a computer is playing as w. If it is, then user_win is incremented and comp_win is decreased.
If the computer is playing as g, then user_win and comp_win are both increased.
Finally, if the player chooses to play as s, both user_win and comp_win are increased again.
The code then loops through all of the rounds in the game and prints out a message indicating who won that particular round.
The code also updates variables for each round so that they reflect how many rounds have been played thus far in the game.
The code will check to see if the computer is playing as either ‘s’ or ‘g’.
If so, it will check to see if the player has won the round.
If not, it will announce that a draw has occurred.
The code also keeps track of how many rounds have been played and updates the appropriate message accordingly.
