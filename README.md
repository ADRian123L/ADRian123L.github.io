# adrian123l.github.io

Personal site and portfolio for **Adrian Lozada** — M.S. Computational Science &
Engineering at Georgia Tech. Built with [Jekyll](https://jekyllrb.com) and hosted on
GitHub Pages at <https://adrian123l.github.io>.

## Layout

```
_config.yml           Site metadata, plugins, build settings
index.md              The entire site — hero, experience, projects, education, skills, awards
404.md                Not-found page
_layouts/
  default.html        Page chrome: navbar, footer, and the site's JavaScript
  page.html           Generic wrapper for any future standalone page
_includes/
  meta.html           <head> metadata: description, Open Graph, Twitter card, canonical
_sass/
  _reset.scss         Meyer reset
  _variables.scss     Design tokens — colors, fonts, sizing, shadows, breakpoints
style.scss            All component styles; compiled by Jekyll to /style.css
images/profile.png    Avatar used for social previews
files/                Static downloads (e.g. research PDFs)
```

The site is a single page. Every section lives in `index.md` as plain HTML, and the
navbar links to in-page anchors (`#about`, `#experience`, `#projects`, `#education`,
`#skills`, `#awards`).

## Local development

Requires **Ruby 3.x** — and specifically *not* 4.x. The `github-pages` gem
declares `ruby >= 2.6, < 4.0`, so Ruby 4 makes bundler quietly resolve to a
years-old release instead of erroring. macOS's built-in Ruby 2.6 is also too
old (nokogiri needs >= 3.0). Ruby 3.3 is known good:

```bash
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
```

Install dependencies once:

```bash
bundle install
```

Then serve with live reload:

```bash
bundle exec jekyll serve --livereload
```

The site is at <http://127.0.0.1:4000>. Jekyll rebuilds on save; `_site/` is generated
output and is git-ignored.

To check the build the way GitHub Pages will run it:

```bash
bundle exec jekyll build
```

`bundle exec` matters: it pins Jekyll to the same version GitHub Pages uses. A
bare `jekyll build` from a globally installed gem may use a newer Jekyll and
behave differently.

## Making changes

**Content** — edit `index.md`. Sections follow repeating patterns you can copy:

| Section    | Pattern                                                     |
| ---------- | ----------------------------------------------------------- |
| Experience | `.timeline-item` → marker, header (role + date), company, bullets |
| Projects   | `.card` → `.card-tag`, heading, bullets, `.card-tags`        |
| Education  | `.edu-item` → school, degree, meta, detail lines             |
| Skills     | `.skill-group` → heading + `.skill-tags` spans               |
| Awards     | `.award-item` → `.award-info` + `.award-meta`                |

Adding a new nav section means adding the section to `index.md` with an `id`, and a
matching link in the `.nav-links` block of `_layouts/default.html`.

**Design** — change `_sass/_variables.scss` first; the accent color, neutrals, container
width, nav height, radii, shadows, and breakpoints are all tokens used throughout
`style.scss`.

**Contact links** — `footer-links` in `_config.yml` drives the footer icons.

## Deploying

Push to `master`. GitHub Pages rebuilds automatically, usually within a minute or two.

## License

[MIT](LICENSE)
