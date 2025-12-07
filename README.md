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

## 🔧 Build & Install (Recommended)

Clone this repository and build the package:

```bash
git clone https://github.com/Shirzadea2/eitaa-for-linux.git
cd eitaa-for-linux
makepkg -si
```

---

## 🔽 Use the release package

Install the built package
Download the .tar.zst file and install directly:
```bash
sudo pacman -U eitaa-bin-0-1-x86_64.pkg.tar.zst
```
