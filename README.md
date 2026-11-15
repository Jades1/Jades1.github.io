# James Ades: personal website

A one-page personal site about the data science and app projects James Ades has built.
Status: live at https://jamesades.com (GitHub Pages, repository `james-ades/james-ades.github.io`), published 2026-11-13.

## Features

- One page titled with the name "James Ades", with tabs for Apps, Data Science, About, and Contact that jump to each section.
- A hero band with the name, a one-line description, and a button to the projects.
- Twelve project cards, each with a picture where one exists (six so far), a short description, and a "Built with" line where the stack is known.
- Projects with a live site link to it, and their picture is a clickable thumbnail (four apps and the recipe site; five thumbnails).
- A Contact section linking to LinkedIn, ResearchGate, Google Scholar, ORCID, and GitHub. No email address, phone number, or contact form.
- Light and dark modes that follow the visitor's system setting.
- A phone layout with one column of cards and a collapsible menu.
- No trackers, no web fonts, and no requests to any outside server.
- Search metadata: page description, canonical address, and structured data naming the three profiles.

## Preview

Open `index.html` in a browser, or serve the folder locally:

    python3 -m http.server 8000

## Files

- `index.html`: the whole site (inline styles, two small inline scripts for the phone menu).
- `img/`: project pictures, one per card, named `<slug>.png` at 1200 by 750. Holds six pictures so far.
- `robots.txt`, `sitemap.xml`, `CNAME`, `.nojekyll`: publishing files for GitHub Pages at `jamesades.com`.
- `THIRD_PARTY.txt`: credit for the CoHub theme the design is modeled on (MIT license).
- `CLAUDE.md`: working rules and open items for this project.
