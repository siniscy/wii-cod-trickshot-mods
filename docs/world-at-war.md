# World at War — Trickshot Mod

[← Back to the overview](../README.md)

Call of Duty: World at War (Wii) with a trickshot menu and console-style killcams, played in Dolphin online through
the World at War community server.

**Downloads:** `WaW-Trickshot-Xbox-Controls.zip` · `WaW-Trickshot-Own-Controls.zip` from
[Releases](../../../releases/latest)

## What you need

- Your own **Call of Duty: World at War** for the Wii, **USA version, first release** (game ID `RVYE52`), as a
  `.wbfs`, `.iso` or `.rvz` file.
- Your **Wii NAND** from your own Dolphin (see [Your Wii NAND](#your-wii-nand)).
- An Xbox controller (Xbox-Controls version), or your controller set up in your own Dolphin (Own-Controls).
- About 3.5 GB of free space.

## Setup

1. Extract the zip (right-click > Properties > **Unblock** first, then **Extract All**).
2. Double-click **`1 - SETUP (run once).cmd`** and pick your World at War game file. When it asks about your Wii
   NAND, you usually just click **Yes**. If your PC isn't set up for online World at War yet, it offers to do that
   too (click **Yes**; Windows asks for permission).
3. Double-click **`2 - PLAY WaW Trickshot.cmd`**. If Windows says "Windows protected your PC", click
   **More info** > **Run anyway**.

Go to **Multiplayer > Nintendo Wi-Fi Connection** and start a **Private Match**, so you are the host. Add bots with
the mod menu's Bot Menu. Fullscreen: **Alt+Enter**.

## The mod menu

**Open:** crouch, then hold your **melee (knife)** button for half a second. A message at the start of each match
shows your melee button.
**Navigate:** Up = aim button · Down = melee button · Select = use button.

| Menu | What it does |
|---|---|
| Bot Menu | Spawn, freeze and move bots, make them face you, rename them |
| Weapons Menu | Every gun with its attachments, grenades and equipment |
| Trickshot Menu | Fast Last, Unlimited Time, Save / Load Position, UFO Mode, Rocket Riding, Death Barriers, Suicide |
| Account Menu | Unlock all, max level, prestige (finish the match to save) |
| Admin Menu | Players, killstreaks, visions, god mode, restart the map |
| Customization | Menu colors, sounds, buttons, which side of the screen |

**UFO Mode** without the menu (host): lie down (prone) and press **D-pad down**; press it again to turn it off. You
drop from where you are, so be over the ground.

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

## Controls

- **Xbox-Controls:** World at War on the Wii only works with the Wii Remote and Nunchuk, so your Xbox controller acts
  as both, with the maker's layout. The right stick aims like a normal stick (no pull back to level, aim rests in
  the middle).
- **Own-Controls:** the setup copies the controller settings of your own Dolphin.

To change any button: while the game runs, **Controllers** > **Configure** next to Wii Remote 1.

## Troubleshooting

| Problem | Fix |
|---|---|
| "The game is not set up yet" | Run `1 - SETUP (run once).cmd` first. |
| Setup says it's the wrong game | The mod needs the USA first release (`RVYE52`). |
| Windows Firewall asks about Dolphin | Click **Allow access** (online play needs it). |
| Black screen at the end of a match | Run the setup again and pick the NAND of your own Dolphin. |
| The game runs slowly | In Dolphin: **Graphics > Enhancements > Internal Resolution > Native**. |
| Start fresh | Run `1 - SETUP` again. It makes a new game copy; your saves stay. |
