# ⚡ SNAZY Optimizer

<p align="center">
  <img src="assets/screenshots/bannerv2.jpg" width="900" alt="SNAZY Optimizer">
</p>

<h1 align="center">SNAZY Optimizer</h1>

<p align="center">
  <strong>Android Gaming Performance Optimizer</strong><br>
  Profiles • Root • Shizuku • Non-Root • Background Freeze • Touch Optimization
</p>

<p align="center">
  <b>Current Version: v2.2.22</b> • Android 10+ • Application ID: <code>com.sethikadv.snazy</code>
</p>

<p align="center">
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases">
    <img src="https://img.shields.io/github/v/release/sethikaDV/Snazy-optimizer-?style=for-the-badge" alt="Latest Release">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/releases">
    <img src="https://img.shields.io/github/downloads/sethikaDV/Snazy-optimizer-/total?style=for-the-badge" alt="Downloads">
  </a>
  <a href="https://github.com/sethikaDV/Snazy-optimizer-/stargazers">
    <img src="https://img.shields.io/github/stars/sethikaDV/Snazy-optimizer-?style=for-the-badge" alt="Stars">
  </a>
  <img src="https://img.shields.io/badge/Android-10%2B-111827?style=for-the-badge&logo=android" alt="Android 10+">
  <img src="https://img.shields.io/badge/Flutter-Dart%20%2B%20Kotlin-111827?style=for-the-badge&logo=flutter" alt="Flutter">
</p>

---

## 🚀 About

**SNAZY Optimizer** is an Android gaming performance utility designed to prepare your device for gaming using the system controls and privileges that are actually available on the device.

SNAZY supports three execution paths:

- **Root** — widest access to supported system-level controls.
- **Shizuku** — elevated shell-level access for supported non-root devices.
- **Standard Android** — safe public Android APIs and device information without pretending to have root access.

The app is designed around a simple rule:

> **Optimize the device environment, not the game files.**

SNAZY does not need to modify a game's APK, OBB, save files, or game configuration files to run its optimization workflow.

---

# 🆕 v2.2.22 — Bug Fix Update

**v2.2.22** is a stability and compatibility update focused on fixing issues reported in the v2.x release.

### Fixed

- 🛠️ **App crash issues** — improved stability around affected app flows.
- 🛡️ **Play Protect / installation compatibility issues** — addressed the release-side issues that could cause installation or security-check problems.
- 📱 **Apps not opening correctly** — fixed the affected app-launch workflow.
- 🎮 **Optimize Apps issues** — fixed the optimization/app-selection flow so supported apps can be processed correctly.
- 👆 **Touch Boost Optimization** — fixed the touch optimization flow and related boost handling.
- ♻️ **Boost / Restore stability** — improved the transition between optimization and restore states.
- 🔧 **General v2.x reliability** — cleanup and compatibility improvements across the affected services.

> **Note:** Android security checks, OEM restrictions, kernel support, and privilege availability can still vary between devices. SNAZY cannot bypass Android or Google security policies.

---

# ✨ Main Features

| Feature | Root | Shizuku | Standard |
|---|:---:|:---:|:---:|
| Game selection | ✅ | ✅ | ✅ |
| Game launching | ✅ | ✅ | ✅ |
| Performance profiles | ✅ | ✅ | Normal / limited |
| CPU tuning where supported | ✅ | ✅ | — |
| GPU tuning where supported | ✅ | ✅ | — |
| Background Freeze | ✅ | ✅ | Limited |
| Safe Apps | ✅ | ✅ | ✅ |
| Touch Response Boost | ✅ | ✅ | Limited |
| OpenGL ES / Vulkan preference | ✅ | ✅ | ✅ |
| Device information | ✅ | ✅ | ✅ |
| Restore | ✅ | ✅ | ✅ |

**Availability depends on Android version, OEM, kernel, device hardware and the permissions available to SNAZY.**

---

# ⚡ Performance Profiles

SNAZY provides four profiles designed for different situations.

### ⚡ Performance

Maximum available **stock** performance.

Where the device exposes compatible controls, SNAZY can:

- Use a performance CPU governor.
- Select the highest CPU frequency exposed by the kernel.
- Apply supported GPU governor controls.
- Prepare the device for a gaming session.

**This is not a universal hardware overclock.** SNAZY does not attempt to force frequencies above the limits exposed by the device/kernel.

### 🚀 Better

A more balanced high-performance profile.

It is designed to provide strong performance without simply forcing every available CPU clock to its absolute maximum.

### ⚖️ Normal

Returns to the normal device behavior / captured baseline where supported.

This is the recommended profile when you do not want SNAZY to apply performance tuning.

### 🔋 Ultra Battery Saver

A battery-focused profile intended for longer battery life.

Where supported, it can apply lower-power CPU/GPU settings. Performance can intentionally be lower in this mode.

---

# 👑 Root Mode

If the device already has root access, SNAZY can use its root execution path for supported operations.

Root access can unlock features that ordinary Android applications cannot access, including device/kernel controls exposed by the particular ROM and kernel.

**SNAZY does not root your phone.**

Root availability does not guarantee that every CPU/GPU control exists on every device.

---

# 🔧 Shizuku Mode

SNAZY supports **Shizuku** for supported non-root devices.

Shizuku can provide shell-level access to applications that have been granted permission through the Shizuku service.

### Setup

1. Install Shizuku.
2. Start the Shizuku service.
3. On supported Android versions, enable **Developer options → Wireless debugging**.
4. Pair the device when required.
5. Start Shizuku.
6. Open SNAZY.
7. Open **Set up Shizuku**.
8. Grant SNAZY permission.
9. Return to Profiles / Boost.

SNAZY includes a built-in Shizuku status screen that checks whether the service is installed, running and granted.

Official Shizuku website:

https://shizuku.rikka.app/

---

# ❄️ Background Freeze

Background Freeze is intended to reduce unnecessary background activity while gaming.

SNAZY uses a **temporary force-stop based workflow** for supported applications.

### It does

- Stop selected background apps before/during the gaming workflow.
- Skip apps saved in **Safe Apps**.
- Avoid touching protected/core packages.
- Allow the user to restore the normal state.

### It does NOT

- ❌ Uninstall applications.
- ❌ Permanently disable applications.
- ❌ Delete app data.
- ❌ Modify game files.
- ❌ Modify APK/OBB files.
- ❌ Guarantee extra RAM or FPS.

Android and OEM software may restart certain background services automatically.

---

# 🛡️ Safe Apps

Use **Safe Apps** to exclude important applications from Background Freeze.

For example, you may want to keep a:

- Messenger
- Music player
- VPN
- Authentication app

available during a gaming session.

---

# 👆 Touch Response Boost

SNAZY includes a **Touch Response Boost** option with an adjustable sensitivity value.

On supported devices with the required privilege, SNAZY can attempt vendor/kernel touch-boost controls.

The implementation is intentionally **best-effort** because Android does not provide one universal API for changing touch timing on every phone.

If your device does not expose a compatible touch control, SNAZY cannot safely invent one.

---

# 🎮 Game Optimization

The basic workflow is:

```text
Select Game
     ↓
Select Profile
     ↓
Configure optional features
     ↓
Apply optimization
     ↓
Optional Background Freeze
     ↓
Optional Touch Boost
     ↓
Launch Game
     ↓
Restore when finished
```

SNAZY is designed to work around the game rather than modify the game itself.

---

# 🎨 Graphics Backend

SNAZY exposes:

- **OpenGL ES**
- **Vulkan**

as graphics-related preferences where supported.

Actual graphics API behavior is controlled by Android, the game engine, GPU driver and OEM implementation. Selecting a preference does not guarantee that every game will switch rendering APIs.

---

# 📊 Device Information

The dashboard can display information such as:

- CPU usage
- RAM usage
- Battery level
- Charging state
- Current CPU governor where readable
- Selected game
- Active profile

Values are based on available Android/device information.

---

# 🖼️ Screenshots

## Dashboard

<p align="center">
  <img src="assets/screenshots/dashboard.jpeg" width="340" alt="SNAZY Optimizer Dashboard">
</p>

## Game Selection

<p align="center">
  <img src="assets/screenshots/game-selection.jpeg" width="340" alt="SNAZY Optimizer Game Selection">
</p>

## Boosting

<p align="center">
  <img src="assets/screenshots/boosting.jpeg" width="340" alt="SNAZY Optimizer Boosting">
</p>

---

# 📱 Requirements

| Requirement | Details |
|---|---|
| Android | Android 10 or newer |
| Minimum SDK | 29 |
| Target SDK | 34 |
| Root | Optional |
| Shizuku | Optional |
| Application ID | `com.sethikadv.snazy` |
| Current version | `2.2.22+3` |

---

# 📥 Installation

Download the latest release from GitHub:

https://github.com/sethikaDV/Snazy-optimizer-/releases

### Install

1. Download the latest SNAZY APK.
2. Install it on Android 10+.
3. Open SNAZY Optimizer.
4. Choose your available access mode.
5. Select a performance profile.
6. Select your game.
7. Configure Background Freeze / Touch Boost if required.
8. Press Boost.
9. Restore when finished.

If Android blocks an APK installation, check the installation source and Android's own security settings. Do not disable security features blindly.

---

# 🛡️ Play Protect & Security

SNAZY is an Android utility that interacts with installed packages and, when authorized, uses elevated system interfaces such as root or Shizuku.

Google Play Protect may inspect applications installed outside Google Play.

**SNAZY does not and should not attempt to bypass Play Protect.**

If Play Protect shows a warning, verify that you downloaded the APK from the official project release and review the warning before continuing.

---

# 🧠 What SNAZY Can Actually Control

Android restrictions are different on every device.

| Requested action | Reality |
|---|---|
| Universal CPU overclock | ❌ No generic Android API |
| CPU governor change | ✅ Only where device/kernel exposes it and privilege allows |
| CPU stock max frequency | ✅ Where readable/writable |
| GPU governor | ✅ Only on compatible exposed interfaces |
| Stop background apps | ✅ With supported privilege; limited without it |
| Permanently disable apps | ❌ Not part of SNAZY's temporary freeze workflow |
| Modify game files | ❌ No |
| Guarantee FPS increase | ❌ Impossible to guarantee |
| Guarantee lower temperatures | ❌ Device/workload dependent |
| Touch timing optimization | ✅ Best-effort on supported devices |
| Restore settings | ✅ Where SNAZY has a supported baseline/control |

---

# ⚠️ Important Notes

Performance is affected by:

- SoC and GPU
- Kernel
- ROM
- Android version
- Thermal throttling
- Battery temperature
- OEM restrictions
- Game engine
- Current system workload
- Root/Shizuku availability

A performance profile can increase power consumption and heat.

Ultra Battery Saver intentionally prioritizes battery life over maximum performance.

**No optimizer can guarantee a specific FPS increase on every Android phone.**

---

# 🔐 Privacy & Permissions

SNAZY uses Android capabilities required for its features.

The project includes support for:

- Installed-app/package discovery
- Internet access
- Notifications
- Firebase services used by the project
- Shizuku integration

Installed-app visibility is required so users can choose games and Safe Apps.

SNAZY does not need to modify the selected game's files for its optimization workflow.

---

# 🛠️ Development

SNAZY is built with:

| Component | Technology |
|---|---|
| UI | Flutter |
| Main language | Dart |
| Native Android | Kotlin |
| Platform communication | Flutter MethodChannel |
| Privileged non-root path | Shizuku |
| Local preferences | SharedPreferences |
| Battery information | battery_plus |
| Installed apps | installed_apps |
| Analytics / messaging | Firebase |

### Build

```bash
flutter pub get
flutter analyze
flutter test
flutter build apk --release
```

Release APK output:

```text
build/app/outputs/flutter-apk/app-release.apk
```

---

# 🤖 GitHub Actions

The project can be built through GitHub Actions.

Typical flow:

```text
Push / Manual Run
       ↓
Checkout
       ↓
Java 17
       ↓
Flutter
       ↓
Android setup
       ↓
flutter pub get
       ↓
Release build
       ↓
APK artifact
```

---

# 🗂️ Project Structure

```text
Snazy-optimizer/
│
├── android/
├── assets/
│   ├── icon/
│   └── screenshots/
│
├── lib/
│   ├── models/
│   ├── screens/
│   ├── services/
│   ├── widgets/
│   ├── main.dart
│   └── theme.dart
│
├── .github/
│   └── workflows/
│
├── pubspec.yaml
├── firebase.json
├── firestore.rules
└── README.md
```

---

# ❓ FAQ

### Does SNAZY require root?

No. Root is optional. Supported non-root devices can use Shizuku for elevated operations.

### Can I use it without root or Shizuku?

Yes, but Android limits system-level controls available to ordinary applications.

### Does SNAZY modify game files?

**No.** The optimization workflow is designed to operate at the Android system/process level.

### Is Performance mode an overclock?

No. It uses supported stock limits and exposed device controls. A universal Android overclock is not possible.

### Will it increase FPS?

It can help when the device is limited by controllable CPU/GPU/background workload factors, but there is no universal FPS guarantee.

### Does Background Freeze disable apps?

No. It is intended as temporary force-stop based background control, not permanent app disabling.

### Why does Shizuku need to be restarted sometimes?

Shizuku's non-root service can stop after a reboot depending on the device/setup. Start it again and return to SNAZY.

### Why does a feature say unsupported?

The device/kernel/OEM may not expose the required system interface. SNAZY avoids pretending an unsupported operation succeeded.

---

# 🐛 Reporting Bugs

If you find an issue in v2.2.22, open a GitHub issue:

https://github.com/sethikaDV/Snazy-optimizer-/issues

Please include:

- SNAZY version
- Android version
- Device model
- Root / Shizuku / standard mode
- Steps to reproduce
- Screenshot or relevant log information

Do not include passwords, tokens or other private information.

---

# 📜 Release History

| Version | Type | Summary |
|---|---|---|
| **v2.2.22** | 🛠️ Bug Fix | Crash, Play Protect/installation compatibility, app opening, Optimize Apps and Touch Boost fixes |
| **v2.0.0** | 🚀 Major Update | New UI, profiles, Shizuku support, optimizer improvements and gaming workflow |

---

# 🤝 Contributing

Pull requests and constructive bug reports are welcome.

Before submitting a change:

```bash
flutter pub get
flutter analyze
flutter test
flutter build apk --release
```

Keep changes focused and avoid removing existing functionality without a clear reason.

---

# 👨‍💻 Developer

<p align="center">
  <strong>SNAZY Optimizer</strong><br>
  <sub>Developed by <strong>sethikaDV</strong></sub><br>
  <sub>v2.2.22</sub>
</p>

---

<p align="center">
  <sub>Real controls. Real device limits. No fake FPS promises.</sub>
</p>
