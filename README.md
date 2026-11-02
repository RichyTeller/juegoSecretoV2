# Secret Number Game | Juego del número secreto

An interactive guessing game built with **HTML, CSS and vanilla JavaScript**. Guess a secret number between 1 and 10 and receive feedback after each attempt.

## Features
- Generate a random number from 1 to 10.
- Tell the player whether the secret number is higher or lower.
- Count attempts and display a success message.
- Enable a **New Game** button after a correct answer.
- Track previously generated secret numbers to avoid repeats until the available range is exhausted.

## Run locally
```bash
git clone https://github.com/RichyTeller/juegoSecretoV2.git
cd juegoSecretoV2
```
Open `index.html` in Chrome or launch it with **VS Code Live Server**. No build process is required.

## Project files
- `index.html` — interface and input field.
- `style.css` — visual design.
- `app.js` — game logic, feedback, random-number generation and reset.
- `img/` — interface image assets.

## Technical walkthrough
`condicionesIniciales()` initializes the screen and generates a secret number. `verificarIntento()` compares the player's input with that number, updates the hint and tracks attempts. `reiniciarJuego()` resets the controls.

## Known limitations / future improvements
- The current code does not explicitly reject empty, non-integer or out-of-range guesses.
- The generator logs the secret number to the browser console for debugging.
- After all ten distinct numbers have been used, the generator needs a better reset strategy.

These are good candidates for future validation and testing improvements.

## Source and download
[View the repository](https://github.com/RichyTeller/juegoSecretoV2) · [Download ZIP](https://github.com/RichyTeller/juegoSecretoV2/archive/refs/heads/main.zip)

## What I practiced
DOM updates, functions, conditionals, arrays, random numbers, events and application state.

**Author:** José Ricardo González Carmona
