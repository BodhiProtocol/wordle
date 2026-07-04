# Wordle — BodhiProtocol

> Guess the hidden word. Kids mode: 3 letters, 8 tries, 1 hint. Adult mode: 5 letters, 6 tries, no mercy.

[![Play Now](https://img.shields.io/badge/Play%20Now-live-1D9E75?style=flat-square)](https://bodhiprotocol.github.io/wordle/)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

---

## How to Play

- Guess the hidden word in the given number of tries
- After each guess, tiles reveal how close you are:
  - 🟩 **Green** — right letter, right spot
  - 🟨 **Yellow** — right letter, wrong spot
  - ⬜ **Grey** — letter not in the word

## Modes

| | Kids | Adult |
|---|---|---|
| Word length | 3 letters | 5 letters |
| Tries | 8 | 6 |
| Hint | 1 free hint | None |

## Features

- Arrow keys + on-screen keyboard
- Works on mobile
- Dark mode
- Zero dependencies — works offline
- Single HTML file

## Tech Stack

Vanilla HTML · CSS · JavaScript · No frameworks · No build step

## Run Locally

```bash
# any static server works
python -m http.server 8080
# then open http://localhost:8080
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

---

**Built with [Claude AI](https://claude.ai) · MIT Licensed · [BodhiProtocol](https://github.com/BodhiProtocol)**
