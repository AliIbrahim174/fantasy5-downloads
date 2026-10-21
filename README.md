# Fantasy 5 — Android downloads

Official Android downloads and installation instructions. Application source stays in a separate private repository. No GitHub account is needed to download.

## Download v1.1.0-beta.1

| Who uses it | Download |
| --- | --- |
| Friends / fantasy managers | **[Fantasy 5](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.1.0-beta.1/Fantasy5-v1.1.0-beta.1-android.apk)** |
| Verified administrator | **[Fantasy 5 Admin](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.1.0-beta.1/Fantasy5-Admin-v1.1.0-beta.1-android.apk)** |

[Release notes](https://github.com/AliIbrahim174/fantasy5-downloads/releases/tag/v1.1.0-beta.1) · [SHA-256 checksums](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.1.0-beta.1/SHA256SUMS.txt) · [Build information](https://github.com/AliIbrahim174/fantasy5-downloads/releases/download/v1.1.0-beta.1/build-info.json)

Android 7.0 or newer. Each universal APK is about 55 MB. Android shows version 1.1.0 (build 3). The apps install side by side. Docker is not needed.

## Install or update

1. Download and open the appropriate APK. If Android asks, allow installation from that browser or file app.
2. Existing users should update in place and retain app data. Do not uninstall to resolve a signing error; contact the administrator first.
3. Managers open **Fantasy 5**, register with their own email/password, confirm their email, then save a squad before the displayed deadline. Existing accounts can sign in normally.
4. The administrator opens **Fantasy 5 Admin** and signs in with the existing verified admin account. Installing this APK does not grant a role. The manager app has no admin controls, including for the owner.

## Admin matchdays

1. While online, press **Verify admin & download matchday**. Prepare and sync attendance/teams before the fantasy deadline.
2. At the pitch, record starts/finishes, events, keeper duty, substitutions and corrections offline. Successful edits save immediately on the phone and survive an app restart.
3. Reconnect and press **Sync matchday**. Wait for zero pending actions. Managers receive updates and published points after sync.
4. Keep the app data. Use the backup icon to save a JSON copy through Android's file picker. Automatic replacement-phone backup import is not included.

Initial verified download, account/catalog/competition decisions and remote result distribution require connectivity. Test apps are for synthetic data only; use these official editions for real gameweeks.

## Beta status

The release was checked on a Samsung SM-S938B, including three synthetic offline matches, a cold restart and duplicate-free synchronization. It uses the retained signing certificate for compatibility with the previous official APK. This is a direct-install beta, not a Play Store release. Broader devices/networks and long outages have not been fully verified. The Admin password-reset email roundtrip remains unverified; Android callback resolution was checked.

Older downloads remain available on the [releases page](https://github.com/AliIbrahim174/fantasy5-downloads/releases).
