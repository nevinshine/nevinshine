<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=0078D4&text=Nevin%20Shine&height=150&fontSize=70" alt="Nevin Shine" />

  <h3>Undergraduate Systems Security Researcher</h3>

  <p>
    <b>Research Focus:</b> Linux Runtime Defense & Kernel-Bypass Networking (eBPF)<br>
    <b>Current Status:</b> Architecting the TELOS Runtime
  </p>

  <a href="mailto:nevinshine05@outlook.com">
    <img src="https://img.shields.io/badge/Email-nevinshine05%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/nevin-shine-b403b932b">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://nevinshine.github.io/system-security-research-dossier">
    <img src="https://img.shields.io/badge/Dossier-Research%20Portfolio-2ea44f?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

---

## Research Abstract

I am an **Undergraduate Researcher** working at the intersection of **Systems Engineering** and **AI Safety**. My work targets the *semantic gap* in autonomous agents—preventing malicious execution by enforcing strict controls at the **kernel** and **network** layers.

---

## Active Research: The TELOS Runtime

**TELOS** is a hybrid defense platform designed to prevent large-scale data exfiltration in agentic systems through a split-plane architecture:

| Component | Engine | Technology Stack | Defense Role |
|----------|-------|------------------|-------------|
| **CORE (Host)** | [**Sentinel Runtime**](https://github.com/nevinshine/sentinel-runtime) | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) | **The Bodyguard.** Intercepts `execve` via `ptrace` and LSM hooks. |
| **EDGE (Network)** | [**Hyperion XDP**](https://github.com/nevinshine/hyperion-xdp) | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![eBPF](https://img.shields.io/badge/eBPF-orange?style=flat-square) | **The Border Patrol.** Drops malicious packets at the NIC in constant time via XDP. |

---

## Technical Arsenal

### Kernel & Systems
![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![eBPF](https://img.shields.io/badge/eBPF_XDP-orange?style=for-the-badge)
<br>
![C](https://img.shields.io/badge/C_Language-00599C?style=for-the-badge&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

### Control Plane & Analysis
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
<br>
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### Tools & Diagnostics
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![GDB](https://img.shields.io/badge/GDB_Debugger-DD0031?style=for-the-badge&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

---

## Selected Works & Milestones

- **Sentinel M3.2:** Implemented watchdog persistence against SIGKILL and robust path canonicalization.
- **Hyperion M4.6:** Added dynamic policy injection using `BPF_MAP_TYPE_ARRAY` with a Go control plane.
- **Mindscape BCI:** Awarded *Best Project 2025* for real-time EEG signal processing pipelines.

---

<div align="center">
  <sub>
    Based in Nürnberg, Germany (Permanent) / India (Academic).  
    Open to HiWi and internship opportunities starting May 2026.
  </sub>
</div>