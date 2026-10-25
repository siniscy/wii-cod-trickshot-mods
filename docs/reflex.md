# Modern Warfare: Reflex — Trickshot Mod

[← Back to the overview](../README.md)

Call of Duty: Modern Warfare: Reflex (Wii, Call of Duty 4) with a trickshot menu, console-style killcams and
Xbox-style controls, played in Dolphin online through the Reflex community server.

**Downloads:** `CoD4-Trickshot-Xbox-Controls.zip` · `CoD4-Trickshot-Own-Controls.zip` from
[Releases](../../../releases/latest)

## What you need

- Your own **Call of Duty: Modern Warfare: Reflex** for the Wii, **USA version, first release** (game ID `RJAE52`),
  as a `.wbfs`, `.iso` or `.rvz` file.
- Your **Wii NAND** from your own Dolphin (see [Your Wii NAND](#your-wii-nand)).
- An Xbox controller (Xbox-Controls version), or your controller set up in your own Dolphin (Own-Controls).
- About 4.5 GB of free space.

## Setup

1. Extract the zip (right-click > Properties > **Unblock** first, then **Extract All**).
2. Double-click **`1 - SETUP (run once).cmd`** and pick your Reflex game file. When it asks about your Wii NAND, you
   usually just click **Yes**. If your PC isn't set up for online Reflex yet, it offers to do that too.
3. Double-click **`2 - PLAY CoD4 Trickshot.cmd`**. If Windows says "Windows protected your PC", click
   **More info** > **Run anyway**.

Go to **Multiplayer > Nintendo Wi-Fi Connection** and start a **Private Match**, so you are the host. Add bots with
the mod menu's Bot Menu. Fullscreen: **Alt+Enter**.

## Controls (Xbox-Controls version)

Reflex had Classic Controller support hidden and switched off; the mod turns it on, so the Xbox controller plays like
the Xbox version of CoD4 (normal stick aiming, crosshair in the middle).

| Button | Action | Button | Action |
|---|---|---|---|
| Left stick | Move | Right stick | Look / aim |
| RT | Shoot | LT | Aim down sights |
| A | Jump | B | Crouch / prone |
| X | Reload / use | Y | Switch weapon |
| RB | Frag grenade | LB | Special grenade |
| L3 | Sprint | R3 | Knife |
| D-pad left | Killstreaks | Back | Scores |

In the game's menus: **B** = select, **A** = back. The **Own-Controls** version uses the game's own Wii Remote +
Nunchuk controls with your Dolphin's settings.

## The mod menu

**Open:** press **B** to crouch, then hold **R3 (knife)** for half a second.
**Navigate:** Up = LT · Down = R3 · Select = X. (Own-Controls: aim / melee / use buttons.)

| Menu | What it does |
|---|---|
| Bot Menu | Spawn, freeze and move bots, make them face you, rename them |
| Weapons Menu | Every CoD4 gun with its attachments, grenades, C4 and claymores |
| Trickshot Menu | Fast Last, Unlimited Time, Save / Load Position, UFO Mode, Rocket Riding, Death Barriers, Suicide |
| Account Menu | Unlock all, max level, prestige (finish the match to save) |
| Admin Menu | Players, killstreaks, visions, god mode, teleport, restart the map |
| Customization | Menu colors, sounds, buttons, which side of the screen |

### Without the menu (lying down / prone)

| Buttons | Does |
|---|---|
| Prone + R3 (knife) | Save your position |
| Prone + Back (scoreboard) | Go back to it (press Back again to close the scoreboard) |
| Prone + D-pad down | UFO mode on (again: off) |

## Killcams

- **Final killcam** at the end of Team Deathmatch and Free-for-all.
- **Round-winning kill** after every Search & Destroy round won by a kill.
- The killer's view with their gun, slow motion, hitmarkers, the victim falling, and the game's sounds.
- Every match counts like a ranked one: XP and the Match Bonus show at the end.

## Your Wii NAND

The game keeps your profile and rank in the Wii NAND, and online play needs certificate files that are in it. The
setup finds your own Dolphin's NAND and asks to use it, or you pick the folder (with `title`, `ticket` and `shared2`).

- **Certificate files missing:** in your Dolphin, **Tools > Manage NAND > Extract Certificates from NAND**, then run
  the setup again.
- **A `nand.bin` from a real Wii:** **Tools > Manage NAND > Import BootMii NAND Backup**, then run the setup again.

## Online DNS

The online servers are run by the community and found through their DNS server (`67.222.156.250`). The setup sets
that up if needed; **`Remove online DNS.cmd`** undoes it.

## Troubleshooting

| Problem | Fix |
|---|---|
| "The game is not set up yet" | Run `1 - SETUP (run once).cmd` first. |
| Setup says it's the wrong game | The mod needs the USA first release (`RJAE52`). |
| Windows Firewall asks about Dolphin | Click **Allow access** (online play needs it). |
| Black screen at the end of a match | Run the setup again and pick the NAND of your own Dolphin. |
| The game runs slowly | In Dolphin: **Graphics > Enhancements > Internal Resolution > Native**. |
| Start fresh | Run `1 - SETUP` again. It makes a new game copy; your saves stay. |
