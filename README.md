# Ranking Companion

Windows companion for Blade & Soul Live: separate account rosters, background class rankings, expected Hongmoon Coin, history, and weekly/season rewards.

**[Download the latest installer](https://github.com/9lvexe8/RankingCompanion-Releases/releases/latest)**

## Install or upgrade

1. Close all Live clients and exit Ranking Companion through its tray menu.
2. Run the installer. Keep **Finish game setup and open Ranking Companion** checked.
3. Setup finds a single supported Live installation automatically. If there are several installations or a custom location, select the game folder once.
4. Enter the world on one character per account. The companion discovers the roster and collects rankings in the background; F11 does not need to stay open.

No manual character lists or Google connection are required. Existing accounts, rankings, rewards and preferences remain on your PC. Google Sheets is optional.

## Updates from 1.2 onward

Install 1.2 manually once to receive the updater. Future releases appear inside the companion with patch notes and an **Update / Later** choice. Automatic checks can be disabled in **Setup & data**; a manual check is also available from the tray menu.

Release metadata is signed, and the installer size and SHA-256 are checked before running it. Live must be closed. The Windows executable itself is not Authenticode-signed.

## Compatibility and limits

- Validated: **Live 5.49.10701.2**, executable SHA-256 `6AE9777FB13ECD954A2217B35E147BE88AAAF3DE7235DD232723BBC139460E50`.
- Other executable builds and NEO are not validated; setup does not force unknown builds.
- Full scans can take several minutes depending on roster size, server replies and area changes.
- Inactive characters can have season estimates. Weekly qualification requires confirmed current-week evidence and remains **Unknown** otherwise.
- The dungeon loot tracker is a design preview and is **not included in 1.2**.
- See each release's patch notes and verification report for tested behavior and remaining validation limits.

This repository contains public installers, update metadata and documentation only. It contains no private source, account keys, saved rankings or Google credentials. Update checks do not upload your account or character data.

Ranking Companion is an independent project, not an official Blade & Soul application.
