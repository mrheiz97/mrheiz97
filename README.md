<!-- ========================================================= -->

<!--                    STUMPFWORKS PROFILE                     -->

<!-- ========================================================= -->

<div align="center">

# `STUMPFWORKS_`

### SOFTWARE × INFRASTRUCTURE × HARDWARE

**Open Source · Self-Hosted · Security by Design**

<br>

> ### `BUILD IT. UNDERSTAND IT. OWN IT.`

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-TheRealHZL-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TheRealHZL)
[![StumpfWorks](https://img.shields.io/badge/STUMPFWORKS-ECOSYSTEM-0969DA?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Stumpf-works)
[![Discord](https://img.shields.io/badge/DISCORD-CONNECT-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](https://discord.gg/rv2h8FrD)

<br>

```text
╔══════════════════════════════════════════════════════╗
║              STUMPFWORKS SYSTEM STATUS              ║
╠══════════════════════════════════════════════════════╣
║                                                      ║
║   SW.ID       ● ONLINE       Identity                ║
║   SW.ACCESS   ● BUILDING     Access Control          ║
║   SW.FW       ● BUILDING     Framework               ║
║   SW.A        ○ QUEUED       Archive                 ║
║   RETTCONNECT ○ FUTURE       Medical Technology      ║
║   SW.LABS     ● RUNNING      Experiments             ║
║                                                      ║
╚══════════════════════════════════════════════════════╝
```

</div>

---

# `> WHOAMI`

```yaml
user: MrHeiz97
github: TheRealHZL
home: StumpfWorks

roles:
  - developer
  - builder
  - tinkerer
  - self-hoster

building:
  - backend systems
  - self-hosted applications
  - identity & access systems
  - developer infrastructure
  - embedded systems
  - automation

interested_in:
  - Go
  - application architecture
  - security
  - Linux
  - networking
  - embedded hardware
  - protocols
```

I like building things from the ground up.

Not just the frontend.

Not just the API.

I want to understand what happens **underneath it**.

```text
USER
 │
 ▼
APPLICATION
 │
 ▼
API
 │
 ▼
IDENTITY ──────► SECURITY
 │
 ▼
INFRASTRUCTURE
 │
 ▼
PROTOCOL
 │
 ▼
EMBEDDED CONTROLLER
 │
 ▼
HARDWARE
```

That's where **StumpfWorks** comes from.

---

# `01 // STUMPFWORKS`

StumpfWorks is my growing **open-source technology ecosystem**.

It isn't supposed to be a single application.

It's a collection of software, infrastructure, tools, protocols and hardware projects built around a common philosophy.

<div align="center">

### `OPEN SOURCE`

### `SELF-HOSTED`

### `MODULAR`

### `SECURITY BY DESIGN`

### `NO MANDATORY CLOUD`

</div>

The goal is simple:

> **Build systems you can run, inspect, modify and actually own.**

---

## `STUMPFWORKS://ARCHITECTURE`

```text
                         ┌──────────────────────┐
                         │     STUMPFWORKS_     │
                         └──────────┬───────────┘
                                    │
             ┌──────────────────────┼──────────────────────┐
             │                      │                      │
             ▼                      ▼                      ▼
      ┌─────────────┐        ┌─────────────┐        ┌─────────────┐
      │  SOFTWARE   │        │    CORE     │        │  HARDWARE   │
      └──────┬──────┘        └──────┬──────┘        └──────┬──────┘
             │                      │                      │
         Web Apps                 SW.ID                 ESP8266
         Services                SW.FW                  ESP32
         APIs                    Security               Raspberry Pi
         Tools                   Updates                RFID / NFC
             │                      │                      │
             └──────────────────────┼──────────────────────┘
                                    │
                                    ▼
                           ┌─────────────────┐
                           │ INFRASTRUCTURE  │
                           └────────┬────────┘
                                    │
                              Linux / Docker
                              Networking
                              Monitoring
                              Automation
```

---

# `02 // CORE SYSTEMS`

## 🔐 `SW.ID`

### StumpfWorks Identity

```text
┌─ SYSTEM INFORMATION ─────────────────────────┐
│ ID        SW.ID                              │
│ TYPE      Identity & Authentication          │
│ ROLE      Core Service                       │
│ STATE     ● ACTIVE                           │
└──────────────────────────────────────────────┘
```

`SW.ID` is the identity layer of the StumpfWorks ecosystem.

It provides a common foundation for applications and devices that need to know:

**Who are you?**

**What are you allowed to do?**

**Which device is connecting?**

**Can this application be trusted?**

```text
                  ┌─────────────┐
                  │    SW.ID    │
                  └──────┬──────┘
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
      USERS           DEVICES          CLIENTS
        │                │                │
        └────────────────┼────────────────┘
                         │
                         ▼
                 AUTHENTICATION
                         │
                         ▼
                  AUTHORIZATION
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
           SOFTWARE              HARDWARE
```

### `CAPABILITIES`

`AUTHENTICATION`
`USER MANAGEMENT`
`DEVICE MANAGEMENT`
`CLIENT REGISTRATION`
`ACCESS CONTROL`
`SIGNED UPDATES`
`AUDIT LOGGING`
`PRIVACY-SAFE DIAGNOSTICS`

---

## 🚪 `SW.ACCESS`

### StumpfWorks Access

```text
┌─ SYSTEM INFORMATION ─────────────────────────┐
│ ID        SW.ACCESS                          │
│ TYPE      Physical Access Control            │
│ BRIDGE    Software ↔ Hardware                │
│ STATE     ● ACTIVE DEVELOPMENT               │
└──────────────────────────────────────────────┘
```

`SW.ACCESS` connects the digital StumpfWorks world with the physical one.

Authentication shouldn't have to stop at a website.

```text
                        USER
                          │
                    ┌─────▼─────┐
                    │   SW.ID   │
                    └─────┬─────┘
                          │
                    AUTHENTICATED
                          │
                  ┌───────▼───────┐
                  │   SW.ACCESS   │
                  └───────┬───────┘
                          │
              ┌───────────┴───────────┐
              │                       │
              ▼                       ▼
          WEB / API               EDGE NODE
                                      │
                         ┌────────────┼────────────┐
                         │            │            │
                         ▼            ▼            ▼
                       RFID          PIN        PASSKEY
                         │            │            │
                         └────────────┼────────────┘
                                      │
                                      ▼
                                OUTPUT CONTROL
                                      │
                                ┌─────┴─────┐
                                ▼           ▼
                              GATE         DOOR
```

### `DESIGN GOAL`

```text
NO REQUIRED CLOUD
       +
LOCAL HARDWARE
       +
SELF-HOSTED SERVER
       +
STRONG IDENTITY
       =
SW.ACCESS
```

---

# `03 // SHARED FOUNDATION`

## 🧩 `SW.FW`

### StumpfWorks Framework

```text
┌─ SYSTEM INFORMATION ─────────────────────────┐
│ ID        SW.FW                              │
│ TYPE      Application Framework              │
│ ROLE      Shared Foundation                  │
│ STATE     ● IN DEVELOPMENT                   │
└──────────────────────────────────────────────┘
```

Building multiple applications shouldn't mean rebuilding the same foundation every time.

Without a shared foundation:

```text
PROJECT A ─► AUTH + CONFIG + LOGGING + SECURITY + API
PROJECT B ─► AUTH + CONFIG + LOGGING + SECURITY + API
PROJECT C ─► AUTH + CONFIG + LOGGING + SECURITY + API
```

With `SW.FW`:

```text
                        ┌─────────────┐
                        │    SW.FW    │
                        ├─────────────┤
                        │ APP CORE    │
                        │ AUTH        │
                        │ RBAC        │
                        │ CONFIG      │
                        │ DATABASE    │
                        │ LOGGING     │
                        │ AUDIT       │
                        │ SECURITY    │
                        │ EVENTS      │
                        │ API         │
                        │ UPDATES     │
                        │ TELEMETRY   │
                        └──────┬──────┘
                               │
               ┌───────────────┼───────────────┐
               ▼               ▼               ▼
          PROJECT A        PROJECT B       PROJECT C
```

> **Build the foundation once. Build the interesting part next.**

---

# `04 // NEXT IN QUEUE`

## 📦 `SW.A`

### StumpfWorks Archive

```text
┌─ SYSTEM INFORMATION ─────────────────────────┐
│ ID        SW.A                               │
│ NAME      StumpfWorks Archive                │
│ FORMAT    SWA                                │
│ FILE      *.swa                              │
│ TYPE      Archive / Container Format         │
│ STATE     ○ QUEUED                           │
└──────────────────────────────────────────────┘
```

`SW.A` asks a simple question:

> **What if StumpfWorks had its own archive format?**

Not just a renamed ZIP.

A documented, versioned format with its own specification and reference implementation.

```text
                        EXAMPLE.SWA

┌────────────────────────────────────────────────────┐
│ SWA HEADER                                         │
│ magic · format version · flags                     │
├────────────────────────────────────────────────────┤
│ METADATA                                           │
│ archive information · timestamps · attributes      │
├────────────────────────────────────────────────────┤
│ FILE TABLE                                         │
│ paths · sizes · offsets · properties               │
├────────────────────────────────────────────────────┤
│                                                    │
│                 COMPRESSED DATA                    │
│                                                    │
├────────────────────────────────────────────────────┤
│ INTEGRITY                                          │
│ hashes · validation                                │
└────────────────────────────────────────────────────┘
```

### `SW.A://ROADMAP`

```text
SWA FORMAT SPECIFICATION v1
            │
            ▼
GO REFERENCE LIBRARY
            │
            ▼
SWA CLI
            │
            ▼
PACK / UNPACK
            │
            ▼
ZSTD COMPRESSION
            │
            ▼
INTEGRITY VERIFICATION
            │
            ▼
OPTIONAL ENCRYPTION
```

`PROJECT = SW.A`

`FORMAT = SWA`

`EXTENSION = .swa`

---

# `05 // FUTURE`

## 🚑 `RETTCONNECT`

### A StumpfWorks Project

```text
┌─ PROJECT INFORMATION ────────────────────────┐
│ PROJECT   RettConnect                        │
│ PARENT    StumpfWorks                        │
│ DOMAIN    Medical & Emergency Technology     │
│ STATE     ○ FUTURE                           │
└──────────────────────────────────────────────┘
```

RettConnect is a future StumpfWorks project focused on digital tools for medical and emergency environments.

```text
                         RETTCONNECT
                              │
           ┌──────────────────┼──────────────────┐
           │                  │                  │
           ▼                  ▼                  ▼
        PATIENT            OPERATIONS         RESOURCES
           │                  │                  │
     Documentation        Coordination        Vehicles
     Medical Records      Medical Teams       Equipment
     Workflows            Deployments         Inventory
           │                  │                  │
           └──────────────────┼──────────────────┘
                              │
                              ▼
                          REPORTING
```

Potential areas include:

`PATIENT DOCUMENTATION`

`EVENT MEDICAL SERVICES`

`CHECKLISTS`

`TEAM COORDINATION`

`VEHICLES`

`EQUIPMENT`

`OPERATIONAL WORKFLOWS`

`REPORTING`

RettConnect isn't being rushed.

Before building a system that may eventually deal with sensitive medical information, the underlying architecture should be ready for it.

That's one reason `SW.FW`, security and the rest of the StumpfWorks foundation come first.

---

# `06 // LABS`

## 🧪 `SW.LABS`

```bash
$ tree ~/stumpfworks/labs

labs/
├── embedded/
│   ├── esp8266/
│   ├── esp32/
│   └── raspberry-pi/
│
├── hardware/
│   ├── rfid-nfc/
│   ├── sensors/
│   ├── relays/
│   └── controllers/
│
├── infrastructure/
│   ├── linux/
│   ├── networking/
│   ├── monitoring/
│   └── automation/
│
├── protocols/
│   └── experiments/
│
└── ideas/
    └── definitely-too-many/
```

Not everything needs a product name.

Sometimes I just want to connect a sensor.

Or control a relay.

Or build a protocol.

Or find out whether an idea that probably shouldn't work...

**works.**

Some experiments disappear.

Some become useful tools.

Some eventually become the next:

`SW.*`

---

# `07 // TOOLCHAIN`

<div align="center">

### `LANGUAGES`

![Go](https://img.shields.io/badge/GO-00ADD8?style=for-the-badge\&logo=go\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Bash](https://img.shields.io/badge/BASH-4EAA25?style=for-the-badge\&logo=gnubash\&logoColor=white)

<br>

### `APPLICATION`

![React](https://img.shields.io/badge/REACT-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/NEXT.JS-000000?style=for-the-badge\&logo=nextdotjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/NODE.JS-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)

<br>

### `INFRASTRUCTURE`

![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Proxmox](https://img.shields.io/badge/PROXMOX-E57000?style=for-the-badge\&logo=proxmox\&logoColor=white)

<br>

### `HARDWARE`

![Raspberry Pi](https://img.shields.io/badge/RASPBERRY_PI-A22846?style=for-the-badge\&logo=raspberrypi\&logoColor=white)
![Arduino](https://img.shields.io/badge/ARDUINO-00878F?style=for-the-badge\&logo=arduino\&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-111111?style=for-the-badge)
![ESP32](https://img.shields.io/badge/ESP32-111111?style=for-the-badge)

</div>

---

# `08 // GITHUB TELEMETRY`

<div align="center">

```text
ACTIVITY // PUBLIC REPOSITORIES // LANGUAGE DISTRIBUTION
```

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=TheRealHZL\&theme=tokyonight\&hide_border=true\&border_radius=10)](https://git.io/streak-stats)

<br>

![Profile Stats](https://github-readme-stats.vercel.app/api?username=TheRealHZL\&show_icons=true\&theme=tokyonight\&hide_border=true\&border_radius=10\&include_all_commits=true\&count_private=true)

<br>

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=TheRealHZL\&layout=compact\&theme=tokyonight\&hide_border=true\&border_radius=10)

</div>

---

# `09 // CURRENT ROUTE`

```text
                              NOW
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼
           SW.ID           SW.ACCESS           SW.FW
             │                 │                 │
             └─────────────────┼─────────────────┘
                               │
                               ▼
                       COMMON FOUNDATION
                               │
                               ▼
                             SW.A
                               │
                               ▼
                    MORE STUMPFWORKS SYSTEMS
                               │
                               ▼
                         RETTCONNECT
```

There isn't a finish line for StumpfWorks.

There is always another layer to understand.

Another system to build.

Another protocol to experiment with.

Another piece of hardware to connect.

---

# `10 // PHILOSOPHY`

```text
╔══════════════════════════════════════════════════════╗
║                                                      ║
║                     BUILD IT.                        ║
║                                                      ║
║                  UNDERSTAND IT.                      ║
║                                                      ║
║                      OWN IT.                         ║
║                                                      ║
╚══════════════════════════════════════════════════════╝
```

<div align="center">

### `STUMPFWORKS_`

**OPEN SOURCE / SELF-HOSTED / BUILT FROM THE GROUND UP**

<br>

`SOFTWARE` × `INFRASTRUCTURE` × `HARDWARE`

<br><br>

[![GitHub](https://img.shields.io/badge/GITHUB-TheRealHZL-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TheRealHZL)
[![StumpfWorks](https://img.shields.io/badge/STUMPFWORKS-ORGANIZATION-0969DA?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Stumpf-works)
[![Discord](https://img.shields.io/badge/DISCORD-CONNECT-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](https://discord.gg/rv2h8FrD)

<br><br>

<sub>Designed, built and occasionally over-engineered by MrHeiz97.</sub>

<br>

<sub>`STUMPFWORKS SYSTEM // END OF FILE`</sub>

</div>
