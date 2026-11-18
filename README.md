<div align="center">

# Hi, I'm Guest

I write Android system mods: Xposed hooks that replace parts of System UI on rooted Samsung phones.

<a href="https://t.me/coloredmodules"><img src="https://img.shields.io/badge/Telegram-@coloredmodules-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram channel"></a>
<img src="https://img.shields.io/badge/Discord-gtsw1-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord: gtsw1">

</div>

<br>

## ColorCC

<a href="https://github.com/addictedcaf/ColorCC"><img src="https://raw.githubusercontent.com/addictedcaf/ColorCC/main/assets/banner.png" alt="ColorCC" width="100%"></a>

A ColorOS-style control centre for One UI 9, 8.5 and 8, running inside System UI as an LSPosed module. It draws its own panel over a live blur of the screen, with glass cards, a drag-and-resize editor, a full media player and per-item spring physics that follow your finger.

Some of what went into it:

- About 14,000 lines of Java across 12 files, hooking Samsung's System UI at runtime without touching anything on disk.
- No Gradle. The APK is built with `javac`, `d8` and `aapt2` from a single PowerShell script.
- Its own motion system: every card, slider and tile runs a separate spring, and parts are drawn once and then only moved so budget phones keep up.
- A crash guard that hands control back to the stock panel on any failure and switches the module off after three crashes.
- Translated into English, Turkish, Italian, Indonesian and French.

**[See the repo](https://github.com/addictedcaf/ColorCC)** · **[Download the latest release](https://github.com/addictedcaf/ColorCC/releases/latest)**

<br>

## What I work with

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android">
<img src="https://img.shields.io/badge/LSPosed%20%2F%20Xposed-6a45d6?style=flat-square" alt="LSPosed and Xposed">
<img src="https://img.shields.io/badge/Magisk%20%7C%20KernelSU-2b2b33?style=flat-square" alt="Magisk and KernelSU">
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">

I spend most of my time reading decompiled System UI, finding the right methods to hook, and making custom views render smoothly on top of it.

<br>

## Early builds

I post previews of ColorCC updates and of whatever I'm building next on [Telegram](https://t.me/coloredmodules) before they go public.
