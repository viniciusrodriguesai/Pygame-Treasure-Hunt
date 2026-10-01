# Treasure Hunt prototype

A historical Python/Pygame learning prototype. The current script initializes a window, loads images and sounds, runs a timed event loop and plays a sound when the user clicks.

## Run locally

Create and activate a Python 3 virtual environment, then run from the repository root:

```bash
python -m pip install -r requirements.txt
python "jogo pygame/jogo_pygame.py"
```

A graphical desktop and audio device are required. Assets are resolved relative to the script directory.

## Current scope

The tracked script does not implement a playable treasure-hunt board, exploration, scoring, obstacles or persistent game history. Existing assets and `historico.json` are historical materials, not evidence that those mechanics work.

The bundled media do not have a documented attribution/licensing inventory. Verify their provenance before redistribution or a public demo. The repository's source-code license does not establish rights to third-party media.

## Validation

Paths and imports were inspected during the portfolio audit. Interactive gameplay was not validated; this project should be presented as a learning prototype.

## Source-code license

[MIT](LICENSE).
