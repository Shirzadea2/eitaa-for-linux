# Eitaa Arch Linux Package

This repository contains a simple Arch Linux PKGBUILD for the [Eitaa Messenger](https://eitaa.com) desktop application.  
It wraps the official binary release into a proper Arch package, including a `.desktop` entry and icon, so Eitaa is available globally from both the terminal and your desktop environment.

---

## 📦 Features
- Installs the Eitaa binary into `/usr/bin/eitaa`
- Adds a `.desktop` entry for integration with KDE Plasma, GNOME, etc.
- Installs an application icon for menu/launcher visibility
- Managed by `pacman` like any other package

---

## 🔧 Build & Install

Clone this repository and build the package:

```bash
git clone https://github.com/Shirzadea2/eitaa-for-linux.git
cd eitaa-bin
makepkg -si
