# Ranking Companion

Windows companion for Blade & Soul Live: separate account rosters, background class rankings, expected Hongmoon Coin, history, weekly/season rewards, tokens, gold and a Dungeon Journal.

**[Download the latest installer](https://github.com/9lvexe8/RankingCompanion-Releases/releases/latest)** · [1.3.1 patch notes](https://github.com/9lvexe8/RankingCompanion-Releases/releases/tag/v1.3.1)

## Install or upgrade

1. Close all Live clients and exit Ranking Companion through its tray menu.
2. Run the installer. Keep **Finish game setup and open Ranking Companion** checked.
3. Setup finds a single supported Live installation automatically. Multiple or custom installations may require selecting the game folder once.
4. Enter the world on one character per account. Characters and accounts are discovered automatically, and rankings are collected with F11 closed.

No manual character lists or Google connection are required. Existing accounts, rankings, rewards, history and preferences stay on your PC. Google Sheets is optional.

## Venture Tokens

The **Tokens** page tracks Venture, Brilliant Venture and Sparkling Venture Tokens in normal character inventories, with separate account totals and normal/Premium HMC values.

Enter the world on each character once to record their tokens. Counts refresh while that character is logged in; inactive characters retain their last recorded counts and observation time. Loading inventories do not replace saved counts with temporary zeros. Unread counts and unconfirmed membership remain **Unknown**.

Storage, mail, unclaimed shop items and existing HMC balances are not included. Tokens are never used automatically.

## Gold and account groups

Gold, silver and copper appear beside each character in Cards and Compact list, with a separate saved total for each account. Enter each character once to record their balance; inactive characters retain their last observation.

Use **Manage accounts** to create, rename and reorder custom groups and assign accounts. Each account's data stays separate.

## Dungeon Journal

Namdo Shrine, Hall of Trials and Substratum have separate Stage 5 and Stage 6 catalogs and automatic clear tracking. The run ledger shows recorded shared loot, quantities and recipients, with original item icons. Personal loot is hidden; confirmed auction awards remain visible.

Stay until auctions finish so winner messages can be recorded. Partial captures may have missing drops or recipients. Observed percentages require complete capture of that loot source; more clears alone do not unlock a percentage. Reference and assumed rates are labelled, and rare-drop outlooks are estimates, not guarantees.

## Updates

From 1.3.1, automatic checks run shortly after launch and every 30 minutes. A new version opens a prompt with patch notes and an **Update / Later** choice, and a prominent notice stays at the top left. **Later** postpones the prompt for 24 hours. Automatic checks can be disabled; manual **Check for updates** remains available in Setup & data and the tray menu.

From 1.2.2, automatic game-component updates can download a matching verified release and install it after all Live clients close. This option can be disabled in **Setup & data**. Unknown game builds wait for validated support; the app does not force old plugins to load.

Release information is signed, and the installer size and SHA-256 are checked before it runs. The Windows installer itself is not Authenticode-signed.

## Compatibility

- Current supported game: **Live 5.49.10702.18**. NEO is not supported.
- Full scans can take several minutes depending on roster size, server replies and area changes.
- Weekly qualification requires confirmed current-week evidence and remains **Unknown** otherwise. A season rank alone does not prove participation.
- Hall of Trials Stage 6 has been verified in-game; Stage 5 is enabled and still needs a live clear check.

This repository contains public installers, update information and documentation only. Source code remains private. No account keys, saved rankings or Google credentials are distributed. Update checks do not upload your characters or account data.

Ranking Companion is an independent project, not an official Blade & Soul application.
