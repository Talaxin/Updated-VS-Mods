# Updated Vintage Story mods (1.22.7)

Drop-in zips for the **A New Life** server on Vintage Story **1.22.7**.

Install **Flawless** once. The zip below is still version **1.0.4** (so ModDB does not 400), rebuilt for 1.22.7. Delete any **1.0.5** zip — that unpublished version made the join screen say “missing 0 mods / Bad Request”. Official ModDB 1.0.4 also works on the client; the server uses this patched build to hide unpublished forks from that screen.

After Flawless is loaded, vanilla pulls Better Ruins / BloodTrail / ConfigLib from ModDB, then Flawless sends Auto Map Markers 5.0.4, ImGui 1.2.8, and AutoConfigLib 2.0.11 from the server.

| Zip | Mod id | Version | Notes |
| --- | --- | --- | --- |
| [mods/flawlesssvanaxforkv1.0.4-1227.zip](mods/flawlesssvanaxforkv1.0.4-1227.zip) | `flawlesssvanaxfork` | 1.0.4 | Put in `%APPDATA%\VintagestoryData\Mods`. Delete 1.0.5. |
| [mods/AutoMapMarkers-5.0.4.zip](mods/AutoMapMarkers-5.0.4.zip) | `egocaribautomapmarkers` | 5.0.4 | Rebuilt for 1.22.7. Stays **off** until you press **Ctrl+Shift+M**. |
| [mods/vsimgui_1.2.8.zip](mods/vsimgui_1.2.8.zip) | `vsimgui` | 1.2.8 | Official 1.2.7 binaries, game dependency retargeted to 1.22. |
| [mods/autoconfiglib_2.0.11.zip](mods/autoconfiglib_2.0.11.zip) | `autoconfiglib` | 2.0.11 | Official 2.0.10 binaries, pinned to ConfigLib 1.13.2. |
| [mods/configlib_1.13.2.zip](mods/configlib_1.13.2.zip) | `configlib` | 1.13.2 | Official release (also on ModDB). |
| [mods/bloodtrailpersist_1.0.0.zip](mods/bloodtrailpersist_1.0.0.zip) | `bloodtrailpersist` | 1.0.0 | Keeps BloodTrail pools after harvest. Requires BloodTrail 1.2.5. |

If you already have older official versions (ImGui 1.2.7, AutoConfigLib 2.0.10, Auto Map Markers 5.0.3), delete those zips first so they do not conflict.
