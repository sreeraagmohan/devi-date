# Kitten, will you go out with me?

A small animated invitation to dinner at Sea Strings, Sanlitun, on a Saturday.

One self-contained `index.html`. No build step, no dependencies, no network calls.
Open the file, or visit the Pages URL.

## What's in it

- Flat SVG scene: a tea cat and a labrador pup under string lights, with a
  planted sign. Tails wag, eyes blink, bulbs flicker, waves drift. Tap the cat.
- Five strings you can strum with a thumb. Real audio, synthesised with the Web
  Audio API on a pentatonic scale — no sound files.
- Paw-print confetti on RSVP.
- Mobile-first, light and dark themes, `prefers-reduced-motion` respected.

## Fonts

[Jost](https://github.com/indestructible-type/Jost) (display) and
[Karla](https://github.com/googlefonts/karla) (body) are embedded as base64
`woff2` data URIs, because the page has to render identically on any phone with
no font CDN available. Both are licensed under the
[SIL Open Font License 1.1](https://openfontlicense.org).

Everything else is written by hand.
