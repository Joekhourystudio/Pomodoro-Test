# Mojo Jojo's Pomodoro

A minimal, single-file Pomodoro timer in the browser. Set a focus intention, run 25-minute work blocks and 5-minute breaks, and control the timer with Start, Pause, and Reset.

## Features

- **Work / Break phases** — 25 min work, 5 min break; timer auto-switches when a phase ends
- **Intention input** — Optional “What’s your focus for this session?” before starting; it’s shown during the work phase and hidden when you pause or reset
- **Controls** — Start, Pause, Reset
- **No build step** — Plain HTML, CSS, and JavaScript; open `index.html` in a browser

## How to use

1. Open `index.html` in a modern browser (Chrome, Firefox, Safari, Edge).
2. Optionally type a focus intention in the text field.
3. Click **Start** to begin the work phase. The intention (if any) is displayed and the input is hidden.
4. Use **Pause** to stop the timer; the intention field reappears so you can change it before starting again.
5. Use **Reset** to go back to 25:00 work and show the intention field again.
6. When the work timer hits 0:00, it switches to a 5-minute break; when the break ends, it switches back to 25 minutes of work.

## Tech

- One file: `index.html` (inline CSS and JS)
- No frameworks or dependencies
- Works offline after the file is loaded

## License

Use and modify as you like.
