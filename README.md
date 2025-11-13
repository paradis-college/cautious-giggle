# cautious-giggle

A Flask web application featuring an interactive movable square game rendered in HTML5 Canvas.

## Requirements

- Python 3.7 or higher
- Flask 3.0.0
- pygame-ce 2.5.6 (used as backend library)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/paradis-college/cautious-giggle.git
cd cautious-giggle
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

Run the Flask application with:
```bash
python app.py
```

Then open your web browser and navigate to `http://localhost:5000`

## How to Play

- Use **Arrow Keys** or **WASD** to move the blue square
- The game runs in your web browser using HTML5 Canvas
- Close the browser tab to exit

## Features

- Flask web server backend
- HTML5 Canvas-based rendering
- Real-time keyboard input handling via JavaScript
- Client-server game state synchronization
- Smooth 60 FPS gameplay
- Player movement with boundary checking
- Input validation for API requests