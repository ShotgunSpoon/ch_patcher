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

### General

| Key | Action |
|-----|--------|
| **Tab** | Cycle forward through screens (Combat → Heroes → Stats → Achievements) |
| **Shift+Tab** | Cycle backward through screens |
| **Enter** | Activate / confirm current selection |
| **Escape** | Go back / close popup |
| **F10** | Toggle between Screen Reader and SAPI speech output |

### Combat

| Key | Action |
|-----|--------|
| **Space** | Click on monster (attack) |
| **Left Arrow** | Previous zone |
| **Right Arrow** | Next zone |

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

### Hero Screen

| Key | Action |
|-----|--------|
| **Page Up / Page Down** | Navigate through hero list |
| **Shift+Page Up / Shift+Page Down** | Jump 10 heroes |
| **Left Arrow / Right Arrow** | Navigate buttons on current hero |
| **L** | Level up selected hero |

### Skills

| Key | Action |
|-----|--------|
| **K** | Toggle skill navigation mode |
| **Page Up / Page Down** | Navigate between skills (in skill mode) |
| **Enter** | Activate selected skill (in skill mode) |

### Shop

| Key | Action |
|-----|--------|
| **R** | Announce ruby count |
| **H** | Show shop help / ruby info |
| **B** | Open gold-to-ruby conversion popup |
| **Left Arrow / Right Arrow** | Adjust sliders in popups |

## Known Issues

- Sound effects may not always play as expected. Some audio cues may be missing, delayed, or fail to trigger in certain situations.

## Don't Have the Game?

Clicker Heroes is free to play! Add it to your Steam library here:

[Clicker Heroes on Steam](https://store.steampowered.com/app/363970/Clicker_Heroes/)

## Manual Installation

If you'd prefer to install the mod manually without the patcher, see the instructions on the [ch_access repo](https://github.com/ShotgunSpoon/ch_access).
