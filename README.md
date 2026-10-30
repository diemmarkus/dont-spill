# Don't Spill

A comic-style soda glass is fizzing over. Tap the bubbles before they reach the top. Keep your phone level, because tilting it pours the soda out.

**Play:** https://diemmarkus.github.io/dont-spill/

## How it plays

- **Levels** last 25 seconds. Each level fills the glass higher and bubbles spawn faster.
- **Bubbles** that reach the surface splash soda onto the table. The fuller the glass, the bigger the splash.
- **Tilt:** the water surface stays level with the real world (device orientation). If the water rises over a rim, it pours out.
- **Game over** when the spill meter hits 100%.

Tilt needs HTTPS. On iPhone, tap **POUR IT!** and allow motion access. Without a motion sensor, a tilt slider and the arrow keys stand in.

## Languages

English, German, French, Spanish, Italian and Portuguese. The game picks the browser's language. You can switch on the start screen, and your choice is remembered. Force a language with `?lang=de` (or `en`, `fr`, `es`, `it`, `pt`). All strings live in the `I18N` table in `index.html`, so a new language is one more entry there.

Single self-contained `index.html` with no build step.
