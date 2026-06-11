# Kathak Tala Practice Tool

A browser-based practice tool for Kathak dancers and musicians. Generates rhythmic tala (taal) cycles with synthesized tabla sounds, adjustable tempo, and a visual theka display.

**Live demo:** [aaryantest.duckdns.org/kathak-taal](http://aaryantest.duckdns.org/kathak-taal)

## Talas Included

| Tala | Matras (Beats) | Vibhag Structure |
|------|---------------|-------------------|
| Teental | 16 | 4 + 4 + 4 + 4 |
| Ektaal | 12 | 2 + 2 + 2 + 2 + 2 + 2 |
| Jhaptaal | 10 | 2 + 3 + 2 + 3 |
| Rupak | 7 | 3 + 2 + 2 |
| Dadra | 6 | 3 + 3 |
| Keharwa | 8 | 4 + 4 |

## Features

- **Synthesized tabla sounds** — Dha, Dhin, Ta, Tin, Na, Ge, Kat, and more, mapped to distinct synthesized voices via [Tone.js](https://tonejs.github.io/)
- **Visual theka** — Each beat displayed with its bol, highlighted in real-time as it plays
- **Tali/Khali/Sam markers** — Clap (✋), wave (🌊), and Sam emphasis clearly marked on the grid
- **Vibhag grouping** — Beats grouped by vibhag with visual separators
- **Adjustable tempo** — 40–240 BPM slider
- **Keyboard shortcut** — Space bar to play/pause
- **Dark theme, mobile responsive**

## How to Use

1. Open the page in any modern browser
2. Select a tala from the buttons at the top
3. Adjust tempo with the slider
4. Press **Play** (or hit Space) to start
5. Watch the beat highlight move through the cycle
6. Practice your footwork, hand gestures, or instrument along with the rhythm

## Tech Stack

- Vanilla HTML/CSS/JS — no build step, no dependencies beyond Tone.js CDN
- [Tone.js](https://tonejs.github.io/) (v14) for Web Audio synthesis and transport scheduling
- Nginx reverse proxy for live serving

## Why This Exists

Free, good-quality tala practice tools for Indian classical dance are surprisingly scarce. Most existing options are either paid apps, low-quality MIDI, or YouTube videos with fixed tempos. This tool fills that gap — it's free, runs in any browser, and gives dancers full control over tempo and tala selection.

Built for [NrityaSADAN](http://aaryantest.duckdns.org/nrityasadan), a Kathak dance initiative.
