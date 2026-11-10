# Project Kratos — Website Preview

Preview builds of the [Project Kratos website](https://github.com/Kratos-The-Rover/Kratos-The-Rover.github.io),
published from its `development-branch` before changes go live.

**Preview:** https://kratos-the-rover.github.io/preview-site/

## How it updates

The **Build preview** workflow (`.github/workflows/deploy.yml`) checks `development-branch` every 15 minutes.
When there are new commits it builds the site with Vite and deploys it to this repository's GitHub Pages.

To publish straight away, open **Actions → Build preview → Run workflow**.

This repository only holds the workflow. The site's source lives in
[Kratos-The-Rover.github.io](https://github.com/Kratos-The-Rover/Kratos-The-Rover.github.io).
