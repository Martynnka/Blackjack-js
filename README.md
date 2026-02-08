# Blackjack Game (JavaScript)

A simple **Blackjack game** built from scratch while learning **JavaScript, HTML, and CSS**.

The goal of this project was to practice:
- JavaScript logic
- DOM manipulation
- Conditional statements
- Arrays and objects

## Features
- Start a new Blackjack game
- Draw new cards
- Automatic Blackjack (21) detection
- Game-over logic when exceeding 21
- Dynamic UI updates using JavaScript

## Tech Stack
- HTML
- CSS
- JavaScript (Vanilla)

## How the game works
- The player starts with two random cards
- Cards with value:
  - `2–10` → face value
  - `J, Q, K` → 10
  - `A` → 11
- If the total sum:
  - is **less than 21** → player can draw a new card
  - equals **21** → Blackjack 🎉
  - exceeds **21** → game over

## What I learned
- How to generate random values in JavaScript
- How to update the DOM dynamically
- How to manage game state (`isAlive`, `hasBlackJack`)
- How to structure simple game logic without libraries

## Run locally
Just open `index.html` in your browser.

## Future improvements
- Add betting system using player chips
- Add dealer logic
- Improve UI and animations
- Add reset game button
