# Roadmap

## MVP
- Keep the static rehab tracker usable offline.
- Preserve local-only progress storage.
- Let logged pain data be corrected without resetting progress.

## Current Priority
- Deploy `rehab-v16` and verify the installed PWA shows the selectable PAIN exercise phase.

## Done
- Replaced the informational flare curriculum card with a real PAIN phase.
- PAIN phase can be selected after Phase 5 and uses normal exercise cards, set completion, rest timers, post-session pain logging, and recent-session history.
- Bumped service-worker cache from `rehab-v15` to `rehab-v16`.
- Replaced Phase 5 "If Pain Returns" text with staged knee and elbow return-from-flare curricula.
- Added gates, rules, and stop/red-flag notes for each flare curriculum.
- Bumped service-worker cache from `rehab-v14` to `rehab-v15`.
- Fixed GitHub Pages runtime crash caused by Babel 8 emitting `react/jsx-runtime` for a UMD React page.
- Pinned Babel standalone to `7.26.10` and removed module-mode inline JSX.
- Bumped service-worker cache from `rehab-v13` to `rehab-v14`.
- Recent pain-log rows are clickable.
- Pain breakdown rows are clickable.
- Editing saves back to the existing local session record.
- Service worker cache version bumped and HTML loads are network-first.
