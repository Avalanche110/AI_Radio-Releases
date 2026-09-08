# AI_RADIO Releases

This public repository contains AI_RADIO installers, in-app update feed assets, and release records. Application source is maintained separately.

## Download and install

The current in-app beta and interactive installer are **0.9.39** for Windows
x64.

1. Download the [interactive MSI installer](https://github.com/Avalanche110/AI_Radio-Releases/releases/download/v0.9.39/AI_RADIO-Desktop-beta.msi), or open the [0.9.39 release notes](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/v0.9.39).
2. Check the installer's SHA-256 below before running it. In PowerShell, use `Get-FileHash -Algorithm SHA256` with the downloaded file path.
3. Close DCS before updating. Afterward, use **Install / Repair Hook** in AI_RADIO. The 0.9.39 update includes GameGUI hook 0.15.7, mission bridge 0.11.18, native radio bridge 0.6.9, and TTS shim 0.5.10.

Installer: `AI_RADIO-Desktop-beta.msi` (966,987,776 bytes).

```text
795d0f852c73c188e17d0ac890e1beb22f8b2bbc11c3c5a64b475bdbc0e15d00
```

Do not download GitHub's automatically generated **Source code** archives as installers. Releases labelled **Update Feed (managed)** contain machine-readable update packages, not the interactive MSI.

## In-app updates

Installed AI_RADIO 0.9.2 and later use this repository for operator-initiated
in-app updates. The [0.9.39 managed beta feed](https://github.com/Avalanche110/AI_Radio-Releases/releases/tag/updater-v0.9.39-beta)
contains `releases.beta.json`, the full package, and a 3.27 MiB delta from
0.9.38. The installer and update include the configured Piper runtime and the
four supported voice models (Amy, John, LibriTTS-R medium, and LibriTTS high);
no separate speech-model download is required. Obsolete Piper models are not
included.

The current beta binaries are unsigned, so Windows SmartScreen may show an unknown-publisher warning. Installer legal documents remain drafts; this is a beta prerelease.
