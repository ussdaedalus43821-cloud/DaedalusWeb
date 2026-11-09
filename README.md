# Daedalus Web

> **Dependency-free JavaScript.** The whole game is plain JavaScript, HTML and
> CSS in two files: no build step, no framework, no libraries, and nothing
> fetched from a CDN. It runs offline, even straight from a USB drive.

**Daedalus Web**: the browser edition of Daedalus, an open-world space combat
sim that runs entirely in the browser, offline, from a single HTML file. The
desktop edition (Windows, macOS, Linux) is a separate Godot project,
[DaedalusGodot](https://github.com/ussdaedalus43821-cloud/DaedalusGodot),
whose game rules are written in NovaLang.

## Play

Open `index.html` — it's a "tap to play" gate that hands off to the actual game in `daedalus_web.html`.

- Runs fully offline (designed to run from a USB drive on a Tesla center screen, tuned for its 1920×1080 display)
- Gamepad support via the Gamepad API (the Tesla yoke does not work: the game cannot communicate with it)
- Fullscreen toggle available in-game

## Structure

- `index.html` — launcher / title screen
- `daedalus_web.html` — the game itself
