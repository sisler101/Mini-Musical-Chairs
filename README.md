# Mini Musical Chairs

## Project Description

- Created a miniaturized musical chairs game that is intended to be played with your fingers.  
- The chairs are initially all facing the players.  
- The LCD display prompts the users to enter the number of people playing, and then spins the chairs not in play to face the opposite direction.
- The players must wait until the music stops playing to put their finger on a chair, and the player who can't find a chair to place their finger on is eliminated. (An LED strip was also included in case the music can't be heard. The LED strip is initially one color and then flashes quickly to indicate the music has stopped.)  
- Play continues until only one player remains.  
- The chairs reset and the LCD will once again prompt the user to input the number of players.

## Components
- Two Arduinos (used two to solve power issues that arose from having many components)
- Laser Cut box made from wood
- LCD Display
- Three buttons (add, subtract, enter)
- Speaker
- LED Strip
- Four Servo Motors
- Five 3D printed chairs
- Four 3D printed connectors to attach the servo motors to the chairs

## Code
Written using Arduino (variation on C++). Two .ino files were used: the primary to act as the controller and deal with the main functions of the game, the secondary to control the LED strip and respond to the controller when a round has ended.

## Fritzing Diagram
![Fritzing Diagram](https://github.com/sisler101/Mini-Musical-Chairs/blob/main/Fritzing-Diagram.png?raw=true)
