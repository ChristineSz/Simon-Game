# Simon-Game
Game app

What have I learned :

-To use jQuery to select the button with the same id as the randomChosenColour

-To use Google/Stackoverflow to figure out how I can use jQuery to animate a flash to the button selected in step 1. 

-To use Google/Stackoverflow to figure out how you I use Javascript to play the sound for the button colour selected in step 1.

-To use jQuery to detect when any of the buttons are clicked and trigger a handler function. 

-To use jQuery to add this pressed class to the button that gets clicked inside animatePress(). 

-To use Google/Stackoverflow to figure out how I can use Javascript to remove the pressed class after a 100 milliseconds.

-To use use jQuery to detect when a keyboard key has been pressed, when that happens for the first time, call nextSequence()

   -Inside nextSequence(), increase the level by 1 every time nextSequence() is called.

   -Inside nextSequence(), update the h1 with this change in the value of level.

-Create a new function called checkAnswer(), it should take one input with the name currentLevel

-Call checkAnswer() after a user has clicked and chosen their answer, passing in the index of the last answer in the user's sequence.

-Writed an if statement inside checkAnswer() to check if the most recent user answer is the same as the game pattern. If so then log "success", otherwise log "wrong".

-To Restart the Game -Create a new function called startOver()

                     -Call startOver() if the user gets the sequence wrong

                     -Inside this function, I'll need to reset the values of level, gamePattern and started variables. 
