<div align="center">
  <h1>Nevin Shine</h1>
  <h3>Undergraduate Systems Security Researcher</h3>
  <p>
    <b>Research Focus:</b> Linux Runtime Defense & Kernel-Bypass Networking (eBPF/XDP)<br>
    <b>Current Status:</b> Architecting the TELOS Runtime
  </p>

  <br>

  <a href="mailto:nevinshine05@outlook.com">
    <img src="https://img.shields.io/badge/Email-nevinshine05%40outlook.com-333333?style=flat-square&logo=microsoftoutlook&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/nevin-shine-b403b932b">
    <img src="https://img.shields.io/badge/LinkedIn-Nevin%20Shine-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://nevinshine.github.io/system-security-research-dossier">
    <img src="https://img.shields.io/badge/Portfolio-Research%20Dossier-0055aa?style=flat-square&logo=firefoxbrowser&logoColor=white" />
  </a>
</div>

<br>

---

### Research Abstract

I am an **Undergraduate Researcher** focusing on the intersection of **Systems Engineering** and **AI Safety**. My work addresses the "Semantic Gap" in Autonomous AI Agents—preventing them from executing malicious intents (e.g., Indirect Prompt Injection) by enforcing strict boundaries at the **Kernel** and **Network** layers.

My primary research artifact is **TELOS**, a split-plane defense architecture that decouples high-level intent verification from low-level enforcement.

---

### Active Research: The TELOS Runtime

TELOS is a hybrid security system designed to prevent "The Great Exfiltration" in Agentic AI. It consists of two independent engines working in a closed loop.

| Component | Engine Name | Technology | Defense Role |
| :--- | :--- | :--- | :--- |
| **CORE (Host)** | [**Sentinel Runtime**](https://github.com/nevinshine/sentinel-runtime) | `ptrace` / `LSM` | **The Bodyguard.** Intercepts `execve` and file syscalls to prevent unauthorized local execution. |
| **EDGE (Network)** | [**Hyperion XDP**](https://github.com/nevinshine/hyperion-xdp) | `eBPF` / `XDP` | **The Border Patrol.** Drops malicious packets at the NIC level ($O(1)$) before they touch the OS stack. |

---

### Technical Arsenal

I specialize in **low-level systems programming** and **kernel instrumentation**.

| Domain | Technologies & Methods |
| :--- | :--- |
| **Kernel Space** | eBPF (Extended Berkeley Packet Filter), XDP, Linux Security Modules (LSM), Ring Buffers |
| **User Space** | C (Systems), Go (Control Plane), Rust (Memory Safety), Namespaces/Cgroups v2 |
| **Analysis** | Python (Scikit-learn), GDB, bpftool, Wireshark, Perf |
| **Architecture** | Split-Plane Security, Event-Driven Architecture, Zero-Copy Memory Management |

---

### Selected Works & Milestones

- **Sentinel M3.2:** Implemented watchdog persistence against SIGKILL and path canonicalization.
- **Hyperion M4.6:** Achieved dynamic policy injection using `BPF_MAP_TYPE_ARRAY` with a Go controller.
- **Mindscape BCI:** Awarded *Best Project 2025* for real-time EEG signal processing pipeline.

<br>

<div align="center">
  <sub>Currently based in Nürnberg, Germany (Permanent) / India (Academic). Open to HiWi/Internship opportunities starting May 2026.</sub>
</div>

