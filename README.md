# SONAR · a ripple synth in your browser

**Play it:** [ryankhartman.github.io/sonar](https://ryankhartman.github.io/sonar) (works on phone and desktop; turn your sound on)

Tap anywhere on the screen to send a pulse. Each pulse ripples outward like sonar and plays a note: higher on the screen means a higher pitch, and left or right pans the sound between your speakers. Pick a musical scale (Pentatonic, Lydian or Minor) so anything you tap sounds good, or hit **Auto** and let it play itself.

## Why I built it

A small experiment in building something purely for delight: turning a single interaction (a tap) into sound and motion that feels good, works on any device, and needs zero instructions.

## How it works

- **One HTML file.** No framework, no build step, no dependencies beyond a web font.
- **Web Audio API** generates every tone in real time; nothing is pre-recorded.
- **Canvas** draws the ripples, with a calmer animation for people who have reduced motion turned on.
- Notes snap to the chosen scale across three octaves starting at G3, so random taps stay musical.

## Run it locally

Download `index.html` and open it in any modern browser.
