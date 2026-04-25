<div align="center">

[![AtulOS Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0a0f1e,50:00b4d8,100:00e5ff&height=200&section=header&text=ATUL%20%2F%2F%20SYSTEMS%20ARCHITECT&fontSize=36&fontColor=00e5ff&fontAlignY=38&desc=Firmware%20%E2%80%A2%20Embedded%20Systems%20%E2%80%A2%20OS%20Engineering%20%E2%80%A2%20IoT%20Infrastructure&descAlignY=58&descSize=14&descColor=7ecfff&animation=fadeIn)](https://github.com/atul-singh-07)

<svg width="800" height="230" viewBox="0 0 800 230" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Terminal glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Border glow -->
    <filter id="borderGlow" x="-5%" y="-5%" width="110%" height="110%">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Scanline gradient -->
    <linearGradient id="scanGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#00e5ff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00e5ff" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#00e5ff" stop-opacity="0"/>
    </linearGradient>
    <!-- Glass background gradient -->
    <linearGradient id="bgGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0d1528"/>
      <stop offset="100%" stop-color="#060c18"/>
    </linearGradient>
  </defs>

  <!-- Terminal window body -->
  <rect x="2" y="2" width="796" height="226" rx="10" ry="10" fill="url(#bgGrad)" stroke="#00b4d8" stroke-width="1.2" filter="url(#borderGlow)" opacity="0.97"/>

  <!-- Title bar -->
  <rect x="2" y="2" width="796" height="30" rx="10" ry="10" fill="#0a1a2e"/>
  <rect x="2" y="22" width="796" height="10" fill="#0a1a2e"/>

  <!-- Title bar dots -->
  <circle cx="22" cy="17" r="5" fill="#1a3a5c" opacity="0.9"/>
  <circle cx="40" cy="17" r="5" fill="#1a3a5c" opacity="0.9"/>
  <circle cx="58" cy="17" r="5" fill="#00b4d8" opacity="0.7"/>

  <!-- Title bar label -->
  <text x="400" y="21" font-family="'Courier New', Courier, monospace" font-size="11" fill="#4a9ebe" text-anchor="middle" opacity="0.9">AtulOS — Terminal v1.0</text>

  <!-- Divider line under title bar -->
  <line x1="2" y1="32" x2="798" y2="32" stroke="#00b4d8" stroke-width="0.5" opacity="0.4"/>

  <!-- Boot line 1: [BOOT] -->
  <g opacity="0">
    <animateTransform attributeName="transform" type="translate" values="0,0" dur="0.01s" begin="0s" fill="freeze"/>
    <animate attributeName="opacity" values="0;1" dur="0.15s" begin="0.3s" fill="freeze"/>
    <text x="28" y="62" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00b4d8" filter="url(#glow)">[BOOT]</text>
    <text x="100" y="62" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#7ecfff">Initializing AtulOS Core...</text>
    <text x="700" y="62" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" opacity="0.6">0.001s</text>
  </g>

  <!-- Boot line 2: [LOAD] -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.15s" begin="1.1s" fill="freeze"/>
    <text x="28" y="88" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00b4d8" filter="url(#glow)">[LOAD]</text>
    <text x="100" y="88" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#7ecfff">Loading IoT Control Modules...</text>
    <text x="700" y="88" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" opacity="0.6">0.038s</text>
  </g>

  <!-- Boot line 3: [LINK] -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.15s" begin="1.9s" fill="freeze"/>
    <text x="28" y="114" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00b4d8" filter="url(#glow)">[LINK]</text>
    <text x="100" y="114" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#7ecfff">Connecting Firebase Cloud Layer...</text>
    <text x="700" y="114" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" opacity="0.6">0.112s</text>
  </g>

  <!-- Boot line 4: [SYNC] -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.15s" begin="2.7s" fill="freeze"/>
    <text x="28" y="140" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00b4d8" filter="url(#glow)">[SYNC]</text>
    <text x="100" y="140" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#7ecfff">Mounting ESP32 + Sensor Array...</text>
    <text x="700" y="140" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" opacity="0.6">0.204s</text>
  </g>

  <!-- Boot line 5: [OK] — green-blue highlight -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="3.5s" fill="freeze"/>
    <text x="28" y="166" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" filter="url(#glow)" font-weight="bold">[OK]</text>
    <text x="100" y="166" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" filter="url(#glow)" font-weight="bold">Smart Infrastructure Online</text>
    <text x="700" y="166" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00e5ff" opacity="0.6">0.391s</text>
  </g>

  <!-- Prompt line -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.15s" begin="4.1s" fill="freeze"/>
    <text x="28" y="200" font-family="'Courier New', Courier, monospace" font-size="13.5" fill="#00b4d8">atul@AtulOS:~$</text>
    <!-- Blinking cursor block -->
    <rect x="183" y="186" width="9" height="16" fill="#00e5ff" opacity="0">
      <animate attributeName="opacity" values="0;0;1;1;0;0" dur="1.1s" begin="4.3s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Scanline sweep overlay -->
  <rect x="3" y="33" width="794" height="45" rx="0" fill="url(#scanGrad)" opacity="1">
    <animateTransform attributeName="transform" type="translate" values="0,0;0,160;0,0" dur="5s" repeatCount="indefinite" calcMode="linear"/>
    <animate attributeName="opacity" values="0.7;0.4;0.7" dur="5s" repeatCount="indefinite"/>
  </rect>

  <!-- Subtle flicker overlay on entire terminal -->
  <rect x="3" y="33" width="794" height="194" rx="0" fill="#00e5ff" opacity="0">
    <animate attributeName="opacity" values="0;0;0;0.015;0;0;0;0.008;0" dur="7s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

---

```diff
+ SYSTEM IDENTIFICATION — AtulOS Terminal v1.0
──────────────────────────────────────────────────────────────
  OPERATOR     : Atul Singh
  HANDLE       : @atul-singh-07
  ROLE         : Systems Engineer | Embedded Developer | OS Builder
  STACK DEPTH  : Hardware → Firmware → Cloud → UI
  ACTIVE BUILD : AtulOS — Custom OS with AI command layer
  STATUS       : [ ONLINE ] — Mission-critical systems running
──────────────────────────────────────────────────────────────
```

---

<div align="center">

## ◈ ARCHITECTURE — CONTROL MAP

</div>

```txt
╔══════════════════════════════════════════════════════════════════╗
║                    ╔═══════════════╗                            ║
║                    ║    AtulOS     ║  ← CONTROL CORE            ║
║                    ║  AI Commands  ║                            ║
║                    ║ Device Control║                            ║
║                    ╚══════╤════════╝                            ║
║                           │                                     ║
║          ┌────────────────┼────────────────┐                    ║
║          │                │                │                    ║
║   ┌──────▼──────┐  ┌──────▼──────┐  ┌──────▼──────┐           ║
║   │   PARKING   │  │     EV      │  │     IoT     │           ║
║   │   MODULE    │  │  CHARGING   │  │   CLOUD     │           ║
║   │  ESP32 + FW │  │  CTRL + MON │  │  DASHBOARD  │           ║
║   └──────┬──────┘  └──────┬──────┘  └──────┬──────┘           ║
║          │                │                │                    ║
║          └────────────────┼────────────────┘                    ║
║                           │                                     ║
║                    ┌──────▼──────┐                              ║
║                    │  HARDWARE   │                              ║
║                    │  LAYER      │                              ║
║                    │Sensors / MCU│                              ║
║                    └─────────────┘                              ║
╚══════════════════════════════════════════════════════════════════╝
```

---

<div align="center">

## ◈ ACTIVE MODULES

</div>

| MODULE | STACK | LINK |
|:---|:---|:---:|
| `[MOD-01]` **Smart Parking System** — ESP32 + IR sensors, Firebase sync, real-time dashboard | `ESP32` `Firebase` `IoT` `Web` | [**→ LAUNCH**](https://github.com/atul-singh-07/Smart-Parking-Dashboard) |
| `[MOD-02]` **IoT Cloud Dashboard** — Live sync, device telemetry, data visualization | `Node.js` `Firebase` `HTML/CSS/JS` | [**→ LAUNCH**](https://github.com/atul-singh-07/atul-singh-07.github.io) |
| `[MOD-03]` **AtulOS** — Terminal UI OS with AI command layer + device control shell | `C` `Linux` `AI Layer` `CLI` | `[ IN BUILD ]` |
| `[MOD-04]` **EV Charging System** — Control + monitoring + prepaid booking engine | `Embedded` `Cloud` `Control Logic` | `[ IN BUILD ]` |

---

<div align="center">

## ◈ LIVE SYSTEM PREVIEW

> *Smart Parking Dashboard — Real-time occupancy monitoring via ESP32 + Firebase*

[![Smart Parking Dashboard](https://img.shields.io/badge/LIVE_PREVIEW-Smart_Parking_Dashboard-00e5ff?style=for-the-badge&logo=googlecloud&logoColor=black)](https://github.com/atul-singh-07/Smart-Parking-Dashboard)

</div>

```yaml
# SYSTEM: Smart-Parking-Dashboard
  hardware_core  : ESP32 + IR Proximity Sensors
  data_pipeline  : Sensor → Firmware → Firebase RTDB → Web UI
  features:
    - Real-time slot occupancy tracking
    - Firebase-synced live dashboard
    - Multi-sensor array management
    - Web visualization layer
  status         : DEPLOYED
```

---

<div align="center">

## ◈ TECH STACK

**Embedded & Hardware**

![C](https://img.shields.io/badge/C-00b4d8?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-0077b6?style=for-the-badge&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-00e5ff?style=for-the-badge&logo=espressif&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-023e8a?style=for-the-badge&logo=arduino&logoColor=white)
![RTOS](https://img.shields.io/badge/FreeRTOS-0096c7?style=for-the-badge&logoColor=white)

**Cloud & Backend**

![Firebase](https://img.shields.io/badge/Firebase-00b4d8?style=for-the-badge&logo=firebase&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-0077b6?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-023e8a?style=for-the-badge&logo=python&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-00e5ff?style=for-the-badge&logo=eclipsemosquitto&logoColor=black)

**Systems & OS**

![Linux](https://img.shields.io/badge/Linux-00b4d8?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-0077b6?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-023e8a?style=for-the-badge&logo=git&logoColor=white)

**Frontend & UI**

![HTML5](https://img.shields.io/badge/HTML5-00b4d8?style=for-the-badge&logo=html5&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-0077b6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-023e8a?style=for-the-badge&logo=javascript&logoColor=white)

</div>

---

<div align="center">

## ◈ SYSTEM METRICS

<img src="https://github-readme-stats.vercel.app/api?username=atul-singh-07&show_icons=true&theme=transparent&title_color=00e5ff&icon_color=00b4d8&text_color=7ecfff&border_color=00b4d8&border_radius=8&hide_border=false&include_all_commits=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=atul-singh-07&layout=compact&theme=transparent&title_color=00e5ff&text_color=7ecfff&border_color=00b4d8&border_radius=8&hide_border=false" height="165"/>

<img src="https://streak-stats.demolab.com?user=atul-singh-07&theme=transparent&border=00b4d8&ring=00e5ff&fire=00b4d8&currStreakLabel=00e5ff&sideLabels=7ecfff&dates=7ecfff&border_radius=8" height="165"/>

</div>

---

<div align="center">

## ◈ CONTRIBUTION GRID

<img src="https://raw.githubusercontent.com/atul-singh-07/atul-singh-07/output/github-contribution-grid-snake-dark.svg" alt="contribution-snake" />

> *If the snake hasn't rendered yet — [configure the GitHub Action](https://github.com/Platane/snk) in your profile repo.*

</div>

---

<div align="center">

## ◈ CURRENT MISSION

</div>

```diff
+ MISSION LOG — AtulOS Build Cycle
────────────────────────────────────────────────────────────
+ [ACTIVE]   AtulOS — Terminal-native OS, AI command routing
+ [ACTIVE]   EV Charging System — Prepaid booking + control layer
+ [ACTIVE]   IoT Cloud Infra — Scaling real-time device telemetry
- [QUEUED]   AtulOS GUI shell — Hardware-accelerated UI layer
- [QUEUED]   Edge ML — On-device inference for sensor fusion
────────────────────────────────────────────────────────────
  DIRECTIVE  : Ship systems that solve physical-world problems.
               Not demos. Infrastructure.
────────────────────────────────────────────────────────────
```

---

<div align="center">

## ◈ ENGINEERING PHILOSOPHY

</div>

```txt
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   "The stack is vertical by design.                     │
  │    From silicon to cloud — own every layer."            │
  │                                                         │
  │   Hardware without software is inert.                   │
  │   Software without hardware is abstract.                │
  │   Systems that command both — that's real engineering.  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

---

<div align="center">

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00e5ff,50:00b4d8,100:0a0f1e&height=120&section=footer&text=AtulOS+%2F%2F+All+Systems+Nominal&fontSize=16&fontColor=00e5ff&fontAlignY=65)](https://github.com/atul-singh-07)

`[ SESSION CLOSED ]` · `[ UPTIME: ALWAYS ]` · `[ SYSTEMS: ONLINE ]`

</div>
