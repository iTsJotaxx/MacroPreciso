# AltVigil

A Windows app to record and play back keyboard and mouse macros with precise timing, built with Roblox in mind. A single `.exe` file, no installer (about 1.3 MB: it includes the Microsoft WebView2 files used to sign in to Roblox accounts).

**[⬇ Download AltVigil.exe](https://github.com/iTsJotaxx/MacroPreciso/releases/latest/download/AltVigil.exe)** · Windows 10/11, 64-bit · [Official website](https://jotabuilds.pages.dev)

## Features

- **Record and play back** keyboard and mouse macros with exact timings.
- **Roblox camera macros**: measures the camera and restores it before each loop.
- **Saved macros** with their own hotkey, so you can trigger them from anywhere.
- **Autoclicker** and **Detector**.
- Opens `.mcp` recordings and TinyTask `.rec` files, and can create an `.exe` with a macro built in.
- **Multi Roblox panel**: open several Roblox accounts at once, each in its own cell of a grid inside AltVigil (also on a second monitor), with full screen for one account, reconnect and a double-click disconnect button per account.
- **A different game per account**: each account can join its own game, chosen from a list or by browsing the Roblox website inside the app.
- **Performance mode** for many accounts: caps the FPS of the accounts in the background (adjustable in Settings), lowers Roblox graphics while accounts open, and frees memory of background accounts.
- Languages: Spanish, English and French.

## How to use it

1. Download `AltVigil.exe` from the **Releases** section of this repository.
2. Run it. No installation or administrator rights needed.
3. Record a macro, save it and give it a hotkey.

## About the Windows warning

The first time you run it you may see **"Windows protected your PC"** (SmartScreen) or an antivirus warning. This happens with most small unsigned programs, and more so with ones that simulate keyboard and mouse input, which is exactly what a macro tool does.

To check that you have the original file:

- Compare its **SHA-256** hash with the one in the notes of each Release. In PowerShell: `Get-FileHash .\AltVigil.exe -Algorithm SHA256`
- Upload it yourself to [virustotal.com](https://www.virustotal.com) and check the result.
- If you trust it, click **More info → Run anyway**.

## Disclaimer

Use at your own risk. Check the rules of the game you use it in: some games do not allow automating actions.
