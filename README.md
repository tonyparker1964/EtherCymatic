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
- Three looks: sand on a vibrating plate (Chladni patterns), water in a dish, and plasma (writhing filaments from a glowing core, like a plasma globe).
- Colour from the sound's pitch raised by whole octaves into visible light, or pick any spectrum colour, rainbow, white on black, or a black-on-white negative.
- Save still images (or have one saved automatically as each word's tone finishes) and record video with sound.

## Files

- `index.html` – the app (one self-contained file, no build step)
- `about.html` – the about page

## Run it locally

Open `index.html` in Chrome, Edge or Safari. Nothing to install.
