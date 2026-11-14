![Silksong Local8 — 8-player co-op](https://github.com/user-attachments/assets/40c5edf0-326a-45aa-995b-318024948546)

# Silksong Local8

**Experimental public beta · Local co-op for up to 8 players**

Bring up to seven friends into the same Silksong game, on one PC and one shared screen. Open **F8** to add players, choose their controls and adjust the co-op settings.

## What's included

- Up to eight Hornets, with health, silk and equipment for each player.
- Controllers or a shared keyboard, with bindings for each extra player.
- A shared camera, player colours and a HUD for the group.
- Recovery, revival and silk rescue options to help the group stay together.
- Settings for damage, difficulty, the camera and waiting at room exits.

This is local co-op. It does not add online multiplayer.

## Before you play

This is a testing release. The full campaign has not been verified from start to finish. The opening weakness events, the final collapse and Churchkeeper conversation in Bonetown, special transport and interrupted interactions still need more in-game testing. Visual effects, translations and performance with larger groups are also being reviewed.

Use a separate save or back up your save before testing. If an event leaves a player without controls, capture a report before restarting when possible.

## Compatibility

Built against **Silksong Steam 1.0.30000** and **BepInEx 5.4.23.4**. The mod checks the game assembly against the reviewed build and rejects unreviewed assemblies. Other updates and storefront builds have not been verified. Linux, macOS, Steam Deck and combinations with other mods need in-game testing; compatibility is not established by the build tests.

## Installation

### With a mod manager

Install **SilksongLocal8** from the Silksong catalog in a Thunderstore-compatible manager. Its manifest lists BepInExPack Silksong as a dependency. Launch the game through that profile.

### Manually

1. Install BepInEx 5.4.23.4 for Silksong and launch the game once.
2. Close the game. Extract the `BepInEx` folder from this package into the game folder. The plugin belongs at `BepInEx/plugins/SilksongLocal8/SilksongLocal8.dll`.
3. Check for an older copy of `SilksongLocal8.dll` elsewhere in `BepInEx/plugins` and remove that duplicate before launching. Keep your configuration and saves.
4. Enter a save, press **F8**, select an empty player slot and choose a controller or keyboard. Close F8 to join the game.

P1 uses the game's control settings. Set the extra players' bindings in F8 and select **Apply changes** when editing them. The normal view after adding players is one shared screen, not split-screen.

## Reporting a problem

Describe the room, what happened just before the problem, the players involved, their input devices and whether you can reproduce it. Include the version shown in F8.

Use **F8 → Reports → Capture report for this room**, then open the reports folder. Attach the relevant JSON, the `Local8-activity` files and `BepInEx/LogOutput.log`. Reports are under `BepInEx/Local8-Reports` in the active game or manager profile. Check files for personal information before sharing them. The mod does not upload reports automatically.

## Development and credits

This mod has been possible thanks to AI. I know a lot of people aren't fans of using AI to make mods, but this mod wouldn't exist without its help.

Cloth-colour resources are adapted from **Michael4d45's HornetCloakColor 1.16.1**, under the MIT licence: https://github.com/Michael4d45/HornetCloakColor. The original licence notice is included. Thanks to the BepInEx and Harmony projects. Hollow Knight: Silksong belongs to Team Cherry. This is an unofficial fan mod.

The mod is distributed under the MIT licence. Third-party notices retain their own attribution.

A Spanish translation is included in `docs/README.es.md`.
