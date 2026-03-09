# QuestLog

QuestLog is a multi-page adventure-themed web project built with semantic HTML and CSS.  
Users launch routes from the World Map, review mission status in Quest Log, and complete checklist objectives on dedicated quest pages.

## Tech Stack

- HTML5
- CSS3

## Features

- Semantic page structure (`header`, `nav`, `main`, `section`, `footer`)
- Responsive layout with Flexbox/Grid patterns
- Lightweight motion and micro-interactions
- Accessibility support:
  - Skip link
  - Visible focus states
  - `prefers-reduced-motion` support
  - In-page `Reduce Motion` toggle
- Route risk and safety UI:
  - Risk badges (`Low`, `Medium`, `High`, `Restricted`)
  - Safety callouts on quest pages

## Page Roles

- `index.html`: home and route overview
- `map.html`: world map quest launch surface
- `quest-log.html`: mission status dashboard (no quest launch actions)
- `quest-emerald.html`, `quest-dunes.html`, `quest-reef.html`, `quest-canyon.html`: active quest pages
- `quest-crystal.html`: locked endgame route
- `team.html`: team role overview
- `styles.css`: shared styling, layout, animation, accessibility, and component styles

## Run Locally

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in your browser (or run with a simple local server / Live Server).

## Project Notes

- Quest launch is intentionally handled by `map.html`.
- Quest Log is intentionally a status/management view.

## Bonus Feature

Created an example AI assistant intended to show what it could like for a user who might need some help navigating the map.
Includes an input box, and a familiar interface so users immediately know what to do.
