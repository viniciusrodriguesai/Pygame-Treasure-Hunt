# Treasure Hunt prototype

A historical Python/Pygame learning prototype. The current script initializes a window, loads images and sounds, runs a timed event loop and plays a sound when the user clicks.

## Run locally

Create and activate a Python 3 virtual environment, then run from the repository root:

```bash
python -m pip install -r requirements.txt
python "jogo pygame/jogo_pygame.py"
```

A graphical desktop is required. Audio is optional: startup continues without sound if the audio backend is unavailable. Assets are resolved relative to the script directory.

## Current scope

The tracked script does not implement a playable treasure-hunt board, exploration, scoring, obstacles or persistent game history. Existing assets and `historico.json` are historical materials, not evidence that those mechanics work.

The bundled media do not have a documented attribution/licensing inventory. Verify their provenance before redistribution or a public demo. The repository's source-code license does not establish rights to third-party media.

## Validation

The script was executed with Pygame 2.6.1 and SDL dummy video/audio drivers; all bundled resources loaded and a posted QUIT event ended the loop. This checks startup/resources/shutdown, not interactive gameplay. Unused NumPy imports were removed, so the prototype needs only Pygame.

## Source-code license

[MIT](LICENSE).
