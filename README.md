# Miréio Trinley

Applied computer science student (B.Sc.) at HTWG Konstanz, sixth semester. From
September 2026 I am an exchange student at ENSEEIHT in Toulouse. I work on the
layer below the application: bare-metal C on microcontrollers, embedded Linux,
and what happens to timing once software meets real hardware. I am interested in
systems where being late counts the same as being wrong, and I would rather
answer a question with a measurement than with an argument.

## Looking for a Bachelor's thesis placement

I am looking for a Bachelor's thesis placement in France for spring 2027,
starting around February and running for five to six months. I will be applying
from October 2026. The topics below are the ones I would like to work on. If any
of them overlap with your team's work, I would be glad to hear from you.

Contact: mireio.trinley@htwg-konstanz.de

## Interests

- Real-time operating systems: schedulers, context switching, priority inversion
- Worst-case execution time analysis; measured timing versus analytical bounds
- Multicore interference: shared caches, memory bandwidth, partitioning and
  isolation for mixed-criticality workloads (CAST-32A / AMC 20-193)
- Embedded Linux: kernel configuration, Buildroot, cross toolchains, device drivers
- Deterministic networking for critical systems: TSN, AFDX, network calculus
- Hypervisors and virtualisation on embedded targets

## Public projects

- **Digital-Camera-Calibration** — Image sensor characterisation on raw captures:
  dark-frame and flat-field correction, noise analysis, defective-pixel repair.
- **Kairos** — An adaptive study planner: offline-capable PWA with a Node/SQLite
  backend. Included as evidence that I also finish and ship application software.

## University coursework, not publishable

The following was done as graded coursework at HTWG Konstanz. It lives in private
university repositories and contains material I did not write, so I cannot publish
it. I am listing it because it is where most of my systems experience comes from.

- **Embedded systems lab** — Kernel configuration and build for Raspberry Pi 4,
  Buildroot integration with an external package, cross-toolchain setup for
  aarch64, initramfs and BusyBox, QEMU smoke test wired into CI, serial console
  bring-up, and a character device exposing a hardware cycle counter.
- **Microcontroller programming** — Bare-metal C on an MSP430FR5729: clock tree
  and timer prescaler derivation, event-driven main loop with low-power mode,
  button debouncing as a state machine, and a non-blocking SPI driver written as
  a state machine with microsecond timing constraints.
- **Digital design** — VHDL on a Microsemi FPGA: two-flip-flop synchronisers with
  edge detection, a generic up/down counter, and a hex-to-seven-segment decoder.

Two projects that reproduce this kind of work from scratch, with published
measurements and a documented build, are currently in preparation.
