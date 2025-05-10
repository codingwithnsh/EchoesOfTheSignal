# Echoes of the Signal — Extended Edition

Welcome to the extended "Echoes of the Signal" sci-fi mystery thriller game. This README provides an overview and usage instructions so you can experience the narrative-driven exploration in a terminal-based or GUI-based format.
This project took me around 3 months to make. Hope you enjoy it!

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Setup](#setup)
4. [How to Play](#how-to-play)
5. [Code Structure](#code-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Overview
"Echoes of the Signal" is a text- or GUI-based game set aboard an abandoned orbital research station named ECHO-9. Earth has been receiving anomalous transmissions from this station, which was reportedly abandoned five years prior. As Dr. Alex Riven, you explore dark corridors and make crucial decisions about a dangerous, possibly sentient, cosmic signal.

This extended edition provides:  
• A longer playtime (~20 minutes).  
• More branching story paths.  
• Thematically rich setting and puzzles.  

## Features
• Narrative-Driven Gameplay: Uncover the station’s mysteries through text-based interactions or a GUI.  
• Branching Storylines: Multiple endings depending on your choices.  
• Puzzles and Clues: Encounter riddles, circuit box puzzles, and cryptic logs.  
• Replay Value: Try different decisions leading to unique outcomes.  

## Setup
1. Install Python 3 (if not already installed).  
2. Clone or download the repository into a local directory.  
3. Optionally, create and activate a virtual environment (recommended for Python projects):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```
4. Install any requirements (if a requirements.txt is provided):  
   ```bash
   pip install -r requirements.txt
   ```

## How to Play
### Text-Based Version
1. Navigate to the project directory in your command line.
2. Run the text-based game script:
   ```bash
   python mega_adventure.py
   ```
3. Follow the on-screen prompts, read the story, and make your choices by entering the appropriate number.

### GUI Version
1. Install a GUI library (e.g., Tkinter is usually included with Python on most systems).  
2. Run the GUI script:
   ```bash
   python echoes_of_the_signal_gui.py
   ```
3. Use the buttons and on-screen text to progress through the story.

## Code Structure
Below is a simplified overview of the main scripts:

1. mega_adventure.py  
   - Extended text-based implementation with puzzles and branching paths.
2. echoes_of_the_signal_gui.py  
   - A Tkinter-based GUI approach for users preferring a windowed interface.
3. brief_description.md  
   - A concise summary of the game’s storyline and development timeline.
4. step-to-step_guide.md  
   - Detailed instructions for installation, usage, and deployment.
5. README.md (this file)  
   - High-level overview of the project.

## Contributing
1. Fork this repository on GitHub.  
2. Create a new branch for your feature or bug fix.  
3. Commit your changes with clear messages.  
4. Submit a pull request providing details about your modifications.

## License
This project is released under the MIT License. See the LICENSE file for details.
