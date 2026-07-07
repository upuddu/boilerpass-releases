<div align="center">

# 🔑 BoilerPass

**Purdue access in one native app — VPN, SSH, files, and a remote desktop.**

Everything is self-contained: the VPN client (`openconnect`) is bundled,
so you install BoilerPass and there's **nothing else to set up**.

[![Download latest](https://img.shields.io/github/v/release/upuddu/boilerpass-releases?include_prereleases&label=Download%20latest&color=CEB888&style=for-the-badge)](https://github.com/upuddu/boilerpass-releases/releases/latest)

</div>

---

## ⬇️ Download

Open the **[latest release →](https://github.com/upuddu/boilerpass-releases/releases/latest)** and grab the one file for your system:

### 🍎 macOS &nbsp;·&nbsp; Intel *or* Apple Silicon (one universal build)
**`BoilerPass_*_universal.dmg`** → open it, drag **BoilerPass** to Applications.

### 🪟 Windows 10 / 11
**`BoilerPass_*_x64-setup.exe`** → run it. *(Also works on Windows-on-ARM via emulation.)*

### 🐧 Linux
| Your distro | Download | Install |
|---|---|---|
| Debian / Ubuntu | **`*_amd64.deb`** · `*_arm64.deb` | `sudo dpkg -i <file>` |
| Fedora / RHEL / SUSE | **`*.x86_64.rpm`** · `*.aarch64.rpm` | `sudo rpm -i <file>` |
| Portable (arm64) | **`*_aarch64.AppImage`** | `chmod +x <file>`, then run |

> [!NOTE]
> First launch is **unsigned**: on macOS right-click the app → **Open**; on Windows click
> **More info → Run anyway**. This one-time step goes away once the app is code-signed.

---

## What's inside

- **VPN** — one click onto the Purdue network (Cisco AnyConnect, fully automated).
- **SSH & files** — a built-in terminal and SFTP browser for the RCAC / ECN clusters.
- **Remote desktop** — a graphical Linux desktop, streamed into the app.
- **Microsoft verification codes** — generated for you, no phone juggling.

<div align="center">
<sub>This repository hosts the public installers only — there's nothing to build here.
The source lives in a separate private repository.</sub>
</div>
