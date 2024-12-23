# Snake Game in Go

This project is a simple implementation of the classic Snake game using Go. It allows you to control the snake to collect food, which causes the snake to grow longer. The game ends when the snake collides with itself or the wall.

### Features:
- Classic snake gameplay.
- Use keyboard input to control the snake.
- Snake grows as it eats food.
- Game ends when the snake hits the wall or itself.

Below is a screenshot of the game in action:

![Screenshot of Snake Game](captures/Screenshot%20from%202024-12-17%2018-49-13.png)
![Screenshot of Snake Game](captures/Screenshot%20from%202024-12-17%2018-51-21.png)
![Screenshot of Snake Game](captures/Screenshot%20from%202024-12-17%2018-51-50.png)

## Project Setup and Execution

Follow these steps to set up and run the Snake game on your local machine.

### Prerequisites

Before running the Snake game, ensure you have the following installed:
- **Go**: Go programming language installed on your system. You can download and install it from [Go's official website](https://golang.org/dl/).
- **Terminal (CLI)**: You need a terminal or command line interface to execute Go commands.

### Steps to Execute

1. **Clone the Repository**
   Clone the project repository to your local machine:

   ```bash
   https://github.com/Abhishek-Jain-1925/Snake-Game-with-GO.git
   cd snake-game;
   ```
   
2. **Install Dependencies**
   This project uses the github.com/hajimehoshi/ebiten package for handling terminal graphics and keyboard inputs. Install the required dependency using:
   
   ```bash
   go install github.com/hajimehoshi/ebiten/v2@latest
   ```
   ```bash
   sudo apt-get install libx11-dev
   ```
   ```bash
   sudo apt-get install libxrandr-dev
   ```
   ```bash
   sudo apt-get install libgl1-mesa-dev libglu1-mesa-dev libglx-dev
   ```
   ```bash
   sudo apt-get install libxcursor-dev
   ```
   ```bash
   sudo apt-get install libxinerama-dev
   ```
   ```bash
   sudo apt-get install libxi-dev
   ```
   ```bash
   sudo apt-get install libxxf86vm-dev
   ```
   ```bash
   go mod tidy
   ```
  
3. **Run the Game**
   Execute the following command to run the Snake game:


   ```bash
   go run main.go
   ```
   Once the game starts, you will see a simple text-based interface representing the game board.
   
    Controls
        Use the Arrow keys to control the snake.
        The game will display your score in the terminal.
        Press Ctrl + C to exit the game.

**Game Rules**
- **Objective:** Eat food (represented by a White Square Box) to grow longer.
- **Game Over:** The game ends if the snake collides with the walls or itself.
- **Score:** Your score is displayed on the top-left corner of the screen. The score increases as you eat food.
    
    

### Detailed Description of the Project
The Snake Game in Go is a terminal-based implementation of the classic Snake game. The project uses the `termbox-go` library to interact with the terminal for handling keyboard input and rendering the game. It involves fundamental game mechanics such as moving the snake, growing it when it eats food, and handling collision detection.

Key features include:
1. **Snake Movement**: The snake moves continuously in the terminal. The user can control the direction using arrow keys.
2. **Food**: Random food appears on the screen, and when the snake eats it, its size increases.
3. **Collision Detection**: The game ends if the snake collides with the walls or itself.

This project provides a solid foundation for understanding game development principles and Go's capabilities in handling terminal-based interfaces.


**Package Author** - github.com/hajimehoshi/ebiten

