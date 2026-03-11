# Focus Board

Focus Board is a minimal single-page productivity app built with plain HTML, CSS, and vanilla JavaScript. It combines a Pomodoro timer, task tracking, and lightweight browser-only habit insights in a static site that runs by opening `index.html`.

## Features

- Pomodoro timer with editable focus and break durations
- Start, pause, reset, and focus/break session switching
- Clear distinction between completed focus sessions and interrupted/reset sessions
- Task list with add, complete, delete, filter, and `Clear Completed`
- Progress summary with completed tasks count and visual progress bar
- Daily completed focus-session counter that resets when the local date changes
- Adaptive Habit Insights panel with:
  - best-performing focus duration
  - best-performing time window
  - recent consistency label from the last 10 focus outcomes
  - one deterministic recommendation
- LocalStorage persistence for tasks, timer state, daily stats, insight stats, and focus-session history
- Responsive layout with keyboard-friendly controls and visible focus states

## Run locally

1. Download or clone the repository.
2. Open `index.html` directly in any modern browser.

No install step, package manager, backend, or build process is required.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. In GitHub, open `Settings` > `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select your branch and `/ (root)` folder, then save.
5. GitHub Pages will publish the site directly from this repository.

The included `.nojekyll` file keeps GitHub Pages deployment unchanged and simple.

## Personalization Notes

- Personalization happens entirely in the browser using `localStorage`.
- No backend is used.
- No external API is used.
- No external ML library or TensorFlow.js is used.
- The insight panel is deterministic and rule-based, not a real machine learning model.
