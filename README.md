# Ethel E. Mensah

Personal academic website for Ethel Elikem Mensah, hosted with GitHub Pages at:

https://ethel-elikem.github.io/eeamensah.github.io/

## Site Structure

- `_pages/about.md` controls the homepage.
- `_pages/publications.html` lists publications from `_publications/`.
- `_pages/writing.md` links to selected writing published through I2SC.
- `_pages/cv.md` controls the CV page.
- `_sass/layout/_custom.scss` contains the custom visual styling.
- `_config.yml` contains site-wide metadata, author details, and GitHub Pages settings.
- `images/profile.png` is the profile image used on the homepage.
- `files/cv_ethel.pdf` is kept for a downloadable CV or future linking.

## Editing

Most text changes can be made directly in the Markdown files under `_pages/` and `_publications/`.

After editing, commit and push changes to both `master` and `afi` if GitHub Pages remains configured to publish from `afi`.

## Local Preview

This is a Jekyll site. On a machine with a current Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/eeamensah.github.io/`.

## Notes

The site was originally forked from Academic Pages, but template demo content, old talk/teaching placeholders, sample posts, generators, and demo assets have been removed to keep the repository focused.
