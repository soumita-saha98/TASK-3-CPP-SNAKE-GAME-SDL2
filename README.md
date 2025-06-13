# TASK-3-CPP-SNAKE-GAME-SDL2
COMPANY : CODETECH IT SOLUTION PVT.LTD
NAME : SOUMITA SAHA 
INTERN ID : CTO4DN493
DOMAIN C++ PROGRAMMING 
DURATION 4 WEEKS
MENTOR :NEELA SANTOSH

This C++ program implements a classic Snake game using the SDL2 library, along with SDL_ttf for text rendering and SDL_mixer for sound effects. The game runs in a 640x480 window divided into tiles, and features a moving snake that grows in size when it eats a fruit, accompanied by a sound effect.

Key Components:

Game Initialization: SDL, SDL_ttf, and SDL_mixer are initialized at the start. A window and renderer are created, and a font and a sound file (eat.wav) are loaded.

Main Menu: A basic text-based menu is displayed, where the player can press ENTER to start or ESC to quit.

Gameplay Loop:

The snake is controlled using arrow keys.

Movement occurs at a set time interval (delay), which decreases as the game progresses to increase difficulty.

The snake grows when it eats a fruit, score increases, and a sound is played.

Collision with the walls or itself ends the game.


Game Over Screen: Displays a “Game Over” message, the final score, and prompts the player to restart or quit.

Rendering: The fruit is red, and the snake is green. The score is displayed using SDL_ttf.


Functions:

spawnFruit(): Randomly places a fruit on the board.

checkCollision(): Detects wall or self-collisions.

moveSnake(): Moves the snake based on direction and handles fruit collection.

drawText(), drawGame(), showGameOver(), showMainMenu(): Responsible for rendering visuals and text.

resetGame(): Resets variables for a new game session.


Overall, this is a simple, well-structured Snake game using SDL2, featuring sound, score tracking, and smooth graphics rendering.


>>OUTPUT:
![Image](https://github.com/user-attachments/assets/0b196e4a-b279-4339-bdfe-bbb5eef24eb1)
