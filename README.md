# BlackoutUO — downloads

This repository only hosts what the launcher downloads. It has no code.

## Install

1. Download **`BlackoutUO-Setup-vX.Y.Z.exe`** from the latest `launcher-v…` release
   ([releases](https://github.com/srosellj/blackout-releases/releases)).
2. Windows will show "Windows protected your PC" because the executable is not code-signed
   during the Alpha. Click **More info**, then **Run anyway**.
3. Pick the folder (or keep the one proposed) and finish. No administrator rights needed. The
   setup adds a Start-menu entry and, if you leave the box ticked, a desktop shortcut.
4. Start **BlackoutUO**. The launcher downloads the client and the game data (~1.2 GB the first
   time; afterwards only what changed) and the button turns into **Play**.

The launcher keeps itself, the client and the data up to date on every start. There is nothing to
accept: the shard only admits the current build.

### Without the installer

If you prefer a bare executable, download `BlackoutLauncher.exe` from the same release and run it
from wherever you like; it asks for the folder on first start. The SmartScreen click-through is
the same. This is also the file the launcher uses to update itself, so an installed launcher never
needs a new setup.

### Uninstall

**Settings → Apps → BlackoutUO → Uninstall.** It asks whether to delete the downloaded client and
data too (~1.2 GB); if you keep them, reinstalling into the same folder reuses them.

### Something went wrong

Click **Open log** in the launcher and attach `launcher.log` to your report. If the launcher
cannot reach the update server, it still lets you play the version you already have.
