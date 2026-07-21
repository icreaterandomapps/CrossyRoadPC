# Crossy Road Offline Installer

An offline APPX installer for **Crossy Road** on Windows.

This project lets you install Crossy Road without needing the Microsoft Store by installing the required dependencies first and then installing the game package.

---

## Requirements

- Windows 10 or Windows 11
- Administrator permissions

---

## Installation

!!YOU HAVE TO BE SIGNED IN IN YOUR MICROSOFT ACCOUNT BEFORE OR AFTER INSTALL!!

NOTE: Run AOnlyCrossyRoad.bat if You are NOT using ltsc!
1. [Download](https://github.com/icreaterandomapps/CrossyRoadPC/releases/download/CrossyRoad/CrossyroadINstall.zip) this repository.
2. Extract all files into the same folder.
3. Right-click the installer `.bat` file.
4. Select **Run as administrator**.
5. Wait until installation finishes.

---

## Files

### `AFullInstall.bat`
Full installer.

Installs:
1. Microsoft dependencies
2. Crossy Road

Recommended for first-time installation.

---

### `AInstall_Microsoft_Libs.bat`
Installs required APPX dependencies:

- Microsoft .NET Native Framework
- Microsoft .NET Native Runtime
- Microsoft Visual C++ Libraries
- Microsoft UI XAML

---

### `AInstall_CrossyRoad_Only.bat`
Installs only the Crossy Road game.

Use this if the dependencies are already installed.

