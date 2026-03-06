# Memory Matching Game

A browser-based Memory Matching Game built with jQuery, HTML, and CSS as a web development lab assignment. Famous Landmarks theme, difficulty levels, leaderboard, and sound effects — all in a single HTML file.

## Live Demo

Download and open `memory-game.html` directly in any browser. No server or installation required.

## How to Play

1. Select a difficulty — Easy, Medium, or Hard
2. Click any card to flip it and reveal the landmark
3. Flip a second card to find its match
4. Matched pairs stay face-up — unmatched pairs flip back after 1 second
5. Find all pairs to win. Your score is saved to the leaderboard!

## Features

- Famous Landmarks card theme — Eiffel Tower, Colosseum, Taj Mahal, Big Ben and more
- Card flip animation with match pulse effect
- Only 2 cards can be flipped at a time — board locks during comparison
- Move counter and live timer (starts on first flip, stops on win)
- Sound effects on match and miss via Web Audio API — no external audio files needed
- Three difficulty levels — Easy (8 cards), Medium (12 cards), Hard (16 cards)
- Leaderboard tracking top 5 scores per difficulty, sorted by moves then time
- You Win screen showing final moves and time, auto-saves score to leaderboard

## How to Run

```bash
git clone https://github.com/your-username/memory-matching-game.git
cd memory-matching-game
# open memory-game.html in your browser
```

No build step. No npm install. No server needed.

## Project Structure

```
memory-matching-game/
└── memory-game.html    # Complete game — HTML, CSS, and JS in one file
```

## Technologies Used

| Technology | Usage |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Animations, transitions, grid layout |
| JavaScript ES6 | Game logic and state management |
| jQuery 3.7.1 | DOM manipulation and events |
| Web Audio API | Match and wrong sound effects |

## Skills Practiced

- jQuery selectors and event handling
- DOM manipulation
- Game state management
- CSS keyframe animations and 3D transforms
- Fisher-Yates shuffle algorithm
- Leaderboard sorting logic

## License

MIT
