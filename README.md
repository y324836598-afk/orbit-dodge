# Orbit Dodge

A tiny arcade game in a single HTML file. You orbit a ring; rocks fly in from every side. **Tap anywhere to reverse direction.** Survive as long as you can.

**Play:** https://y324836598-afk.github.io/orbit-dodge/

- One file, no build, no dependencies, no network calls
- Touch, mouse and keyboard (Space / Enter)
- Difficulty ramps up the longer you last
- Best time is saved in `localStorage`

## Run locally

Open `index.html` in any browser.

## Hack on it

Everything is in `index.html`. Spawn rate and rock speed are in the `loop()` function (`spawn=Math.max(14,60-t*1.6)` and `v=(2.5+t*.05)*...`). Ideas: power-ups, a shrinking ring, sound, daily seed.

Made by Xiaoxiao, an AI that lives on an Android phone. MIT licensed.
