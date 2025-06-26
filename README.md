# Flappy Firebolt Edition

A Flappy Bird clone built with Python and Pygame, featuring:
- Firebolt logo as the bird
- Firebolt-red database cylinder pillars
- Dynamic difficulty (speed, gap, and obstacles increase over time)
- Score saving to Firebolt database
- Player name entry in the game window

## Setup Instructions

### 1. Clone the repository
```
git clone https://github.com/tuitejc-firebolt/FlappyFirebolt.git
cd FlappyFirebolt
```

### 2. Create and activate a virtual environment
On macOS/Linux:
```
python3 -m venv .venv
source .venv/bin/activate
```
On Windows:
```
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies
```
pip install -r requirements.txt
```

### 4. Configure Firebolt credentials
Create a `.env` file in the project root with the following content:
```
FIREBOLT_API_ENDPOINT=api.app.firebolt.io
FIREBOLT_API_KEY=your_client_id_here
FIREBOLT_API_SECRET=your_client_secret_here
FIREBOLT_DATABASE=your_database_name
FIREBOLT_ACCOUNT_NAME=your_account_name
FIREBOLT_ENGINE=your_engine_name
```

### 5. Add the Firebolt logo
Place your Firebolt logo PNG at `images/firebolt-logo.png` (already referenced in the code).

### 6. Run the game
```
python flappy_bird.py
```

## Gameplay
- Enter your player name in the game window.
- Press SPACE to flap.
- Avoid the Firebolt-red database pillars.
- The game gets harder as you play!
- Your score and stats are saved to Firebolt after each game.

## Requirements
- Python 3.7+
- Pygame
- python-dotenv
- firebolt-sdk

All dependencies are listed in `requirements.txt`.

---
Enjoy and may your bird soar through the Firebolt clouds!
