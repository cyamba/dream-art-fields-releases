# Dream Art Fields: Windows installers

Signed installers for [Dream Art Fields](https://dreamartfields.com), the local AI image and video
studio for Windows by YambaCode AB. The source code is not here; this repository only hosts the
release files.

**Download:** the newest version is under [Releases](https://github.com/cyamba/dream-art-fields-releases/releases/latest).
The app needs a licence: buy one at [dreamartfields.com](https://dreamartfields.com). Nothing opens
without it.

## Before you install

- Windows 11 and an NVIDIA RTX card: 24 GB VRAM recommended, 16 GB minimum. A recent driver (R570 or newer).
- About 115 GB free disk for the starter models (310 GB for the full commercial set), 32 GB RAM recommended.
- Step by step: [dreamartfields.com/start.html](https://dreamartfields.com/start.html).

## Check the download

Each installer is signed by **YambaCode AB** (Certum code-signing certificate). In Windows:
right-click the file → Properties → Digital Signatures should show *YambaCode AB*. Or in PowerShell:

```powershell
Get-AuthenticodeSignature .\DreamArtFields-1.0.0-setup.exe   # Status: Valid, signer YambaCode AB
Get-FileHash -Algorithm SHA256 .\DreamArtFields-1.0.0-setup.exe   # compare with the .sha256 file in the release
```

Support: support@dreamartfields.com
