# Clicker Heroes Access Patcher

*Code written by Claude 4.6 Opus (Max subscription).*

A standalone installer for the [Clicker Heroes Access](https://github.com/ShotgunSpoon/ch_access) mod, which adds screen reader accessibility to [Clicker Heroes](https://store.steampowered.com/app/363970/Clicker_Heroes/) on Steam.

## Download

Download **ClickerHeroesAccessPatcher.exe** from the [latest release](https://github.com/ShotgunSpoon/ch_patcher/releases/latest).

## How to Use

1. Run **ClickerHeroesAccessPatcher.exe**.
2. It will ask for your Clicker Heroes install folder. The default is:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\Clicker Heroes
   ```
   If your game is installed somewhere else, paste the correct path or click **Browse for Folder** to find it.
3. Click **Patch Clicker Heroes**.
4. The patcher will:
   - Check if MelonLoader is installed. If not, it downloads and opens the MelonLoader installer — follow its prompts, then close it.
   - Download the latest **ClickerHeroesAccess.dll** from GitHub.
   - Place the DLL in the game's **Mods** folder.
5. Launch Clicker Heroes through Steam. The mod will load automatically.

## Finding Your Install Folder

If you're not sure where Clicker Heroes is installed:

1. Open **Steam**.
2. Go to your **Library**.
3. Right-click **Clicker Heroes** and select **Properties**.
4. Click the **Installed Files** tab.
5. Click **Browse**.
6. This opens the game's install folder. Copy the path from the address bar and paste it into the patcher.

The default Steam install path is:
```
C:\Program Files (x86)\Steam\steamapps\common\Clicker Heroes
```

## Mod Controls

Once the mod is installed and the game is running:

All screens use standard navigation: **Up/Down** or **Page Up/Page Down** to browse lists, **Left/Right** to switch sub-lists or adjust sliders, **Enter** to activate or confirm, **Escape** to go back or close.

### Navigation

| Key | Action |
|-----|--------|
| **Tab / Shift+Tab** | Cycle through screens (Combat → Heroes → Ancients → Outsiders → Stats → Achievements) |
| **T** | Cycle level scale for the current tab (x1, x10, x25, x100, etc.) |
| **F10** | Toggle between Screen Reader and SAPI speech output |

### Combat

| Key | Action |
|-----|--------|
| **Space** | Click on monster (attack) |
| **Left Arrow / Right Arrow** | Navigate zones |

### Information

| Key | Action |
|-----|--------|
| **G** | Announce current gold |
| **S** | Announce stats (DPS, click damage) |
| **Z** | Announce zone info |
| **H** | Announce enemy health |
| **I** | Announce current item/hero info |
| **O** | Announce hero list summary |
| **R** | Read current screen content |
| **Shift+R** | Announce ruby count from anywhere |

### Heroes

| Key | Action |
|-----|--------|
| **L** | Hire, level up, or purchase upgrades for the selected hero |
| **U** | Toggle upgrade navigation mode for the selected hero |
| **K** | Toggle skill navigation mode |

### Progression

| Key | Action |
|-----|--------|
| **A** | Check ascension progress (hero souls to gain, zone info) |
| **Ctrl+A** | Ascend (open ascension confirmation) |
| **Shift+T** | Check transcension progress (ancient souls, transcendent power) |
| **Ctrl+T** | Transcend (open transcension confirmation) |

### Shop

| Key | Action |
|-----|--------|
| **R** | Announce ruby count |
| **H** | Show shop help / ruby info |
| **B** | Open gold-to-ruby conversion popup |

## Known Issues

- Sound effects may not always play as expected. Some audio cues may be missing, delayed, or fail to trigger in certain situations.

## Don't Have the Game?

Clicker Heroes is free to play! Add it to your Steam library here:

[Clicker Heroes on Steam](https://store.steampowered.com/app/363970/Clicker_Heroes/)

## Manual Installation

If you'd prefer to install the mod manually without the patcher, see the instructions on the [ch_access repo](https://github.com/ShotgunSpoon/ch_access).
