# xgfhh0x11

Low-level security researcher focused on Windows kernel internals,
hardware-assisted mitigations, and microarchitectural side channels.
My work also draws on analytic philosophy, structural and discrete
mathematics, and formal methods — in particular the formal verification
of formal and low-level systems.

---

## Portfolio

Each project ships honest documentation: what actually runs, what is a
stub or dead code, and what a result does and does not prove.

**Formal methods & verification**
- [extp-paper](https://github.com/xgfhh0x11/extp-paper) — EXTp: a soundness theorem for counterfactual exploit replay on formally verified microkernels (seL4), with Isabelle/HOL mechanization
- [extp-artifact](https://github.com/xgfhh0x11/extp-artifact) — mechanization, measurements, and boot images backing the EXTp paper
- [verifierloop](https://github.com/xgfhh0x11/verifierloop) — eBPF verifier differential-testing lab: two oracles, a subsumption model + calibration, held-out classification study

**Kernel security — Windows**
- [KMTO](https://github.com/xgfhh0x11/KMTO) — mitigation telemetry observatory (SMEP/SMAP/PAC/CFG/KASLR/KPTI), live CR4/MSR handshake
- [SILM](https://github.com/xgfhh0x11/SILM) — per-CPU ISR/DPC latency monitor with online change-point anomaly detection
- [KSIF](https://github.com/xgfhh0x11/KSIF) — semantic-integrity framework expressing the invariants DKOM-class attacks violate
- [KRzr](https://github.com/xgfhh0x11/KRzr) — kernel race-condition fuzzer (WDM driver + Python client)
- [Kernel-levelHoneypot](https://github.com/xgfhh0x11/Kernel-levelHoneypot) — six-layer kernel-mode deception framework
- [SYM_Triage](https://github.com/xgfhh0x11/SYM_Triage) — static + pattern IOCTL triage, WinRing0.sys BYOVD case study

**Decision intelligence & attack-surface systems**
- [Tiefenriss](https://github.com/xgfhh0x11/Tiefenriss) — sealed exploitability-value core for low-level attack surfaces; honest about its central negative result
- [Prozessfall](https://github.com/xgfhh0x11/Prozessfall) — ambient attack-surface graph organ (persistent Rust daemon + Python sidecars + sigma.js UI)

**Hardware / microarchitecture**
- [CTPhys](https://github.com/xgfhh0x11/CTPhys) — physical constant-time timing-jitter experiment on x86
- [SPIFault](https://github.com/xgfhh0x11/SPIFault) — SPI-flash fault-injection campaign description framework

**Virtualization & networking**
- [HGS-Analyzer](https://github.com/xgfhh0x11/HGS-Analyzer) — Hyper-V Host Guardian Service attestation-path analyzer
- [StealthL4Guard](https://github.com/xgfhh0x11/StealthL4Guard) — silent L4 DDoS-defense pipeline (XDP -> TC/eBPF -> nftables -> HAProxy)

**Writeups**
- [security-writeups](https://github.com/xgfhh0x11/security-writeups) — 28 long-form technical writeups: hypervisor/VMX internals, Windows & Linux kernel exploitation, CVE analysis, and microarchitecture

**Other**
- [ObserverRealityEngine](https://github.com/xgfhh0x11/ObserverRealityEngine) — observation-driven state-machine library (Python)
