# Arold

**Embedded Software Developer · AI Engineering & IT Student**

I build software close to the hardware and close to the user — Yocto-based Linux BSPs for
i.MX8M and Raspberry Pi boards, ultra-wideband spatial interaction on iOS, cross-platform
mobile apps in Flutter, and full-stack TypeScript when a project needs a web face.

Most of my work sits where embedded systems meet applied AI: on-device intelligence,
sensor-driven interaction, and the build infrastructure that keeps both shippable.

---

## Tech Stack

**Embedded & Systems**

![Yocto](https://img.shields.io/badge/Yocto%20Project-1A1A1A?style=flat-square&logo=yocto&logoColor=white)
![BitBake](https://img.shields.io/badge/BitBake-4B4B4B?style=flat-square)
![Linux](https://img.shields.io/badge/Embedded%20Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![NXP](https://img.shields.io/badge/NXP%20i.MX8M-000000?style=flat-square&logo=nxp&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%205-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![U-Boot](https://img.shields.io/badge/U--Boot-2E2E2E?style=flat-square)

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Qt](https://img.shields.io/badge/Qt%20%2F%20QML-41CD52?style=flat-square&logo=qt&logoColor=white)

**Web & Backend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Codemagic](https://img.shields.io/badge/Codemagic-F45E3F?style=flat-square&logo=codemagic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## Selected Work

### RECLAIM — AI-Powered Recovery Coach
`Flutter` · `Dart` · `on-device AI` · `Android + iOS`

A recovery companion app that helps people break addictive behaviour patterns. An AI coach
handles 24/7 conversational support, backed by streak tracking with a live timer, a
multi-stage craving-intervention flow, a three-step emergency anti-relapse protocol,
journaling with AI mood analysis, gamified habit replacement, and AI-generated weekly
reports. Runs fully on-device. Shipped through a Codemagic CI pipeline for both platforms.

### UWB Spatial Interaction with Third-Party Accessories
`Swift` · `iOS` · `Nearby Interaction` · `Ultra-Wideband`

An iOS app that pairs with third-party ultra-wideband accessories and continuously ranges
their distance and direction relative to the device, built on Apple's Nearby Interaction
framework and the U1/U2 chip. Extends the WWDC21 reference design with Camera Assistance
(iOS 16+) for improved directional accuracy, plus accessory configuration handling and a
Codemagic build pipeline.

### Restaurant Order System — [`Tegrask/rest`](https://github.com/Tegrask/rest)
`TypeScript` · `Next.js 16` · `React 19` · `Prisma` · `Tailwind`

A full-stack QR-code ordering platform for restaurants. Guests scan a table code and order
straight from their phone; staff work a live order board. Includes JWT session auth
(`jose` + `bcryptjs`), a Prisma-managed relational schema with migrations and seeding, and
an admin dashboard with Recharts-based sales analytics, table management, and menu CRUD.

### Variscite i.MX8M BSP Layer
`Yocto` · `BitBake` · `NXP i.MX8M`

A Yocto Project BSP layer for Variscite i.MX8M system-on-modules (DART-MX8M, VAR-SOM-MX8M),
covering kernel and U-Boot integration plus pre-configured minimal, Qt, and Wayland images.
Supports the NXP i.MX8M Quad, Dual, and Nano variants.

### Applied Yocto on Raspberry Pi 5
`BitBake` · `CMake` · `C++` · `QML`

Custom Yocto layers, recipes, and image definitions for the Raspberry Pi 5, including a
Qt/QML application built and deployed as part of the generated image — an end-to-end pass
from recipe to running board.

> Repositories without a link are private. Happy to walk through the code on request.

---

## Language Overview

Measured across all my repositories, public and private, by source bytes:

| Language | Share | Where |
|---|---:|---|
| Dart | 49.0 % | Flutter mobile apps |
| Swift | 34.4 % | iOS / UWB |
| TypeScript | 13.7 % | Next.js full-stack |
| BitBake | 1.0 % | Yocto recipes & layers |
| Shell | 0.6 % | Build & deploy scripts |
| Batchfile | 0.6 % | Windows build tooling |
| CMake | 0.3 % | Native build config |
| JavaScript | 0.1 % | Web config & tooling |
| CSS | 0.1 % | Styling |
| C++ | 0.1 % | Embedded application code |
| QML | < 0.1 % | Qt user interfaces |
| Kotlin | < 0.1 % | Android platform channels |
| C | < 0.1 % | Low-level integration |

Byte share favours application code over configuration — the Yocto and CMake work carries
far more weight in practice than its line count suggests.

---

## Currently

Deepening the overlap between embedded systems and applied AI — on-device inference,
UWB-driven spatial interaction, and reproducible Yocto builds for custom hardware.
