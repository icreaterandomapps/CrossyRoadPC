# Crossy Road Offline Installer

An offline APPX installer for **Crossy Road** on Windows.

This project lets you install Crossy Road without needing the Microsoft Store by installing the required dependencies first and then installing the game package.

## Features

✅ Offline installation  
✅ No Microsoft Store required  
✅ Installs required Microsoft libraries automatically  
✅ Simple `.bat` installers  
✅ Works on Windows 10/11  

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

---

## Installation

!!YOU HAVE TO BE SIGNED IN IN YOUR MICROSOFT ACCOUNT BEFORE OR AFTER INSTALL!!
NOTE: Run AOnlyCrossyRoad.bat if You are NOT using ltsc!
1. Download or clone this repository.
2. Extract all files into the same folder.
3. Right-click the installer `.bat` file.
4. Select **Run as administrator**.
5. Wait until installation finishes.

## Requirements

- Windows 10 or Windows 11
- Administrator permissions
- APPX files must remain in the same folder as the scripts

