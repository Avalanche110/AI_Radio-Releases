# AI_RADIO Releases

This public repository contains AI_RADIO installers, in-app update feed assets, and release records. Application source is maintained separately.

## Download and install

The current in-app beta and interactive installer are **0.9.38** for Windows
x64.

1. Download the [interactive MSI installer](https://github.com/Avalanche110/AI_Radio-Releases/releases/download/v0.9.38/AI_RADIO-Desktop-beta.msi), or open the [0.9.38 release notes](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/v0.9.38).
2. Check the installer's SHA-256 below before running it. In PowerShell, use `Get-FileHash -Algorithm SHA256` with the downloaded file path.
3. Close DCS before updating. Afterward, use **Install / Repair Hook** in AI_RADIO. The 0.9.38 update includes GameGUI hook 0.15.7, mission bridge 0.11.17, and TTS shim 0.5.10.

Installer: `AI_RADIO-Desktop-beta.msi` (967,000,064 bytes).

```text
e90e5b4d89ee5c5cd48c925e0f14739f1861d9cdbd390a99d6e1dede3474398b
```

Do not download GitHub's automatically generated **Source code** archives as installers. Releases labelled **Update Feed (managed)** contain machine-readable update packages, not the interactive MSI.

## In-app updates

Installed AI_RADIO 0.9.2 and later use this repository for operator-initiated
in-app updates. The [0.9.38 managed beta feed](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/updater-v0.9.38-beta)
contains `releases.beta.json`, the full package, and a 128.5 MB delta from
0.9.37. The installer and update include the configured Piper runtime and the
four supported voice models; no separate speech-model download is required.

The current beta binaries are unsigned, so Windows SmartScreen may show an unknown-publisher warning. Installer legal documents remain drafts; this is a beta prerelease.
