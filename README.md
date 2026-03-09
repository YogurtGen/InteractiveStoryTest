# Di Antara Halaman dan Hati

> *Between the Pages and the Heart*

A small interactive web story — a personal experiment in turning an old piece of writing into something you can actually experience in a browser.

**[▶ Read it here](https://yogurtgen.github.io/InteractiveStoryCarlotta/)**

---

## About

This is a test project. A while back I wrote a short romantic fantasy story in Notion — the kind you write late at night and probably never share. It was about a library, a mysterious girl named Carlotta, and the strange feeling of meeting someone who doesn't quite belong to your world.

This is that story, rebuilt as an interactive experience with scenes, animations, ambient sound, and a bit of atmosphere.

It's not a game. It's not a visual novel (well, kind of). It's just a story you click through.

---

## What's inside

- 13 scenes with unique backgrounds and particle animations
- Falling books, crystal cracks, maple leaves, page storms, rose petals
- Web Audio API sound effects — no external audio files needed (except optional background music)
- Custom character art support via `mascot.png` and `profil.png`
- Fully responsive — works on desktop and mobile
- Single HTML file, no frameworks, no dependencies (except Google Fonts)

---

## Running it

Just open `di-antara-halaman-dan-hati.html` in any modern browser. No build step, no server required.

If you want background music, drop an `audio.mp3` file in the same folder. It'll play automatically when the reader hits **Mulai Membaca**.

To use your own character art:
- `mascot.png` — the main character illustration shown in the story
- `profil.png` — the avatar used in dialogue bubbles

Both fall back to a built-in SVG if the files aren't found.

---

## Controls

| Device | Action |
|--------|--------|
| Desktop | Click anywhere / Arrow keys / Space / Enter |
| Mobile | Swipe left or tap the next button |

---

## Tech

Pure HTML + CSS + vanilla JS. No libraries. The audio is synthesized on the fly using the Web Audio API (oscillators, noise buffers, gain envelopes). Animations are CSS keyframes and Canvas 2D.

---

## Note

This is a personal project and a learning experiment — not a polished product. The story is original, written in Indonesian, loosely inspired by something I once wrote privately. Carlotta is a fictional character.

---

*Made with too much coffee and a Notion draft from a quiet night.*
