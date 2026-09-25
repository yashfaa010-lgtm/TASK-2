# WD_4_TicTacToe_byte

Two-player Tic Tac Toe in vanilla JavaScript. Built for Task 4 of the Arithmatrix AVIP 2026 Web Development track.

**Live demo:** magnificent-souffle-ba6e25.netlify.app

## How to play
Players X and O share one screen and take turns tapping a square. The first to get three in a row wins. A full board with no winner is a draw.

## Features
- 3x3 grid with clear turn labels ("Player X's turn")
- Neon arcade look with hand-drawn X and O animations, sound effects (toggle) and confetti on a win
- Two modes: 2 Players on one screen, or vs an unbeatable CPU (minimax algorithm)
- Detects wins (highlighted line) and draws
- "New round" keeps the score and alternates who starts; "Reset scores" starts over
- Scoreboard for X, O and draws
- Responsive, with large touch targets; keyboard and screen-reader friendly (buttons with labels, live status)

## Run it
Open `index.html` in a browser. No build step.

## Screenshots
**Screenshot 1: **
<img width="1885" height="910" alt="image" src="https://github.com/user-attachments/assets/f9fbf7f6-f125-4d7e-9e85-0b16282c9fb8" />

**Screenshot 2: **
<img width="1887" height="893" alt="image" src="https://github.com/user-attachments/assets/b9898f9c-cf84-4320-bef0-11d1076756cd" />


## Breakpoints
Tuned for phone (<600px), tablet (600-1000px) and laptop/desktop (>1000px), with extra tweaks under 380px for small phones.
