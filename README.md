# Roberta Santiago, portfolio

Personal website. Ten case studies, three bilingual books and an interactive CV, as one self-contained page plus three reader pages.

No build step, no dependencies, no framework. Every file is plain HTML with its CSS and JavaScript inline and its images embedded, so it runs from a web server or straight off a disk.

## Files

| | |
|---|---|
| `index.html` | The site. Case studies, the wider work grid, the CV page, the motivations research and the accessibility panel. |
| `teoria-do-design.html` | Teoria do Design / Design Theory. Nine chapters, 143 illustrations, Portuguese and English in one file. |
| `empresas-do-futuro.html` | Empresas do futuro / Companies of the Future. Twelve chapters. |
| `simplificando-a-digitalizacao.html` | Simplificando a digitalização / Simplifying Digitalisation. Five sections. |
| `Roberta_Santiago_CV.pdf` | Downloadable CV. |
| `og-card.png` | Social preview image, 1200 by 630. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are, with no Jekyll processing. |

## Accessibility

Built to WCAG 2.1 AA, which is the standard EN 301 549 and the European Accessibility Act point to.

Every page carries a preferences panel, bottom right, offering three text sizes, a dyslexia-friendly typeface and a high-contrast palette. Choices persist per device across all pages. Full keyboard operation with a visible focus ring, a skip link on first tab, and Escape to close. Every image on the site and every one of the 143 book illustrations carries a real description in both languages.

## Publishing

GitHub Pages, from the default branch, root folder.

The metadata in `index.html` assumes the site is served at `https://betstg.github.io/portfolio/`. If the repository is named something other than `portfolio`, three tags need the new path: `link rel="canonical"`, `og:url` and the two image URLs.

## Author

Roberta Santiago. Founder and lead product designer, Kolabs.
