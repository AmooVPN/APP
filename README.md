# AmooVPN — Official Desktop Releases

Official binary distribution repository for **AmooVPN**, a proprietary VPN client for Windows and Linux.

This repository provides compiled application releases, version information, checksums, and resources used by the AmooVPN automatic updater.

**The proprietary AmooVPN source code is not published in this repository.**

## Download

**Latest release:** [AmooVPN](https://github.com/AmooVPN/APP/releases/)

| Platform | Package | Download |
|---|---|---|
| Windows x64 | ZIP | [Download for Windows](https://github.com/AmooVPN/APP/releases/latest/download/AmooVPN-windows-amd64.zip) |
| Windows x64 | 7z | [Alternative Windows archive](https://github.com/AmooVPN/APP/releases/latest/download/AmooVPN-windows-amd64.7z) |
| Linux x86_64 | ZIP | [Download for Linux](https://github.com/AmooVPN/APP/releases/latest/download/AmooVPN-linux-amd64.zip) |
| Linux x86_64 | 7z | [Alternative Linux archive](https://github.com/AmooVPN/APP/releases/latest/download/AmooVPN-linux-amd64.7z) |

[View all releases](https://github.com/AmooVPN/APP/releases)

## Installation

### Windows

1. Download the Windows ZIP archive.
2. Extract the archive to a folder of your choice.
3. Run `AmooVPN-windows.exe`.
4. Sign in to your AmooVPN account.

Windows may display a security warning for an application that has not established publisher reputation. Download only from official sources and verify the package checksum.

### Linux

1. Download the Linux ZIP archive.
2. Extract it.
3. Open a terminal in the extracted directory.
4. Make the executable runnable and launch it:

```bash
chmod +x AmooVPN-linux
./AmooVPN-linux
```

Depending on your system and selected VPN mode, additional permissions or system components may be required.

## Verify Downloads

Official releases provide SHA-256 checksums.

[Download checksums.txt](https://github.com/AmooVPN/APP/releases/download/v2.0.0/checksums.txt)

On Linux:

```bash
sha256sum AmooVPN-linux-amd64.zip
```

On Windows PowerShell:

```powershell
Get-FileHash .\AmooVPN-windows-amd64.zip -Algorithm SHA256
```

Compare the result with the corresponding entry in `checksums.txt`.

## Automatic Updates

AmooVPN includes an automatic update mechanism that checks published releases for newer versions.

This repository serves as the official release distribution endpoint.

## Supported Languages

Persian, Arabic, English, German, Russian, and Chinese.

## Website

**Official website:** https://amoodev.space

## Licensing

AmooVPN's original application is proprietary, closed-source software.

Third-party components retain their respective licenses and copyright notices. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and [LICENSE](LICENSE) for details.

© 2026 AmooVPN. All rights reserved.
