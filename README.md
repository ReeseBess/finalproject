# THE BAT HAUNTING GAME
#### Video Demo:  [My Bat Game Video explaination ](https://youtu.be/SyjCDihUIew)
#### Description: 

About the Game : 

1) Click Start to begin the game
2) Use arrow keys to move "Jamal" to left or right
3) Use spacebar key to attack on the bat using the sun sprite
4) Both Jamal and Bat have same life line i.e. "5" chances
5) The Bat dies and you win if the sun sprite touches the bat 5 times
6) Jamal dies if the bat touches him 5 times and the Game will be over.

Backdrops : 

There are 4 backdrops in this game

1) Game Start back drop : This back drop will be displayed at the beginning or start screen, which displays the name of the game with a subtitle.
2) Game Over back drop : This back drop will appear when the bat touches Jamal 5 times and game is over.
3) Woods backdrop : This backdrop will be displayed when the game is started
4) Winner backdrop : This backdrop will be displayed when Jamal defeats the bat.

Coding Part : 
 
* I have written an if condition for moving his position to left or right. If the right arrow key is pressed then Jamal's position changes to +10 steps and he moves towards right.
* And if the left arrow key is pressed then Jamal's position changes to -10 steps and he moves towards left.
* If the spacebar key is pressed then the sun sprite moves from Jamal's position pointing to the bat or the top edge, and if the sun sprite touches the bat a pop sound will be played.
* And Bats life line will be decreased by -1, for this i have used if touching Jamal function 
* For Jamal's to throw the sun sprite also i have used switch to costume function
* Normally Jamal will having costume a, but while throwing the sprite his costume will switch to c,d.
* I have used play sound until done function at different stages like Game Start, Game Over, Winner.
* The bat sprite is navigated to random places using the go to random position function
* And if it touches the edge it will bounce back
* To show the bat as flying i have used switch costume to a, b, d function
* And if the sun sprite hits the bat it will switch to costume c.
* If the bat touches Jamal his life line will reduce by -1, for this i have used if touching Bat function.
* And i have used when key is pressed function for switching to start page when "s" is pressed.
* And i have used if condition for both of their lifelines
* If Jamal's life line is equal to zero then switch backdrop to Game Over.
* If Bat's life line is equal to zero then switch backdrop to Winner.
