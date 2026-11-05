# Ruslan Strazhnyk

Personal site at [desperado.github.io](https://desperado.github.io), built as a single static HTML page and published with GitHub Pages.

The page covers my background, featured projects (QualityMax, 9lives, AFTERHOURS, and TokenHunger), selected open-source work from [Desperado](https://github.com/Desperado) and [Quality-Max](https://github.com/Quality-Max), experience, talks, and contact details.

## Preview locally

No build step or dependencies are required:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000>.

## Update content

Edit `index.html`. Project descriptions and status should match the linked public READMEs. The current 9lives entry points to the Go runner; the older Python CLI is in maintenance mode. The QualityMax repository is an ecosystem guide, while individual tools have their own source repositories and licenses.

The GitHub activity chart is served by [ghchart](https://ghchart.rshah.org/). Contribution totals are linked to GitHub rather than copied into the page, so there is no fixed count to maintain.

Before publishing, check the page at desktop and mobile widths, navigation anchors, and any changed project links. Keep the site static and avoid adding a build system for content updates.
