# Fantasy Street League ? Android downloads

Official Android apps, downloads and guides. Application source remains in a separate private repository. No GitHub account is needed to download.

## Download v1.3.0-beta.1

| Who uses it | Download |
| --- | --- |
| Friends / fantasy managers | **[Fantasy Street League (FSL)](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.3.0-beta.1/Fantasy5-v1.3.0-beta.1-android.apk)** |
| Verified administrator | **[Fantasy 5 Admin](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.3.0-beta.1/Fantasy5-Admin-v1.3.0-beta.1-android.apk)** |

[Release notes](https://github.com/AliIbrahim174/fantasy5-downloads/releases/tag/v1.3.0-beta.1) ? [SHA-256 checksums](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.3.0-beta.1/SHA256SUMS.txt) ? [Build information](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.3.0-beta.1/build-info.json) ? [Admin matchday guide](ADMIN-GUIDE.md)

Android 7.0 or newer. Each universal APK is about 57 MB. Android displays **1.3.0 (build 7)**. The apps install side by side. Docker is unnecessary for either official app.

## Install or update

1. Download and open the appropriate APK. If Android asks, allow installation from that browser or file app.
2. Install over the existing app and retain its data. FSL updates the existing Fantasy 5 manager app; your account remains valid. Do not uninstall to resolve a signing error?contact the administrator first.
3. Managers open **Fantasy Street League**, register/confirm their email if new, or sign in to their existing account. Save the squad before the displayed deadline. The starting budget remains **60.0 credits**.
4. The administrator opens **Fantasy 5 Admin**, using the existing verified admin account. Installing Admin does not grant a role. The manager edition has no administration controls.

## What's new

- FSL manager interface, gameweek lineup/points history, other manager profiles, primary-position player search and a gameweek-specific matchday feed.
- Clear Prepare ? Play ? Review Admin controls, two or more named/color teams, full rosters including substitutes, and explicit first pairing/starters/keepers.
- Timed **SUB** and **GK SUB**, between-match transfers, automatic later pairings with a waiting queue, match timelines and confirmed-absence review.
- Future gameweeks: primary GK gets 1 point per complete three saves; other primary positions get 2. Emergency +2 requires neither registered role GK and more than five actual keeper minutes. Clean sheets still need full qualifying duty. First-match penalties decide rotation only; fantasy scoring retains a draw. GW1 keeps its original rules and results.

## Offline Admin matchdays

1. Online, **Verify admin & download matchday** (or download latest setup from the menu). Create the gameweek with Cairo kickoff/deadline, confirm attendees and save teams. **Sync before the fantasy deadline** so managers can select squads.
2. At the pitch, starts/finishes, all match events, SUB/GK SUB, transfers between matches, recaps, absence review and publication requests save on this phone without connectivity. Restarting the app retains them.
3. Reconnect and **Sync matchday**. Wait for zero pending actions and a finalised gameweek. Managers receive changes and published points after synchronization.
4. Keep app data. Export a backup through the download icon and Android's file picker. Automatic import onto a replacement phone is not included.

Account/catalog/price decisions, initial verified download, manager purchases and result distribution need connectivity. Test apps contain synthetic data and are not for real gameweeks. See the [complete Admin guide](ADMIN-GUIDE.md) for substitutions, keeper swaps, transfers, penalties, absences and conflict recovery.

## Beta status

The matching workflow passed a Samsung offline recording/cold-restart/sync check using four custom teams, three synthetic matches, eleven events and 49 saved actions. Manager match details and the owner-approved Admin UI were inspected. The public build uses the retained signing certificate. This is a direct-install beta, not a Play Store release.

Broader physical devices, simultaneous two-phone recording, prolonged outages, automatic replacement-phone backup import and the hosted Admin password-reset email roundtrip were not newly verified.

Older versions remain on the [releases page](https://github.com/AliIbrahim174/fantasy5-downloads/releases). This repository contains downloads and guides, not private application source, private inputs, passwords or signing keys.
