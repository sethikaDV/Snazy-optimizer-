# 🚀SNAZY Optimizer V4.5.6

<p align="center">
  <img src="assets/V4banner.jpg" alt="SNAZY Optimizer Banner" width="100%">
</p>

<p align="center">
  <strong>A Smarter Android Gaming Optimization Experience</strong><br>
  Improve responsiveness, manage background processes, and optimize your gaming experience.
</p>

<p align="center">
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases/latest">
    <img src="https://img.shields.io/github/v/release/sethikaDV/Snazy-optimizer-?style=for-the-badge&color=00C853" alt="Latest Release">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases">
    <img src="https://img.shields.io/github/downloads/sethikaDV/Snazy-optimizer-/total?style=for-the-badge&color=2196F3" alt="Downloads">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/commits">
    <img src="https://img.shields.io/github/last-commit/sethikaDV/Snazy-optimizer-?style=for-the-badge&color=9C27B0" alt="Last Commit">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/issues">
    <img src="https://img.shields.io/github/issues/sethikaDV/Snazy-optimizer-?style=for-the-badge&color=FF9800" alt="Issues">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/sethikaDV/Snazy-optimizer-?style=for-the-badge" alt="License">
  </a>
</p>

<p align="center">
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases/latest">
    <img src="https://img.shields.io/badge/DOWNLOAD-LATEST%20RELEASE-00C853?style=for-the-badge&logo=android&logoColor=white" alt="Download Latest Release">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases">
    <img src="https://img.shields.io/badge/ALL%20VERSIONS-RELEASES-2196F3?style=for-the-badge&logo=github&logoColor=white" alt="All Releases">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/issues/new">
    <img src="https://img.shields.io/badge/REPORT-A%20BUG-FF5252?style=for-the-badge&logo=github" alt="Report a Bug">
  </a>
</p>

---

## Overview

**SNAZY Optimizer** is an Android optimization application designed to improve gaming responsiveness, manage background applications, and provide convenient performance controls.

The project focuses on practical device optimization, accessible controls, and compatibility-aware features for both rooted and supported non-rooted Android devices.

## Latest Update — V4.5.6

This minor update introduces improvements to game detection, memory management, background process control, and system Game Mode handling.

### What's New

#### 🎮 Game Boost
- **Faster Game Detection** — Checks for game launches every 2 seconds during the first minute of boosting.
- **Game Protection (Root)** — Helps protect the active game from being terminated under memory pressure.
- **Storage Priority** — Adjusts the game's storage scheduling priority to help reduce stuttering on slower devices.
- **File Cache Management (Root)** — Clears the file cache once when Boost starts.
- **Performance Game Mode** — Sets Android Game Mode to `performance` on supported Android 12+ devices while boosting.
- **Automatic Restoration** — Restores the previous Game Mode setting when Boost is stopped, where supported.

#### 🧊 Background Freeze & Auto-Start
- Clears cached background processes after freezing apps to help free up memory.
- Repeatedly handles apps that restart themselves, with up to three additional attempts.
- Blocks locked apps from starting at boot on supported ROMs.
- Restores supported boot-start restrictions when apps are restored.

#### ⚙️ Settings
- The Game Panel switch defaults to ON when no previous preference exists.
- Existing users' Game Panel preferences are preserved.
- The relevant overlay features still require the **Display over other apps** permission.

#### 📱 Version
- Updated the displayed application version to **4.5.6**.

## Features

- Game Boost and game launch detection.
- Background application freeze controls.
- Root-dependent optimization features.
- Compatibility-aware Android Game Mode management.
- Background process management.
- App restoration controls.
- Game Panel integration.
- Support for different Android configurations, subject to feature availability.

## Compatibility

| Requirement | Details |
|---|---|
| Platform | Android |
| Root access | Required for selected features |
| Android Game Mode | Android 12+ on supported devices |
| Boot-start restrictions | Supported ROMs only |
| Overlay functionality | Requires applicable permission |

Feature availability and actual results depend on the Android version, device manufacturer, ROM, kernel, and permissions.

## Download

<p align="center">
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases/latest">
    <img src="https://img.shields.io/badge/Download-APK-00C853?style=for-the-badge&logo=android&logoColor=white" alt="Download APK">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases">
    <img src="https://img.shields.io/badge/View-Release%20History-2196F3?style=for-the-badge&logo=github" alt="Release History">
  </a>
</p>

1. Open the latest GitHub Release.
2. Download the APK asset provided with the release.
3. Install it on your Android device.
4. Grant only the permissions needed for the features you intend to use.

**Note:** V4.5.6 must be built and tested before its APK is published. Test game stability, background freezing, and restoration behavior on a low-end device before declaring the release verified.

## Bug Reports & Feedback

Found a bug or have a suggestion?

<p align="center">
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/issues/new">
    <img src="https://img.shields.io/badge/Open-an%20Issue-FF5252?style=for-the-badge&logo=github" alt="Open an Issue">
  </a>
</p>

When reporting an issue, include your Android version, device model, root status, steps to reproduce the problem, and relevant logs where possible. Do not include passwords, private keys, or sensitive personal information.

## Disclaimer

SNAZY Optimizer cannot guarantee a specific FPS increase or eliminate all stuttering. Results vary between devices and games. Root-level operations can affect system behavior, so use them carefully and verify that restoration works correctly.

## Developer

<p align="center">
  <a href="https://github.com/sethikaDV">
    <img src="https://img.shields.io/badge/Developer-sethikaDV-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Developer">
  </a>
</p>

<p align="center">
  <sub>Developed by sethikaDV</sub><br>
  <strong>Optimize Smarter. Play Smoother.</strong>
</p>
