### Hi, I'm Vincent 👋

I build small, self-hosted tools — the kind I wanted and couldn't find. Everything here is MIT-licensed
and runs on your own machine or server, with no account to create. Toronto, Canada.

---

#### 🎤 [TextFromTrack Roon Companion](https://github.com/r45635/roon.app.textfromtrack.com) — synced lyrics for everything Roon plays

<img src="https://raw.githubusercontent.com/r45635/roon.app.textfromtrack.com/main/docs/media/clips/karaoke.gif" width="480" alt="Lyrics highlighted line by line, in time with the music">

Follows a Roon zone and shows the lyrics line by line, in time with the music — Qobuz, TIDAL, radio or
your own files. Full screen, on your phone or a tablet on the shelf. Desktop app (macOS, Windows, Linux)
or Docker on your NAS. → [Download](https://github.com/r45635/roon.app.textfromtrack.com/releases/latest)

And its hardware sidekick, **[TFT Panel](https://github.com/r45635/tft-panel)**: open firmware that turns a
7" ESP32 touch screen (Elecrow CrowPanel, Waveshare ESP32-P4) into a lyrics display and remote for Roon.

#### 🐾 [claude-pet](https://github.com/r45635/claude-pet) — see what Claude Code is doing, at a glance

<img src="https://raw.githubusercontent.com/r45635/claude-pet/main/docs/media/hero.gif" width="240" alt="The creature coding, with three subagents walking around it">

A tiny creature in a corner of your Mac that shows when Claude Code is thinking, coding, storming
through a big task — or waiting for you. Custom avatars in the [avatar library](https://github.com/r45635/claude-pet-avatars).

```bash
brew install r45635/tap/claude-pet && claude-pet setup
```

#### 🛡️ [Easy-WG-Combo](https://github.com/r45635/Easy-WG-Combo) — your own VPN + ad-blocking DNS on one small VPS

WireGuard, AdGuard Home and an admin portal in one install: devices and QR codes, per-device DNS
filtering, an optional VLESS + Reality tunnel (Xray) for censored networks, security checks, backups,
monitoring and alerts. English, French, Chinese.

```bash
curl -fsSL https://raw.githubusercontent.com/r45635/Easy-WG-Combo/refs/heads/main/install.sh | bash
```

#### 📚 [PDF to CBZ Converter](https://github.com/r45635/pdf-to-cbz-converter) — comics and manga, PDF ↔ CBZ

Live preview, smart DPI detection, batch mode, no recompression when it isn't needed. 10k+ Docker pulls.
[Try it online](https://pdf-to-cbz-converter.vercel.app), run `docker run -p 3000:3000 r45635/pdf-to-cbz`,
or get the [desktop app](https://github.com/r45635/pdf-to-cbz-converter2/releases/latest) for macOS, Windows and Linux.

---

<sub>Older but still used: <a href="https://github.com/r45635/HVAC-IR-Control">HVAC-IR-Control</a> —
control Mitsubishi and Panasonic heat pumps over IR from an Arduino (270+ ★).</sub>
