# Chenyu Du — Academic Homepage

Personal academic homepage: https://yuuu-05.github.io/

Static HTML and CSS. Open index.html locally, or run `python -m http.server 8000`. GitHub Pages serves main from the repository root. No build dependencies or tracking scripts.

## Content and layout

The homepage introduces the research direction, highlights HoldLight and RoboBlockly Studio with visible personal contributions and study findings, and provides a compact publication list and background. `research.html` expands the two selected projects into research case studies. Existing `#holdlight`, `#roboblockly`, and `#background` homepage links remain supported.

Research interests follow the CV order: Human–Computer Interaction, Accessibility, XR, Human–Robot Interaction. The homepage uses navigation only above a single name heading. Full papers and workshop papers are listed separately; the equal-contribution notation appears once below the list. Study summaries name the comparison and keep conclusions within the evidence.

Original code and owner-approved assets. Typography and colors follow the owner-selected reference, Lindsay Popowski (https://lipopowski.github.io/): Charter/Georgia/Cambria/Times serif body text, system sans-serif navigation, white background, charcoal text and burgundy (#8c1515) links. The greeting appears once. The full coastal photograph is 380px wide to the left of the introduction on desktop and fills the content width (up to 420px) beneath the greeting on mobile. A 900px WebP derivative reduces the photograph's transfer size from approximately 8.46 MB to 177 KB; the original is retained. Mobile layout uses a single column. The primary content is available without JavaScript.

Only accepted or published work receives paper entries, images, and links. Work under review is represented by broad interests only. Do not publish its titles, author lists, figures, methods, results, PDFs, or videos before acceptance without explicit instruction from the owner.

All HoldLight video links point to the owner-specified release: https://github.com/Yuuu-05/HoldLight/releases/tag/project-demo . Do not restore the superseded local video.

CV is available by email until a public version has been reviewed for unpublished research details.

## Updating

Edit `index.html` for homepage content, `research.html` for project narratives, and `styles.css` for appearance. Store approved public images in `assets/` and documents in `files/`. Review the entire file tree, including unlinked assets, before deployment. Preserve accurate authorship and publication status. Homepage project summaries explain personal contributions; the publication list preserves the formal titles and author lists.

Before publishing, check desktop and narrow-screen layouts, internal links and anchors, image loading, keyboard focus, and publication/resource links. The request-CV link intentionally opens email; do not add the private application CV to this repository.
