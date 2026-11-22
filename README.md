# Pocket Speaker — downloads

Use your phone as a wireless speaker for your Windows PC, over your own Wi-Fi.
No app on the phone, no account, no cloud: scan a QR code and listen.

## Download

**[⬇ Download the latest version](https://github.com/umerraza28/pocket-speaker-releases/releases/latest)**,
then run `PocketSpeaker-Setup-<version>.exe`.

- Windows 10 or 11 (64-bit). Installs for your user account only, so no admin is needed.
- Windows may say *"Windows protected your PC"* because the app is not code-signed yet:
  click **More info → Run anyway**.
- The first time you open it, allow Pocket Speaker on **private networks** when Windows Firewall asks.

## How to use

1. Open **Pocket Speaker** on the PC. A window with a QR code appears.
2. Connect the phone to the same Wi-Fi, scan the QR code and open the link.
3. Tap **Listen on this phone** and play anything on the PC.

Works on iPhone and Android in Safari, Chrome and Opera. Live mode has about 0.1–0.2 s delay.
Keep the page open. On iPhone, set Auto-Lock to *Never* while listening if your browser can't keep the screen on.

## Updates

Pocket Speaker checks this page for new versions. When one is out, a green bar appears in the
app: click **Update now** and it installs and reopens by itself. You can also click
**Check for updates** at the top of the window.

## Verify a download (optional)

Each release includes `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\PocketSpeaker-Setup-1.0.0.exe -Algorithm SHA256
```

This repository only holds the installers; the source code is private.
