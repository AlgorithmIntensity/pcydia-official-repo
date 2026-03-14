# 📦 PCydia Repository

![PCydia](https://algorithmintensity.github.io/pcydia-official-repo/icon.png)

Official package repository for **PCydia** - a package manager for Windows in the style of Cydia.

## 📋 About

This repository contains useful Windows applications packaged in `.pcydia` format for installation via PCydia. All packages are distributed for free.

### 📊 Statistics

| Metric | Value |
|---------|----------|
| 📦 Packages | 4 |
| 🔄 Last updated | March 2026 |
| 👤 Maintainer | @maxutko99 |
| 📥 Total downloads | — |

## 🔧 How to Add This Repository to PCydia

1. Open PCydia
2. Go to the **"Sources"** tab
3. Click **"Add"**
4. Enter the URL:
https://maxutko99.github.io/pcydia-repo/

5. Click **"Refresh"**

## 📥 Installing Packages

After adding the repository:

1. Go to the **"Packages"** tab
2. Find the program you want (use search or categories)
3. Select the package and click **"Install"**
4. PCydia will automatically download and install the program

Packages are installed to:
%LOCALAPPDATA%\PCydia\apps\

## 🛠️ Package Format (.pcydia)

`.pcydia` is a regular ZIP archive renamed to `.pcydia`. It can contain:

- Program executable files
- Libraries and resources
- `install.pconf` — configuration file for auto-installation

### Example `install.pconf`:
```ini
[Package]
Name=7-Zip
Version=24.09
Executable=7zFM.exe
InstallType=portable
CreateShortcut=true
ShortcutName=7-Zip File Manager
