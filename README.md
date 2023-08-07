# Conway's Game of Life Web App

## Table of Contents
* [About Game of Life](#about-game-of-life)
* [Rules of the Game](#rules-of-the-game)
* [Key Features](#key-features)
* [Tech Stack Used](#tech-stack-used)
* [Installation](#installation)
* [Images of ](#images-of-working-app)


## About Game of Life
Welcome to the Conway's Game of Life Web App! This React-based interactive application allows you to explore the fascinating world of cellular automata through John Conway's famous Game of Life. Create intricate patterns, watch them evolve, and enjoy the mesmerizing dynamics that emerge.

## Rules of the Game
#### At every generation / timestamp:
- A live cell dies if it has fewer than two live neighbors.
- A live cell with two or three live neighbors lives on to the next generation.
- A live cell with more than three live neighbors dies.
- A dead cell will be brought back to live if it has exactly three live neighbors.
#### The simulation continues onward to the next generation until a stable layout is achieved.

## Key Features
#### Interactive Simulation
The user can create custom starting layouts and observe their evolution through time.

#### Custom Update Interval
The user can control the speed of the simulation by adjusting the update interval time. Speed it up for a dynamic display or slow it down to observe each generation closely.

#### Start/Stop the Simulation Anytime
The user has the power to start and stop the simulation at any stage, allowing him to closely examine specific generations or patterns.

#### Clear All Cells
Reset the grid to its initial state, where all cells are dead. This feature is particularly useful when you want to start fresh or experiment with new patterns.

#### Random Starting Layout
Generate a random starting layout of living cells to kickstart the simulation. This feature is perfect for exploring the diverse possibilities and patterns that can arise in the Game of Life.
 

## Tech Stack Used
- HTML
- CSS
- JavaScript
- React.js

## Installation

- Clone the repository or download the zip file
```bash
  git clone https://github.com/t-kadre/TalkZone
```

- Install all packages and project dependencies 
```bash
  npm install
```

- Start the server
```bash
  npm run devStart
```
- Website is hosted on port 3000
```bash
  localhost:3000
```
## Images of Working App




