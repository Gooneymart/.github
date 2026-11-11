 <div align="center">

# ⚡ GOONEYMART

### Indigenous Semiconductor IP & Systems Engineering

**Gooneymart Silicon Sdn. Bhd.**  
Registration No. 202601046179 / 1708274-M

<p align="center">
  <strong>Deep-Tech Engineering from Sabah, Malaysia 🇲🇾</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Sabah%2C%20Malaysia-0f766e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-RISC--V-6b21a8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Engineering-Hardware--Software%20Co--Design-1d4ed8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Open%20Source-MPL--2.0-orange?style=for-the-badge" />
</p>

**We build specialized computing technology through the convergence of silicon architecture and software engineering.**

*Build Small. Think Deep. Go Beyond Silicon.*

</div>

---

## 🛰️ Who We Are

**Gooneymart Silicon Sdn. Bhd.** is a Sabah-based deep-tech engineering company developing specialized computing technologies at the intersection of **RISC-V, semiconductor IP, hardware–software co-design, and systems programming.**

We believe advanced semiconductor engineering should not be confined to traditional technology hubs.

From **Sabah, Malaysia**, we develop software-centric RISC-V instruction extensions, accelerator IP, and the supporting software infrastructure required to bring specialized computing architectures closer to practical deployment.

Our engineering approach extends beyond RTL development. We work across the entire technology stack:

- RISC-V instruction-set extensions and accelerator architecture.
- Synthesizable RTL and FPGA prototyping.
- Software reference models and hardware verification.
- Bare-metal firmware and low-level systems programming.
- Linux kernel integration and driver development.
- Runtime software, developer tooling, and process observability.

We are deliberately building a lean engineering organization focused on proprietary intellectual property, technical validation, and sustainable innovation.

> **World-class computing architecture can be engineered anywhere.**

Our philosophy is straightforward:

**Start with the objective. Remove unnecessary complexity. Engineer the solution. Verify the implementation.**

---

## 🧠 What We Build

Our core competency is **hardware–software co-design**.

Rather than treating silicon architecture and software infrastructure as separate engineering disciplines, we develop them as interconnected components of a specialized computing platform.

### Our Technology Stack

```text
                 GOONEYMART COMPUTING ECOSYSTEM

 ┌───────────────────────────────────────────────────────────┐
 │                  APPLICATIONS & WORKLOADS                 │
 ├───────────────────────────────────────────────────────────┤
 │              RUNTIME & USERSPACE SOFTWARE                 │
 │                gooney-mon / SDK / Runtime                  │
 ├───────────────────────────────────────────────────────────┤
 │             LINUX KERNEL & DRIVER INTEGRATION             │
 │                     gooney-ringzero                        │
 ├───────────────────────────────────────────────────────────┤
 │                  BARE-METAL FIRMWARE                      │
 │                     xzxt-firmware                          │
 ├───────────────────────────────────────────────────────────┤
 │              RISC-V ISA & CUSTOM EXTENSIONS               │
 │                       Albatross XZXT                       │
 ├───────────────────────────────────────────────────────────┤
 │             SOFTWARE REFERENCE & VALIDATION               │
 │                       gooney-emu                           │
 ├───────────────────────────────────────────────────────────┤
 │                 RTL & HARDWARE IMPLEMENTATION             │
 │                   Veryl / SystemVerilog                    │
 ├───────────────────────────────────────────────────────────┤
 │                  FPGA PROTOTYPING / ASIC                   │
 │                   SYNTHESIS & INTEGRATION                  │
 └───────────────────────────────────────────────────────────┘
```

This vertically integrated development model allows us to evaluate architectural decisions across software, instruction execution, RTL implementation, and system integration.

---

## ⚙️ Core Technology

### `Albatross XZXT` — Specialized RISC-V Extension IP

Our flagship development initiative explores software-centric RISC-V instruction extensions and accelerator IP for specialized computing workloads.

**Albatross XZXT** focuses on bridging the gap between established software ecosystems and emerging RISC-V computing platforms.

Its initial development direction investigates x86-to-RISC-V instruction translation through custom RISC-V execution extensions, combining hardware-assisted execution paths with complementary software runtime components.

The architecture is designed around:

- RISC-V CUSTOM-0 instruction extensions.
- Specialized instruction execution and translation operations.
- Hardware–software partitioning of execution responsibilities.
- RTL-based implementation and FPGA validation.
- Software reference models and runtime integration.

Our objective is to explore practical alternatives to conventional software-only translation approaches while preserving the ability to support established software workloads.

### `gooney-emu` — RISC-V Software Reference Emulator

A Rust-based RISC-V ISA simulation and development environment.

`gooney-emu` provides a software reference model for RISC-V instruction execution, custom extension development, and hardware/software validation.

Key development areas include:

- RV64I instruction simulation.
- Custom instruction extension support.
- Modular extension architecture.
- Execution tracing and workload testing.
- Reference-model validation against hardware implementations.
- Developer-facing TUI and command-line tooling.

It serves as an important part of our pre-silicon engineering workflow, enabling reproducible testing before hardware deployment.

### `gooney-ringzero` — Hardware Verification & Kernel Integration

A modular Rust-based design-verification and hardware/software co-simulation toolkit.

`gooney-ringzero` is designed to bridge RTL verification, simulation environments, and Linux kernel-space integration.

Its engineering components include:

- Hardware verification infrastructure.
- Verilator-based simulation and co-simulation.
- Automated driver-generation tooling.
- Linux DKMS configuration auditing.
- Kernel-space validation workflows.
- Reproducible testing and integration utilities.

The objective is to reduce the engineering friction between custom hardware IP and its supporting Linux software ecosystem.

### `gooney-mon` — Linux Process Observability

A high-precision, Rust-native process monitoring and telemetry dashboard for Linux.

Unlike conventional system-wide monitoring utilities, `gooney-mon` emphasizes deep inspection of individual processes and complex userspace runtimes.

Its monitoring architecture explores:

- Thread and worker topology inspection.
- Process memory and RSS profiling.
- Linux procfs and memory-map analysis.
- Cgroup v2 resource monitoring.
- CPU throttling statistics.
- Pressure Stall Information (PSI).
- Target-specific monitoring through PID and systemd service resolution.

It is designed to provide meaningful operational visibility into complex systems software without introducing unnecessary monitoring overhead.

### `xzxt-firmware` — Bare-Metal Systems Software

A lightweight Rust-based firmware environment for custom RISC-V instruction extensions.

`xzxt-firmware` provides a low-level execution and validation environment for exercising custom instructions directly within a bare-metal RISC-V environment.

Its development focuses on:

- RV64 bare-metal execution.
- Custom instruction integration.
- Low-level hardware interaction.
- Reference-model validation.
- Firmware-level functional testing.

### Veryl / SystemVerilog — RTL Engineering

We utilize modern hardware description language workflows to translate architectural specifications into synthesizable hardware implementations.

Our RTL engineering activities include:

- Custom RISC-V instruction execution logic.
- Arithmetic and logical execution paths.
- Instruction decoding and control logic.
- Pipeline and hazard management.
- Hardware/software interface design.
- FPGA synthesis and prototyping.

The objective is to develop specialized hardware IP supported by a reproducible software verification environment.

---

## 🔬 Engineering Philosophy

### 01. Software-Centric Silicon

We believe hardware architecture should be developed with software behavior and ecosystem requirements in mind.

Our focus is not simply building another processor core. We investigate specialized instruction extensions and accelerator IP that address specific computing challenges through hardware–software collaboration.

### 02. Hardware–Software Co-Design

The instruction architecture, RTL, emulator, firmware, kernel drivers, runtime, and verification tools must evolve together.

We design the software infrastructure alongside the hardware implementation rather than treating it as an afterthought.

### 03. Verification First

Architectural assumptions must be demonstrable.

We prioritize software reference models, reproducible test vectors, RTL simulation, hardware validation, and systematic verification before advancing toward physical implementation.

### 04. Open Engineering

We embrace open standards, transparent development practices, and open-source tooling wherever commercially and technically appropriate.

Our goal is to contribute useful engineering infrastructure while maintaining the ability to commercialize proprietary semiconductor IP.

### 05. Lean & Sustainable Innovation

We believe meaningful semiconductor innovation does not require an unnecessarily large organization.

Gooneymart is structured around focused R&D, reusable engineering infrastructure, specialized intellectual property, and sustainable technical development.

---

## 🧪 Technology Development Roadmap

Our development strategy follows a progressive validation model, moving from software and RTL verification toward FPGA-based system integration and commercial IP readiness.

```text
       SOFTWARE & RTL VALIDATION
                  TRL 4
                    │
                    ▼
          FPGA PROTOTYPING
                  TRL 5
                    │
                    ▼
        HARDWARE VALIDATION
                  TRL 6
                    │
                    ▼
       SYSTEM INTEGRATION & PILOTS
                  TRL 7
                    │
                    ▼
        COMMERCIAL QUALIFICATION
               TRL 8–9
```

| Stage | Engineering Focus |
|---|---|
| TRL 4 | Software reference validation, RTL simulation, and co-simulation |
| TRL 5 | FPGA synthesis, prototyping, and experimental hardware validation |
| TRL 6 | Integrated hardware/software demonstrator and relevant-environment validation |
| TRL 7 | System-level demonstration and pilot integration |
| TRL 8–9 | Qualification, deployment, and commercial readiness |

*Technology readiness levels are development targets. Actual advancement depends on documented validation evidence and the applicable TRL assessment criteria.*

---

## 🌏 Why Sabah?

Malaysia has an increasingly important role in the global semiconductor industry.

While much of the country's established semiconductor ecosystem is concentrated in Peninsular Malaysia, we believe East Malaysia also has opportunities to contribute to the next generation of computing technology.

Gooneymart Silicon Sdn. Bhd. was established in Sabah with a clear ambition:

**To demonstrate that specialized semiconductor IP, RISC-V architecture, and advanced systems engineering can originate from East Malaysia.**

Our location is not a limitation on our engineering ambitions.

We aim to participate in the broader Malaysian and international semiconductor ecosystem through:

- Research and development collaborations.
- FPGA and RTL engineering partnerships.
- University and research institution engagement.
- Hardware validation and integration partnerships.
- International RISC-V ecosystem participation.
- Commercial semiconductor IP development.

We intend to grow through engineering capability, validated technology, and meaningful partnerships.

---

## 📦 Open-Source Engineering Projects

Our GitHub organization hosts a growing collection of engineering tools and supporting infrastructure developed alongside our semiconductor IP initiatives.

| Project | Description | Primary Technology |
|---|---|---|
| 🧠 **gooney-emu** | RISC-V software reference emulator and custom extension validation | Rust |
| 🛡️ **gooney-ringzero** | Modular DV, co-simulation, and kernel integration toolkit | Rust / Linux |
| 📊 **gooney-mon** | Linux process monitoring and runtime telemetry dashboard | Rust / Ratatui |
| ⚙️ **xzxt-firmware** | Bare-metal firmware for custom RISC-V extensions | Rust |
| 🧩 **Albatross XZXT** | Specialized RISC-V instruction extension and accelerator IP | SystemVerilog / Rust |
| 🔬 **Gooneymart RTL** | Synthesizable hardware implementation and verification | Veryl / SystemVerilog |
| 🛠️ **Gooney Tooling** | Developer utilities, testing infrastructure, and integration tools | Rust |

Explore our repositories to follow ongoing engineering development.

---

## 🛠️ Technology & Engineering Tools

Our development ecosystem incorporates modern systems programming, hardware design, and verification technologies.

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,c,linux,bash,git,github" />
</p>

**Hardware & Architecture**
- RISC-V ISA
- Veryl
- SystemVerilog
- FPGA prototyping
- RTL simulation and synthesis

**Systems Software**
- Rust
- Linux kernel development
- Bare-metal firmware
- DKMS
- Userspace runtime development

**Verification & Tooling**
- Verilator
- Cocotb
- Hardware/software co-simulation
- Golden-reference validation
- Automated design verification

---

## 🤝 Commercial & Technical Partnerships

**Gooneymart Silicon Sdn. Bhd.** develops specialized semiconductor IP and supporting engineering infrastructure.

We welcome opportunities for collaboration in:

- RISC-V instruction extension development.
- Custom accelerator and specialized compute IP.
- Hardware–software co-design.
- RTL development and FPGA prototyping.
- Semiconductor IP integration.
- Firmware, runtime, and Linux driver engineering.
- Hardware verification and validation.
- Research and technology demonstration.

We are particularly interested in collaborations with semiconductor companies, research institutions, universities, FPGA engineering teams, and organizations exploring open computing architectures.

### Commercial Engagement

For proprietary IP licensing, custom architecture development, ASIC integration, engineering services, or enterprise support:

**📧 gooneymart@gmail.com**

**GitHub:** [github.com/gooneymart](https://github.com/gooneymart)

---

## 📄 Licensing & Intellectual Property

Gooneymart adopts a hybrid intellectual property strategy.

Selected developer tools, validation frameworks, and supporting software are released under open-source licenses, including the Mozilla Public License 2.0 (MPL-2.0).

Proprietary semiconductor IP, architectural implementations, and commercial deliverables may be subject to separate licensing and contractual agreements.

Please refer to the individual repository's `LICENSE` file for its applicable licensing terms.

For commercial licensing and IP inquiries, contact Gooneymart directly.

---

<div align="center">

# ⚡ GOONEYMART SILICON

### Build Small. Think Deep. Go Beyond Silicon.

**Engineered in Sabah, Malaysia 🇲🇾**

<sub>Gooneymart Silicon Sdn. Bhd. · Registration No. 202601046179 / 1708274-M</sub>

</div>
