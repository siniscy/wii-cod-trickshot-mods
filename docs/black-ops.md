# Black Ops — Trickshot Mod

[← Back to the overview](../README.md)

Call of Duty: Black Ops (Wii) with a trickshot menu and console-style killcams, played in Dolphin through the
[CodN](https://codn.live/) community client (included).

**Downloads:** `BO1-Trickshot-Xbox-Controls.zip` · `BO1-Trickshot-Own-Controls.zip` from
[Releases](../../../releases/latest)

## What you need

- Your own **Call of Duty: Black Ops** for the Wii, **USA version** (game ID `SC7E52`), as a `.wbfs`, `.iso` or
  `.rvz` file.
- Your **Wii NAND** from your own Dolphin (see [Your Wii NAND](#your-wii-nand)).
- An Xbox controller (Xbox-Controls version), or your controller set up in your own Dolphin (Own-Controls).
- About 5 GB of free space.

## Setup

1. Extract the zip (right-click > Properties > **Unblock** first, then **Extract All**).
2. Double-click **`1 - SETUP (run once).cmd`** and pick your Black Ops game file. When it asks about your Wii NAND,
   you usually just click **Yes**. It makes a modded copy of the game in the `Game` folder.
3. Double-click **`2 - PLAY BO1 Trickshot.cmd`**. If Windows says "Windows protected your PC", click
   **More info** > **Run anyway**.

The first time, Black Ops asks you to pick or create a profile. Then go to **Multiplayer** and start a
**private match** or **Combat Training** with bots, so you are the host. Fullscreen: **Alt+Enter**.

## The mod menu

**Open:** crouch, then hold your **knife** button for half a second.
**Navigate:** Jump = up · Knife = down · Use (reload / pick up) = select. The buttons are shown at the bottom.

| Menu | What it does |
|---|---|
| Bot Menu | Spawn, freeze and move bots, make them face you, rename them |
| Weapons Menu | Snipers with attachments, every other gun, lethals, equipment, One Bullet, Canswap |
| Account Menu | Unlock all, max level, prestige (finish the match to save) |
| Unlimited Time | The clock restarts just before 0:00, so the match never ends on time |
| Rocket Riding | Everyone rides their own rockets |
| Death Barriers | Off: no kill zones, for everyone |
| UFO Mode | Fly anywhere, through walls |
| Fast Last | One kill left to win (FFA: your score, TDM: your team's score) |
| Steady Aim Pro | The Steady Aim Pro perk for you, whatever class you use (stays on when you respawn) |
| Admin Menu | Players, killstreaks, visions, restart the map |
| Customization | Menu colors, sounds and buttons |

### Without the menu (host, lying down / prone)

| Buttons | Does |
|---|---|
| Prone + knife | Save your position |
| Prone + scoreboard | Go back to the saved position |
| Prone + D-pad down | UFO mode on (D-pad down again: off; you drop from where you are) |

## Killcams

- **Final killcam** at the end of Team Deathmatch and Free-for-all.
- **Round-winning kill** after every Search & Destroy round won by a kill.
- The killer's own view, slow motion near the kill, hitmarkers and the game's sounds.

## Your Wii NAND

The NAND is your Wii's storage (system files and saves). The setup finds your own Dolphin's NAND and asks to use it,
or you pick the folder (the one with `title`, `ticket` and `shared2` inside).

- If your NAND doesn't have the Black Ops update CodN needs, the setup offers to add it. Nothing else is changed.
- Your profile and rank come from that NAND, so the Account Menu changes that profile.
- **Missing Wii system files:** in your Dolphin, **Tools > Perform Online System Update > United States**, then run
  the setup again.
- **A `nand.bin` from a real Wii:** in Dolphin, **Tools > Manage NAND > Import BootMii NAND Backup**, then run the
  setup again.

## Controls

- **Xbox-Controls:** your Xbox controller works as a Wii Classic Controller with the maker's layout.
- **Own-Controls:** the setup copies the controller settings of your own Dolphin.

To change any button: while the game runs, **Controllers** > **Configure** next to Wii Remote 1.

## Troubleshooting

| Problem | Fix |
|---|---|
| "The game is not set up yet" | Run `1 - SETUP (run once).cmd` first. |
| Setup says it's the wrong game | The mod needs the USA version of Black Ops (`SC7E52`). |
| The game runs slowly | In Dolphin: **Graphics > Enhancements > Internal Resolution > Native**. |
| Start fresh | Run `1 - SETUP` again. It makes a new game copy; your saves stay. |
