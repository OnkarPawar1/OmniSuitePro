# Omni Business Suite Pro — Phase 4

Static, local-first ERP for Facebook page and video-production workflows.

## Features
Phase 3: dashboard, page manager, video inventory, production board, publishing planner, search, world clocks, and local video/TXT management.

Phase 4: monthly calendar, manually entered Facebook analytics, earnings and RPM tracking, production pipeline stages, CSV import/export for analytics and earnings, and combined metadata backup/restore.

## Privacy
Connect a local folder in Chrome/Chromium. Phase 3 metadata stays in `OmniSuitePro/system/metadata.json` (schema v3); Phase 4 data is saved separately in `OmniSuitePro/system/phase4.json`. The public repository contains application source code only. Video media and TXT content are **not** included in the metadata backup.

## Deployment
GitHub Pages uses `.github/workflows/pages.yml` on pushes to `main`. Source files: `index.html`, `styles.css`, `app.js`, and `phase4.js`.

**Important:** Analytics and earnings are manually entered or CSV-imported, not synced from Meta. The production pipeline is a tracker, not an automated video renderer or publisher.
