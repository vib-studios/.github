<div align="center">

# Vib Studios

**A Minecraft server written from scratch, and a launcher to play it with.**

[![Website](https://img.shields.io/badge/vibstudios.space-0E0503?style=for-the-badge&logo=github&logoColor=FB794A)](https://vibstudios.space)
[![Licence](https://img.shields.io/badge/GPL--3.0--or--later-FB794A?style=for-the-badge&logoColor=white)](https://www.gnu.org/licenses/gpl-3.0)
[![Vibecoded](https://img.shields.io/badge/vibecoded-ff69b4?style=for-the-badge)](https://github.com/vib-studios/vib-MC)

</div>

---

We build two halves of the same thing: a Minecraft Java Edition server implemented from nothing, and
a desktop launcher that installs, manages and plays against it. Both are GPL-3.0-or-later, both are
built in the open, and both are honest about what they do not do yet.

## Projects

### vib-MC

[![Release](https://img.shields.io/github/v/release/vib-studios/vib-MC?style=flat-square&color=FB794A&label=release)](https://github.com/vib-studios/vib-MC/releases)
[![Language](https://img.shields.io/github/languages/top/vib-studios/vib-MC?style=flat-square&color=E65719)](https://github.com/vib-studios/vib-MC)
[![Licence](https://img.shields.io/github/license/vib-studios/vib-MC?style=flat-square&color=555)](https://github.com/vib-studios/vib-MC/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/vib-studios/vib-MC?style=flat-square&color=555)](https://github.com/vib-studios/vib-MC/commits)
[![Stars](https://img.shields.io/github/stars/vib-studios/vib-MC?style=flat-square&color=555)](https://github.com/vib-studios/vib-MC)

A Minecraft Java Edition server built from scratch by AI, one prompt at a time - no vanilla code, no
Bukkit fork. It serves the vanilla **Minecraft 1.12.2 protocol (340)**, and 1.12.2 clients join the
same server to walk persistent procedurally generated worlds. As of v0.0.7
the survival loop is real: blocks drop, tools wear, furnaces smelt, and you can starve, drown, burn
and fall.

Not a Paper or Vanilla replacement, and it says so.

[![vib-MC](https://gh-card.dev/repos/vib-studios/vib-MC.svg)](https://github.com/vib-studios/vib-MC)

### Vib-launcher

[![Release](https://img.shields.io/github/v/release/vib-studios/viblauncher?style=flat-square&color=FB794A&label=release)](https://github.com/vib-studios/viblauncher/releases)
[![Language](https://img.shields.io/github/languages/top/vib-studios/viblauncher?style=flat-square&color=E65719)](https://github.com/vib-studios/viblauncher)
[![Licence](https://img.shields.io/github/license/vib-studios/viblauncher?style=flat-square&color=555)](https://github.com/vib-studios/viblauncher/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/vib-studios/viblauncher?style=flat-square&color=555)](https://github.com/vib-studios/viblauncher/commits)
[![Arch](https://img.shields.io/badge/Arch-PKGBUILD-1793D1?style=flat-square&logo=archlinux&logoColor=white)](https://github.com/vib-studios/viblauncher/tree/main/packaging/arch)

A native Minecraft launcher and vib-MC server control panel for Linux. Isolated instances, Microsoft
and offline accounts, Fabric and Quilt, mods from Modrinth, and local vib-MC servers, in one Avalonia
desktop application. No browser, no WebView, no Electron, no embedded web page anywhere in it.

**Linux is the supported platform** - it is what the launcher is developed and tested on. The same
codebase builds for Windows, but nobody here runs Windows any more, so it is untested and may lag.

[![Vib-launcher](https://gh-card.dev/repos/vib-studios/viblauncher.svg)](https://github.com/vib-studios/viblauncher)

### avalonia-linux-port

[![Language](https://img.shields.io/github/languages/top/vib-studios/avalonia-linux-port?style=flat-square&color=E65719)](https://github.com/vib-studios/avalonia-linux-port)
[![Licence](https://img.shields.io/github/license/vib-studios/avalonia-linux-port?style=flat-square&color=555)](https://github.com/vib-studios/avalonia-linux-port/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/vib-studios/avalonia-linux-port?style=flat-square&color=555)](https://github.com/vib-studios/avalonia-linux-port/commits)

The WPF-to-Avalonia port that took Vib-launcher off Windows-only WPF and onto Linux, kept as its own
readable artifact: the Classic theme as Avalonia resource dictionaries, the views and the view
models. The README writes down what does not carry over from WPF, including two traps that compile
cleanly, raise no binding warnings and simply draw nothing.

Useful if you are doing the same migration. It does not build standalone.

[![avalonia-linux-port](https://gh-card.dev/repos/vib-studios/avalonia-linux-port.svg)](https://github.com/vib-studios/avalonia-linux-port)

## Built with

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Netty](https://img.shields.io/badge/Netty-4A4A4A?style=for-the-badge)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%2010-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Avalonia](https://img.shields.io/badge/Avalonia%2011-8B44AC?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-0E0503?style=for-the-badge&logo=linux&logoColor=FB794A)
![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)

## At a glance

| Project | What it is | Language | Status |
|---|---|---|---|
| [vib-MC](https://github.com/vib-studios/vib-MC) | Minecraft Java Edition server, from scratch | Java | Playable survival, experimental |
| [viblauncher](https://github.com/vib-studios/viblauncher) | Launcher and server control panel | C# / Avalonia | Released, Linux-first |
| [avalonia-linux-port](https://github.com/vib-studios/avalonia-linux-port) | The launcher's Avalonia UI layer | C# / Avalonia | Reference, not standalone |
| [vib-studios.github.io](https://github.com/vib-studios/vib-studios.github.io) | The project page, live at vibstudios.space | HTML | Live |

<div align="center">

**[vibstudios.space](https://vibstudios.space)**

</div>
