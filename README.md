# Ocarina Reborn

The project website: **https://ocarina-pc-native-build.github.io/**

**Current release: v1.1.4 · November 17, 2026**

[Download / Releases](https://github.com/ocarina-pc-native-build/ocarina-pc-native-build.github.io/releases/latest) · [Discord](https://discord.gg/vDPAcc6JnY)

The website includes the forest background, feature cards, update section and community links. The current launcher and downloadable installer are v1.1.4, adding optional Classic UI, launcher improvements and targeted startup/diagnostic fixes.

## Updating

Restart the launcher and click **Update**, then install over your existing installation. Afterwards, let the launcher update the game components. Saves and settings stay; existing working game data is reused.

## Latest update

- Engine v2.3.2: improved CPU-thread coordination, renderer scheduling and memory reuse.
- Better cleanup of shader resources and memory-allocation recovery under Windows memory pressure.
- Frame Generation respects display capacity; improved HDR, ultrawide transitions and shader compatibility.
- Automatic save backups outside the game folder; improved audio recovery and crash reports.
- Optional CRT filters and optional Intel XeSS runtime support in F1.
- Classic UI selection and direct downloads, plus return to launcher after builds.
- Same-folder startup protection and accurate debug-session reporting.

Engine update: let the launcher update the game and prepare shaders. Re-download manually if the withdrawn first 1.1.4 was installed. Saves and settings stay.

[Full v1.1.4 patch notes and checksums](https://github.com/ocarina-pc-native-build/ocarina-pc-native-build.github.io/releases/tag/v1.1.4)

## Licenses

The engine is distributed under [GPL-3.0-or-later](LICENSE). [License notices and corresponding source](CREDITS.md) are provided with the releases.

This repository's main branch contains the website. The actual launcher, engine and build source is in [OoT2026-PC-Recomp](https://github.com/misterrageguy-cyber/OoT2026-PC-Recomp), also linked from each release. Existing launchers use this repository's latest stable release and the `Ocarina-Reborn-Alpha-Setup.exe` asset name.

[Optional project support](https://buymeacoffee.com/hotdevilsauce) · [Publishing procedure](PUBLISHING.md)

Ocarina Reborn is an unofficial community project, not affiliated with Nintendo. No game files or encryption keys are provided.
