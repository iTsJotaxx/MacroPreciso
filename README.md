# MacroPreciso

A Windows app to record and play back keyboard and mouse macros with precise timing, built with Roblox in mind. A single `.exe` file, no installer.

**[⬇ Download the latest version](https://github.com/iTsJotaxx/MacroPreciso/releases/latest)** (`MacroPreciso.exe`)

## Features

- **Record and play back** keyboard and mouse macros with exact timings.
- **Roblox camera macros**: measures the camera and restores it before each loop.
- **Saved macros** with their own hotkey, so you can trigger them from anywhere.
- **Autoclicker** and **Detector**.
- Opens `.mcp` recordings and TinyTask `.rec` files, and can create an `.exe` with a macro built in.
- Languages: Spanish, English and French.

## How to use it

1. Download `MacroPreciso.exe` from the **Releases** section of this repository.
2. Run it. No installation or administrator rights needed.
3. Record a macro, save it and give it a hotkey.

## About the Windows warning

The first time you run it you may see **"Windows protected your PC"** (SmartScreen) or an antivirus warning. This happens with most small unsigned programs, and more so with ones that simulate keyboard and mouse input, which is exactly what a macro tool does.

To check that you have the original file:

- Compare its **SHA-256** hash with the one in the notes of each Release. In PowerShell: `Get-FileHash .\MacroPreciso.exe -Algorithm SHA256`
- Upload it yourself to [virustotal.com](https://www.virustotal.com) and check the result.
- If you trust it, click **More info → Run anyway**.

## Disclaimer

Use at your own risk. Check the rules of the game you use it in: some games do not allow automating actions.
