# Dorian Baudry's academic website

Static Hugo/Wowchemy website, deployed to GitHub Pages by `.github/workflows/build.yml`.

## Content

- `content/authors/admin/_index.md`: profile, current introduction and education metadata.
- `content/home/`: homepage sections. The existing `supervision` and `teachings` anchors are retained.
- `content/background/`: historical biography, experience and education; the current CV remains a PDF download.
- `content/students/index.md`: Students page. Edit `data/students.yaml` to update the students and internships displayed here and on the homepage.
- `content/publication/<paper>/index.md`: publication metadata and abstracts. `summary` is a short explanation for previews and search; `featured = true` selects the four papers shown on the homepage.

## Publication resources and citations

Use `links = [{name = "Conference", url = "https://..."}]` for additional resource buttons.

Include `outputs = ["HTML", "BibTeX"]` in each publication's front matter. Hugo generates `publication/<paper>/cite.bib` from the title, authors, date, publication type, venue, DOI and resource URLs. The paper page, archive and homepage previews link directly to the download. There is no separate citation file to maintain.

Optional citation fields: `citation_venue` (plain venue name), `citation_volume`, `citation_pages`, and `citation_school` (for a thesis). Use these when the display venue contains extra bibliographic information or the citation needs a separate field.

## Local build

Use Hugo **Extended 0.76.5**, matching the GitHub Pages workflow, with Go available for Hugo Modules:

```sh
hugo --minify
```

For a local preview, run `./view.sh`.

Agreed follow-up work is recorded in [docs/website-next-steps.md](docs/website-next-steps.md).
