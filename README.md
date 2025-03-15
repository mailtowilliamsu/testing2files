# Bouncing Balls Animation

A simple HTML and JavaScript animation featuring bouncing balls of different colors (red, blue, green, and white) within a rectangular canvas.

## Features

- 20 balls with different sizes bounce around the canvas
- Each ball has its own random velocity and direction
- Balls change direction when they hit the edges of the canvas
- Balls collide with each other using realistic physics
- Four colors: red, blue, green, and white
- Control buttons to start, pause, and exit the animation

## Controls

- **Start**: Begin or resume the animation
- **Pause**: Temporarily stop the animation while preserving the current state
- **Exit**: Stop the animation completely and display a message

## How to Run

1. Download or clone this repository
2. Open the `index.html` file in any modern web browser
3. Use the control buttons at the bottom of the page to manage the animation

## Customization

You can modify the following in the `script.js` file:
- Number of balls: Change the `ballCount` variable
- Ball sizes: Adjust the random radius calculation
- Ball speeds: Modify the velocity range in the Ball constructor
- Colors: Add or remove colors from the `colors` array
- Physics: Adjust the `restitution` value for bouncier or less bouncy collisions

## Requirements

- Any modern web browser with JavaScript enabled 