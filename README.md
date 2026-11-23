<p align="center">
  <a href="https://weedvpn.surf">
    <img src="https://weedvpn.surf/og-banner.png" alt="WeedVPN — Private No-Email Windows VPN" width="760" />
  </a>
</p>

# WeedVPN for Windows

Official signed desktop releases for **[WeedVPN](https://weedvpn.surf)** — a private Windows VPN with **no emails, no passwords, no logs, and no recurring subscriptions**.

[**Website**](https://weedvpn.surf) · [**Download Page**](https://weedvpn.surf/download) · [**Pricing**](https://weedvpn.surf/pricing) · [**Support & Refunds**](https://weedvpn.surf/support) · [**Discord**](https://discord.gg/qJjBmupnRY)

---

## Key Features

- **Anonymous 16-Digit Accounts** — Generate a random 16-digit account number with zero email or personal information. Only a keyed one-way hash is stored server-side.
- **Native Windows Kill Switch** — Uses a lightweight background Windows service (`WeedVPNService`) with Wintun and Windows Filtering Platform (WFP) rules to prevent IPv4, IPv6, and DNS leaks.
- **Modern Protocols & Multi-Hop** — Fast Anycast **WireGuard**, **OpenVPN**, **Double VPN** (two-country routing), and **Tor Mode** with built-in `obfs4` & `meek` bridges.
- **Encrypted DNS & Tracker Blocking** — Quad9 DNS (`9.9.9.9`) inside the tunnel with a built-in Ad & Tracker Blocker.
- **Free Tier + One-Time Passes** — Use the permanent **Free** plan (1 Windows PC, 4 core regions) forever, or unlock all 56+ countries, Double VPN, Tor Mode, and up to 5 PCs with one-time GBP Pro passes from £1.99 via card (Stripe) or crypto (NOWPayments) — zero auto-renewal.

---

## Download

Grab the latest verified Windows 10 / 11 (64-bit) installer from either:
- **[weedvpn.surf/download](https://weedvpn.surf/download)** *(includes one-click PowerShell SHA-256 verification)*
- **[GitHub Latest Release](https://github.com/WdVpn/WeedVpn-Releases/releases/latest)**

### Requirements
- Windows 10 or Windows 11 (64-bit)
- One-time administrator approval during installation to register the Wintun adapter and Windows Firewall service (after setup, the desktop app runs as a standard user)

*Linux, macOS, and Android support are planned for future releases.*

---

## Verify Your Installer (SHA-256)

Every release installer is verified via **Ed25519-signed release manifests** and published **SHA-256 checksums** in each release's notes.

To verify your download locally in PowerShell (replace `<version>` with the version you downloaded):

```powershell
Get-FileHash .\WeedVPN-Setup-<version>.exe -Algorithm SHA256
```

Compare the output hash against the SHA-256 checksum listed on the [latest release](https://github.com/WdVpn/WeedVpn-Releases/releases/latest) or on [weedvpn.surf/download](https://weedvpn.surf/download).

---

## Community & Support

- **Discord:** [discord.gg/qJjBmupnRY](https://discord.gg/qJjBmupnRY) — setup help, release updates, and support tickets
- **Support & 14-Day Refund Policy:** [weedvpn.surf/support](https://weedvpn.surf/support)
- **Privacy Policy:** [weedvpn.surf/privacy](https://weedvpn.surf/privacy)
