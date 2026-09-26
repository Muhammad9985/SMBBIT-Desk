# 🚀 SMBBIT-Desk

<div align="center">

```
   _____ __  __ ____  ____ _____ _______     _____            _    
  / ____|  \/  |  _ \|  _ \_   _|__   __|   |  __ \          | |   
 | (___ | \  / | |_) | |_) || |    | |______| |  | | ___  ___| | __
  \___ \| |\/| |  _ <|  _ < | |    | |______| |  | |/ _ \/ __| |/ /
  ____) | |  | | |_) | |_) || |_   | |      | |__| |  __/\__ \   < 
 |_____/|_|  |_|____/|____/_____|  |_|      |_____/ \___||___/_|\_\
```

### **The Lightning-Fast, 100% Free & Unlimited Remote Desktop Solution**
*Direct Peer-to-Peer • Zero Ads • Unlimited Session Time • No Subscriptions • No "Commercial Use" Locks*

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-0078D7?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Muhammad9985/SMBBIT-Desk/releases)
[![Free Forever](https://img.shields.io/badge/Price-100%25%20Free%20Forever-2ea44f?style=for-the-badge)](https://github.com/Muhammad9985/SMBBIT-Desk)
[![Zero Ads](https://img.shields.io/badge/Ads-Zero%20%2F%20None-success?style=for-the-badge)](https://github.com/Muhammad9985/SMBBIT-Desk)
[![Unlimited Sessions](https://img.shields.io/badge/Session%20Duration-Unlimited%20%E2%88%9E-orange?style=for-the-badge)](https://github.com/Muhammad9985/SMBBIT-Desk)
[![WebRTC Engine](https://img.shields.io/badge/Engine-Direct%20WebRTC%20P2P-red?style=for-the-badge&logo=webrtc&logoColor=white)](https://webrtc.org/)

---

### *Why pay $20 to $50/month for AnyDesk or TeamViewer just to get kicked out after 5 minutes?*

**SMBBIT-Desk** gives you enterprise-grade remote desktop control completely free of cost. No timers, no nag screens, no subscription paywalls, and no annoying video ads.

[📥 **Download Latest Windows Release (.zip)**](https://github.com/Muhammad9985/SMBBIT-Desk/releases) • [✨ Feature Highlights](#-feature-highlights) • [📊 Comparison](#-why-choose-smbbit-desk) • [⚡ Quick Start Guide](#-quick-start-guide) • [❓ FAQ](#-frequently-asked-questions)

---

</div>

## 📊 Why Choose SMBBIT-Desk?

If you've ever had a remote session abruptly terminated by AnyDesk with a *"Commercial Use Suspected"* lockout, or had to wait through 30 seconds of countdown advertisements just to fix a family member's computer, you know the frustration.

Here is how **SMBBIT-Desk** compares:

| Feature / Capability | AnyDesk Free | TeamViewer Free | **SMBBIT-Desk** |
| :--- | :---: | :---: | :---: |
| **Pricing & Licensing** | Monthly Subscriptions ($14.90+) | Expensive Tiers ($24.90+) | **100% Free For Everyone** |
| **Advertisements & Sponsors** | ❌ Persistent Ads & Banners | ❌ Sponsored Popups | **✅ Completely Ad-Free** |
| **Session Time Limits** | ❌ Timed / 5-min kickouts | ❌ Sudden session cutoffs | **♾️ Unlimited (Run for days)** |
| **"Commercial Use" Lockouts** | ❌ Automatic device blocking | ❌ Frequent false positives | **✅ Never Locks Or Bans You** |
| **Unattended Access** | Requires account/license | Complicated setup | **✅ One-Click Custom Password** |
| **Streaming Architecture** | Often routed through servers | Central relay servers | **✅ True Peer-to-Peer (WebRTC)** |
| **RAM / Resource Usage** | ~250MB+ | ~350MB+ | **⚡ ~60MB - 90MB (Lightweight)** |
| **Installation Requirement** | Requires installation | Heavy registry modifications | **✅ 100% Portable (Unzip & Run)** |
| **Background Resilience** | ❌ Often drops on minimize | Variable | **✅ Asynchronous Non-Blocking Engine** |

---

## ✨ Feature Highlights

### ⚡ 1. Ultra-Low Latency 60 FPS WebRTC Streaming
Powered by native hardware-accelerated **WebRTC**, SMBBIT-Desk establishes direct peer-to-peer data and media pipelines between the host and client. Video frames stream at native display refresh rates with sub-50ms latency over standard internet connections.

### 🖱️ 2. Accurate 1:1 Pixel Mapping & True DPI Scaling
No more offset cursors or mouse misalignment when connecting between monitors with different resolutions (e.g., 4K laptop to 1080p desktop). 
- Hardware cursor tracking maps coordinates with sub-pixel precision.
- Full multi-monitor and aspect-ratio adaptation.
- Full support for right-click, middle-click, precision scrolling, and click-and-drag.

### ⌨️ 3. Native Unicode Keyboard & Complete Shortcut Injection
- Type naturally in **any language** (English, Arabic, Urdu, Spanish, Chinese, Japanese, etc.) without character corruption or numpad mapping bugs.
- Full support for system shortcuts: `Ctrl+C`, `Ctrl+V`, `Alt+Tab`, `Win+D`, `Ctrl+Shift+Esc`, Function Keys (`F1`-`F12`), and navigation blocks.

### 🛡️ 4. One-Click Unattended Access
Access your remote workstation, office machine, or home computer 24/7 without needing anyone physically present at the remote screen:
- Set your own custom permanent password.
- Connect seamlessly from anywhere in the world.
- Passwords are verified with secure cryptographic hashing.

### 🪟 5. Freeze-Proof Asynchronous Window Architecture
Most remote desktop software freezes or loses sync when you minimize or maximize the application window on the remote PC. SMBBIT-Desk features a dedicated asynchronous Win32 message-passing pipeline:
- Minimize, Maximize, or Restore the remote app window with zero lag.
- The remote stream **never freezes, locks up, or drops connection**.

### 📁 6. Seamless Bidirectional File Transfer
- Transfer documents, software installers, images, and folders between local and remote machines.
- High-speed streaming directly over encrypted peer-to-peer channels without intermediary cloud size caps.

### 💬 7. Built-in Session Chat
- Communicate in real time with the remote user right inside the connection window.
- Perfect for remote tech support, client assistance, and team collaboration.

### 📦 8. Truly Standalone & Portable
- **Zero Installation Required**: Runs directly from any USB flash drive or folder.
- **Pre-bundled Runtime**: Ships with all required Visual C++ 2015–2022 64-bit runtime libraries included out-of-the-box. Runs cleanly even on freshly formatted Windows installations without missing DLL errors.

---

## 🏗️ Architecture & How It Works

```
┌────────────────────────┐                   ┌────────────────────────┐
│      Controlling       │                   │       Remote PC        │
│       Client PC        │                   │         (Host)         │
└───────────┬────────────┘                   └───────────┬────────────┘
            │                                            │
            │           1. Lightweight Signaling         │
            ├─────────────── (Firebase RTDB) ────────────┤
            │       [Exchange SDP & ICE Candidates]      │
            │                                            │
            │           2. Direct P2P WebRTC Link        │
            │◄══════════════════════════════════════════►│
            │                                            │
            │  <<< 60 FPS Desktop Video Stream (H.264)   │
            │  ════════════════════════════════════════  │
            │                                            │
            │  >>> Hardware Mouse & Keyboard Input (SCTP)│
            │  ════════════════════════════════════════  │
            │                                            │
            │  <<<>>> Encrypted File Transfer & Chat     │
            │  ════════════════════════════════════════  │
```

1. **Signaling**: Devices discover each other using a compact, fast 9-digit address via a secure signaling channel.
2. **Direct P2P Link**: Once discovered, a direct WebRTC peer connection is established. Video and input never bounce through third-party servers.
3. **Hardware-Level Injection**: Incoming input packets are translated via Windows `SendInput` APIs at the OS kernel driver level for instantaneous response.

---

## ⚡ Quick Start Guide

### Step 1: Download & Extract
1. Go to the [**Releases Page**](https://github.com/Muhammad9985/SMBBIT-Desk/releases).
2. Download **`Release_Windows.zip`**.
3. Right-click and extract the archive to your preferred location (e.g. `C:\SMBBIT-Desk\` or a USB drive).

### Step 2: Run the App
- Double-click **`smbbit_desk.exe`** (or execute `RUN_WINDOWS_APP.bat`).
- The application will launch instantly with your unique **9-Digit Address**.

```
SMBBIT-Desk/
├── smbbit_desk.exe        <-- Double-click to launch!
├── RUN_WINDOWS_APP.bat    <-- One-click batch launcher
├── flutter_windows.dll
├── libwebrtc.dll
├── data/
└── [All required MSVC runtime DLLs included]
```

### Step 3: Connect!

#### Option A: Quick Interactive Session (Tech Support)
1. Ask the remote person for their **9-Digit Address** (displayed on their SMBBIT-Desk screen).
2. Enter their address into the top bar and click **Connect**.
3. A prompt will appear on the remote screen: they click **Accept**, and you are in control!

#### Option B: Unattended Access (Your Own Computers)
1. On your remote PC, go to **Settings** in SMBBIT-Desk.
2. Toggle **Enable Unattended Access** and set your password.
3. From any other PC, type the 9-digit address and enter your password to connect instantly anytime, anywhere.

---

## ⌨️ In-Session Quick Actions & Shortcuts

SMBBIT-Desk provides quick one-click shortcuts located in the session toolbar:

| Action Button | Function |
| :--- | :--- |
| 🛡️ **Task Manager** | Simulates `Ctrl+Shift+Esc` to open Windows Task Manager |
| 🪟 **Start Menu** | Sends native `Windows Key` press to open remote Start menu |
| 🖥️ **Show Desktop** | Sends `Win + D` to instantly reveal the remote desktop |
| 🔒 **Lock Workstation** | Sends `Win + L` to lock the remote computer securely |
| 📁 **File Manager** | Opens the file transfer dialog to send/receive files |
| 💬 **Chat Panel** | Toggles the real-time session messaging drawer |
| ⛶ **Fullscreen** | Toggles seamless fullscreen mode |

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>1. Is SMBBIT-Desk truly 100% free? Are there any hidden fees or subscriptions?</b></summary>
Yes! SMBBIT-Desk is completely free for both personal and professional use. There are no subscriptions, no credit card requirements, no trial periods, and no ads.
</details>

<details>
<summary><b>2. Will I ever be locked out for "Commercial Use"?</b></summary>
No. Unlike AnyDesk and TeamViewer which monitor usage patterns and enforce aggressive algorithmic lockouts, SMBBIT-Desk does not track your use or restrict your sessions.
</details>

<details>
<summary><b>3. Do I need Administrator permissions to run SMBBIT-Desk?</b></summary>
No! SMBBIT-Desk is fully portable. You can extract it to your desktop, documents folder, or run it straight from a portable USB drive without standard administrator installation.
</details>

<details>
<summary><b>4. Does the remote session work across different Wi-Fi networks or over the Internet?</b></summary>
Yes. SMBBIT-Desk uses standard WebRTC STUN/ICE protocols, allowing connections across home routers, cellular hotspots, office firewalls, and NAT configurations.
</details>

<details>
<summary><b>5. Why does SMBBIT-Desk not freeze when minimized?</b></summary>
SMBBIT-Desk features custom non-blocking Win32 title bar interception. Instead of allowing synchronous modal tracking loops to starve the event thread, actions are processed asynchronously via Windows message queues, ensuring screen capture and input injection remain 100% active in the background.
</details>

---

## 🎯 Ideal Use Cases

- 🏢 **Remote Work & Home Office**: Connect to your office PC from your laptop with zero latency.
- 👨‍💻 **IT Support & System Administration**: Provide swift, hassle-free remote support without forcing clients to install heavy packages.
- 👨‍👩‍👧 **Family & Friends Assistance**: Help relatives fix computer problems without countdown ads or 5-minute disconnects.
- 🖥️ **Headless Servers & Rigs**: Manage servers, lab computers, or render rigs effortlessly.

---

## 🛡️ Privacy & Security

- **Direct End-to-End Encryption**: All WebRTC video feeds, SCTP input data, and file transfers are secured with DTLS and SRTP encryption.
- **Zero Third-Party Relays**: Audio, video, and keystroke data travel directly between the two peer devices.
- **Client-Controlled Access**: You decide who connects. Sessions can be accepted manually or secured with strong custom unattended passwords.

---

## 🤝 Community & Support

- **Repository**: [https://github.com/Muhammad9985/SMBBIT-Desk](https://github.com/Muhammad9985/SMBBIT-Desk)
- **Issues & Bug Reports**: [Open an Issue](https://github.com/Muhammad9985/SMBBIT-Desk/issues)
- **Feature Requests**: Have an idea? Submit a feature suggestion in Discussions!

---

## ⭐ Star the Project!

If **SMBBIT-Desk** saved you money, eliminated frustrating timeouts, and gave you a better remote desktop experience, please give our repository a **⭐ Star** on GitHub! It helps more users find this free alternative.

<div align="center">

**Developed with ❤️ by [Muhammad](https://github.com/Muhammad9985)**

*Freeing remote desktop users from unnecessary subscriptions and advertisements.*

</div>
