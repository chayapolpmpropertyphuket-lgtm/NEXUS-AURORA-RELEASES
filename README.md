# NEXUS AURORA — Public Updates

This public repository contains release metadata and signed APK downloads only.
The Android source code remains in the separate private repository.

## Update metadata

The app checks this file:

https://raw.githubusercontent.com/chayapolpmpropertyphuket-lgtm/NEXUS-AURORA-RELEASES/main/latest.json

When publishing a new version:
1. Upload the signed APK to a GitHub Release in this repository.
2. Update latest.json with the new versionCode, versionName, releaseNotes, and the direct browser-download URL for the APK asset.
3. Keep using the original NEXUS AURORA release keystore. Never replace or regenerate it.

Never upload keystores, passwords, access tokens, or private source code here.

Current channel: 0.4.0 (versionCode 4). The first APK release asset has not yet been published.
