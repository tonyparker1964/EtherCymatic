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
- Three looks, each a physics simulation driven by the sound:
  - **Sand on a plate:** the sound drives the plate's vibration modes. A grain only leaves the surface where the plate's acceleration beats gravity (Γ = Aω²/g > 1); there it is thrown a random short distance, elsewhere friction holds it. Grains random-walk out of the moving zones and stop on the still lines.
  - **Water (Faraday instability):** shaking modulates gravity for the liquid and pumps surface waves at half the drive frequency (parametric resonance). Above a threshold, ripples of the length set by water's real dispersion grow out of tiny random motion and settle into a pattern. Simulated on a grid as a parametrically driven, damped wave equation.
  - **Light from sound (sonoluminescence):** the sound's pressure swings make gas bubbles swell and collapse (Rayleigh–Plesset equation). A violent collapse heats the gas to thousands of kelvin and it glows; colour from that temperature, brightness ∝ T⁴. Bubbles attract each other (Bjerknes force) and gather into clusters.
- Golden-ratio cascade tone (Dan Winter): partners at f·φⁿ whose sums and differences land on other members of the series. The arithmetic is exact; Winter's wider claims (implosion, gravity, consciousness) are hypotheses, not established physics.
- Colour from the sound's pitch raised by whole octaves into visible light, or pick any spectrum colour, rainbow, white on black, or a black-on-white negative.
- Quality: Standard (720p), HD (1080p) or Ultra 4K (3840 × 2160, with 4× supersampling and individual sand grains). Images and videos are rendered at that size, not enlarged from the screen.
- Save still images (or have one saved automatically as each word's tone finishes) and record video with sound.

## Files

- `index.html` – the app (one self-contained file, no build step)
- `about.html` – the about page

## Run it locally

Open `index.html` in Chrome, Edge or Safari. Nothing to install.
