<p align="center">
  <img src="banner.png" alt="A New Life — Vintage Story 1.22.7" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Vintage%20Story-1.22.7-8B5A2B?style=for-the-badge" alt="Vintage Story 1.22.7">
  <img src="https://img.shields.io/badge/UnitedMods-required-3d5a40?style=for-the-badge" alt="UnitedMods required">
  <img src="https://img.shields.io/badge/server-A%20New%20Life-6b4f2a?style=for-the-badge" alt="A New Life server">
</p>

Drop-in zips for the **A New Life** dedicated server. **UnitedMods** is Talaxin's own join helper. Public mods still come from ModDB; custom packs on this server are sent by UnitedMods.

## Install

1. Download [`UnitedMods-v1.0.0.zip`](mods/UnitedMods-v1.0.0.zip).
2. Put it in `%APPDATA%\VintagestoryData\Mods`.
3. Delete any leftover downloader zips (**UnitedMods 1.0.4**, **Flawless**, **1.0.5**, or **ME Custom Mod Downloader**).
4. Join **A New Life**.

Until UnitedMods is on ModDB, you install this zip yourself. After it is published, the vanilla join screen can download it like any other public mod. Custom / unpublished packs still come from the server.

## What the mods do

| Mod | What it does |
| --- | --- |
| **UnitedMods** | Talaxin's join helper (`unitedmods` 1.0.0). Public ModDB mods install the normal way. Custom packs on this server are hidden from that screen and downloaded from the host. |
| **Auto Map Markers** | Drops map markers for ores, traders, and other finds. Stays **off** until you press **Ctrl+Shift+M**. |
| **ImGui** | In-game UI toolkit. Other mods (ConfigLib, Auto Map Markers) need it for their menus. |
| **ConfigLib** | Adds a settings button in the escape menu so you can tweak supported mods without editing JSON. |
| **AutoConfigLib** | Extra config helpers used by Auto Map Markers. Pinned to ConfigLib 1.13.2. |
| **BloodTrail Persist** | Optional sidecar: BloodTrail pools stay after you harvest an animal. Needs BloodTrail 1.2.5. |

After UnitedMods is loaded, vanilla pulls **Better Ruins**, **BloodTrail**, **ConfigLib**, and **Footprints** from ModDB. UnitedMods then sends **Auto Map Markers 5.0.4**, **ImGui 1.2.8**, and **AutoConfigLib 2.0.11** from the server.

## Downloads

| Download | Version | Notes |
| --- | ---: | --- |
| [UnitedMods-v1.0.0.zip](mods/UnitedMods-v1.0.0.zip) | 1.0.0 | Required. Original Talaxin mod (`unitedmods`). Upload this zip to ModDB. |
| [AutoMapMarkers-5.0.4.zip](mods/AutoMapMarkers-5.0.4.zip) | 5.0.4 | Rebuilt for 1.22.7. Enable with **Ctrl+Shift+M**. |
| [vsimgui_1.2.8.zip](mods/vsimgui_1.2.8.zip) | 1.2.8 | Official 1.2.7 binaries, game dependency retargeted to 1.22. |
| [autoconfiglib_2.0.11.zip](mods/autoconfiglib_2.0.11.zip) | 2.0.11 | Official 2.0.10 binaries, pinned to ConfigLib 1.13.2. |
| [configlib_1.13.2.zip](mods/configlib_1.13.2.zip) | 1.13.2 | Official release (also on ModDB). |
| [bloodtrailpersist_1.0.0.zip](mods/bloodtrailpersist_1.0.0.zip) | 1.0.0 | Optional. Requires BloodTrail 1.2.5. |

## Also on the server (ModDB)

These are not in this repo. The game downloads them when you join:

- **Better Ruins** `0.6.3` — world gen ruins and loot.
- **BloodTrail** `1.2.5` — animals leave blood when injured.
- **Footprints** `1.2.5` — players and animals leave prints on soft ground.

## Cleanup

If you already have older official zips, delete them so they do not sit next to these builds:

- ImGui **1.2.7**
- AutoConfigLib **2.0.10**
- Auto Map Markers **5.0.3**
- Any **UnitedMods 1.0.4**, Flawless, or **1.0.5** zip
