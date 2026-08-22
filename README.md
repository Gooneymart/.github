<div align="center">

# ⚡ Gooneymart

### **Deep-Tech Engineering from Sabah, Malaysia**

**Zero-Overhead RISC-V Compute IP · Hardware–Software Co-Design · Silicon Architecture**

[![Location](https://img.shields.io/badge/Based_in-Sabah%2C_Malaysia-0f766e?style=for-the-badge)](#)
[![Architecture](https://img.shields.io/badge/Architecture-RISC--V-6b21a8?style=for-the-badge)](#)
[![Focus](https://img.shields.io/badge/Focus-Deep--Tech-111827?style=for-the-badge)](#)
[![Open Source](https://img.shields.io/badge/Open%20Source-MPL--2.0-orange?style=for-the-badge)](#)

**We build the computing architecture we want to see in the world.**

</div>

---

## 🛰️ Who We Are

**Gooneymart™ is a Sabah-based deep-tech company building indigenous computing technology at the intersection of silicon architecture, RISC-V, hardware design, and low-level software.**

We believe advanced semiconductor engineering does not have to originate from traditional technology hubs.

From **Sabah, Malaysia**, we are building the foundations for modular, transparent, and highly efficient computing systems — from instruction-set architecture and RTL, all the way to firmware, verification, and eventually physical silicon.

> **World-class silicon architecture can be engineered anywhere.**

Our approach is deliberately different:

**Start with the objective. Remove the bloat. Build the technology. Verify it rigorously.**

---

## 🧠 What We Build

Gooneymart focuses on **hardware–software co-design**, developing the entire computing stack rather than treating hardware and software as isolated disciplines.

```text
                    GOONEYMart TECHNOLOGY STACK

 ┌─────────────────────────────────────────────────────────┐
 │                  Applications / Runtime                 │
 ├─────────────────────────────────────────────────────────┤
 │                 User-Space Software                     │
 ├─────────────────────────────────────────────────────────┤
 │              DKMS / Runtime Infrastructure              │
 ├─────────────────────────────────────────────────────────┤
 │                 xzxt-firmware                            │
 │              Bare-Metal Rust / C                        │
 ├─────────────────────────────────────────────────────────┤
 │                  RISC-V ISA                             │
 │              Custom xzxt Extensions                     │
 ├─────────────────────────────────────────────────────────┤
 │              gooney-emu                                 │
 │       Cycle-Accurate Reference / Validation             │
 ├─────────────────────────────────────────────────────────┤
 │              Veryl / SystemVerilog                       │
 │                 RTL / Compute Core                     │
 ├─────────────────────────────────────────────────────────┤
 │                    FPGA / ASIC                           │
 │                Physical Silicon                         │
 └─────────────────────────────────────────────────────────┘
```

---

## ⚙️ Core Technology

### `xzxt`

A custom **RISC-V instruction-set extension architecture** designed for specialized computation.

The goal is simple:

> **Move specialized workloads closer to the machine without unnecessary architectural overhead.**

Our extension work explores domain-specific instruction design, custom execution paths, and tight integration between ISA, RTL, emulator, and firmware.

---

### `gooney-emu`

Our **Rust-based, cycle-accurate reference emulator and validation engine**.

`gooney-emu` acts as the software-side golden reference for our hardware architecture.

It enables us to:

* Model custom RISC-V instructions
* Validate CPU behavior
* Compare software execution against RTL
* Detect hardware/software divergence
* Develop extensions before physical hardware exists
* Build reproducible verification workflows

The objective is straightforward:

**If the emulator says it should happen, the hardware should do exactly the same thing.**

---

### `xzxt-firmware`

A lightweight **bare-metal Rust/C firmware environment** designed to execute directly on custom RISC-V compute architectures.

No unnecessary operating-system layers.

No legacy software assumptions.

Just:

```text
Boot
 ↓
Firmware
 ↓
CPU
 ↓
Custom Instructions
 ↓
Hardware
```

---

### `Veryl / SystemVerilog`

We use modern HDL workflows to translate architectural ideas into synthesizable RTL.

Our hardware development stack is designed around:

* Modular RTL
* RISC-V compatibility
* Custom instruction execution
* Simulation
* Formal verification
* FPGA prototyping
* Future ASIC integration

---

## 🔬 Our Engineering Philosophy

### **Zero Overhead**

We aggressively question unnecessary layers between software intent and physical execution.

### **Open Architecture**

We build around open standards and transparent engineering wherever possible.

### **Hardware–Software Co-Design**

The ISA, emulator, RTL, firmware, and runtime must evolve together.

### **Verification First**

We do not want architecture that merely *looks correct*.

We want architecture that can be **demonstrated, reproduced, compared, and verified**.

### **Build From Sabah**

Geography should not determine who is allowed to build advanced technology.

Gooneymart exists to demonstrate that sophisticated semiconductor architecture and systems engineering can be developed from **East Malaysia**.

---

## 🧪 Current Technology Roadmap

Our development follows a progression from software validation toward physical silicon.

```text
TRL 4
 │
 │  Simulation & Co-Simulation
 │  ├── xzxt ISA
 │  ├── gooney-emu
 │  ├── Veryl RTL
 │  └── Zero-Divergence Validation
 │
 ▼
TRL 5
 │
 │  FPGA Prototyping
 │  ├── Physical RTL execution
 │  ├── Synthesis
 │  ├── Timing analysis
 │  └── Hardware debugging
 │
 ▼
TRL 6
 │
 │  Compliance & System Integration
 │  ├── RISC-V compliance
 │  ├── Runtime infrastructure
 │  ├── DKMS
 │  └── Integration tooling
 │
 ▼
TRL 7
 │
 │  Commercial IP
 │  ├── Production-ready documentation
 │  ├── Verification infrastructure
 │  ├── Integration package
 │  └── Semiconductor licensing
```

Our company profile identifies the foundational validation stage as **TRL 4**, with the current engineering focus on transitioning toward **TRL 5 physical FPGA prototyping**.

---

## 🌏 Why Sabah?

The semiconductor industry is becoming increasingly important to Malaysia's technological future.

But advanced computing should not be concentrated exclusively in Kuala Lumpur, Penang, Singapore, Silicon Valley, or other established technology centers.

**Sabah can build too.**

Gooneymart is an experiment in proving exactly that.

We want to contribute to a future where engineers in East Malaysia can work on:

* CPU architecture
* RISC-V
* FPGA
* ASIC design
* semiconductor IP
* embedded systems
* hardware verification
* low-level systems software
* hardware acceleration

Our company profile explicitly positions Gooneymart as a Sabah-based effort to develop indigenous compute IP and demonstrate that high-end hardware/software co-design can be engineered in East Malaysia.

---

## 🌐 Open Source Meets Commercial IP

Gooneymart follows a **hybrid technology model**.

Open-source projects provide transparency, developer access, experimentation, and verification.

Commercial technology can provide specialized semiconductor IP, integration, and engineering services.

```text
                 GOONEYMart ECOSYSTEM

                      ┌───────────┐
                      │   RISC-V  │
                      └─────┬─────┘
                            │
                 ┌──────────┴──────────┐
                 │                     │
            OPEN SOURCE          COMMERCIAL IP
                 │                     │
        ┌────────┴────────┐     ┌──────┴──────┐
        │                 │     │             │
    gooney-emu       xzxt-firmware  xzxt Core   Integration
        │                 │     │             │
        └────────┬────────┘     └──────┬──────┘
                 │                     │
                 └──────────┬──────────┘
                            │
                      PHYSICAL SILICON
```

Our development philosophy is to maintain an auditable verification path from RTL through emulator and software tooling, while commercializing semiconductor IP through licensing and integration.

---

## 📦 Projects

| Project                | Description                                                                       |
| ---------------------- | --------------------------------------------------------------------------------- |
| 🧠 **gooney-emu**      | Cycle-accurate RISC-V emulator and hardware/software divergence validation engine |
| ⚙️ **xzxt-firmware**   | Bare-metal Rust/C firmware for custom RISC-V extensions                           |
| 🔬 **xzxt**            | Custom RISC-V instruction-set extension architecture                              |
| 🧩 **Gooneymart RTL**  | Veryl/SystemVerilog compute-core architecture                                     |
| 🛠️ **Gooney Tooling** | Developer, verification, and integration tools                                    |

> Individual repositories may evolve independently as the architecture matures.

---

## 🛠️ Technology

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square\&logo=c\&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square)
![Veryl](https://img.shields.io/badge/Veryl-HDL-blue?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-RTL-green?style=flat-square)
![FPGA](https://img.shields.io/badge/FPGA-Prototyping-purple?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-Engineering-black?style=flat-square\&logo=linux)

</div>

---

## 🚀 Where We're Going

Our long-term objective is not simply to create another emulator or another RISC-V core.

We are building toward a **complete, independently developed compute architecture ecosystem**.

```text
       ARCHITECTURE
             │
             ▼
        CUSTOM ISA
             │
             ▼
            RTL
             │
             ▼
        VERIFICATION
             │
             ▼
        FPGA PROTOTYPE
             │
             ▼
        SYSTEM SOFTWARE
             │
             ▼
        COMMERCIAL IP
             │
             ▼
          SILICON
```

The eventual objective is a commercially licensable semiconductor IP package capable of integration into third-party RISC-V SoC designs.

---

## 🤝 Collaborate With Us

We're interested in connecting with people and organizations working on:

* RISC-V
* CPU architecture
* FPGA
* ASIC
* Semiconductor IP
* Hardware verification
* Embedded systems
* Rust
* Low-level systems
* Hardware acceleration
* Academic research
* Deep-tech commercialization

Whether you're an engineer, researcher, university, startup, semiconductor company, or simply someone who enjoys breaking computers at the instruction level:

**You're welcome here.**

---

## 📡 Commercial & Technical Partnerships

Gooneymart's technology roadmap includes semiconductor IP licensing, custom instruction-extension co-design, ASIC integration, and specialized engineering support.

For commercial licensing, proprietary ASIC integration, custom architecture development, or technical partnerships:

**📧 [gooneymart@gmail.com](mailto:gooneymart@gmail.com)**

---

## 🌴 Built in Sabah. Designed for the World.

We are not trying to imitate Silicon Valley.

We are not trying to become another legacy semiconductor company.

We're building something smaller, sharper, more transparent, and fundamentally engineering-driven.

From **Sabah, Malaysia**, we're starting at the instruction level and working our way toward silicon.

> ### **The next generation of computing doesn't have to come from somewhere else.**
>
> ### **We can build it here.**

<br>

<div align="center">

**Gooneymart™**

*Deep-Tech Engineering · RISC-V · Silicon Architecture*

**Sabah, Malaysia 🇲🇾**

</div>

---

<div align="center">

### ⚡ Build Small. Think Deep. Go Beyond Silicon.

</div>

