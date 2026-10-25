# Modern Warfare 3 — Trickshot Mod (Private Server)

[← Back to the overview](../README.md)

Call of Duty: Modern Warfare 3 (Wii) with a trickshot menu, bots and console-style killcams, online on its own
private server (not CodW). The server is included, so you can play by yourself with bots any time, or join a friend
who hosts.

**Downloads:** `MW3-Trickshot-Xbox-Controls.zip` · `MW3-Trickshot-Own-Controls.zip` from
[Releases](../../../releases/latest)

## What you need

- Your own **Call of Duty: Modern Warfare 3** for the Wii, **USA version, first release** (game ID `SM8E52`), as a
  `.wbfs`, `.iso` or `.rvz` file.
- An Xbox controller (Xbox-Controls version), or your controller set up in your own Dolphin (Own-Controls).
- About 4.5 GB of free space. **No Wii NAND needed**: this Dolphin makes its own Wii storage.

## Setup

1. Extract the zip (right-click > Properties > **Unblock** first, then **Extract All**).
2. Double-click **`1 - SETUP (run once).cmd`** and pick your MW3 game file. It makes a modded copy in the `Game`
   folder.
3. Choose your server:
   - **Yes** = the server in this folder, on your own PC. Play by yourself with bots any time.
   - **No** = a friend's server. Type the address they gave you (numbers with dots).

   Run the setup again any time to switch.
4. Double-click **`2 - PLAY MW3 Trickshot.cmd`**. With your own server, a small **MW3 Server** window starts too
   (minimized): leave it open while you play.

## Playing

1. The first time, the game asks to create save data: **Yes**, then type a short profile name.
2. **Multiplayer > MW3 ONLINE**. You should see "Welcome to the MW3 private server!" at the bottom. (If the
   Multiplayer menu shows again after connecting, press MW3 ONLINE once more.)
3. **PRIVATE MATCH > START GAME**, so you are the host. Add bots with the Bot Menu.

**With friends:** everyone on the same server is automatically your ally. In the Private Match lobby press **Y
(Allies)**, pick a friend, **INVITE TO GAME**; they pick **ACCEPT INVITE > YES**. Your mod runs for everyone in your
match.

## Controls (Xbox-Controls version)

| Button | Action | Button | Action |
|---|---|---|---|
| Left stick | Move | Right stick | Look / aim |
| RT | Shoot | LT | Aim down sights |
| A or L3 | Sprint / jump | B | Crouch / prone |
| X | Reload / use | Y | Switch weapon |
| RB, LB | Grenades | R3 | Knife |
| Start | Pause | Back | Scores |

The **Own-Controls** version copies the controller settings of your own Dolphin.

## The mod menu

**Open:** crouch, then hold your **knife** button.
**Navigate:** Up = aim button · Down = knife button · Select = reload / use button.

| Menu | What it does |
|---|---|
| Bot Menu | Spawn enemy / friendly bots, freeze them, teleport them to your crosshair, bot spawn point, kick |
| Weapons Menu | Every gun by type, launchers, lethal and tactical equipment |
| Trickshot Menu | Fast Last, Unlimited Time, Death Barriers, Save / Load Position, UFO Mode, Suicide |
| Spots Menu | Teleport spots kept for each map (the host saves them) |
| Admin Menu | Players, killstreaks, visions, god mode, invisibility, teleport, restart the map |
| Account Menu | Level, prestige, Unlock All (saved to your account within seconds) |
| Customization | Menu colors, sounds and buttons |

### Without the menu (lying down / prone)

| Buttons | Does |
|---|---|
| Prone + knife | Save your position |
| Prone + D-pad left or Back | Go back to it |
| Prone + D-pad down | UFO mode on / off |

## Killcams

- **Final killcam** at the end of Team Deathmatch and Free-for-all ("GAME WINNING KILL").
- **Round-winning kill** after every Search & Destroy round won by a kill.
- The killer's view with their gun, slow motion, hitmarkers, and the calling card to the end.
- Every private match counts like a ranked one: XP, challenges and the Match Bonus.

## Playing with a real Wii

Not ready yet. Joining from a real Wii console needs a patch on the console side that isn't included.

## Troubleshooting

| Problem | Fix |
|---|---|
| "The game is not set up yet" | Run `1 - SETUP (run once).cmd` first. |
| Setup says it's the wrong game | The mod needs the USA first release (`SM8E52`). |
| Windows Firewall asks about `mw3-server.exe` or Dolphin | Click **Allow access** (needed for friends to join you). |
| "Unable to connect to the Call of Duty: MW3 servers" | Own server: check the MW3 Server window is open and start `2 - PLAY` again. Friend's server: wrong address, their server is off, or their internet isn't set up for friends yet. |
| The game runs slowly | In Dolphin: **Graphics > Enhancements > Internal Resolution > Native**. |
| Start fresh | Run `1 - SETUP` again. It makes a new game copy; your saves stay. |
