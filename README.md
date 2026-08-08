# linzhihaozlin22.github.io

Personal academic website of Zhihao Lin — large language models, adaptive generation, representation learning, and AI systems.

Built with [al-folio](https://github.com/alshedivat/al-folio) (v1.x) and deployed to GitHub Pages by the `Deploy site` GitHub Action, which publishes the built site to the `gh-pages` branch.

## Where the content lives

| What                         | File                       |
| ---------------------------- | -------------------------- |
| Homepage bio, news, socials  | `_pages/about.md`          |
| Research interests           | `_pages/research.md`       |
| Bibliography (empty for now) | `_bibliography/papers.bib` |
| CV content                   | `_data/cv.yml`             |
| Social links                 | `_data/socials.yml`        |
| News items                   | `_news/`                   |
| Site config, SEO, navigation | `_config.yml`              |

The publications page and its navbar entry are intentionally absent while there is
nothing public to list. To bring them back, add entries to `_bibliography/papers.bib`
and restore `_pages/publications.md` with `nav: true`.

## Local development

Requires Ruby 3.x and Node 20+. On macOS, `jekyll-scholar` needs a UTF-8 locale,
and the Jupyter converter needs `jupyter-nbconvert` on `PATH` only if you add
notebook posts.

```bash
bundle install
npm ci
LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8 bundle exec jekyll serve
```

Before pushing:

```bash
npm run lint:prettier && npm run lint:style-contract
```

See [`AGENTS.md`](AGENTS.md) and [`docs/`](docs/) for the upstream al-folio architecture and customization guides.
