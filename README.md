# Meowdoku 🐾

A cute, hand-drawn-style **cat sudoku** for the browser — a single `index.html`, zero dependencies, no build step.

Inspired by [kayleenasser/Meowdoku](https://github.com/kayleenasser/Meowdoku), a Unity Android sudoku app with hand-drawn cat UI. This is an independent web remake with a working **Continue** save system and full keyboard controls.

## Play

Open `index.html` in any modern browser — that's it. Or visit the GitHub Pages URL once enabled.

## Features

- **Real generated puzzles** — every board has a unique solution, guaranteed by a solver during generation
- **4 difficulties** — Easy (45 givens) · Medium (38) · Hard (32) · Expert (27)
- **3 lives** — paw-strike tracker; three mistakes and it's game over
- **Notes mode** — pencil turns blue, jot candidates without risk
- **Eraser, pause (board naps behind a blur), timer**
- **Continue** — autosaves after every move; resume exactly where you left off
- **Keyboard play** — `1`–`9` place · `Backspace` erase · `N` notes · arrow keys move
- Accessible: focus rings, ARIA labels, reduced-motion respected, responsive phone→desktop

## Tech

Single-file vanilla HTML/CSS/JS. Sudoku generation via randomized backtracking + uniqueness verification. Design language: icy-blue sky, ink-doodle cat, chunky bubble type (Baloo 2) with pencil handwriting (Gaegu), wobbly hand-drawn borders.

## Credits

- Design inspiration and gameplay flow: [kayleenasser/Meowdoku](https://github.com/kayleenasser/Meowdoku) (MIT) by Kaylee Nasser
- Frontend-design craft guided by the `frontend-design` skill via [reskill](https://github.com/kanyun-inc/reskill)

## License

MIT
