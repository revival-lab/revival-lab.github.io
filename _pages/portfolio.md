---
permalink: /portfolio/
title: Selected Work
toc: true
toc_sticky: true
excerpt: "_Client projects and selected open source contributions in scientific software, compilers, and embedded systems._"
header:
  overlay_image: /assets/images/blurry-rust.jpg
  overlay_filter: rgba(0, 50, 0, 0.7)
---
### Molecular Simulation

[Faunus](https://github.com/mlund/faunus) is a scientific software written in modern C++/Python for simulating
molecular systems at multiple length and time scales.
Over two decades we have kept up with the C++ standard and is now at C++20.
We have recently ported most of Faunus to Rust and [GPU-accelerated WASM](https://mlund.github.io/duello-web).

**Contribution:** Creator and development lead.
{: .notice--success}

{% include video id="mFOooBQE3mg" provider="youtube" %}


### Compiler Backend Development

[LLVM-MOS](https://github.com/llvm-mos) supports the MOS Technology 65xx series of microprocessors and enables C, C++, Rust compilers on a series of 8-bit computers.

**Contribution:** memory layout for the MEGA65 and Commander X16 targets; (dis)assembly for 65CE02 CPU derivatives.
See all PR's
[here](https://github.com/llvm-mos/llvm-mos/pulls?q=is%3Apr+author%3Amlund+) and
[here](https://github.com/llvm-mos/llvm-mos-sdk/pulls?q=is%3Apr+author%3Amlund+).
{: .notice--success}

{% include video id="iPX4ydAPaKo" provider="youtube" %}

### Ancient Plotting

[Xmgr](https://github.com/mlund/xmgr-resurrection) is an ancient but still popular GUI tool
for plotting scientific data. It was utterly abandoned until we resurrected the code base.

**Contribution:** CMake build system; bug fixes; and support for 64-bit systems; Macports recipe.
{: .notice--success}

{% include figure image_path="/assets/images/acegr.jpg" %}


### Embedded

#### Scientific instrumentation

Firmware and microservice design in Rust. Sensor control and on-device database management and exposure on local network.
Anonymous client, Sweden.

#### Hardware Abstraction Layers (HAL)

<i class="fab fa-rust"></i> Rust
[HAL for MOS Technology graphics and sound chips](https://github.com/mlund/mos-hardware) using memory-mapped I/O.
This includes FFI bindings to [mega65-libc](https://github.com/MEGA65/mega65-libc).

**Contribution:** Creator and development lead. Mega65-libc contributions [here](https://github.com/mega65/mega65-libc/pulls?q=author%3Amlund+).
{: .notice--success}

{% include video id="wifYmhIRAEs?start=2532" provider="youtube" %}

#### Rust on Espressif ESP Micro-controllers

We have made contributions to the [`esp-idf-hal`](https://crates.io/crates/esp-idf-hal)
crate for running Rust on Espressif's ESP family of micro-controllers.

**Contribution:** Refactoring of RGB color handling.
{: .notice--success}

#### Graphics Display Driver

We maintain a [library for display drivers](https://crates.io/crates/retro-display)
for graphics on extremely restricted systems using the `embedded-graphics` crate.

**Contribution:** Creator and development lead.
{: .notice--success}

{% include figure image_path="https://github.com/mlund/retro-display/raw/HEAD/assets/c64demo.png" %}

#### Hardware Remote Control via HTTP and Serial Communications

[Ultimate64](https://github.com/mlund/ultimate64) is a CLI for communicating with Ultimate 64/II+ hardware via HTTP requests.
[Matrix65](https://github.com/mlund/matrix65) is a modern text user-interface
([TUI](https://en.wikipedia.org/wiki/Text-based_user_interface))
for serial communication with the MEGA65 computer.
Both tools are written in Rust <i class="fab fa-rust"></i>.

**Contribution:** Creator and development lead.
{: .notice--success}

{% include video id="dUvXLtUUC-Y" provider="youtube" %}
