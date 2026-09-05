# betty-zeng.github.io

Personal site of Hui (Betty) Zeng — Business and Applied AI Consultant, entrepreneurial leader.

Built on the [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll
theme (Minimal Mistakes). The theme's infrastructure is kept — SEO tags
(`_includes/seo.html`), Google Analytics (`_includes/analytics.html`), and the contact
sidebar (`_includes/author-profile.html`: email, LinkedIn, GitHub, location) — with a
custom "museum" visual layer and an interactive world map.

## Where things live

| What | File |
|---|---|
| Site + author metadata (title, description, URL, email, LinkedIn, GitHub, GA id) | `_config.yml` |
| All page content (About, News, Projects, Education, Engagement, Journey) | `_pages/about.md` |
| Top-nav links | `_data/navigation.yml` |
| Custom styling (palette, fonts, dark mode, component styles, map) | `_sass/_custom.scss` |
| Font + Leaflet `<link>`/`<script>` tags | `_includes/head/custom.html` |

## Still to fill in

Search for `# TODO` in `_config.yml` and `▸` in `_pages/about.md`:

- **`_config.yml`**: `google_analytics_id`, `google_site_verification`, `url` /
  custom domain, `repository`, confirm `author.github` / `author.email`
- **CV**: drop the PDF at `assets/cv.pdf` (path set by `author.cv` in `_config.yml`). The
  profile sidebar shows LinkedIn + Full CV under the GitHub icon.
- **Portrait**: add `images/profile.jpg`
- **`_pages/about.md`**: News & Talks entries (vertical timeline), two Public Engagement
  entries
- **Journey map**: the two "adventure" pins and the MBA campus — see the `TODO` comment in
  the `places` array in the `<script>` at the bottom of `about.md`

## Local preview

```
bundle install
bundle exec jekyll serve
```

then open http://localhost:4000. If Ruby/Jekyll isn't set up locally, pushing to `main`
triggers the GitHub Pages build.
