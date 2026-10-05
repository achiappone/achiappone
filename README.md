# Anthony Chiappone

**Software engineer and senior product manager in professional lighting and control systems.**
B.S., Engineering (DeVry University) · 15 years at Chauvet Professional · Sunrise, FL

I build software that talks to hardware: mobile apps that configure fixtures over BLE and NFC,
RDM and DMX protocol work, ESP32 firmware, and the web tools and infrastructure around them.
My path here was technical writer → product engineer → product manager → senior product manager.
I still ship code alongside the engineering team, so I understand both the product requirements and the implementation.

**Core stack:** TypeScript · React · React Native · Node.js · MobX-State-Tree · Python · C/C++ (ESP32 / ESP-IDF / Arduino) · C#
**Protocols:** DMX512 · RDM (ANSI E1.20) · Art-Net · sACN · OSC · BLE · NFC · NMEA 2000 / CAN · WebRTC
**Ops:** GitHub Actions · Proxmox / LXC · systemd · Docker · Cloudflare Tunnel · Ansible

---

## Professional work · Chauvet Professional

These codebases are proprietary, so this section describes my work rather than linking to it.

**NFC/BLE fixture configuration app** — Cross-platform mobile app (React Native, iOS and Android) that configures
and diagnoses professional lighting fixtures over NFC and Bluetooth LE, including fixtures that are not yet powered.
35 merged PRs, including:
- NFC tag memory mapping for fixture configuration data, with sequential tag writing
- BLE firmware updates with capability checks and post-update verification
- Diagnostics reporting: reworked report layout and export, clearer pass/warning/fail results
- Secured job data, network address patching and DMX input validation
- iOS/Android UI parity and fixture profile data

**Wireless DMX gateway — RDM support** — A fixture-control app and the SBC-based wireless DMX gateway it talks to.
- Co-developed **RDM** (ANSI E1.20) support across app and gateway: device addressing, protocol alignment,
  polling reliability and wireless link stability
- Front-end UI design, plus much of the QA test planning and execution

**Lighting-control system designer** — Sales-enablement web tool that lets sales and support teams draw
complete lighting-control system diagrams from a product catalogue (React + TypeScript).
- Contributed as part of the development team, with focus on front-end UI design and QA

**Product leadership** — I define requirements, run Agile delivery with the software team, and take
products from concept to release with engineering, marketing, sales and support.

---

## Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**Particle Analyzer & Doser**](https://github.com/achiappone/DMX_Haze_Regulator) | Closed-loop particle control: PM2.5 particle sensor → DMX512 dosing output, with a live web UI, OTA updates and a watchdog | ESP32-S3, C++, I2C, RS-485 |
| [**K2 Plus Dashboard**](https://github.com/achiappone/k2plus-dashboard) | Read-only proxy dashboard for a Klipper/Moonraker printer, including an in-browser WebRTC camera negotiation | Python (stdlib only), JS |
| [**Development Dashboard**](https://github.com/achiappone/pve-stack) | Remote and performance monitoring for a self-hosted dev server: live host metrics, service health, camera feeds, one-click deploys, network failover | TypeScript, Python, Bash, systemd |
| [**OpenMarine Pi**](https://github.com/achiappone/openMarineChipAjoi) | Raspberry Pi boat computer: Signal K, NMEA 2000 over CAN, engine diagnostics, config managed as code | Pi 4, Node, Python, Ansible |
| [**K2 ESP32 Cam**](https://github.com/achiappone/k2_esp32_cam) | Single-file camera firmware whose endpoints match the dashboard's relay | ESP32-CAM, C++ |
| [**NVWAPP**](https://github.com/achiappone/NVWAPP) | LED video-wall planner that generates PDF system documentation | React Native (Expo), TypeScript |

**Hobby:** [**Helm Design**](https://github.com/achiappone/helm-design) — parametric CAD as code for a 3D-printed boat helm display housing (Python, build123d).

---

[Portfolio](https://achiappone.github.io/resume-portfolio) · [LinkedIn](https://www.linkedin.com/in/anthonychiappone) · anthonychiappone@gmail.com
