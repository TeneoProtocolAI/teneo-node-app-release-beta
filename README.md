# Teneo Beacon

**Teneo Beacon turns the devices you already own into part of a global network that gives AI agents real-time access to the open web.** Run it in the background, share bandwidth you aren't using, and earn rewards for every hour your Beacon is online.

AI agents increasingly need to see the web the way people do: live pages, local results, from real connections in real countries. Beacon operators provide exactly that. Since launching in April 2026, the network has grown to **20,000+ verified operators in 150+ countries**, with **8,300+ Beacons online** across **120+ countries**.

[Download](#download) · [Expedition Hub](https://hub.teneo.pro) · [Website](https://teneo.pro) · [Discord](https://discord.gg/WJQpSUsbu3)

---

## Download

**Current version: 0.4.9**

| Platform | Get it | |
|----------|--------|---|
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=teneo.node) | |
| **iOS** | [TestFlight](https://testflight.apple.com/join/bSUKTYJn) | Public TestFlight; App Store release to follow |
| **macOS** (Apple Silicon + Intel) | `.dmg` from the [latest release](https://github.com/TeneoProtocolAI/teneo-node-app-release-beta/releases/latest) | Developer ID signed and notarized by Apple |
| **Windows 10/11** | `.exe` installer (recommended) or `.msi` from the [latest release](https://github.com/TeneoProtocolAI/teneo-node-app-release-beta/releases/latest) | |
| **Linux** (Debian/Ubuntu, Fedora/RHEL) | `.deb` / `.rpm` from the [latest release](https://github.com/TeneoProtocolAI/teneo-node-app-release-beta/releases/latest) | |
| **Raspberry Pi, servers, NAS** | [Teneo Beacon CLI](https://github.com/TeneoProtocolAI/teneo-beacon-cli) | Headless, one-line install |

Desktop apps update themselves: when a new version is published you'll see an in-app update prompt. Every update is cryptographically signed and verified before it installs.

## How it works

1. **Install** Beacon on your phone, laptop or desktop.
2. **Sign up** with your Teneo account and review the consent screen.
3. **Connect.** Beacon runs quietly in the background and starts earning right away.
4. **Boost** every 8 hours in the app to grow your multiplier.

You can disconnect at any time.

## What you earn

| | |
|---|---|
| **Fragments** | Earned continuously while your Beacon is online. |
| **Beacon Power** | Claim your Fragments every 8 hours to grow a multiplier of up to 3x. Consistency is rewarded; missed windows decay it gradually, and earned Fragments are never lost. |
| **Teneo Points** | Earned alongside Fragments while your node is connected. |
| **Seasons & Beacon Drops** | Each season ends with USDC prize draws for active operators. Across Seasons 1–4, **7,500+ USDC** has been awarded to **2,300+ winners**. |
| **Referrals** | Earn a share of the Fragments your referrals generate, plus milestone bonuses and a growing referral multiplier. |
| **Your fleet** | Run Beacon on every device you own. Each device on its own internet connection earns on its own. |

Track everything — Fragments, quests, referrals and your device fleet — in the **[Expedition Hub](https://hub.teneo.pro)**.

## Safety and privacy

- **Opt-in, always.** Beacon asks for your explicit consent before it shares anything, and you can stop at any time.
- **Your private network stays private.** Beacon refuses connections to your local network, your router and other private or loopback addresses.
- **Abuse-prone ports are blocked on the device.** Email sending, remote login, DNS, file sharing, databases and device-debugging ports are refused by the app itself, regardless of what the network asks for.
- **No access to your data.** Beacon relays network connections only. It does not read your files, browsing history, contacts or other apps.
- **Fair use.** Bandwidth contributed per device is limited, so Beacon stays light on your data plan and battery.
- **Home and mobile connections only.** Beacon is built for real residential and mobile internet connections. VPNs and proxies are not supported.
- **Signed builds.** macOS builds are signed and notarized by Apple, Android builds are signed for Google Play, and desktop updates are signature-verified before they install.

Full details: [Terms of Service](https://legal.teneo.pro/terms) · [Privacy Policy](https://legal.teneo.pro/privacy)

## Install notes

### Android
Install from [Google Play](https://play.google.com/store/apps/details?id=teneo.node) and sign in. For best uptime, allow Beacon to run in the background when the app asks. Some manufacturers' battery savers stop background apps, and the app shows device-specific tips when that happens.

### iOS
Join via [TestFlight](https://testflight.apple.com/join/bSUKTYJn), install the app, then sign in with your Teneo account.

### macOS
Open the `.dmg` and drag **Teneo Beacon** to Applications.

### Windows
Run the `.exe` installer (or the `.msi`). If Windows SmartScreen shows "Windows protected your PC", choose **More info → Run anyway**.

### Linux
```bash
# Debian / Ubuntu
sudo apt install ./Teneo.Beacon_*_amd64.deb

# Fedora / RHEL
sudo dnf install ./Teneo.Beacon-*.x86_64.rpm
```

## Links

| | |
|---|---|
| Expedition Hub | [hub.teneo.pro](https://hub.teneo.pro) |
| Website | [teneo.pro](https://teneo.pro) |
| Beacon CLI (Raspberry Pi / Linux / macOS servers) | [teneo-beacon-cli](https://github.com/TeneoProtocolAI/teneo-beacon-cli) |
| Discord | [discord.gg/WJQpSUsbu3](https://discord.gg/WJQpSUsbu3) |
| X | [@teneo_protocol](https://x.com/teneo_protocol) |
| Terms of Service | [legal.teneo.pro/terms](https://legal.teneo.pro/terms) |
| Privacy Policy | [legal.teneo.pro/privacy](https://legal.teneo.pro/privacy) |

This repository hosts the official signed Teneo Beacon builds.
