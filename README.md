# MythShelf Public Website

Public-facing GitHub Pages version of MythShelf.

## Pages

- `index.html`
- `shelf.html`
- `wish-shelf.html`
- `writing.html`

## Live data

The public shelf reads from:

`https://docs.google.com/spreadsheets/d/1kd9gestpjoV03IBcvCoEbTo93Ybknr-mm7wiQKLl8DI/export?format=csv&gid=0`

The forms submit to:

`https://script.google.com/macros/s/AKfycbx9A-7XQnXYmffFZso8-eFXh8NqgxiLjqU1TPWwr3Zoh5HqXJTBhGr31hyCe4ASGidc/exec`

## Icon

The site icon is stored as:

`assets/mythicshelf-01.ico`


## Shelf Recommends page

New page added: `recommends.html`

Files added:
- `recommends.html`
- `assets/recommends.css`
- `assets/recommends.js`

The page uses the same Google Sheet CSV as the rest of MythShelf, with `books.csv` as a local fallback. It supports:
- up to 3 selected archetypes;
- up to 9 archetype-blend recommendations;
- archetype constellation SVG shapes;
- a separate book-to-book recommendation engine with Series Path and Myth Path modes.

Recommended Google Sheet columns for best results:
- `SeriesOrder`
- `PrimaryArchetype`
- `SecondaryArchetype`
- `TertiaryArchetype`
- `ArchetypeBlend`
- `ArchetypeRationale`

Navigation has been updated to include `Recommends`.


## Pages
- `index.html` — homepage with dynamic Top Voted Quests
- `about.html` — About MythShelf, featuring the logo crest
- `shelf.html` — Full Shelf
- `recommends.html` — Shelf Recommends tools
- `wish-shelf.html` — Wish Shelf voting/suggestions
- `writing.html` — Writing shelf
