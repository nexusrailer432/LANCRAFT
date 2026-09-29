<div align="center">

<img src="assets/banner.png" width="640" alt="LANCRAFT"/>

### Your server. Your pocket. Your rules.

[![Release](https://img.shields.io/github/v/release/nexusrailer432/LANCRAFT?color=00E5FF&label=release&labelColor=0D1117)](https://github.com/nexusrailer432/LANCRAFT/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/nexusrailer432/LANCRAFT/total?color=3CF07C&label=downloads&labelColor=0D1117)](https://github.com/nexusrailer432/LANCRAFT/releases)
[![Platform](https://img.shields.io/badge/Android-8%2B-3DDC84?logo=android&logoColor=white&labelColor=0D1117)](https://github.com/nexusrailer432/LANCRAFT/releases)
[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white&labelColor=0D1117)](https://discord.gg/rjykaH9nUu)

**A real Minecraft Java Edition server — running on your phone.**

No PC · no renting · no queue · your phone *is* the server.
Friends on the same Wi-Fi or hotspot join directly — and with **Remote Play**,
friends in other cities join too. No port forwarding. No PC. Ever.

<br/>

<a href="https://github.com/nexusrailer432/LANCRAFT/releases">
<img width="270" src="https://img.shields.io/badge/%E2%AC%87_Download-v4.0.1-3CF07C?style=for-the-badge&labelColor=0D1117" alt="Download LANCRAFT"/>
</a>

</div>

---

## ⚡ The v4 toolkit

<img src="assets/features.png" width="860" alt="LANCRAFT features"/>

| | |
|---|---|
| ⛏ **Real Paper server** | A full Minecraft Java server (1.21+) running on-device — not a proxy, not an emulator |
| 🌍 **Remote Play** | Free playit.gg tunnel built in — friends join from **any network on Earth** |
| ☁️ **Cloud backups** | Ship your worlds to Google Drive with one tap — phones die, worlds don't |
| ⏰ **Automation** | Schedule console commands (nightly saves, restarts) that run while you play |
| 🧩 **One-tap plugins** | Geyser, ViaVersion, ViaBackwards, Floodgate, LuckPerms, EssentialsX — straight from Modrinth |
| 📈 **Live TPS monitor** | Real server health stats on your dashboard — know about lag before your players do |
| 🎨 **MOTD builder** | Color-coded server list message with live preview |
| 🌍 **World transfer** | Copy worlds between server profiles in-app |
| 🖥 **Live console** | Read logs, run any command, watch players join in real time |
| 🌐 **Web dashboard + live map** | Open `http://<phone-ip>:8765` in any browser on your network |
| 🗺 **World manager** | Import / export worlds & datapacks, set seeds, switch active world |
| 👥 **Player manager** | OP, kick, give XP, gamemode, effects, ban / unban |
| 📡 **LAN broadcast** | Your server appears in every Java client's *"Scanning for games on your local network"* list |
| 🔗 **QR join code** | Friends scan & connect — no typing IPs |
| 📱 **Widget + join alerts** | Server status on your home screen, pings when someone joins |
| 🎮 **Bedrock support** | Phone / console players join with their Xbox gamertag via Geyser |

## 🚀 Quick start

1. **Install** — grab the APK from [Releases](https://github.com/nexusrailer432/LANCRAFT/releases) and open it. Android will warn about unknown apps: **More details → Install anyway** (normal for anything outside the Play Store — same as Termux / PojavLauncher)
2. **Tap DOWNLOAD RUNTIME** — the app now pulls its Java 21 runtime from this repo with one tap. No browser, no file picker
3. **Create a profile** — name, version, RAM (1536 MB is a good default on 4 GB phones)
4. **Import the server JAR** — e.g. `paper-1.21.4.jar` from [papermc.io](https://papermc.io/downloads) and accept the EULA
5. **START** — watch the console come alive. Players join `<phone-ip>:25565`, pick the server from the LAN tab, or enable **Remote Play** for a public address that works from anywhere

> Why import the server JAR yourself? Mojang's licensing doesn't let anyone redistribute their files. You download once from the official sources — LANCRAFT never bundles them.

## 🌍 Remote Play — friends from anywhere

LAN-only servers are yesterday's news. Enable Remote Play and LANCRAFT runs a free [playit.gg](https://playit.gg) tunnel alongside your server:

- One-time setup: approve the tunnel in your browser (~30 seconds, free account)
- Add a **Minecraft Java** tunnel (local port 25565) in the playit dashboard
- The public address appears in the app, the QR code and the console — share it anywhere

Works for both the free tier and premium. LAN play stays fully functional either way.

## 🆓 Free vs 💎 Premium

| | Free | Premium |
|---|---|---|
| Hosting, worlds, plugins, dashboard, Remote Play | ✅ | ✅ |
| Server mode | Online (Microsoft account required) | **Offline — any name works** (TLauncher, SKLauncher, Pojav…) |
| Internet at server start | Required | **Not needed — fully offline hotspot hosting** |
| Cloud backups · Automation · MOTD builder · World transfer · TPS monitor | — | ✅ all of them |
| Key | — | One-time · verified **offline** (signed keys, no license server, no tracking) |

➡️ Premium keys live in our [Discord](https://discord.gg/rjykaH9nUu) — ₹29 (1 mo) · ₹99 (6 mo) · ₹149 (1 yr) · ₹249 (lifetime).

## 🎮 Bedrock players & plugins

- **Offline mode (Premium)** — tap INSTALL on Geyser in the Mods tab, done. Bedrock joins on port 19132 with just a gamertag
- **Online mode (Free)** — also install Floodgate so Bedrock players join without a Java account (name shows a `.` prefix)
- **Version mismatch** — ViaVersion + ViaBackwards let older / newer clients in

All of them install with **one tap** from the **Mods** tab inside the app.

## ❓ FAQ

<details><summary><b>Play Protect blocked the install</b></summary>

Tap **More details → Install anyway**. LANCRAFT isn't on the Play Store because it runs a real server process — Play policy doesn't allow that (it's why Termux isn't there either). The release APK is signed; installs are safe.
</details>

<details><summary><b>Why do I import the server JAR myself?</b></summary>

Mojang's licensing forbids redistributing their software. LANCRAFT ships none of their files — you bring your own from official sources. This keeps everything legal. (The Java runtime we ship you directly is our own packaging of open-source builds, so one tap is fine there.)
</details>

<details><summary><b>Will my phone survive this?</b></summary>

A phone is a modest server — vanilla / Paper with a handful of friends works well. It runs warm: keep it charging, out of a case, and off your pillow 🙂
</details>

<details><summary><b>Does Remote Play cost money?</b></summary>

No — playit.gg's free tier covers personal use. LANCRAFT's Remote Play itself is free for everyone, free-tier and premium alike.
</details>

<details><summary><b>Can it run 24/7?</b></summary>

Only while the phone is on, charging, and LANCRAFT is running. That's the deal with hosting on a phone.
</details>

## ⚖️ Legal

LANCRAFT is **not affiliated with Mojang Studios or Microsoft**. Minecraft is a trademark of Mojang Studios. LANCRAFT ships none of Mojang's files — you import your own runtime, server JAR, and own legitimate copies of the game. Minecraft EULA acceptance is required and enforced.

## 💬 Community

Questions, plugin help, premium keys:

<a href="https://discord.gg/rjykaH9nUu">
<img width="180" src="https://img.shields.io/badge/Discord-join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
</a>

---

<div align="center"><sub>LANCRAFT — your server, your pocket, your rules.</sub></div>
