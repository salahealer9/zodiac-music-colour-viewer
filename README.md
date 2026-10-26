# Zodiac · Music · Colour — Interactive Wheel

Explore an interactive zodiacal coordinate wheel connecting **12 signs**, **36 decans**, **360 degrees**, pitch classes, elemental musical triads, planetary-face annotations and two selectable colour-design conventions. You can play individual tones and simultaneous three-note chords.

The viewer is a **standalone, self-contained HTML application**. Open `index.html` in a browser, or serve it from GitHub Pages. Sound starts only after you enable it. No third-party scripts, fonts, trackers or network APIs are required by the application.

## How to use it

1. Rotate/select the wheel, enter an exact longitude, or use the keyboard to explore the decans.
2. Turn **Sound on** to try **♪ Note** or **♫ Chord**; use **Stop** to silence it. Adjust octave (3/4/5) and tuning (432 or 440 Hz).
3. Choose between angle-hue and pitch-class-hue conventions, explore the historical annotations, and export a state link, JSON state or SVG wheel.

## Mathematical and scientific scope

The fixed **432 Hz circle tuning** uses an author-defined **unequal-interval** twelve-note sequence; it is **not 12-tone equal temperament**. Its octave-4 base is `[252,270,288,306,324,342,360,378,414,432,468,486]` Hz. The **440 Hz** option uses conventional 12-TET. The mathematical digit-9 pattern is part of an explicit design convention, **not** a demonstrated physical relationship between the zodiac, sound, colour, human physiology or planets.

The wheel's equal 30° signs and 10° decans are a mathematical coordinate convention, not an astronomical map of constellation boundaries. Elemental triangles illustrate the model's specified note/chord correspondences. Planetary and Renaissance annotations are qualified historical layers; authorship of the underlying twelve-note sequence remains unresolved. Colours are selected visualisation rules, **not** a physical equivalence between light frequency and sound.

The visible **OKLCH** rendering is the default design. The selectable legacy **HSL** comparison does not meet the tested wheel-label contrast target and is explicitly labelled accordingly. No complete accessibility audit or cross-browser/device certification is claimed.

## Reproducibility and version identity

- Release: **v0.3.4 A07**, public-facing wrapper derivative dated **26 October 2026**.
- Source baseline: **author-GPG-signed, scoped P4-T1 v0.3.4 A07 certification closeout** dated 25 October 2026.
- Frozen A07 original SHA-256: `24fb93969652f32f34ddb534d6b2dbd07b263dbef9e948ff6e22d10a245896e9`.
- Certified scientific-data JSON SHA-256 (unchanged within `index.html`): `bb7237171dd1a89340b25b899a4fdcc10d376b38533c58c31c8fa4ba84947594`.
- `index.html` differs from the frozen original in **two user-visible strings only**: the browser title and review-status pill; the entire CSS, JavaScript and embedded scientific JSON are byte-identical. The exact public-release diff and release verification procedure are provided in the separately retained release-custody package.
- The embedded dataset's historical `EXPLORATORY_VIEWER_NOT_P4_CERTIFIED` label identifies its *original schema/build-stage status*. It is retained verbatim to preserve the certified scientific-data bytes. It must not be confused with the subsequent signed, qualified v0.3.4 A07 certification closeout.

This repository contains **only the public application and public documentation**. The research and evidence repository is separate and remains private; signed internal records, test logs and historical source images are not distributed here.

## Rights and acknowledgements

Copyright © 2026 Salah-Eddin Gherbi for original software and arrangement, subject to any third-party rights. **No open-source software licence is granted or implied by this public release candidate.** Public access to the running website does not itself grant permission to redistribute or adapt its code. Any future licence choice will require the author's express approval. No exclusive rights are claimed over zodiac signs, musical concepts or historical facts.

Historical concepts and terminology are presented for mathematical investigation and educational exploration. Original third-party diagrams or scanned images are not included.
