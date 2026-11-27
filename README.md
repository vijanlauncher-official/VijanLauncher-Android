<div align="center">

# Vijan Launcher (Android)

**Play Minecraft: Java Edition natively on Android with custom touch controls and mod support.**

[![Platform](https://shields.io)](../../releases)
[![License: LGPL v3](https://shields.io)](LICENSE)
[![Release](https://shields.io)](../../releases)

[Download APK](../../releases) • [Desktop Edition](https://github.com/vijanlauncher-official/vijanlauncher) • [Report an Issue](../../issues)

</div>

---

> **Disclaimer:** **Vijan Launcher (Android)** is an independent, community-maintained fork of [MojoLauncher](https://github.com). It is **not** affiliated with, endorsed by, or supported by MojoLauncher, PojavLauncher, Mojang Studios, or Microsoft.

---

## ✨ Features

* **Full Java Edition on Mobile:** Run standard Minecraft: Java Edition versions directly on your Android device.
* **Customizable Touch Controls:** Create, resize, and remap on-screen buttons—or connect a physical keyboard and mouse.
* **Modloader Support:** Supports Fabric, Forge, Quilt, and OptiFine for modded gameplay on the go.
* **Hardware-Accelerated Rendering:** Includes OpenGL ES / ANGLE / Zink renderer options tuned for mobile GPUs.
* **Microsoft Account Login:** Official Microsoft authentication support for Minecraft: Java Edition.

---

## 📥 Installation

1. Go to the **[Releases Page](../../releases)** on your Android device and download the latest **`VijanLauncher.apk`**.
2. Open the downloaded `.apk` file and allow **Install from unknown sources** when prompted by Android.
3. Launch **Vijan Launcher**, sign in with your Microsoft account, pick your Minecraft version, and tap **Play**.

---

## 🛠️ Building from Source

Requires **JDK 17** and the Android SDK:

```bash
git clone --recursive https://github.com-Android.git
cd VijanLauncher-Android
./gradlew :app_mojo:assembleDebug
```

---

## 📜 License & Credits

* Licensed under the **GNU Lesser General Public License v3.0 (LGPL-3.0)** — see the [LICENSE](LICENSE) file for details.
* Built upon the open-source work of the [MojoLauncher](https://github.com) and PojavLauncher contributors.
* *Minecraft* is a trademark of Mojang Synergies AB.
