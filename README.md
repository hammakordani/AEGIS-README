<div align="center">

<img src="assets/banner.jpg" alt="AEGIS OS — the white Guardian Owl in AEGIS Blue" width="100%">

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-white.png">
  <img src="assets/logo-navy.png" alt="AEGIS OS Guardian Owl" width="260">
</picture>

# AEGIS OS

### Beyond the ordinary.

**A Debian-based Linux desktop for everyday work, privacy and cybersecurity learning.**

![Debian 13](https://img.shields.io/badge/based%20on-Debian%2013%20trixie-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![KDE Plasma 6](https://img.shields.io/badge/desktop-KDE%20Plasma%206-1D99F3?style=for-the-badge&logo=kde&logoColor=white)
![Wayland](https://img.shields.io/badge/session-Wayland-5B2D90?style=for-the-badge)
![Version](https://img.shields.io/badge/version-0.1.0--alpha1-2F6BFF?style=for-the-badge)
![Status](https://img.shields.io/badge/status-private%20development-0E1B2D?style=for-the-badge)

</div>

---

AEGIS OS is a Linux operating system in development. One desktop, three modes: **Daily** for everyday work, **Gaming** for play and **Cyber** for learning defensive security, plus a built-in **Security Center** that shows what your computer is doing, read straight from the system and never sent anywhere.

![AEGIS OS Daily desktop](screenshots/01-daily-desktop.jpg)

## 🎯 Our main goal

> **One operating system that is easy enough for everyday life and honest enough to trust with your security.**

Most people have to pick between a simple desktop that hides what it does and a security distribution that is hard to live with. AEGIS OS aims to remove that choice:

- **For everyone:** a modern, fast, smooth Linux desktop for work and browsing, safe from the first boot with nothing to configure.
- **For players:** a Gaming mode with its own look and performance settings, without switching off any protection.
- **For learners and defenders:** a built-in, clearly separated Cyber mode with the Security Lab for learning ethical, authorized cybersecurity, one click away.
- **For your privacy:** a system that shows what it is doing with real data, makes no hidden network requests and asks before optional ones.
- **For the long run:** a modular Debian base where every part updates on its own, so AEGIS can keep growing without breaking your computer.

## ✨ What's new

> New features below are built and tested in a virtual machine. They arrive on the installable image with the next build.

| | |
|---|---|
| 🦉 **New white Guardian Owl** | A clean, sharp owl emblem everywhere: boot screen, login, icons and wallpapers. At start-up the owl's eyes light up in AEGIS Blue. |
| 🎮 **Three modes: Daily, Gaming, Cyber** | A new **Gaming** mode with its own green look and the performance power profile on mains power. **Daily** keeps your own look and power settings. **Cyber** is the Security Lab. |
| 🎬 **Smooth mode transitions** | Every switch plays its own effect: Daily a soft fade, Gaming an energy burst, Cyber a scanline glitch. With reduced motion turned on it is a calm still image, and Esc skips it. |
| 🎛️ **Mode menu in the top bar** | Click the mode button and pick Daily, Gaming or Cyber, with a short description of each. Works with the keyboard too (arrows, Enter, Esc), and the active mode is shown by name and check mark, not by colour alone. |
| 🧷 **Safe switching** | A switch is checked after it is applied and only then counts. If something fails on the way into Gaming or Cyber, AEGIS puts your previous mode back instead of leaving a half-changed desktop. |
| 🕹️ **Gaming check and Quick Gaming** | A read-only check (`aegis-gaming status`) shows what your computer offers for games: graphics card and driver, Vulkan, GameMode, power profiles and installed launchers, with plain-language notes. Nothing is sent anywhere and nothing is installed. While Gaming mode is on, background file indexing pauses and resumes when you leave. |
| 🖼️ **Four new wallpapers** | AEGIS Blue, AEGIS Lab, AEGIS Monochrome and AEGIS Purple Scratch. |
| 🔥 **Stronger defaults, now tested** | Firewall on at boot, Firefox privacy settings active, fewer background look-ups at first start, and a security-update card that a stray Enter key cannot trigger. |
| 📦 **Built from modules** | Every AEGIS part is its own Debian package with its own version, so a fix can arrive as one small update instead of a whole new system image. |

## 🌗 Three modes, one owl

> **One click → Gaming. One click → Cyber lab. One click → back to Daily.**
>
> No reboot, no logout and no password. Firewall, AppArmor and security updates stay exactly the same in every mode.

<table>
<tr>
<td align="center" width="33%"><img src="assets/mode-daily.jpg" alt="Daily — AEGIS Blue owl"><br><b>Daily</b> · AEGIS Blue<br><sub>Work, browsing, everyday life</sub></td>
<td align="center" width="33%"><img src="assets/mode-gaming.jpg" alt="Gaming — monochrome owl"><br><b>Gaming</b> · neon green<br><sub>Performance profile, quiet notifications while you play</sub></td>
<td align="center" width="33%"><img src="assets/mode-cyber.jpg" alt="Cyber — purple owl"><br><b>Cyber</b> · Lab purple<br><sub>Authorized, defensive security learning</sub></td>
</tr>
</table>

### Mode transitions

Each mode has its own transition, from simple to intense: a soft **Daily** fade, a **Gaming** energy burst and a **Cyber** glitch. The effect covers the screen while the desktop changes behind it, then reveals the new mode.

![Daily, Gaming and Cyber transitions](screenshots/13-mode-transitions.jpg)

## 🔑 Highlights

| | |
|---|---|
| 🛡️ **AEGIS Security Center** | Nine areas in one place. Every value is read from the system, never guessed and never sent anywhere. |
| 🌍 **Live Connectivity globe and map** | See where your connections go. Country lookup runs offline; your own location is only looked up if you agree. |
| 🔐 **One-click VPN** | Turn your own configured VPN on or off from Connectivity. |
| 🎮 **Gaming mode** | Performance power profile on mains power, notifications paused while a game runs, file indexing paused, a Gaming check for your hardware, and your normal settings back when you leave. |
| 🧪 **AEGIS Security Lab** | Curated, documented tools from Debian (Wireshark, tcpdump, Nmap, mtr, iperf3, Lynis, The Sleuth Kit, GDB). Each one shows its source, allowed use, required rights and guided first steps. |
| 🕶️ **Privacy Session** | A private Firefox that lives only in memory, Tor Browser through Debian's signed launcher, a temporary folder in RAM and one-click cleanup. |
| 🔔 **Security updates you can't miss** | Security fixes get a clear AEGIS card with *Update now* or *Later*. Checks pause on metered connections. |
| 🧱 **Hardened by default** | Firewall on, AppArmor, kernel hardening, computer name not broadcast, local discovery off, KDE Connect removed, no telemetry. |
| 🧰 **Recovery and drivers** | Documented fixes, a privacy-safe support report and guided NVIDIA driver installation. |
| ♿ **Accessible** | High-contrast colour scheme, reduced motion for the boot screen and mode transitions, contrast-checked colours in every mode, and keyboard-friendly apps. |

## 🖼️ Screenshots

> Real screenshots of AEGIS OS development builds running in a virtual machine, not mock-ups.

### Daily, Gaming and Cyber

| Daily | Gaming | Cyber |
|:---:|:---:|:---:|
| ![Daily mode](screenshots/01-daily-desktop.jpg) | ![Gaming mode](screenshots/10-gaming-desktop.jpg) | ![Cyber mode](screenshots/02-cyber-desktop.jpg) |

Pick a mode from the top bar:

![Mode menu: Daily, Gaming, Cyber](screenshots/14-mode-menu.jpg)

AEGIS apps follow the mode, here Security Center in Gaming mode:

![Security Center in Gaming mode](screenshots/11-gaming-security-center.jpg)

### AEGIS Security Center

![Security Center overview](screenshots/03-security-center-overview.jpg)

| Privacy | Monitoring |
|:---:|:---:|
| ![Privacy view](screenshots/08-security-center-privacy.jpg) | ![Monitoring view](screenshots/09-security-center-monitoring.jpg) |

Security fixes get their own card, with *Update now* or *Later*:

![Security update card](screenshots/15-security-update-card.jpg)

### Connectivity

Connections shown by country on a map or a globe, worked out offline on your computer:

![Connectivity map](screenshots/04-connectivity-map.jpg)

### AEGIS Security Lab

![Security Lab](screenshots/05-security-lab.jpg)

### From power-on to desktop

| Boot screen | Login |
|:---:|:---:|
| ![Boot screen: the owl's eyes light up](screenshots/12-boot-splash.jpg) | ![Login screen](screenshots/06-login.jpg) |

| Boot menu |
|:---:|
| ![Boot menu](screenshots/07-boot-menu.jpg) |

## 🔭 Future vision

> **Where AEGIS is heading:** from today's private preview to a **1.0 release** that anyone can install, keep updated and trust, and then on to a **security workstation with an ethical AI assistant**. Every step ships only after it passes its tests.

```mermaid
flowchart LR
    A["Now<br/>0.1.0-alpha1 preview"] --> B["Next<br/>three modes · new owl<br/>Game Hub · Cyber labs"]
    B --> C["1.0<br/>installer · Windows apps<br/>signed updates"]
    C --> D["Beyond 1.0<br/>dashboard desktop<br/>ethical AI assistant<br/>AEGIS V2"]
```

**Next**

- **Next build:** the white owl, three modes with the mode menu, transitions, safe switching and the Gaming check on the installable image.
- **Gaming:** hardware-aware performance settings and an optional full-screen Game Hub. Game launchers stay your choice and are never installed without asking.
- **Cyber Virtual Labs:** optional practice machines, offline and isolated by default, with beginner templates and advanced management.
- **Updates done properly:** module-aware updates with history, health checks, and rollback if something goes wrong.

**On the way to 1.0**

- **Installer:** a beginner flow with safe defaults and a clear summary, and an advanced flow with manual partitioning and full-disk encryption.
- **AEGIS EXE Bridge:** guided support for Windows apps through Wine. Compatibility will be documented honestly, not promised, and Wine is not a sandbox.
- **Signed AEGIS updates:** stable and testing channels with signed packages.
- **1.0 release:** a clean, reproducible build with checksums, a supported-hardware list and known issues.

**Beyond 1.0**

- **Dashboard desktop:** System Monitor, Network and Connectivity cards on the desktop, with a terminal docked at the bottom that holds multiple tabs.
- **AEGIS AI Assistant:** a guided assistant for *authorized* security work that explains triage, recon and pentest workflows step by step. It refuses targets outside what you are allowed to test, asks before every impactful action and keeps a log. No autonomous attacks, mass scanning, credential theft or stealth features, ever.
- **AEGIS V2:** an amnesic live mode, stronger isolation, advanced monitoring, better privacy and wider hardware support.

<sub>Plans may change. Nothing here is promised until it is built and tested.</sub>

## 🧭 Principles

- **Honest by design.** AEGIS says what it protects against and what it does not. It never promises anonymity or perfect security.
- **Your data stays yours.** No hidden telemetry. Every network request the system makes is meant to be explained, and optional ones ask first.
- **Least privilege.** Apps run as you. Administrator rights are asked for one action at a time, never as a blanket root session.
- **Learn responsibly.** Lab tools are for systems you own or are allowed to test, and the Lab says so.

## 📍 Status

<img src="assets/aegis-owl-head.png" alt="" width="64" align="left">

AEGIS OS is in **private development**. Development builds are tested in virtual machines and from a USB stick on real laptop hardware. There is no public release, download or source code yet.

<br clear="left">

<div align="center">
<br>
<sub>AEGIS OS is built on Debian, KDE Plasma and many other free software projects, which keep their own licences.</sub>
</div>
