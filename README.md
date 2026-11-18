# James Ades: personal website

A one-page personal site about the data science and app projects James Ades has built.
Status: live at https://jamesades.com (GitHub Pages, repository `james-ades/james-ades.github.io`), published 2026-11-13.

## Features

- One page titled with the name "James Ades", with tabs for Apps, Data Science, Legal, About, and Contact that jump to each section.
- A full-width hero with a photo of the San Diego skyline, the name, a one-line description, and a button to the projects. The menu sits over the photo and becomes a white bar once the page scrolls.
- Thirteen project cards, each with a picture, a short description, and a "Built with" line where the stack is known. Under Apps, the Recipe Recommendation System is a wide card on its own row (picture left, text right on wider screens), followed by two rows of three: Better Habits, Rent vs. Own, Time Tracker; then Budget, learning_app, Adaptive Typing Trainer. Data Science has six cards in rows of three, led by the published paper "Education and Crime across America: Inequity's Cost", which links to the paper. An incomplete last row is centered.
- A Legal section: a wide card for the case citator with a link to an interactive example, and six text cards (the mediation packet builder and five Claude Code skills: case-law retrieval, evidence extraction, redline, operative version, verify the predicate).
- A case citator example page at `citator/`: a network of 50 published California cases colored by signal; selecting a case shows its place on the four-step status ladder and the cases that cite it, grouped by treatment, each with the quoted passage and its page. The page says its signals reflect the passages read when the sample was made and are not a current check of any case. It is kept out of search indexes.
- A short Publications list at the bottom of Data Science: three published papers in APA style, the name in bold, each title linking to the paper's DOI. No menu tab.
- Five of the Data Science pictures are illustrations made from invented data, and each says so in its caption and in the image.
- Projects with a live site link to it, and their picture is a clickable thumbnail (four apps and the recipe site under Apps, and the paper under Data Science; six thumbnails).
- A Contact section linking to LinkedIn, ResearchGate, GitHub, and Instagram. Google Scholar and ORCID are small text links in the footer and are also in the page's search metadata. No email address, phone number, or contact form.
- An About paragraph that links to the Sammen founder page at sammenhomes.com/about.
- Light and dark modes that follow the visitor's system setting.
- Two columns of cards on tablets, and a phone layout with one column and a collapsible menu.
- No trackers and no requests to any outside server: the fonts (Montserrat and Open Sans) and every picture are served from the site itself.
- A "JA" favicon.
- Search metadata: page description, canonical address, and structured data naming the six profiles and the Sammen founder page.

## Preview

Open `index.html` in a browser, or serve the folder locally:

    python3 -m http.server 8000

## Files

- `index.html`: the whole site (inline styles, small inline scripts for the phone menu and the header).
- `img/`: project pictures, one per card, named `<slug>.png` at 1200 by 750 (thirteen), and `hero.jpg`.
- `citator/`: the case citator example (`index.html`, `data.js`). Built in `Projects/case_citator_app` and copied here.
- `fonts/`: Montserrat and Open Sans (woff2) with their OFL license texts.
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`: the site icon.
- `robots.txt`, `sitemap.xml`, `CNAME`, `.nojekyll`: publishing files for GitHub Pages at `jamesades.com`.
- `THIRD_PARTY.txt`: credits for the CoHub theme the design is modeled on (MIT license), the two fonts, and the hero photo.
- `CLAUDE.md`: working rules and open items for this project.
