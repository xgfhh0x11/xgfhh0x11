# xgfhh0x11

<!-- =========================================================
     PERSONAL STATEMENT — replace this block with your own text.
     Neutral draft below; edit freely before the HBO reviewers read it.
     ========================================================= -->
Low-level security researcher focused on Windows kernel internals,
hardware-assisted mitigations, and microarchitectural side channels.

> _TODO: 2-3 sentences — who you are, what drives this work, and your
> motivation for the NL HBO programme._

---

## Portfolio

Each project ships honest documentation: what actually runs, what is a
stub or dead code, and what a result does and does not prove.

**Kernel security — Windows**
- [KMTO](https://github.com/xgfhh0x11/KMTO) — mitigation telemetry observatory (SMEP/SMAP/PAC/CFG/KASLR/KPTI), live CR4/MSR handshake
- [SILM](https://github.com/xgfhh0x11/SILM) — per-CPU ISR/DPC latency monitor with online change-point anomaly detection
- [KSIF](https://github.com/xgfhh0x11/KSIF) — semantic-integrity framework expressing the invariants DKOM-class attacks violate
- [KRzr](https://github.com/xgfhh0x11/KRzr) — kernel race-condition fuzzer (WDM driver + Python client)
- [Kernel-levelHoneypot](https://github.com/xgfhh0x11/Kernel-levelHoneypot) — six-layer kernel-mode deception framework
- [SYM_Triage](https://github.com/xgfhh0x11/SYM_Triage) — static + pattern IOCTL triage, WinRing0.sys BYOVD case study

**Hardware / microarchitecture**
- [CTPhys](https://github.com/xgfhh0x11/CTPhys) — physical constant-time timing-jitter experiment on x86
- [SPIFault](https://github.com/xgfhh0x11/SPIFault) — SPI-flash fault-injection campaign description framework

**Virtualization & networking**
- [HGS-Analyzer](https://github.com/xgfhh0x11/HGS-Analyzer) — Hyper-V Host Guardian Service attestation-path analyzer
- [StealthL4Guard](https://github.com/xgfhh0x11/StealthL4Guard) — silent L4 DDoS-defense pipeline (XDP -> TC/eBPF -> nftables -> HAProxy)

**Other**
- [ObserverRealityEngine](https://github.com/xgfhh0x11/ObserverRealityEngine) — observation-driven state-machine library (Python)
