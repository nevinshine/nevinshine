<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0D1117,161b22,0D1117&height=280&section=header&text=Nevin%20Shine&fontSize=80&fontColor=0078D4&fontAlignY=35&desc=Undergraduate%20Systems%20Security%20Researcher&descSize=25&descAlignY=60&descAlign=50" alt="Nevin Shine Header" width="100%" />
</div>

<br />

<div align="center">
  <p>
    <b>Research Focus:</b> Linux Runtime Defense & Kernel-Bypass Networking (eBPF)<br>
    <b>Current Status:</b> Architecting the TELOS Runtime
  </p>

  <br />

  <a href="mailto:nevinshine05@outlook.com">
    <img src="https://img.shields.io/badge/Email-nevinshine05%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/nevin-shine-b403b932b">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://nevinshine.github.io/system-security-research-dossier">
    <img src="https://img.shields.io/badge/Dossier-Research%20Portfolio-2ea44f?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

<br /><br />

## Research Abstract

I am an **Undergraduate Researcher** focusing on the intersection of **Systems Engineering** and **AI Safety**. My work addresses the "Semantic Gap" in Autonomous AI Agents—preventing them from executing malicious intents by enforcing strict boundaries at the **Kernel** and **Network** layers.

---

## Active Research: The TELOS Runtime

**TELOS** is a hybrid security system designed to prevent "The Great Exfiltration" in Agentic AI. It operates on a "Split-Plane" architecture:

| Component | Engine Name | Technology Stack | Defense Role |
| :--- | :--- | :--- | :--- |
| **CORE (Host)** | [**Sentinel Runtime**](https://github.com/nevinshine/sentinel-runtime) | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) | **The Bodyguard.** Intercepts `execve` via `ptrace`/LSM hooks. |
| **EDGE (Network)** | [**Hyperion XDP**](https://github.com/nevinshine/hyperion-xdp) | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![eBPF](https://img.shields.io/badge/eBPF-F7931E?style=flat-square&logo=ebpf&logoColor=white) | **The Border Patrol.** Drops malicious packets at the NIC ($O(1)$) via XDP. |

<br />

## Technical Arsenal

**Kernel & Systems**
<br>
![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![eBPF](https://img.shields.io/badge/eBPF_XDP-F7931E?style=for-the-badge&logo=ebpf&logoColor=white)
![C](https://img.shields.io/badge/C_Language-00599C?style=for-the-badge&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

**Control Plane & Analysis**
<br>
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**Tools & Diagnostics**
<br>
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![GDB](https://img.shields.io/badge/GDB_Debugger-DD0031?style=for-the-badge&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

<br />

---

### Selected Works & Milestones

- **Sentinel M3.2:** Implemented watchdog persistence against SIGKILL and path canonicalization.
- **Hyperion M4.6:** Achieved dynamic policy injection using `BPF_MAP_TYPE_ARRAY` with a Go controller.
- **Mindscape BCI:** Awarded *Best Project 2025* for real-time EEG signal processing pipeline.

<br />

<div align="center">
  <sub>Currently based in Nürnberg, Germany (Permanent) / India (Academic). Open to HiWi/Internship opportunities starting May 2026.</sub>
</div>

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=100&section=footer" width="100%" />
