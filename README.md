# Ocarina Reborn

The project website: **https://ocarina-pc-native-build.github.io/**

**Current release: v1.0.9 · November 15, 2026**

[Download / Releases](https://github.com/ocarina-pc-native-build/ocarina-pc-native-build.github.io/releases/latest) · [Discord](https://discord.gg/vDPAcc6JnY)

The website includes the forest background, feature cards, update section and community links. The current launcher and downloadable installer are v1.0.9, with texture-loading optimizations, memory-pressure improvements, a build fix and the Navi toggle.

## Updating

Restart the launcher and click **Update**, then install over your existing installation. Afterwards, let the launcher update the game components. Saves and settings stay; existing working game data is reused.

## Latest update

- Lower CPU overhead for texture uploads through reusable, bounded workers.
- More useful render-target reuse within existing memory limits.
- Smaller temporary buffers for large textures and earlier release of idle buffers under memory pressure.
- Game compilation continues when an optional performance profile is missing.
- A persistent Navi on/off button in the launcher header.

[Full v1.0.9 patch notes and checksums](https://github.com/ocarina-pc-native-build/ocarina-pc-native-build.github.io/releases/tag/v1.0.9)

## Licenses

The engine is distributed under [GPL-3.0-or-later](LICENSE). [License notices and corresponding source](CREDITS.md) are provided with the releases.

This repository's main branch contains the website. The actual launcher, engine and build source is in [OoT2026-PC-Recomp](https://github.com/misterrageguy-cyber/OoT2026-PC-Recomp), also linked from each release. Existing launchers use this repository's latest stable release and the `Ocarina-Reborn-Alpha-Setup.exe` asset name.

[Optional project support](https://buymeacoffee.com/hotdevilsauce) · [Publishing procedure](PUBLISHING.md)

Ocarina Reborn is an unofficial community project, not affiliated with Nintendo. No game files or encryption keys are provided.
