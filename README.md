# C176 - Hangman Word Guessing Game

A classic hangman-style word guessing game ("Guess Me!") implemented with jQuery and Bootstrap.

## Features

- Random word selection from a word bank (word, category hint, and letter count)
- Letter buttons fill the blank slots when they match the target word
- 5 lives — each wrong guess decrements life
- Category-based hint displayed alongside the blanks
- Win/lose detection with result messaging

## Tech Stack

- **HTML5 / CSS3** (custom `style.css`)
- **jQuery 3.6** — DOM manipulation and game logic
- **Bootstrap 4.5** — responsive layout and buttons

## Project Structure

```
├── index.html   # Game page with alphabet buttons and layout
├── game.js      # Game logic (word bank, fillBlanks, click handling)
├── style.css    # Custom styling
└── assets/      # Background and UI images
```

## Installation

1. Clone the repository.
2. No build step required.

## Usage

1. Open `index.html` in a web browser (jQuery and Bootstrap load from CDN).
2. Read the category hint, then click alphabet buttons to guess the word.
3. Fill all blanks before your 5 lives run out to win.
