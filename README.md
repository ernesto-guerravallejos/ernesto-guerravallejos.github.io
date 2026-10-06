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

## Files

- `index.html` — page layout and styles (reads the JSON files above)
- `img/` — photo and paper figures
- `.pages.yml` — Pages CMS configuration (the editing forms)
