# Portfolio — Anik Kanti Dev

A terminal-style portfolio: a bash-like shell you can browse by typing commands
(`help`, `neofetch`, `whoami`, `experience`, `skills`, `contact`, `cv`, …) or by tapping the
quick-command buttons on mobile. Try `theme dracula`.

**Live:** https://anikkdev.github.io/portfolio/

## Stack
Plain HTML, CSS and JavaScript in a single `index.html`. No build step, no
frameworks. Font: JetBrains Mono.

## Editing content
All text lives in the `<template id="t-...">` blocks near the bottom of
`index.html` — one per command. To add a command, add a template and register
it in the `SECTIONS` object in the script.

## Run locally
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
