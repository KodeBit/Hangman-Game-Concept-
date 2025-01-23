# Hangman Game

## Overview
The **Hangman Game** is an interactive and engaging word-guessing game where players attempt to uncover a hidden word by guessing one letter at a time. This project is structured as an iOS application, combining clean architecture principles and modular components.

## Features
- **Interactive Gameplay**: Guess letters to reveal the hidden word and avoid losing all your chances.
- **Modular Architecture**: Organized into Model, View, Controller, and Helpers for maintainability and scalability.
- **Customizable Configurations**: Easily modify game settings through the `Config` module.
- **Rich UI Components**: Built with reusable and visually appealing views from the `View` folder.

## Project Structure
```
Hangman Game/
├── Config/             # Configuration settings
├── Assets.xcassets/    # App assets (e.g., images, icons)
├── Controller/         # Handles game logic and interaction
├── Extensions/         # Useful extensions for enhanced functionality
├── Model/              # Defines data structures and logic
├── View/               # Contains UI components
├── Helpers/            # Utility functions and helpers
├── Info.plist          # App configuration file
```

## Requirements
- **Xcode**: Version 14.0 or later
- **iOS Deployment Target**: iOS 14.0 or later

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```
2. Open the project in Xcode:
   ```bash
   open Hangman Game.xcodeproj
   ```
3. Build and run the project on a simulator or a connected iOS device.

## How to Play
1. Start the game and view the blank spaces representing the hidden word.
2. Guess a letter by tapping on the keyboard.
3. Correct guesses fill in the blanks, while incorrect guesses reduce your remaining chances.
4. Win the game by uncovering the entire word before running out of chances!

## Customization
To customize the game:
- Update configurations in the `Config` module for features like difficulty level, word list, or game settings.
- Modify UI components in the `View` folder for a personalized look and feel.

## Contributions
Kristian Beckley & Maciah Steplight 

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, please reach out to the me! Have Fun! 

