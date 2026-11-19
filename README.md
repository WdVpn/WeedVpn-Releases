# WeedVPN Releases

Official Windows desktop releases for [WeedVPN](https://weedvpn.surf).

## Download

Grab the latest Windows installer from the [Releases](https://github.com/WdVpn/WeedVpn-Releases/releases/latest) page.

## Requirements

- Windows 10 / 11 (64-bit)

## Verification

Every release installer is signed and verified via SHA-256 checksum and Ed25519 release manifests. Checksums are published in each release's notes.

To verify locally in PowerShell:

```powershell
Get-FileHash .\WeedVPN-Setup-1.0.1.exe -Algorithm SHA256
```
