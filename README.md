# Creative Thinking Cards

An online deck of 52 brainstorming tools you can shuffle and draw from, by category, with a timer and an idea list for running a session.

**Live:** https://comstocd.github.io/creative-thinking-cards/

## Features

- **Draw** 1 card, a 3-card spread (Warm up / Shift / Push), or a Combo of two cards from different suits
- **Filter** by suit: Generation, Perspective Shifts, Limitation, Mental Models, Provocation, In Groups
- **No repeats** until you reshuffle; swap any card on the table
- **Brief, timer, and idea list** built in (saved in your browser only)
- **Browse** and search all 52 cards
- **How to use** guide for solo and group sessions

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app: markup, styles, card data, and script in one file |
| `cards.md` | Plain-text transcription of all 52 cards |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Deploy on GitHub Pages

1. Push these files to the `main` branch.
2. Repo **Settings > Pages > Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site appears at `https://<username>.github.io/creative-thinking-cards/` within a minute or two.

## Editing cards

Card text lives in the `CARDS` array inside `index.html`. Each entry is:

```js
C("cat", "Title", ["Paragraph one", "Paragraph two"], "Optional kicker")
```

`cat` is one of `gen`, `per`, `lim`, `men`, `pro`, `grp`.

## Credits and license

Card content: **Creative Thinking Tools** by [School of Thought](https://schoolofthought.org), created by Jesse Richardson, published under [Creative Commons BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/). Non-commercial use only, with attribution.

App code and session guide: David Comstock, MD. See [LICENSE](LICENSE).
