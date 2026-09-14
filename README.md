<div align="center">

# StumpfWorks

### Open software. Your infrastructure. Your control.

Building self-hosted software, infrastructure and connected hardware.

<br>

[![StumpfWorks](https://img.shields.io/badge/StumpfWorks-Open_Source-0969DA?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Stumpf-works)
[![GitHub](https://img.shields.io/badge/@TheRealHZL-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TheRealHZL)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](https://discord.gg/rv2h8FrD)

<br>

**Software** · **Infrastructure** · **Identity** · **Security** · **Embedded**

</div>

---

## 👋 About

I'm **MrHeiz97**, the developer behind StumpfWorks.

I enjoy building systems where software, infrastructure and hardware come together — from Go services and authentication systems to self-hosted infrastructure and microcontrollers.

StumpfWorks is where these projects live.

The idea behind it is simple:

> ### Build software you can understand, operate and own.

No mandatory cloud.
No unnecessary dependencies on external services.
No black box where there doesn't need to be one.

---

## ◈ The StumpfWorks Ecosystem

StumpfWorks isn't a single application.

It's a growing family of independent open-source projects built around shared ideas and, increasingly, shared foundations.

|     | Project         | Purpose                         |    Status   |
| :-: | --------------- | ------------------------------- | :---------: |
|  🔐 | **SW.ID**       | Identity & Authentication       |  🟢 Active  |
|  🚪 | **SW.ACCESS**   | Physical Access Control         |  🟢 Active  |
|  🧩 | **SW.FW**       | Shared Application Framework    | 🟡 Building |
|  📦 | **SW.A**        | Archive & Container Format      |  ⚪ Planned  |
|  🚑 | **RettConnect** | Medical & Emergency Software    |   ⚪ Future  |
|  🧪 | **SW.LABS**     | Hardware & Software Experiments |  🔵 Ongoing |

---

## 🔐 SW.ID

### StumpfWorks Identity

**Identity is where the ecosystem starts.**

SW.ID provides identity and authentication services for StumpfWorks applications and clients.

`Authentication` · `Users` · `Devices` · `Clients` · `Authorization` · `Audit`

It is designed around secure application integration while remaining completely self-hosted.

---

## 🚪 SW.ACCESS

### StumpfWorks Access

**Where software meets the real world.**

SW.ACCESS connects identity and authentication with physical access control.

It combines a self-hosted server with embedded hardware nodes to control things such as gates and doors.

**Software**

`Web Administration` · `API` · `Identity Integration` · `Audit`

**Authentication**

`PIN` · `RFID / NFC` · `Passkeys`

**Hardware**

`ESP8266` · `ESP32` · `Relays` · `Readers` · `Sensors`

The infrastructure belongs to the person operating it.

---

## 🧩 SW.FW

### StumpfWorks Framework

One shared foundation for future StumpfWorks applications.

Rather than implementing the same fundamentals for every new project, SW.FW is intended to provide reusable components for:

`Application Core`

`Authentication & Authorization`

`Configuration`

`Database`

`Logging & Audit`

`Security`

`APIs & Events`

`Updates`

`Observability`

This lets future projects focus on what actually makes them unique.

> **Build the foundation once. Improve it everywhere.**

---

## 📦 SW.A

### StumpfWorks Archive

**Project:** `SW.A`
**Format:** `SWA`
**Extension:** `.swa`

SW.A is the upcoming StumpfWorks archive project.

The goal is to design an actual documented and versioned archive/container format — not simply put a new extension on an existing ZIP file.

Planned components include:

`SWA Format Specification`

`Go Reference Library`

`Command Line Interface`

`Pack / Unpack`

`Zstandard Compression`

`Metadata`

`Integrity Verification`

`Optional Encryption`

### The basic idea

```text
example.swa
    │
    ├── Header
    ├── Metadata
    ├── File Index
    ├── Compressed Data
    └── Integrity Information
```

SW.A will be developed after the current StumpfWorks foundation work.

---

## 🚑 RettConnect

### A future StumpfWorks project

RettConnect is focused on software for **medical, emergency and event medical environments**.

Possible areas include patient documentation, operational workflows, teams, vehicles, equipment, checklists and reporting.

Unlike a simple experimental application, RettConnect may eventually handle particularly sensitive information.

For that reason, there is no reason to rush it.

The plan is to first build a mature StumpfWorks foundation and later develop RettConnect properly on top of it.

---

## 🧪 SW.LABS

### Ideas don't always need a roadmap.

SW.LABS represents the experimental side of StumpfWorks.

This is where software meets breadboards, sensors, networks and occasionally questionable amounts of wiring.

<div align="center">

`ESP8266`　`ESP32`　`Raspberry Pi`　`RFID / NFC`

`Sensors`　`Automation`　`Networking`　`Linux`

`Self-Hosting`　`Protocols`　`Monitoring`　`3D Printing`

</div>

Some experiments stay experiments.

Some solve a problem.

And some become the next StumpfWorks project.

---

## ⚙️ Built With

<div align="center">

### Development

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square\&logo=go\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)

### Web & Data

![React](https://img.shields.io/badge/React-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=nodedotjs\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square\&logo=proxmox\&logoColor=white)

### Embedded

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square\&logo=raspberrypi\&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square\&logo=arduino\&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-333333?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-333333?style=flat-square)

</div>

---

## 📊 Development

<div align="center">

![Profile Stats](https://github-readme-stats.vercel.app/api?username=TheRealHZL\&show_icons=true\&theme=transparent\&hide_border=true\&include_all_commits=true\&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=TheRealHZL\&layout=compact\&theme=transparent\&hide_border=true)

</div>

---

## 🛣️ Where StumpfWorks is going

The current work is focused on establishing the core ecosystem:

**SW.ID + SW.ACCESS + SW.FW**

↓

**Shared StumpfWorks Foundation**

↓

**SW.A**

↓

**New StumpfWorks Projects**

↓

**RettConnect**

The individual projects will change and evolve.

The principles behind them shouldn't.

---

<div align="center">

<br>

## Build it. Understand it. Own it.

**StumpfWorks**

*Open-source software built to run on your infrastructure.*

<br>

[![GitHub](https://img.shields.io/badge/GitHub-TheRealHZL-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/TheRealHZL)
[![StumpfWorks](https://img.shields.io/badge/GitHub-StumpfWorks-0969DA?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Stumpf-works)
[![Discord](https://img.shields.io/badge/Discord-Connect-5865F2?style=flat-square\&logo=discord\&logoColor=white)](https://discord.gg/rv2h8FrD)

<br>

<sub>Built by MrHeiz97.</sub>

</div>
