# Roadmap

## MVP
- Keep the static rehab tracker usable offline.
- Preserve local-only progress storage.
- Let logged pain data be corrected without resetting progress.

## Current Priority
- Push `rehab-v14` and verify the phone install no longer opens to a black screen.

## Done
- Fixed GitHub Pages runtime crash caused by Babel 8 emitting `react/jsx-runtime` for a UMD React page.
- Pinned Babel standalone to `7.26.10` and removed module-mode inline JSX.
- Bumped service-worker cache from `rehab-v13` to `rehab-v14`.
- Recent pain-log rows are clickable.
- Pain breakdown rows are clickable.
- Editing saves back to the existing local session record.
- Service worker cache version bumped and HTML loads are network-first.
