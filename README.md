# Python Adventure Game

A text-based adventure game built with Python and GitHub Copilot where players explore locations, make strategic choices, and search for legendary treasure.

## Overview

This interactive CLI game demonstrates fundamental Python concepts including variables, lists, loops, conditionals, and functions. Players navigate through a dark forest or mysterious cave, making decisions that determine their fate.

## Game Features

- **Interactive storytelling** with player choices
- **Multiple paths** - Forest or Cave route
- **Win/Lose scenarios** based on decisions
- **Replay option** to try different paths
- **GitHub Copilot assisted** development

## How to Play

### Game Objective
Find the legendary treasure by making the right choices and overcoming obstacles.

### Game Flow
1. Enter your name
2. Choose your path (Forest or Cave)
3. Make strategic decisions at each stage
4. Win by finding the treasure or lose and try again

### Winning Paths

**Forest Route**
1. Enter the dark forest
2. Follow the river
3. Find the treasure! 

**Cave Route**
1. Enter the mysterious cave
2. Light a torch
3. Find the treasure!

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/adventure-game.git
cd adventure-game

# No dependencies needed - uses Python standard library
```

## Usage

```bash
# Run the game
python adventure_game.py
```

## Game Structure

```
Start
├── Choose Path
│   ├── Forest Path 
│   │   ├── Follow river → WIN 
│   │   └── Climb tree → LOSE 
│   │
│   └── Cave Path 
│       ├── Light torch → WIN 
│       └── Move in dark → LOSE 
└── Replay or Exit
```

## Code Structure

The game consists of modular functions:

- `start_game()` - Game introduction and initial path selection
- `forest_path()` - Handles forest route logic and outcomes
- `cave_path()` - Handles cave route logic and outcomes
- `restart_game()` - Manages replay functionality

## Technologies Used

- **Python 3.7+**
- **VS Code**
- **GitHub Copilot** - AI-assisted code generation

## GitHub Copilot Assistance

This project was developed with GitHub Copilot, which helped with:

- Function generation and structure
- Conditional logic implementation
- Code optimization and refinement
- Game narrative suggestions
- Error handling improvements

## Learning Outcomes

This project demonstrates:

- Python functions and modular code
- Conditional statements (if/elif/else)
- User input handling
- Control flow and loops
- String formatting
- Recursion for game replay
- AI-assisted development with GitHub Copilot

## Project Files

```
adventure-game/
├── adventure_game.py     # Main game script
├── BUILDI_1.IPY         # Jupyter notebook version
├── README.md
└── report.pdf           # Development summary
```

## Requirements

- Python 3.7 or higher
- No external dependencies

## Author

Built as a course-end project for practicing Python fundamentals with GitHub Copilot.

---

**Enjoy the adventure and good luck finding the treasure!**
