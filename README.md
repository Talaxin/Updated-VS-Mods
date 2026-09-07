# Updated Vintage Story mods (1.22.7)

Drop-in zips for the **A New Life** server on Vintage Story **1.22.7**. Put them in your `VintagestoryData/Mods` folder (or the matching `ModsByServer` folder after you try to join).

| Zip | Mod id | Version | Notes |
| --- | --- | --- | --- |
| [mods/AutoMapMarkers-5.0.4.zip](mods/AutoMapMarkers-5.0.4.zip) | `egocaribautomapmarkers` | 5.0.4 | Rebuilt for 1.22.7. Stays **off** until you press **Ctrl+Shift+M**. |
| [mods/vsimgui_1.2.8.zip](mods/vsimgui_1.2.8.zip) | `vsimgui` | 1.2.8 | Official 1.2.7 binaries, game dependency retargeted to 1.22. |
| [mods/autoconfiglib_2.0.11.zip](mods/autoconfiglib_2.0.11.zip) | `autoconfiglib` | 2.0.11 | Official 2.0.10 binaries, pinned to ConfigLib 1.13.2. |
| [mods/configlib_1.13.2.zip](mods/configlib_1.13.2.zip) | `configlib` | 1.13.2 | Official release (also on ModDB). |

## About in-game autodownload

Vintage Story’s join-server autodownload only fetches matching **mod id + version** from [mods.vintagestory.at](https://mods.vintagestory.at/). It does **not** pull from this GitHub repo.

- `configlib` **1.13.2** autodownloads from ModDB.
- `vsimgui` **1.2.8**, `autoconfiglib` **2.0.11**, and Auto Map Markers **5.0.4** are custom and **will not** autodownload. Install those three from this repo (or they will fail to match the server).

If you already have older official versions (ImGui 1.2.7, AutoConfigLib 2.0.10, Auto Map Markers 5.0.3), delete those zips first so they do not conflict.
