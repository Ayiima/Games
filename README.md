# Basic Tetris HTML Game

This is a basic implementation of the game Tetris, but it's missing a few things intentionally and they're left as further exploration for the reader.

## Further Exploration

- Score
  - When a line is cleared, the score should increase based on the number of lines cleared at once. See https://tetris.fandom.com/wiki/Scoring
  - Display a high score using [localSorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- Next Piece Preview
  - Show the next piece (or pieces) that will enter the playfield. See https://tetris.fandom.com/wiki/Next 
- Hard Drop
  - When the Space key is pressed, the piece should be place as far donw as possible. See https://tetris.fandom.com/wiki/Hard_Drop
- Mobile and touchscreen support
  - Allow the game to be scalled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

## Other Basic Games

- [Snake](https://gist.github.com/straker/ff00b4b49669ad3dec890306d348adc4)
- [Pong](https://gist.github.com/straker/81b59eecf70da93af396f963596dfdc5)
- [Breakout](https://gist.github.com/straker/98a2aed6a7686d26c04810f08bfaf66b)