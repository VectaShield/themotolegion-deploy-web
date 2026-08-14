# themotolegion-deploy-web

Deploy target for **TheMotoLegion.com**.

This repo is auto-populated by the GitHub Actions workflow in
[`VectaShield/Main-TheMotoLegion-Website`](https://github.com/VectaShield/Main-TheMotoLegion-Website).
Every push to that repo's `main` branch builds the site in Docker and force-syncs
the built output (`dist/`) into the root of this repo's `main` branch.

Hostinger pulls this repo's `main` branch into `public_html` via a push webhook.

**Do not edit this repo directly** — changes will be wiped on the next deploy.
