# Sherpalaxy GTA5 Teleport Mod

Click a pin on https://sherpalaxy.gg/gta/5 to teleport in GTA V (Legacy / Enhanced).

## Download
Get the latest zip from [Releases](https://github.com/Sherpalaxy/gta5-teleport-mod/releases/latest).

## Important: add a Windows Defender exclusion first
Windows Defender currently flags `sherpalaxy.exe` (as `Behavior:Win32/DefenseEvasion.A!ml`) and stops it the moment you teleport. **When that happens, the game closes too.**

Before your first teleport, exclude the folder you unzipped the mod into:

1. Open **Windows Security** → **Virus & threat protection**.
2. Under **Virus & threat protection settings**, click **Manage settings**.
3. Scroll to **Exclusions** → **Add or remove exclusions** → **Add an exclusion** → **Folder**.
4. Select the unzipped `Sherpalaxy-0.1.0` folder.

## Why antivirus flags it
The mod injects a DLL into the game, so some antivirus engines flag it by behavior. This is a false positive. Each release zip includes VIRUSTOTAL.txt with the exe's SHA-256 and scan link. False-positive reports have been sent to Microsoft and other vendors; once they are reviewed, the exclusion should no longer be needed.
