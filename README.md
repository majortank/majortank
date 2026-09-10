<div align="center">

# Thabo "Tank" Tankiso Thebe

### Systems Software Engineer • Rust & Linux Specialist • Network Infrastructure

[![Available for Hire](https://img.shields.io/badge/Status-Actively%20Looking%20for%20Work-39ff7a?style=for-the-badge&logo=statuspage&logoColor=black)](mailto:thabo.tankiso.thebe@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-majortank.space-00ffff?style=for-the-badge&logo=firefox-browser&logoColor=black)](https://majortank.space)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/thabotankisothebe)
[![GitHub](https://img.shields.io/badge/GitHub-majortank-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/majortank)

*Building high-performance systems software, low-latency Linux audio engines, and large-scale enterprise campus infrastructure.*

</div>

---

## ⚡ Executive Summary

I am a **Systems, Rust & Linux Software Engineer** with a deep focus on performance, concurrency, and reliability. My work spans:
- **Systems & Low-Latency Audio:** Architecting native Linux audio players and engines in Rust with CPAL, Symphonia multi-format decoding, lock-free ring buffers, real-time 30Hz spectrum visualizers, dynamic `.so` plugin systems, and D-Bus/MPRIS controls.
- **Enterprise Linux Infrastructure & Networking:** Deploying large-scale DHCP architectures servicing 100+ campus VLANs on enterprise server hardware, multicast OS imaging systems across university computer lab fleets, and pfSense/firewall network segmentation.
- **Pure Rust Zero-Dependency Network Services:** Implementing high-throughput HTTP/1.1 servers, socket parsers, token-bucket rate limiters, and in-memory TTL caching from scratch with zero external crate dependencies.
- **Modern Full-Stack Applications:** Developing native desktop GUIs with Iced 0.12 (WGPU) and full-stack web applications with TypeScript, React 19, and Next.js.

> [!IMPORTANT]
> **Currently Looking for Work:** Available immediately for full-time Software Engineering roles (Systems, Rust Backend, Linux Infrastructure, or Full-Stack). Remote, Hybrid, or Worldwide.
> 
> 📧 **Email:** [thabo.tankiso.thebe@gmail.com](mailto:thabo.tankiso.thebe@gmail.com) • [tankiso@majortank.space](mailto:tankiso@majortank.space)  
> 🌐 **Portfolio:** [https://majortank.space](https://majortank.space)

---

## 🛠️ Technical Competencies

| Domain | Technologies & Capabilities |
| :--- | :--- |
| **Systems & Low-Latency (Rust)** | **Rust** (Ownership, Atomics, Lifetimes, Concurrency, FFI), **CPAL** (Audio I/O), **Symphonia** (Multi-format decoding), **Crossbeam** (Lock-free channels), Dynamic Shared Libraries (`.so` / ABI), POSIX APIs |
| **Linux & Infrastructure** | **Arch Linux**, **Ubuntu Server**, **Debian**, **ISC-DHCP** (100+ VLANs, IP Helpers, 802.1Q), **FOG Project** (PXE / Multicasting), **pfSense**, **LDAP**, Systemd daemons, **PKGBUILD / AUR Packaging**, Bash / POSIX Shell |
| **Backend & Protocols** | Socket Programming, Custom HTTP/1.1 Engines, RESTful API Design, **SQLite** (WAL mode & concurrency), **PostgreSQL**, Token-Bucket Rate Limiting, In-Memory TTL Caches, **Python** (FastAPI, Flask) |
| **GUI & Frontend** | **Iced 0.12** (Rust Native GUI, WGPU backend), **TypeScript**, **React 19**, **Next.js**, WebSockets, Tailwind CSS, Terminal CRT UI Design |
| **DevOps & Verification** | Performance Profiling (**Flamegraph**, **Perf**, **Criterion.rs**), **Docker**, **Git / GitHub CLI**, Packet Analysis (**Wireshark**, `tcpdump`), RBAC & Security Hardening |

---

## 🎯 Flagship Engineering Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎵 [Kanono Media Player](https://github.com/majortank/kanono-media-player)
**Modular Arch Linux desktop audio player inspired by Foobar2000**
- Built in **Rust** with an **Iced 0.12** reactive native GUI and dark CRT aesthetics.
- Low-latency **CPAL** output pipeline with sample-accurate PCM scrubbing, lock-free Crossbeam audio queues, and underrun-resilient playback.
- Multi-codec decoding via **Symphonia** (Opus, Vorbis, FLAC, WAV, AAC, MP3) with custom WebM demuxing.
- Real-time 30Hz audio spectrum visualizer, SQLite WAL library indexing, EBU R128 ReplayGain loudness analysis, and D-Bus MPRIS desktop controls.
- Dynamic shared object (`.so`) component plugin system with shared ABI and runtime host loader.
- Native Arch Linux package distribution via `PKGBUILD`.

`Rust` `CPAL` `Symphonia` `Iced` `SQLite WAL` `D-Bus` `PKGBUILD`

</td>
<td width="50%" valign="top">

### 🌐 [Centralized Enterprise DHCP Infrastructure](https://github.com/majortank/Centralized-DHCP-Server)
**Campus-wide dynamic IP addressing across 100+ VLANs**
- Deployed on enterprise **IBM System x3100 M4** hardware running Ubuntu Server.
- Configured **ISC-DHCP-Server** to service dynamic IP allocations across 100+ segmented enterprise VLANs via IP Helper relays on core switches.
- Implemented subnet partitioning, static reservations, failover mechanisms, and exhaustive lease audit logging for university campus operations.

`Linux` `Ubuntu Server` `ISC-DHCP` `802.1Q VLANs` `IP Helpers` `Enterprise Networking`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ [Zero-Dependency Rust Services & CLIs](https://github.com/majortank/github-trending-cli)
**High-throughput REST APIs and CLI tools in pure Rust**
- Engineered production-grade services ([github-trending-cli](https://github.com/majortank/github-trending-cli), [expense-tracker-api](https://github.com/majortank/expense-tracker-api), [todo-list-api](https://github.com/majortank/todo-list-api), [weather-api](https://github.com/majortank/weather-api)) with **zero external crate dependencies**.
- Implemented custom HTTP/1.1 request parsers, socket networking, thread-safe memory models, and token-bucket rate limiters from scratch.
- Demonstrates deep mastery of Rust standard library, raw socket I/O, memory layouts, and thread pooling.

`Pure Rust` `Zero Dependencies` `Socket Programming` `HTTP/1.1` `Concurrency`

</td>
<td width="50%" valign="top">

### 🖥️ [Alternative FOG Multicast Imaging Server](https://github.com/majortank/Alternative-FOG-Multicast-Server)
**Bulk OS multicasting & deployment for university computer labs**
- Built high-throughput disk imaging infrastructure using the FOG Project for fleets of Lenovo ThinkCentre M70a G3 machines.
- Tuned PXE boot environments, TFTP/NFS throughput, and UDP multicast saturation to image entire 100+ seat labs simultaneously with minimal network contention.

`Linux` `FOG Project` `Multicast UDP` `PXE Boot` `Bash Scripting` `Lab Infrastructure`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 [Document Processing OCR & AI Agent](https://github.com/majortank/Document-ProcessingOCR)
**Intelligent document extraction and autonomous agent workflow**
- Automated document analysis combining **Tesseract OCR** with **LangChain** autonomous agent tool-calling.
- Image preprocessing for noisy scanned documents, key-value schema extraction, and webhook integrations for downstream data pipelines.

`Python` `Tesseract OCR` `LangChain` `AI Agents` `Data Pipelines`

</td>
<td width="50%" valign="top">

### 💻 [MajorTank Linux Terminal Portfolio](https://github.com/majortank/majortank-linux-portfolio)
**Retro CRT phosphor-green interactive terminal portfolio**
- High-performance web portfolio built with **React 19**, **TypeScript**, and **Vite**.
- Real-time GitHub API integration, live search/filtering across 50+ repositories, interactive Neofetch identity panel, and CRT scanline styling.
- Live at [majortank.space](https://majortank.space/).

`React 19` `TypeScript` `Vite` `Terminal UI` `CSS Grid`

</td>
</tr>
</table>

---

## 📈 GitHub Analytics & Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=majortank&theme=tokyonight&hide_border=true&date_format=M%20j%2C%20Y)](https://github.com/majortank)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=majortank&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/majortank)

</div>

---

## 📬 Contact & Opportunities

I am **actively seeking full-time opportunities** in:
- **Systems Software Engineering (Rust / C++)**
- **Linux Infrastructure & Site Reliability Engineering**
- **Low-Latency & Audio / Media Software Development**
- **Backend & Network Systems Engineering**

- 📧 **Direct Email:** [thabo.tankiso.thebe@gmail.com](mailto:thabo.tankiso.thebe@gmail.com) • [tankiso@majortank.space](mailto:tankiso@majortank.space)
- 💼 **LinkedIn:** [linkedin.com/in/thabotankisothebe](https://linkedin.com/in/thabotankisothebe)
- 🌐 **Web Portfolio:** [majortank.space](https://majortank.space)
- 📍 **Location:** Johannesburg, South Africa • Open to Worldwide Remote or Relocation

<div align="center">
<sub>Engineered with precision by Thabo "Tank" Tankiso Thebe</sub>
</div>
