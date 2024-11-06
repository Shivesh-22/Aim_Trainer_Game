# Aim_Trainer_Game

  Overview

    A basic aim trainer game created with Pygame and Python can be found in this repository. The purpose of the game is to assist players in increasing their             accuracy and speed of aim. The user has to click on targets that show up on the screen at random before they vanish. The game keeps track of the player's speed,      hit accuracy, and reaction time.


Features

	•	Random Target Generation: Targets spawn at random locations with varying sizes.
	•	Dynamic Target Growth and Shrinking: Targets grow to a maximum size and then shrink if not clicked.
	•	Score Tracking: Measures hit rate, speed (targets per second), and accuracy percentage.
	•	Game Over Condition: Limited lives are available; missing too many targets ends the game.
	•	End Screen Summary: Displays elapsed time, speed, total hits, and accuracy after the game ends.


Gameplay Instructions

	•	Targets will appear on the screen at random intervals.
	•	Click on a target before it disappears to score a hit.
	•	Missing a target reduces your remaining lives, and the game ends when lives reach zero.
	•	The top bar displays elapsed time, hit count, lives remaining, and speed in targets per second.
	•	When the game ends, an end screen will show your performance metrics.


Technologies Used

	•	Python 3.x: Core programming language used for logic.
	•	Pygame: Library used for rendering graphics, handling events, and managing game loops.


Getting Started

  Prerequisites

  Ensure you have Python 3.x and Pygame installed. You can install Pygame via pip:
            
    pip install pygame

Installation

	  1.	Clone this repository:
       git clone https://github.com/Shivesh-22/aim-trainer-game.git

    2.	Navigate to the project directory:
       cd aim-trainer-game

  Running the Game

    To start the game, run the following command:
        python main.py


Code Structure

	•	main.py: The main script containing the game’s logic, target generation, event handling, scoring, and end screen display.

Game Controls

	•	Mouse Click: Click on targets to score hits.
	•	Close/Exit: Press ESC or click the close button to quit.
