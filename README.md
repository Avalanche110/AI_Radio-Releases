# AI_RADIO Releases

This public repository contains AI_RADIO installers, in-app update feed assets, and release records. Application source is maintained separately.

## Download and install

The current in-app beta is **0.9.37** for Windows x64. The current interactive
installer remains **0.9.36**; installed copies can update to 0.9.37 from the app.

1. Download the [interactive MSI installer](https://github.com/Avalanche110/AI_Radio-Releases/releases/download/v0.9.36/AI_RADIO-Desktop-beta.msi), or open the [0.9.36 release notes](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/v0.9.36).
2. Check the installer's SHA-256 below before running it. In PowerShell, use `Get-FileHash -Algorithm SHA256` with the downloaded file path.
3. Close DCS before updating. Afterward, use **Install / Repair Hook** in AI_RADIO. The 0.9.37 in-app update includes GameGUI hook 0.15.6, mission bridge 0.11.16, and TTS shim 0.5.9.

Installer: `AI_RADIO-Desktop-beta.msi` (894,128,128 bytes).

```text
07b62fc26cb6487af49c1b2aade542dfef9c1a04d74f1e629074da6e7c4358ad
```

Do not download GitHub's automatically generated **Source code** archives as installers. Releases labelled **Update Feed (managed)** contain machine-readable update packages, not the interactive MSI.

## In-app updates

Installed AI_RADIO 0.9.2 and later use this repository for operator-initiated in-app updates. The [0.9.37 managed beta feed](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/updater-v0.9.37-beta) contains `releases.beta.json`, the full package, and a 2.6 MB delta from 0.9.36.

The current beta binaries are unsigned, so Windows SmartScreen may show an unknown-publisher warning. Installer legal documents remain drafts; this is a beta prerelease.
