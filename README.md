# Couch Pack — TestPhase

Test build of **Couch Pack**, a Retro Rewind (Mario Kart Wii) mod for playing with friends.

**To install, use `CouchPack.exe`** (the Couch Pack installer). It downloads the files from this branch,
finds your Retro Rewind folder and installs the mod. It only downloads files that changed since your last
update. **Restore normal RR** puts the original Retro Rewind files back.

What's in here:

| Folder | What the installer does with it |
|---|---|
| `payload/replace/<path>` | Replaces that file in your `RetroRewind6` folder (the original is kept as `<file>.original`) |
| `payload/patch/<archive>.szs/@root/` | Adds these files to the root of that Retro Rewind archive |
| `payload/patch/<archive>.szs/@itemicons/` | Adds these icons next to the game's item icons in that archive |
| `manifest.txt` | Version and SHA-256 of every file (the installer checks every download against it) |

Needs the same Retro Rewind version as the build (RetroRewind6). Online play is friends only.

Couch Pack is built on Retro Rewind's code ([Retro Rewind / Pulsar](https://github.com/Retro-Rewind-Team), GPLv3).
