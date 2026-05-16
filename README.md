# `ci` branch

This orphan branch holds the GitHub Actions workflow that builds and deploys
the Bitcoin Core mirror site to GitHub Pages.

The workflow runs nightly: it checks out the backup data from the `master`
branch, clones [github-metadata-mirror](https://github.com/0xB10C/github-metadata-mirror),
builds the static site (HTML + Markdown), and publishes it via the Pages
deployment actions.
