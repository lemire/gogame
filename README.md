# Bouncing Ball Game

A simple game written in Go.

## Description

Control a paddle to keep the bouncing ball in play. You have 3 lives. Score points by hitting the ball with the paddle. If the ball falls off the bottom, you lose a life. When all lives are gone, the game returns to the start menu.

## Controls

- **Left Arrow**: Move paddle left
- **Right Arrow**: Move paddle right
- **Space**: Start game (from menu)

## Assets

- `ball.png`: A 16x16 red square image for the ball.
- `bounce.wav`: A short beep sound played on bounce.

## How to Run

1. Ensure you have Go installed.
2. Clone or download the repository.
3. Run `go run main.go` or `go build` then `./gogame`.

The game window will open showing the start menu. Press Space to begin playing.

## Dependencies

- github.com/hajimehoshi/ebiten/v2
- github.com/ebitengine/oto/v3