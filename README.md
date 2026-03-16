# 👋 Hi, I'm Athan S Maliakkal

**Physics Undergraduate • Systems Architect • OS Developer**

I build the **floor that software walks on**.

While most developers build applications, I'm focused on the layer beneath them—designing operating system architecture and low-level infrastructure.

My main project is **Stardust OS**, a capability-secure, multicore microkernel written in Rust that explores new approaches to **hardware isolation, secure execution, and high-density cloud computing**.

I approach systems engineering with **physics-driven reasoning**: understanding the fundamental constraints of hardware and building elegant solutions on top of them.

---

# 🌌 Featured Project — Stardust OS

*A 64-bit, SMP-aware microkernel designed for secure and scalable compute infrastructure.*

### ⚡ Multicore Architecture

* Bootstrapping and synchronizing **8 CPU cores**
* Advanced **APIC / IO-APIC interrupt routing**
* SMP-aware kernel scheduling foundation

### 🛡️ Capability Security Model

* Implemented a **Capability Derivation Tree (CDT)**
* Hardware-enforced isolation using **IOMMU sandboxing**
* Near **zero-trust execution model**

### 🚀 Modern Userland

* **WebAssembly runtime** for safe user applications
* Sub-20ms cold-starts for potential **serverless workloads**

### 🔌 Bare-Metal Hardware Work

* Intel graphics display pipeline experimentation
* Custom **PS/2 HID drivers**
* Low-level Rust drivers interacting directly with hardware

---

# 🔬 Current Research & Development

**WASI Runtime**

* Implementing WASI support to run standard **Rust / C++ applications**

**Kernel Build Orchestration**

* Custom Python pipeline for automated:

  * Bare-metal builds
  * QEMU deployments
  * Debugging workflows

**Graphics Subsystem**

* Investigating Intel GPU initialization
* Building a low-latency display server architecture

---

# 💻 Technology Stack

### Systems Programming

Rust (nightly) • C++ • x86_64 Assembly • NASM

### Architecture & Hardware

UEFI / OVMF • SMP • Paging / MMU • ACPI • APIC • IOMMU

### Tooling

Python • QEMU • GDB • Git

### High-Level Experiments

WebAssembly (WASM / WASI) • Flutter (hardware instrumentation tools)

---

# 🎯 Supporting the Project

Stardust OS is an independent research project exploring new approaches to **secure kernel architecture, hardware isolation, and modern userland design**.

Much of the work involves deep low-level experimentation with hardware, virtualization environments, and debugging infrastructure.

If you enjoy the technical breakdowns or want to support the development of **independent operating system research**, consider sponsoring the project.

Your support helps improve the development setup and allows more time to push the system further.

**Sponsor:**
https://github.com/sponsors/athansmaliakkal/

**LinkedIn:**
https://www.linkedin.com/in/athansmaliakkal/

---

> *"Physics explains the universe.*
> *Systems programming controls the machine."*


> *"Physics explains the universe.
> Systems programming control
