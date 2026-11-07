<div align="center">
  <img src="./assets/banner.svg" alt="emoorpheus // Next-Gen webOS &amp; Home Cinema Ecosystem" width="100%" />

  <br/><br/>

  <p align="center">
    <a href="https://github.com/emoorpheus?tab=repositories"><img src="https://img.shields.io/badge/Platform-LG%20webOS%2024%2F25-E01E5A?style=for-the-badge&amp;logo=lg&amp;logoColor=white" alt="LG webOS" /></a>
    <a href="https://github.com/emoorpheus"><img src="https://img.shields.io/badge/Aesthetics-OLED%20True%20Black-000000?style=for-the-badge&amp;logo=target&amp;logoColor=38bdf8" alt="OLED True Black" /></a>
    <a href="https://github.com/emoorpheus/eArcNG"><img src="https://img.shields.io/badge/Sound-HDMI--CEC%20eARC-7c3aed?style=for-the-badge&amp;logo=sony&amp;logoColor=white" alt="HDMI-CEC eARC" /></a>
    <a href="https://github.com/emoorpheus"><img src="https://img.shields.io/badge/Location-Kazan%2C%20RU-0f172a?style=for-the-badge&amp;logo=googlemaps&amp;logoColor=38bdf8" alt="Kazan, RU" /></a>
  </p>
</div>

### ⚡ Overview

Software engineer, IT infrastructure lead, and home cinema enthusiast focused on **embedded Smart TV platforms**, **OLED display optimization**, and **frictionless media streaming**.

My primary focus is extending **LG webOS** beyond its factory limits:
- 🔌 **Deep System Integration:** Interfacing directly with low-level `Luna-Send` bus services, IPC daemons, and system audio/display pipelines.
- 🖤 **OLED-First Design:** Engineering pure-black (`#000000`) interfaces, sub-pixel contrast tuning, and glare-free HDR / Dolby Vision subtitle renderers.
- 🚀 **Next-Gen (NG) Applications:** Rebuilding sluggish native web apps into responsive, ad-free, high-performance TV experiences.

---

### 🚀 The Next-Gen (NG) webOS Suite

| Project | Description | Stack | Highlights |
|:---|:---|:---|:---|
| [**HearthNG**](https://github.com/emoorpheus/HearthNG) | **OLED-First Lightweight Custom Launcher for LG webOS**<br/>Fast cold boot, custom true black theme, app hide/reorder, smooth animations &amp; native system toast indicators. | `TypeScript`<br/>`Svelte`<br/>`Luna Bus` | [![Release](https://img.shields.io/github/v/release/emoorpheus/HearthNG?style=flat-square&amp;color=38bdf8&amp;labelColor=0f172a)](https://github.com/emoorpheus/HearthNG/releases) |
| [**eArcNG**](https://github.com/emoorpheus/eArcNG) | **Native HDMI-CEC eARC/ARC Soundbar Volume OSD**<br/>Seamless on-screen volume &amp; mute indicator for external audio systems using private Luna audio bus subscriptions (`com.webos.service.audio`). | `Python`<br/>`Qt / QML`<br/>`Luna Service` | [![Active](https://img.shields.io/badge/v1.0-Active-34d399?style=flat-square&amp;labelColor=0f172a)](https://github.com/emoorpheus/eArcNG) |
| [**YoutubeNG**](https://github.com/emoorpheus/YoutubeNG) | **Next-Gen YouTube Client for webOS**<br/>Ad-free viewing, SponsorBlock, Return YouTube Dislike (RYD), 0.25x–3x custom playback speeds, and pure black OLED dark mode. | `JavaScript`<br/>`webOS Cobalt`<br/>`SponsorBlock` | [![Active](https://img.shields.io/badge/v1.0-Active-34d399?style=flat-square&amp;labelColor=0f172a)](https://github.com/emoorpheus/YoutubeNG) |
| [**TwitchNG**](https://github.com/emoorpheus/TwitchNG) | **Custom Twitch Client for webOS**<br/>High-performance Twitch app with pitch-preserving VOD playback speed controls and an OLED-optimized dark theme. | `JavaScript`<br/>`webOS`<br/>`HLS.js` | [![Active](https://img.shields.io/badge/v1.0-Active-34d399?style=flat-square&amp;labelColor=0f172a)](https://github.com/emoorpheus/TwitchNG) |

---

### 🎬 Home Cinema &amp; Media Streaming Plugins

| Project | Description | Stack | Highlights |
|:---|:---|:---|:---|
| [**lampa-adaptive-subtitles**](https://github.com/emoorpheus/lampa-adaptive-subtitles) | **Anti-Glare Adaptive Subtitles for HDR / Dolby Vision**<br/>Intelligent subtitle luminance control preventing blinding white text glare on high-nit OLED panels while keeping subtitles sharp and readable. | `JavaScript`<br/>`CSS`<br/>`Canvas DOM` | [![Active](https://img.shields.io/badge/OLED-Anti--Glare-38bdf8?style=flat-square&amp;labelColor=0f172a)](https://github.com/emoorpheus/lampa-adaptive-subtitles) |
| [**lampa-skip-intro**](https://github.com/emoorpheus/lampa-skip-intro) | **Automated Intro &amp; Recap Skipper for Lampa**<br/>Smart multi-source timestamp aggregator (KinoPoisk, Anilibria, TVMaze) for zero-click intro and credits skipping. | `JavaScript`<br/>`Lampa Plugin API` | [![Active](https://img.shields.io/badge/Auto--Skip-Enabled-34d399?style=flat-square&amp;labelColor=0f172a)](https://github.com/emoorpheus/lampa-skip-intro) |

---

### 🛠 Tech Stack &amp; Architecture

```
┌─────────────────┬─────────────────────────────────────────────────────────────────────────┐
│ Category        │ Technologies & Tools                                                    │
├─────────────────┼─────────────────────────────────────────────────────────────────────────┤
│ TV & Embedded   │ LG webOS 24/25, Luna Bus (luna-send / luna-service2), WebOSBrew, Linux  │
│ Languages       │ TypeScript, JavaScript (ESNext), Python 3, Qt/QML, Shell / Bash         │
│ Frontend & UI   │ Svelte, Tailwind CSS, Pure Black (#000000), Custom WebProcess Injection │
│ Audio & Video   │ HDMI-CEC eARC, Dolby Vision, HDR10, HLG, Subtitle Pipeline Tuning       │
│ Infrastructure  │ OpenWrt, Armbian HomeLab, WireGuard, Reverse Proxies, Docker            │
└─────────────────┴─────────────────────────────────────────────────────────────────────────┘
```

---

### 📊 GitHub Activity &amp; Streak

<div align="center">
  <a href="https://github.com/emoorpheus">
    <img src="https://streak-stats.demolab.com/?user=emoorpheus&amp;theme=dark&amp;background=050810&amp;border=1e293b&amp;stroke=1e293b&amp;ring=38bdf8&amp;fire=38bdf8&amp;currStreakLabel=38bdf8" alt="GitHub Streak" />
  </a>
  <br/><br/>
  <a href="https://github.com/emoorpheus">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=emoorpheus&amp;theme=tokyonight" alt="Languages Card" />
  </a>
</div>

---

<div align="center">
  <sub>Engineered with precision for true black OLED displays &amp; uncompromised media playback.</sub>
</div>
