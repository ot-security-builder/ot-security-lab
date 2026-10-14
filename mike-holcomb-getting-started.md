# Notes: Getting Started with Industrial Cyber for IT Pros

**Source:** Mike Holcomb (GRID, ISA 62443), *Getting Started in Industrial (ICS/OT) Cyber Security — For IT Cybersecurity Professionals*, v2023.1  
**Local PDF:** [`resources/Getting Started with Industrial Cyber for IT Pros 2023.1.pdf`](../resources/Getting%20Started%20with%20Industrial%20Cyber%20for%20IT%20Pros%202023.1.pdf)  
**Upstream (free):** [GitHub blob — utilsec/Getting_Started_with_ICS](https://github.com/utilsec/Getting_Started_with_ICS/blob/main/Getting%20Started%20with%20Industrial%20Cyber%20for%20IT%20Pros%202023.1.pdf)

> Personal study notes for the OT transition. Not a substitute for the PDF. Copyright remains with the author.

---

## Before you start (Holcomb's tips)

1. **Take your time** — ICS/OT means control systems *and* sector-specific engineering; it will take time.
2. **Expect heavy research** — new acronyms and physical-process concepts; look them up as you go.
3. **Lean on the community** — ICS/OT people generally want to help protect environments that move the world.

Mindset: threats to OT are no longer only nation-states. Ransomware groups, hacktivists, and lone operators matter. **Not if — when.**

---

## Abbreviated history of major ICS/OT events

| Year | Event | Takeaway |
|------|--------|----------|
| **2003** | **Davis-Besse** (nuclear plant) hit by SQL Slammer via an unauthorized vendor connection; thought to be air-gapped | "Air gap" claims fail when vendors dial in; nuclear OT can be reached from IT/Internet paths |
| **2010** | **Stuxnet** — first widely known malware purpose-built for ICS; damaged Iranian centrifuges | Cyber can cause kinetic damage; launched a cyber arms race |
| **2015–2016** | **Ukrainian blackouts** — Russian actors hit power facilities (at night, in winter); related activity continues in the Russia–Ukraine war | Grid disruption is a proven, repeatable adversary playbook |
| **2017** | **TRISIS / Triton** — SIS (safety instrumented system) at a Middle East petrochemical plant compromised | Targeting SIS implies intent to cause physical harm / explosion, not just data theft |
| **2021** | **Colonial Pipeline** — IT ransomware → OT pipeline ops taken offline; largest US gasoline pipeline down ~10 days | IT compromise can force OT shutdown even without a plant-floor exploit |

Most OT incidents are never disclosed publicly — this list is the tip of the iceberg.

---

## Ten steps to getting started (for IT cyber pros)

### 1. Learn to think like an engineer
Shift from "CIA triad / servers / packets" to **how the plant actually runs**: safety of people first, what keeps the process running, and a common language between IT and OT. Every site is different (power ≠ refinery ≠ discrete manufacturing) — research *that* environment's design, ops, and maintenance before you can know what to protect.

**Resources Holcomb points to:** sector videos (critical infrastructure overview, chemical eng, hydropower, manufacturing, nuclear, rail); "Think Like an Engineer" article; free MIT OCW engineering intros.

### 2. Understand industrial control basics
Build a mental model of PLCs, RTUs, IEDs, DCS, SCADA, HMI, SIS, MES, BMS, IACS, CPS, OT — and how they connect. Acronyms feel overwhelming at first; they felt the same when you first learned TCP/UDP/OSI.

**Starter resources:** ICS/OT books and podcasts (see lists below).

### 3. Explore training options for learning
Mix free/public (CISA ICS courses, vendor docs, Capture-the-flag / labs) with structured paths (ISA/IEC 62443 certificate, vendor academies). Prefer hands-on over slide-only.

### 4. Learn the standards and regulations
Know the map: **ISA/IEC 62443**, **NIST SP 800-82**, sector rules (e.g. **NERC CIP** for bulk power), and local law (e.g. Canadian **Bill C-8** for critical cyber systems). Standards tell you *what good looks like*; regs tell you *what is required*.

### 5. Gain hands-on experience
Home lab (soft PLC, Modbus, segmentation), CTFs, volunteer / side projects, or shadowing plant work. Reading alone is not enough.

### 6. Network with the community
Meetups (BSides, ISA sections), discreet outreach, conferences. The community is an ally — use transition email / separate identity if career moves must stay quiet.

### 7. Stay current
Threat reports, ICS advisories (CISA, vendor PSIRTs), podcasts, blogs. OT threat landscape moves quickly.

### 8. Find an experienced mentor
Someone who has lived plant-floor constraints (availability, safety, change freezes) beats pure IT advice.

### 9. Build relevant soft skills
Translate risk for operators and engineers; listen; don't "IT-ify" a plant. Common ground with OT folks is intentional work.

### 10. Get certified
Credentials that signal OT seriousness (e.g. **ISA/IEC 62443 Cybersecurity Fundamentals Specialist**). Treat certs as complement to lab + portfolio, not a substitute.

---

## Holcomb's recommended books (starter list)

1. *Sandworm* — Andy Greenberg  
2. *Hacking Exposed Industrial Control Systems* — Bodungen et al.  
3. *Countdown to Zero Day* — Kim Zetter  
4. *Industrial Network Security* — Knapp & Langill  
5. *Industrial Automation and Control Systems Security Principles* — Krutz  
6. *Industrial Cybersecurity* — Pascal Ackerman  

## Holcomb's favorite ICS/OT podcasts (as of v2023.1)

- Control Loop (CyberWire)  
- Unsolicited Response  
- The (CS)²AI Podcast Show  
- The Industrial Security Podcast (Industrial Defender)  
- The PrOTect OT Cybersecurity Podcast (Waterfall)  

---

## Tie-in to this repo / roadmap

| Holcomb step | This lab / transition plan |
|--------------|----------------------------|
| Think like an engineer | Purdue mapping, plant-tour / integrator chats |
| Control basics | OpenPLC, HMI, Modbus/DNP3/OPC UA pcaps |
| Training | CISA 100W / 210W series |
| Standards | NIST 800-82r3, 62443, NERC CIP, Bill C-8 |
| Hands-on | Virtualized OT home lab + portfolio parser |
| Network | BSides Toronto, ISA Toronto Section |
| Certify | ISA/IEC 62443 Fundamentals Specialist |

---

*Notes drafted from Holcomb v2023.1 for personal study. Re-read the PDF before relying on details.*
