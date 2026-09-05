# YouTube Clone

A responsive, dark-themed clone of YouTube's core layout — built with vanilla HTML, custom CSS, and Bootstrap 5 utilities. Part of an ongoing series of frontend clone projects to practice real-world UI patterns.

## Live Demo
[Live Links](https://justaykhalid.github.io/YouTube-Clone/)


## Features

- **Responsive layout** — mobile-first design with a collapsible sidebar navigation that switches to icon-only on desktop (≥1024px)
- **Dark theme** — YouTube-style dark UI using CSS custom properties for consistent theming across the app
- **Video grid** — fluid card-based layout for video thumbnails, channel avatars, titles, and metadata
- **Search bar** — desktop search input with icon button, hidden on mobile in favor of a compact icon trigger
- **Category pills** — horizontally scrollable filter tags (All, Gaming, Music, Tech, etc.)
- **Bottom/side navigation** — bottom tab bar on mobile, fixed sidebar on desktop, matching YouTube's real navigation pattern

## Tech Stack

- HTML5
- CSS3 (custom properties, Flexbox, media queries)
- [Bootstrap 5.3.8](https://getbootstrap.com/) — grid utilities and form components
- Bootstrap Icons (inline SVG)
- Vanilla JavaScript


## Known Issues / To Do

- [ ] Clean up duplicate/commented-out markup left over from earlier iterations
- [ ] Consolidate repeated CSS rules (some properties like `.video_description` and `.channel_pic` are declared twice)
- [ ] Replace hardcoded video card HTML with JS-generated cards from a data array
- [ ] Add functional search (currently submits to YouTube's search results as a placeholder)
- [ ] Fix minor naming typos (`recomendation_txt`, `Gamming`) for consistency
- [ ] Add hover/active states for nav items and video cards
- [ ] Accessibility pass (ARIA labels, focus states, alt text)

## Notes

This project is a work in progress — the codebase currently has some rough edges (leftover comments, a couple of duplicate CSS declarations, mixed use of classes/IDs in a few places) that I'm actively cleaning up as I iterate.

## Author

Built by [Khalid](https://github.com/justaykhalid) — AYKHALID