# ernesto-guerravallejos.github.io

Personal website of Ernesto Guerra-Vallejos, published with GitHub Pages.

## Editing content

All text lives in two files, so the page design never needs to be touched:

- `data/profile.json` — name, headline, photo, bio, contact email, Google Scholar link, expertise
- `data/publications.json` — publications (title, authors, journal, figure, description, BibTeX…)

The easiest way to edit them is **[Pages CMS](https://app.pagescms.org)**: sign in with GitHub, open this repository and use the "About me" and "Publications" forms. Saving publishes automatically within a minute or two.

## How publications are shown

- **Selected Publications:** the first 5 papers marked *Selected*, in the order of the list.
- **More Publications:** every other paper, newest first, 5 per page with `‹ 1 2 3 ›` pagination.

## Animated figures and video links

Each publication's **Figure** can be a still image or an animated GIF/WebP. Optionally, clicking it can open:

- **Figure link** — any web page (YouTube, a project page…), or
- **Or upload a video** — an MP4 stored in `videos/` on this site.

**Jump to a spot** makes the link land on one place of the destination: an exact phrase from that page
(e.g. `Simulation results`), a section id (`#demo`) or, for a video, a start time (`#t=30`).
Figures with a link show a small play badge, and a "Video" link (or custom **Link text**) is added next to Paper · bibtex · DOI.

## Files

- `index.html` — page layout and styles (reads the JSON files above)
- `img/` — photo, paper figures and browser-tab icon
- `videos/` — optional videos uploaded from Pages CMS
- `favicon.ico` — browser-tab icon (bird)
- `.pages.yml` — Pages CMS configuration (the editing forms)
