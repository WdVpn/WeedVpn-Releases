<p align="center">
  <a href="https://weedvpn.surf">
    <img src="https://weedvpn.surf/og-banner.png" alt="WeedVPN — Private No-Email VPN for Windows & Android" width="760" />
  </a>
</p>

# WeedVPN — Windows & Android Releases

Official signed releases for **[WeedVPN](https://weedvpn.surf)** — a private VPN for **Windows 10/11 (64-bit)** and **Android 8.0+** with **no emails, no passwords, no logs, and no recurring subscriptions**.

[**Website**](https://weedvpn.surf) · [**Download Page**](https://weedvpn.surf/download) · [**Pricing**](https://weedvpn.surf/pricing) · [**Support & Refunds**](https://weedvpn.surf/support) · [**Discord**](https://discord.gg/qJjBmupnRY)

---

## Key Features

- **Anonymous 16-Digit Accounts** — Generate a random 16-digit account number with zero email or personal information. Only a keyed one-way hash is stored server-side.
- **Windows & Android Apps** — Signed desktop installer (`.exe`) for Windows 10 & 11 (64-bit) and direct signed `.apk` for Android 8.0+ with no Google Play Services.
- **System Leak Protection** — Windows Filtering Platform (WFP) Kill Switch on PC and Android Always-On VPN support on mobile to block unencrypted traffic if the tunnel drops.
- **Modern Protocols & Multi-Hop** — Fast Anycast **WireGuard**, **OpenVPN**, **Double VPN** (two-country routing), and **Tor Mode** with built-in `obfs4` & `meek` bridges.
- **Encrypted DNS & Tracker Blocking** — Quad9 DNS (`9.9.9.9`) inside the tunnel with a built-in Ad & Tracker Blocker and per-app Split Tunneling.
- **Free Tier + One-Time Passes** — Use the permanent **Free** plan (1 device, 4 core regions) forever, or unlock all 56+ countries, Double VPN, Tor Mode, and up to 5 devices with one-time GBP Pro passes from £1.99 via card (Stripe) or crypto (NOWPayments) — zero auto-renewal.

---

## Download & Minimum Requirements

Grab the latest verified Windows `.exe` or Android `.apk` from either:
- **[weedvpn.surf/download](https://weedvpn.surf/download)** *(auto-selects Windows or Android with SHA-256 verification)*
- **[GitHub Releases](https://github.com/WdVpn/WeedVpn-Releases/releases)**

### Minimum OS Versions
- **Windows:** Windows 10 or Windows 11 (64-bit) — one-time administrator approval during setup for Wintun and `WeedVPNService`
- **Android:** Android 8.0 or newer (Android 8.0 – 15, ARM64 / ARMv7, non-rooted devices)

---

## Verify Your Download (SHA-256)

Every release is verified via **Ed25519-signed release manifests** and published **SHA-256 checksums** in each release's notes.

**Windows (PowerShell):**
```powershell
Get-FileHash .\WeedVPN-Setup-<version>.exe -Algorithm SHA256
```

**Android (Linux / macOS / Termux):**
```bash
sha256sum WeedVPN-Android-<version>.apk
```

Compare the output hash against the SHA-256 checksum listed in the [release notes](https://github.com/WdVpn/WeedVpn-Releases/releases) or on [weedvpn.surf/download](https://weedvpn.surf/download).

---

## Community & Support

- **Discord:** [discord.gg/qJjBmupnRY](https://discord.gg/qJjBmupnRY) — setup help, release updates, and support tickets
- **Support & 14-Day Refund Policy:** [weedvpn.surf/support](https://weedvpn.surf/support)
- **Privacy Policy:** [weedvpn.surf/privacy](https://weedvpn.surf/privacy)
