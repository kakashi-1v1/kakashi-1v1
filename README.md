<div align="center">

# 🅺🅰🆂🅷🅸

**Android reverse engineer & ROM developer · Founder of [Mods Center](https://github.com/Mods-Center)**

I make system apps on Xiaomi HyperOS, MIUI and other Android ROMs look and work better. I rebuild control centers, launchers and system apps from the inside and ship them as Magisk / KernelSU / APatch modules.

[![Downloads](https://img.shields.io/badge/release_downloads-1.37M%2B-30d158?style=for-the-badge&logo=github)](https://github.com/Mods-Center)
[![Stars](https://img.shields.io/badge/stars-2.3k%2B-ffd60a?style=for-the-badge&logo=github)](https://github.com/Mods-Center)
[![Modules](https://img.shields.io/badge/modules-30-0a84ff?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Mods-Center)
[![Since](https://img.shields.io/badge/modding_since-2022-ff375f?style=for-the-badge)](https://github.com/Mods-Center)

[![Channel](https://img.shields.io/badge/Telegram-channel-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/kashis_cringey_stuffs)
[![Group](https://img.shields.io/badge/Telegram-support_group-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/bootloop_discussion)
[![DM](https://img.shields.io/badge/Telegram-DM-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/kakashi1v1)

</div>

## What I do

- **Port features and UIs between ROMs.** I've built iOS-style and ColorOS-style control centers, OriginOS-style recents and HyperOS 2 features on HyperOS 3, all running inside the stock HyperOS SystemUI.
- **Unlock and extend system apps.** Launcher, Security Center, Theme Manager, App Vault, AOD, Package Installer, Screenshot: high-end and CN-only features enabled on every device, plus new features of my own.
- **Patch the framework.** Signature-verification removal for `framework.jar`, `services.jar` and `miui-services.jar`, patched on the device so it matches the user's ROM.
- **Mod apps that have no dex at all.** The HyperOS 4 launcher is Rust/Flutter, so I mod it with ARM64 binary patches of the compiled Dart and Rust code, plus a native C helper and a companion settings app.
- **Build the pipeline, not just the mod.** Scripted patch sets turn every new ROM update into a rebuilt mod: decompile, apply hooks, inject extra dex, recompile. They support several OS versions (HyperOS 3 and 4) from one script.

## Skills

**Reverse engineering & patching**
<br/>
![Smali](https://img.shields.io/badge/Smali_/_Dex-3DDC84?style=flat-square&logo=android&logoColor=white)
![Apktool](https://img.shields.io/badge/Apktool_/_APKEditor-555?style=flat-square&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64_binary_patching-0091BD?style=flat-square&logo=arm&logoColor=white)
![Dart AOT](https://img.shields.io/badge/Flutter_/_Dart_AOT-02569B?style=flat-square&logo=flutter&logoColor=white)

**Android platform**
<br/>
![SystemUI](https://img.shields.io/badge/SystemUI_&_plugins-3DDC84?style=flat-square&logo=android&logoColor=white)
![Framework](https://img.shields.io/badge/framework.jar_/_services.jar-3DDC84?style=flat-square&logo=android&logoColor=white)
![Resources](https://img.shields.io/badge/Resources_&_overlays-3DDC84?style=flat-square&logo=android&logoColor=white)
![HyperOS](https://img.shields.io/badge/HyperOS_/_MIUI-FF6900?style=flat-square&logo=xiaomi&logoColor=white)
![ColorOS](https://img.shields.io/badge/ColorOS_/_AOSP-1BA784?style=flat-square&logo=oneplus&logoColor=white)

**Languages & tooling**
<br/>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/C_(native_.so)-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Magisk](https://img.shields.io/badge/Magisk_/_KernelSU_/_APatch-00AF9C?style=flat-square&logo=magisk&logoColor=white)
![Termux](https://img.shields.io/badge/Termux-000?style=flat-square&logo=gnometerminal&logoColor=white)

## Featured work

| Project | What it is | Downloads |
|---|---|---|
| **[HyperOS Launcher Mod](https://github.com/Mods-Center/HyperOS-Launcher)** | Widget stacks, super icons for any app, iOS-style app-open animation, icon shapes, auto-resizing dock | 273k+ |
| **[HyperOS Theme Manager](https://github.com/Mods-Center/HyperOS-Theme-Manager)** | Multiple theme servers, premium themes, AI wallpapers, theme import, super icons and widgets | 166k+ |
| **[HyperOS Security Center](https://github.com/Mods-Center/HyperOS-Security-Center)** | Sidebar shortcuts, charge limit, video toolbox and Game Turbo extras, root and account restrictions removed | 111k+ |
| **[New UI Package Installer](https://github.com/Mods-Center/Package-Installer)** | Redesigned installer for any ROM, with `.apks` / `.apkm` support and no Unknown Sources prompt | 84k+ |
| **[Apk Protection Patch](https://github.com/Mods-Center/Apk-Protection-Patch)** | Removes signature verification on AOSP and OEM ROMs by patching the framework on the device | 65k+ |
| **[ColorOS Control Center](https://github.com/Mods-Center/ColorOS_Control_Center)** | ColorOS-style quick settings for HyperOS: free drag-and-drop layout, resizable tiles, custom tiles | 31k+ |
| **[iOS Control Center](https://github.com/Mods-Center/iOS-Control-Center-HyperOS)** | iOS-style control center for HyperOS with jelly animations, glass blur and an iOS volume panel | new |
| **[HyperOS 4 Rust Launcher Mod](https://github.com/Mods-Center/HyperOS-Rust-Launcher-Mod)** | Mods a launcher with no dex at all: ARM64 patches to Dart/Rust code, a native helper and a settings app | new |

**[See all 30 modules →](https://github.com/Mods-Center)**

<div align="center">

<sub>Download counts are GitHub release totals as of November 2026. Older MIUI-era releases account for 370k+ more.</sub>

</div>
