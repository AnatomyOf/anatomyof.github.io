# anatomyof.github.io

Hosting repo for the live **[Anatomy of a File](https://anatomyof.github.io)** site.

This repo contains no source — it only builds and publishes. The app lives in
**[LunarWerxs/anatomyof](https://github.com/LunarWerxs/anatomyof)**. The workflow in
`.github/workflows/deploy.yml` checks out that repo, builds `app/` with Bun, and
deploys the result to GitHub Pages via GitHub Actions.

It runs on manual dispatch, a repository_dispatch ping from the source repo on push,
and a periodic schedule.
