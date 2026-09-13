# linzhihaozlin22.github.io

Personal academic website of Zhihao Lin: https://linzhihaozlin22.github.io/

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and served by GitHub Pages directly from the `main` branch.

## Where the content lives

| What                               | File                       |
| ---------------------------------- | -------------------------- |
| Site identity, author sidebar      | `_config.yml`              |
| Navbar (About, Research, CV)       | `_data/navigation.yml`     |
| Homepage bio and news              | `_pages/about.md`          |
| Research page                      | `_pages/research.md`       |
| Web CV                             | `_pages/cv.md`             |
| Downloadable CV (PDF)              | `files/zhihao_lin_cv.pdf`  |

Publications, Talks, Teaching, Portfolio, and Blog Posts are intentionally absent. To add
publications later, create `_publications/`, restore the template's `_pages/publications.html`,
and add a `Publications` entry to `_data/navigation.yml`.

**TODO — profile photo:** place a headshot at `images/profile.jpg` and set
`author.avatar: "profile.jpg"` in `_config.yml`.

## Local development

Requires Ruby, Bundler, and Node.js (on macOS: `brew install ruby node`).

```bash
bundle install
bundle exec jekyll serve -l -H localhost   # http://localhost:4000
```

Or with Docker: `docker compose up`.

`_config.yml` is not reloaded while the server runs; restart it after config changes.
