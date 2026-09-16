# Changelog

All notable changes to this project are documented in this file.

## [2026.09] - 2026-09-16

- Maintenance review of skynet-growth-assets — a public asset repo used as a CDN origin for the SkynetLabs GitHub-growth content pack (September 2026).
- Status: 29 social cards at 1080×1350 in `cards/`, 12 Pinterest pins at 1000×1500 in `pins/`, and 6 vertical shorts at 1080×1920 in `video/` each with a matching cover PNG. Assets are served through jsDelivr (`cdn.jsdelivr.net/gh/waseemnasir2k26/skynet-growth-assets@main/...`) rather than raw.githubusercontent.com, because raw GitHub returns `application/octet-stream` and social schedulers silently reject it.
- Reviewed September 2026: docs refreshed, CHANGELOG started, released as v2026.09. No assets added, replaced or removed.
- Known gaps: the README pins CDN URLs to `@main` rather than a tag, so any future asset change is picked up immediately by every scheduled post already referencing those URLs — there is no immutable versioned path for previously queued content.
- Repo hygiene: no LICENSE file (relevant here, since these are publicly hosted media) and no CI workflow. There is no package manifest, so no machine-readable version to bump.
