# Drop Text

> Type until it breaks. Watch your words fall.

Drop Text is an experimental web toy that turns typing into a physical experience. Words accumulate on screen — then collapse, tumble, and pile up at the bottom. Part creative tool, part ambient toy, part screen poem.

---

## What it does

You type. Lines stack up. When they overflow, the oldest line shakes and falls apart — characters scatter with physics, land in a heap, and slowly fade away. The more you type, the messier it gets.

You can pick up fallen characters with your cursor and drop them again.

---

## Modes

Four atmospheres, switchable with the button in the top-right:

| Mode | Feel | Sound |
|------|------|-------|
| **B — Bright** | Clean, warm daylight | Soft pentatonic keys |
| **S — Sunny** | Golden light rays through the window | Slow drifting detune |
| **R — Rain** | Blue-grey sky, rain streaks, splashes | Rain, water drops |
| **N — Night** | Deep indigo, drifting stars, meteors | Crickets, wind |

**F — Flow** mode (top-left): characters fall line by line as you write, not in batches. For a more meditative pace.

---

## Design

- Typography: [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) + Noto Serif SC
- Physics: [Matter.js](https://brm.io/matter-js/)
- Sound: Web Audio API (synthesized, no samples)
- No backend. No framework. One HTML file.

---

## Try it

→ **[droptext.pages.dev](https://droptext.pages.dev)** *(coming soon)*

Or clone and open `index.html` directly in a browser.

---

## Details

- Characters are rigid bodies — they stack, bounce, and sleep when still
- Gravity pulls fallen text down; friction keeps it from sliding forever
- Each mode has its own sound palette: scales shift between pentatonic, major, blues, and natural minor
- Night mode: stars slowly drift across the sky; meteors appear every 10–20 seconds
- Rain mode: streaks fall, splash on landing
- Faded text blurs out over four drops

---

## Made by

Design by [Mog](mailto:daftlamb@gmail.com)

Part of the *\*It* series of single-purpose creative tools.

---

*No frameworks were harmed in the making of this.*
