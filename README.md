# Hi, I'm Dan Vladoiu 👋

Security researcher & builder — privacy-first defensive tooling for Linux.

## What I build

### [VIGIL](https://github.com/infinit3l00p/vigil) — eBPF-native EDR
Endpoint Detection and Response with detection logic living in the kernel. Cross-view integrity (kernel vs `/proc`), temporal anomaly detection, self-integrity — built to resist the EvilEDR attack class. Ships with a rootkit simulator so every claim is reproducible.

![VIGIL Dashboard](https://raw.githubusercontent.com/infinit3l00p/vigil/master/docs/screenshots/dashboard.png)

### [RingWatch](https://github.com/infinit3l00p/ringwatch) — Real-time Ring -3 Monitor
Live Intel ME/CSME activity monitoring — HECI bus, firmware registers, MEI clients, PMT telemetry. Read-only, zero risk. One of the few public Ring-3 monitors in existence.

![RingWatch](https://raw.githubusercontent.com/infinit3l00p/ringwatch/master/docs/screenshots/dashboard-full.png)

### [PITBULL](https://github.com/infinit3l00p/pitbull) — Autonomous Digital Explorer
Threat intelligence platform with honeypots, deception layers, Suricata IDS integration, and a Neo4j-backed knowledge graph. It explores, maps, and remembers.

![PITBULL](https://raw.githubusercontent.com/infinit3l00p/pitbull/master/docs/screenshots/dashboard.png)

## Focus areas

- eBPF-based kernel detection & integrity
- Intel ME / firmware-level security (Ring -3)
- Anti-rootkit techniques (cross-view, temporal, lineage)
- Privacy-first architecture: E2E encryption, minimal attack surface

## Currently building

- **DoseStream** — a medication reminder app with family circles, E2E-encrypted sync, and no data harvesting (launching soon)

---

*MIT for userspace • GPL v2 for kernel eBPF (as the kernel demands)*