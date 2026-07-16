# armitakar.github.io

Source for [armitakar.github.io](https://armitakar.github.io/) — Armita Kar's academic website, built with [Jekyll](https://jekyllrb.com/) and a customized fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (via [academicpages](https://academicpages.github.io/)).

This README is a guide for **updating the site's content** without having to touch layout/theme code. If you just want to add a publication, a news item, a project, or a team member, jump to [Adding content](#adding-content) below.

---

## Running the site locally

1. Install Ruby, Bundler, and Node.js (`sudo apt install ruby-dev ruby-bundler nodejs` on Ubuntu/WSL, or use [rbenv](https://github.com/rbenv/rbenv)/[Homebrew](https://brew.sh/) on Mac).
2. Clone the repo and `cd` into it.
3. Run `bundle install` (delete `Gemfile.lock` first if you hit dependency errors).
4. Run `bundle exec jekyll liveserve`.
5. Open `http://localhost:4000` — the site rebuilds automatically as you save changes.

You don't need to run it locally to make edits — you can edit files directly on GitHub and GitHub Pages will rebuild the live site in a minute or two. Running locally is just useful for previewing changes before they go live.

---

## Adding content

Most content lives in `_data/*.yml` files or as one file per item in a `_collection/` folder. **You should rarely need to edit HTML.**

### Publications
Add a new file to `_publications/`, named `YYYY-MM-DD-short-title.md`. Copy an existing file in that folder as a starting template — the front matter (`title`, `date`, `venue`, `paperurl`, etc.) controls what's shown on the Publications page.

### Teaching
Add a new file to `_teaching/`, named `YYYY-season-short-title.md` (e.g. `2026-fall-teaching-5.md`). Copy an existing file as a template.

### Research projects (shown on `/research/`)
Edit **`_data/research_projects.yml`**. Copy one block and fill in:
```yaml
- title: Your project title
  description: A paragraph describing the project.
  link: "#"                     # or a real URL if the project has a page/paper
  images:
    - /images/your-image.jpg    # add one or more; put the file in /images/ first
  caption: Optional caption shown under the image(s)
```

### Research team (shown on `/research_team/`)
Edit **`_data/research_team.yml`**. It's grouped by section (Graduate Students, Undergraduate and High School Students, Collaborators). Add a person under the right section:
```yaml
    - name: Full Name
      role: Their title / program / affiliation
      image: /images/their-photo.jpg   # optional — omit for a placeholder avatar
      url: https://their-website-or-linkedin.com   # optional
```
To add a whole new section, copy a `- section: ...` block and give it a new `section:` name.

### Recent updates (the timeline on the About page)
Edit **`_data/updates.yml`**. Add new entries at the **top** of the file (newest first):
```yaml
- date: "Month Day, Year"
  body: >-
    What happened, in a sentence or two. You can use HTML like <b>bold</b>
    or <a href="...">links</a> here.
  images:
    - /images/optional-photo.jpg
```
Use `body: >-` for a plain paragraph, or `body: |-` if you need multiple lines / an inner `<ul>` list (see existing entries for examples of both).

### CV, About intro text, main navigation
- `_pages/cv.md` — plain markdown, edit directly.
- `_pages/about.md` — the intro paragraphs and the three "research question" cards near the top are still hand-written HTML; the Recent Updates section below them is data-driven (see above).
- `_data/navigation.yml` — controls the top nav bar links.

### Uploading files (PDFs, CVs, posters)
Drop files into `/files/`. They'll be reachable at `https://armitakar.github.io/files/your-file.pdf`.

### Images
Drop images into `/images/`. Keep filenames lowercase with hyphens instead of spaces (e.g. `trb-poster-2026.jpg`, not `TRB Poster 2026.jpg`) — spaces in filenames break some links and are easy to typo in Markdown/HTML.

---

## Site structure (for reference)

```
_config.yml          site-wide settings (title, nav behavior, collections)
_data/                navigation.yml, authors.yml, research_projects.yml,
                       research_team.yml, updates.yml, ui-text.yml
_pages/                about.md, cv.md, publications.md, research.md,
                       research_team.md, teaching.html, 404.md
_publications/         one file per publication
_teaching/             one file per course
_sass/_custom.scss     all custom styling for cards/timeline/masthead —
                       edit this instead of adding new <style> blocks to pages
images/                photos, posters, icons
files/                 PDFs and other downloadable files
markdown_generator/    optional scripts to bulk-generate publication/talk
                       markdown files from a .bib or .tsv file
```

---

## Credit

Built on the [academicpages](https://academicpages.github.io/) template, itself forked from the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme (© Michael Rose, MIT License — see `LICENSE`).
