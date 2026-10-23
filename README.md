# AlbertApps — browser demos

Canonical catalog: https://albertdirksen15.github.io/web_App_spublik/

- `CodeTrainer/` — CodeTrainer demo
- `noma/demo/` — Noma demo
- `learningtracker/` — LearningTracker demo

This repository contains ready-to-run browser files. Application source belongs to the separate CodeTrainer, Noma and LearningTracker repositories. Never publish source trees, source maps, tokens or personal workspace exports here.

Each private application workflow publishes only its own folder using the repository secret `ALBERTAPPS_PUBLISH_TOKEN`. The token must allow Contents read/write on this repository. The Pages workflow deploys the checked-in static files without fetching another website or checking out private source.

The catalog and application URLs are independent of `AlbertApps_Public`. Browser-delivered JavaScript remains downloadable even when minified and obfuscated; private source repositories do not change that browser requirement.
