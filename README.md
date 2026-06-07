# Snake Game

A classic Snake game that runs in the browser, served by a minimal Python HTTP server.

## Requirements

- Python 3.6+

## How to start the server

```bash
python3 server.py
```

The server starts on **http://localhost:8000** and opens the game in your default browser automatically.

Press **Ctrl+C** in the terminal to stop the server.

## How to play

| Key | Action |
|-----|--------|
| Arrow keys | Move the snake |
| Any arrow key | Start / restart the game |

- Eat the red food to grow and score points.
- Hitting a wall or your own body ends the game.

## Files

```
snake_game/
├── index.html   # Game (HTML + CSS + JS, no dependencies)
├── server.py    # Python HTTP server
└── README.md    # This file
```
