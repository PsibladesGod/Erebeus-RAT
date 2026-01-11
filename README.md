# Erebeus RAT v1.0

![Banner](Assets/banner.png)

<p align="center">
  <img src="https://img.shields.io/badge/Stub-Native_C++-blue.svg">
  <img src="https://img.shields.io/badge/Server-.NET_8-purple.svg">
  <img src="https://img.shields.io/badge/Platform-Windows-gray.svg">
  <img src="https://img.shields.io/badge/Encryption-AES_256-green.svg">
</p>

**Erebeus** is a professional, native remote administration tool designed for stability and stealth. The client (stub) is coded in pure **C++**, ensuring maximum performance, minimal size, and zero dependencies on the target machine.

**[ ⚠️ Source code is private. This repo is for demonstration & verification. ]**

## 🔥 Key Features

### 📡 Monitoring & Spy
- **HVNC (Hidden VNC):** Control hidden desktop / browser session without user knowing.
- **Hidden RDP:** Create hidden user & enable RDP instantly.
- **Webcam Monitor:** Live Streaming & Capture snapshots.
- **Microphone:** Live audio recording.
- **Keylogger:** Online/Offline, Unicode support.
- **Screen View:** Real-time desktop control (Keyboard/Mouse) with high FPS.
- **Process Monitor:** View, Kill, Suspend, Resume processes.

### 🛠 System Operations
- **File Manager:** Upload, Download, Run, Delete, ZIP/UnZIP, Edit files.
- **Registry Editor:** Full tree navigation, Create/Edit/Delete values.
- **Shell:** Remote CMD & PowerShell execution.
- **Service Manager:** Manage, start, stop Windows services.
- **TCP Connections:** View active ports & connections.
- **Clipboard Manager:** Read/Write clipboard content.

### 🔓 Evasion & Security
- **UAC Bypass:** Multiple methods included (Fodhelper, ComputerDefaults).
- **Defender Control:** Disable Windows Defender / Add Exclusions.
- **Anti-Analysis:** Detect VM, Sandbox, Wireshark, ProcessHacker, HTTP Debuggers.
- **Startup Manager:** Persistence via Task Scheduler, Registry Run, Startup Folder.
- **BSoD:** Trigger Blue Screen of Death on demand.
- **Self Destruct:** Clean removal from disk & memory traces.

### 💸 Recovery & Stealer
- **Browser Stealer:** Chrome, Edge, Firefox, Opera, Brave, Vivaldi (Passwords/Cookies).
- **Discord:** Token grabber (WEB & App) with HQ badge check.
- **Telegram:** Session grabber (tdata).
- **Steam:** Session grabber.
- **Wallets:** Metamask, Exodus, TrustWallet, Binance, Phantom.
- **File Grabber:** Steal files by extension (.txt, .doc, .pdf, .db).

### 🌐 Network & Proxy
- **SOCKS5 Proxy:** Reverse proxy support for tunneling.
- **Reverse Shell:** Netcat style reverse shell.
- **URL Visit:** Open website (Visible/Hidden).
- **DDOS / Stresser:** TCP, UDP, HTTP Flood capabilities.

### 💎 Fun & Misc
- **Clipper:** Auto-replace crypto addresses (BTC, ETH, LTC, XMR, USDT, TRX).
- **Chat:** Open chat window with user.
- **MessageBox:** Send fake error/info messages.
- **Text to Speech:** Speak text on target PC.
- **Piano:** Play sounds on target machine.

## 🧩 Advanced Architecture

Erebeus is built on a modular core. You don't need to rebuild the stub to add features.
- **Direct Syscalls:** Uses raw system calls (Hell's Gate implementation) to bypass user-mode EDR hooks in `ntdll.dll`.
- **Memory Loader:** Plugins are loaded directly from memory. No disk artifacts.
- **Hot-Swap:** Upload and execute new plugins (.dll) on infected machines instantly.
- **Custom Plugins:** SDK available to write your own C++ or C# modules.

## 🌐 The Ecosystem

We provide a complete suite of tools for management:

1.  **Erebeus Studio:**
    - Advanced IDE & Builder.
    - Drag & Drop interface for configuring your stub.
    - Plugin creator & debugger.
    - Assembly Cloner, Icon Changer, Obfuscator included.

2.  **Mobile App (iOS / Android):**
    - Control your botnet on the go.
    - Push notifications for new connections.
    - Quick commands (Lock, Panic, Kill).

3.  **Web Panel:**
    - Tor-routed web interface for browser access.
    - No port forwarding required.

## 📸 Media & Previews

To avoid GitHub restrictions and provide high-quality demonstrations, all screenshots, video proofs, and UI walkthroughs are hosted on our Telegram channel.

**Inside the channel you will find:**
- Full Server Dashboard walkthrough.
- **Erebeus Studio** builder demonstration.
- **Mobile App** live usage videos.

<div align="center">

[![Join Telegram](https://img.shields.io/badge/Join_Telegram_Channel-View_Screenshots-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)]([https://t.me/erebus])

</div>

## 🛒 Purchase

**Price:**
- **Monthly:** $15
- **Lifetime:** $100
- **Source Code:** Discussed privately.

**Contact:**
- **Telegram:** [@erebusprojects][(https://t.me/erebusprojects)]

---
*Disclaimer: This tool is for educational purposes and authorized security testing only. I am not responsible for any damage caused by this software.*
