![Azahar Emulator](https://azahar-emu.org/resources/images/logo/azahar-name-and-logo.svg)

![Current Release](https://img.shields.io/github/v/release/azahar-emu/azahar?label=Current%20Release)
![Current Prerelease](https://img.shields.io/github/v/release/azahar-emu/azahar?include_prereleases\&label=Current%20Prerelease)

![GitHub Downloads](https://img.shields.io/github/downloads/azahar-emu/azahar/total?logo=github\&label=GitHub%20Downloads)
![Google Play Downloads](https://playbadges.pavi2410.com/badge/downloads?id=io.github.lime3ds.android\&pretty\&label=Play%20Store%20Downloads)
![Flathub Downloads](https://img.shields.io/flathub/downloads/org.azahar_emu.Azahar?logo=flathub\&label=Flathub%20Downloads)
![CI Build Status](https://github.com/azahar-emu/azahar/actions/workflows/build.yml/badge.svg)

**Azahar** is an open-source 3DS emulator project based on Citra.

It was created from the merger of PabloMK7's Citra fork and the Lime3DS project, both of which emerged shortly after Citra was taken down.

The goal of this project is to be the de facto platform for future development.

---

# Installation

## Windows

Azahar is available as both an installer and a ZIP archive.

Download the latest release in your preferred format from the [Releases](https://github.com/azahar-emu/azahar/releases) page.

If you are unsure whether to use MSVC or MSYS2, use MSYS2.

---

## macOS

To download a build that will work on all Macs, download the `macos-universal` build from the [Releases](https://github.com/azahar-emu/azahar/releases) page.

Alternatively, if you want a build specifically for your Mac:

* `macos-arm64` for Apple Silicon Macs
* `macos-x86_64` for Intel Macs

---

## Android

There are two variants of Azahar available on Android: the Vanilla and Google Play builds.

The Vanilla build is technically superior, as it uses a faster alternative file management method, but it is not permitted on the Google Play Store.

For most users, we currently recommend downloading Azahar via the Google Play Store for ease of access:

<a href='https://play.google.com/store/apps/details?id=io.github.lime3ds.android'>
  <img width='180' alt='Get it on Google Play' src='https://raw.githubusercontent.com/pioug/google-play-badges/06ccd9252af1501613da2ca28eaffe31307a4e6d/svg/English.svg'/>
</a>

Alternatively, you can install the app using Obtainium:

1. Download and install Obtainium from [here](https://github.com/ImranR98/Obtainium/releases) (`app-release.apk`)
2. Open Obtainium and click **Add App**
3. Enter `https://github.com/azahar-emu/azahar` in the **App Source URL** field
4. Click **Add**
5. Click **Install** and choose your preferred variant

You can also install the latest APK from the [Releases](https://github.com/azahar-emu/azahar/releases) page.

> **Note:** You will not receive automatic updates when installing via APK.

---

## Linux

The recommended format for using Azahar on Linux is the Flatpak available on Flathub:

<a href='https://flathub.org/apps/org.azahar_emu.Azahar'>
  <img width='180' alt='Download on Flathub' src='https://dl.flathub.org/assets/badges/flathub-badge-en.png'/>
</a>

Azahar is also available as an AppImage on the [Releases](https://github.com/azahar-emu/azahar/releases) page.

Two AppImage variants are available:

* `azahar.AppImage`
* `azahar-wayland.AppImage`

If you are unsure which one to use, we recommend the default `azahar.AppImage` due to potential issues with Wayland.

Unless you explicitly require native Wayland support (e.g. no XWayland), the non-Wayland version is recommended.

The Flatpak build also has native Wayland support disabled by default. You can enable it using [Flatseal](https://flathub.org/en/apps/com.github.tchx84.Flatseal).

---

# Build Instructions

Please refer to the repository's [wiki](https://github.com/azahar-emu/azahar/wiki/Building-From-Source).

---

# How Can I Contribute?

## Pull Requests

If you want to implement a change and have the technical capability, contributions are welcome.

For new features, it is strongly recommended to first open a Feature Request issue to discuss the idea before writing code.

After creating a pull request, please do not repeatedly merge `master` into your branch. A maintainer will update it if necessary.

---

## Language Translations

Translations are handled via [Transifex](https://app.transifex.com/azahar/azahar).

If you know a non-English language listed there, feel free to contribute.

> **Note:** New languages are not currently being accepted.

---

## Compatibility Reports

You can help by reporting game compatibility:

https://github.com/azahar-emu/compatibility-list/blob/master/CONTRIBUTING.md

This helps reflect the emulator’s real-world performance more accurately.

---

# Minimum Requirements

## Desktop

```
Operating System: Windows 10 (64-bit), macOS 13.4 (Ventura), or modern 64-bit Linux  
CPU: x86-64/ARM64 CPU (Windows on ARM not supported)  
     Single-core performance higher than 1,800 on PassMark  
     SSE4.2 required on x86_64  
GPU: OpenGL 4.3 or Vulkan 1.1 support  
Memory: 2 GB RAM (4 GB recommended)  
```

## Android

```
Operating System: Android 10.0+ (64-bit)  
CPU: Snapdragon 835 SoC or better  
GPU: OpenGL ES 3.2 or Vulkan 1.1 support  
Memory: 2 GB RAM (4 GB recommended)  
```

---

# What's Next?

We publish roadmaps as GitHub milestones:

https://github.com/azahar-emu/azahar/milestones

---

# Join the Conversation

Join our Discord community to stay updated and contribute:

https://discord.gg/4ZjMpAp3M6
