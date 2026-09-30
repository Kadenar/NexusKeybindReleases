# Nexus Keybinds

A Guild Wars 2 [Nexus](https://raidcore.gg/Nexus) addon for automatically switching exported XML keybind profiles when your profession, elite specialization, or game mode changes. Uses an in-game ImGui settings window; arcdps is not required.

**In development. No releases or downloads are available yet.** Native importing still needs live game validation.

## Features

- Separate default profiles for PvE and PvP/WvW.
- Add overrides for an entire profession or a specific elite specialization.
- Choose exported XML files using an in-game file picker.
- A missing or invalid override falls back to the mode default; if that also fails, existing bindings remain unchanged.

Profiles are complete GW2 imports, not merged sets of overrides. Automatic switching is disabled until enabled in settings.

## Installation and updates

When a release becomes available, close GW2 and copy `NexusKeybinds.dll` into your game's `addons` folder, then enable it in Nexus. Settings are under **Nexus > Options > Nexus Keybinds**. Export your current controls through GW2 before testing other profiles.

The addon is configured to use Nexus's GitHub update provider with this repository. Nexus update preferences control automatic updates once releases are published. A game update can disable native importing until a compatible addon build is available.

This repository contains public documentation and will host DLL releases. Source code and build/test CI are maintained separately in a private repository. No release publishing is automated at this stage.

Third-party notices are included in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
