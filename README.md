# Dorian Baudry's academic website

Static Hugo/Wowchemy website, deployed to GitHub Pages by `.github/workflows/build.yml`.

## Content

- `content/authors/admin/_index.md`: profile, current introduction and education metadata.
- `content/home/`: homepage sections. The existing `supervision` and `teachings` anchors are retained.
- `content/research/index.md`: Research page. Edit `data/research.yaml` for the three shared research directions and their representative paper references; the homepage uses shorter descriptions from the same file.
- `content/background/`: historical biography, experience and education; the current CV remains a PDF download.
- `content/students/index.md`: Students page. Edit `data/students.yaml` to update the students and internships displayed here and on the homepage.
- `content/publication/<paper>/index.md`: publication metadata and abstracts. `summary` is a short explanation for previews and search; `featured = true` selects the four papers shown on the homepage.

## Publication resources and citations

Use `links = [{name = "Conference", url = "https://..."}]` for additional resource buttons.

Include `outputs = ["HTML", "BibTeX"]` in each publication's front matter. Hugo generates `publication/<paper>/cite.bib` from the title, authors, date, publication type, venue, DOI and resource URLs. The paper page, archive and homepage previews link directly to the download. There is no separate citation file to maintain.

Optional citation fields: `citation_venue` (plain venue name), `citation_volume`, `citation_pages`, and `citation_school` (for a thesis). Use these when the display venue contains extra bibliographic information or the citation needs a separate field.

## Research notes

`content/research-notes/sgb-regret/index.md` provides the stable page for the stochastic-gradient-bandit research note. Its title, author, date and version generate both the displayed citation and the BibTeX download. `projects` in `data/research.yaml` places it below the representative policy-gradient papers.

The current PDF is `static/files/research/sgb-regret.pdf`; the dated version 1 is `static/files/research/sgb-regret-v1-2026-11-16.pdf`. For a revision, add a new dated PDF, update the current PDF and page metadata, and add a `versions` entry. Preserve all previously released dated PDFs and keep the page URL stable. Update the suggested citation in the LaTeX source to match the release metadata.

## Local build

Use Hugo **Extended 0.76.5**, matching the GitHub Pages workflow, with Go available for Hugo Modules:

```sh
hugo --minify
```

For a local preview, run `./view.sh`.

## Presentation

The local presentation layer is in `assets/scss/custom.scss`, with color and font settings in `data/themes/academic.toml` and `data/fonts/academic.toml`. It uses system fonts for body text and Georgia for headings, without remote font requests. Local templates provide the introduction, research overview, publication rows, student lists, accessible navigation and footer.

Research descriptions and publication summaries are editorial copy: check them when updating the associated papers or research priorities. Existing publication URLs and BibTeX output remain unchanged.

Local planning notes, when present, are kept in the ignored `docs/website-next-steps.md` file.
