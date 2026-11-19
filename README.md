# Ether's Cymatic

A browser app that turns words, tones, songs and your voice into glowing cymatic light patterns.

**Open the app:** https://tonyparker1964.github.io/EtherCymatic/
**About:** https://tonyparker1964.github.io/EtherCymatic/about.html

## Features

- Type words: each word plays as one tone. In Exact tuning every word gets its own precise pitch (anagrams too); musical tunings (pentatonic, chromatic, solfeggio) pick a note from the sum of the letter values, so words can share tones. Or play the whole phrase as one tone, or letter by letter as a melody.
- Words can sound as a tone, as a spoken word (the browser's voice; the pattern follows the word's exact tone), or spoken over their tone.
- Pure tones from 20 to 2000 Hz, with sine, triangle, square and saw waves.
- Upload songs as a playlist; the strongest pitch drives the pattern.
- Live microphone input.
- Real plate physics (on by default): an ideal 30 cm × 1 mm brass plate whose modes resonate at f = 18.1 Hz × (n² + m²). Every overtone in the sound drives the plate, so a sine and a square wave look different, and sand only settles clearly near resonant pitches.
- Three looks, each built the way the real thing forms:
  - **Sand:** tens of thousands of simulated grains (up to 160,000 in 4K) bounce wherever the plate moves and come to rest on its still lines.
  - **Water:** a Faraday-wave surface lit by a ring light, as in CymaScope photographs. Squares in the capillary range, hexagons at low pitches, ripple size from real surface-tension physics, with natural lattice defects and ripples from the dish wall.
  - **Plasma:** self-organised filaments of a dielectric-barrier discharge, a flickering hexagonal lattice of micro-discharges with a faint honeycomb glow; strong overtones add a second, rotated lattice.
- Colour from the sound's pitch raised by whole octaves into visible light, or pick any spectrum colour, rainbow, white on black, or a black-on-white negative.
- Quality: Standard (720p), HD (1080p) or Ultra 4K (3840 × 2160, with 4× supersampling and individual sand grains). Images and videos are rendered at that size, not enlarged from the screen.
- Save still images (or have one saved automatically as each word's tone finishes) and record video with sound.

## Files

- `index.html` – the app (one self-contained file, no build step)
- `about.html` – the about page

## Run it locally

Open `index.html` in Chrome, Edge or Safari. Nothing to install.
