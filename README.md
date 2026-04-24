# readme-svgs

Cached SVGs for [zakiego/zakiego](https://github.com/zakiego/zakiego)'s profile README.

A GitHub Action refreshes `github-stats.svg` and `wakatime-stats.svg` every 6 hours by curling the live workers:

- [github-stats.zakiego.workers.dev](https://github.com/zakiego/github-stats)
- [wakatime-stats.zakiego.workers.dev](https://github.com/zakiego/wakatime-stats)

The profile README embeds the committed SVGs from `raw.githubusercontent.com` so cards keep rendering even if the workers hiccup.
