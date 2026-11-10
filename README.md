<div align="center">

# 🏎 Race Maze
### Pixel Circuit

**A browser-based maze racing game built with HTML, CSS, and JavaScript.**

Navigate procedurally generated mazes, collect coins, customize your car, and reach the finish line.

[View Source Code](./index.html) · [Report an Issue](https://github.com/waltdev16/race-maze/issues)

</div>

---

## About the Project

**Race Maze** is an interactive, pixel-art racing game that combines maze exploration, procedural generation, and pathfinding algorithms.

Players navigate through randomly generated circuits, collect coins, and unlock the finish line to advance through increasingly challenging levels.

The project explores the practical implementation of **Depth-First Search (DFS)** and **Breadth-First Search (BFS)** in game development.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Game structure and interface |
| CSS3 | Styling and responsive layouts |
| JavaScript | Game logic and interactions |
| Canvas 2D API | Rendering vehicles, mazes, and animations |
| DFS | Procedural maze generation |
| BFS | Shortest-path calculations |

The game uses vanilla JavaScript without external frameworks or game engines.

## Gameplay Preview

A preview of Race Maze, featuring procedurally
generated circuits, customizable vehicles,
and coin collection.

<img width="542" height="388" alt="image" src="https://github.com/user-attachments/assets/cee669ab-b78a-4160-bd50-bcdff575f95a" />

## Features

- **Procedural Maze Generation:** Randomly generated circuits using DFS.
- **Progressive Difficulty:** Increasing maze dimensions and coin objectives.
- **Vehicle Selection:** Four different car models.
- **Team Customization:** Twelve racing-team color palettes.
- **Coin Collection:** Collect all coins to unlock the finish line.
- **Pathfinding Assistance:** Optional route visualization powered by BFS.
- **Level Progression:** Advance after completing each circuit.
- **Timer System:** Track your time while playing.
- **Pause and Restart:** Control your current session.
- **Responsive Controls:** Keyboard and touchscreen support.
- **Pixel-Art Graphics:** Custom vehicles and circuits rendered with Canvas.

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Move | Arrow Keys / WASD |
| Select vehicle | Up / Down (garage) |
| Change team | Left / Right (garage) |
| Start / Continue | Enter / Space |
| Show / Hide Route | H |
| Pause / Resume | P |
| Restart Level | R |
| Browser Fullscreen | F11 |

Touchscreen users can navigate using the on-screen directional controls.

## How It Works

1. Select a vehicle and racing-team color palette.
2. Start a level to generate a randomized maze.
3. Navigate through the circuit without crossing walls.
4. Collect all available coins.
5. Reach the unlocked finish line.
6. Advance to the next level.

### Depth-First Search (DFS)

The maze generator uses a randomized, stack-based DFS algorithm.

It starts from an initial cell, visits neighboring cells, removes walls to create passages, and backtracks whenever no unvisited neighbors remain.

This process produces interconnected mazes with different layouts.

### Breadth-First Search (BFS)

BFS is responsible for finding shortest paths between accessible cells.

The algorithm explores neighboring positions using a queue and reconstructs the route by tracking previously visited cells.

Because every movement has equal cost, BFS can determine a shortest path through the maze.

## Development Process

The development of Race Maze can be divided into five main components.

### 1. User Interface

Creating the game layout, garage, menus, buttons, timer, and visual indicators using HTML and CSS.

### 2. Maze Generation

Representing the circuit as a two-dimensional grid and implementing DFS to generate randomized pathways.

### 3. Game Mechanics

Implementing vehicle movement, wall collision detection, collectible coins, level progression, and the finish-line system.

### 4. Pathfinding

Using BFS to calculate paths through the maze and provide optional route assistance.

### 5. Rendering and Controls

Drawing pixel-art elements using HTML Canvas and implementing keyboard and touch interactions.

## What I Learned

Working on this project provided an opportunity to explore and strengthen concepts such as:

- Representing environments using two-dimensional arrays.
- Understanding graph traversal algorithms.
- Applying DFS to procedural generation.
- Using BFS for shortest-path calculations.
- Managing game states and event-driven interactions.
- Rendering graphics through the Canvas 2D API.
- Implementing responsive controls.
- Organizing and documenting a software project.

## Future Improvements

- [ ] Separate HTML, CSS, and JavaScript into independent files.
- [ ] Add automated tests for maze generation and pathfinding.
- [ ] Implement a leaderboard for best completion times.
- [ ] Save player progress locally.
- [ ] Introduce additional game modes.
- [ ] Improve accessibility and mobile controls.
- [ ] Add sound effects and visual transitions.
- [ ] Expand gameplay customization.

## Running the Project

### Option 1 — Download

1. Download the repository as a ZIP file.
2. Extract the downloaded files.
3. Open `index.html` in a modern web browser.
4. Select your vehicle and click **INICIAR**.

### Option 2 — Clone the Repository

```bash
git clone https://github.com/waltdev16/race-maze.git
cd race-maze
```

Open `index.html` in your browser.

**Requirements:** A modern web browser with JavaScript and Canvas support.

No additional installation or dependencies are required.

## Gameplay Video

*A gameplay demonstration will be added soon.*

<!-- Replace this section with your video link or thumbnail once available. -->

## Project Structure

```text
race-maze/
├── index.html      # Game interface, styles, and logic
└── README.md       # Project documentation
```

## Gameplay Video

Watch Race Maze in action! This demonstration
shows the gameplay mechanics, maze navigation,
vehicle customization, and level progression.

https://github.com/user-attachments/assets/ae5072cc-b6dc-4e1a-8e0b-cbe1063751e5

## Authors

- **Walter Santos**
- **Patricia Alvarado**

Programa ¡Supérate! Fundación Frech

---

<div align="center">

**Built to explore algorithms, game development, and problem-solving.**

</div>
