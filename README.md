# Awesome-Application-Streaming-Virtual-Desktop

# Awesome-Application-Streaming-Virtual-Desktop 🖥️ 🌐

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Streaming Virtual Desktop Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Application Streaming & Virtual Desktop Ecosystem

**Curated List of Commercial DaaS & App Streaming Platforms with Open-Source VDI and Remote Desktop Alternatives**  
*Focused on Desktop as a Service, Application Publishing, Clientless HTML5 Access & Self-Hosted Virtualization*  

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **application streaming platforms**, **Virtual Desktop Infrastructure (VDI) solutions**, and **open-source remote desktop gateways**. According to the 2026 IDC MarketScape, AWS, Microsoft, Omnissa, Citrix, and Parallels are recognized as Leaders in Desktop as a Service (DaaS), with Workspot, Dizzion, and Inuvika positioned as Capabilities players [citation:1]. Whether you are looking for enterprise-grade commercial DaaS platforms or self-hostable open-source alternatives (like *Apache Guacamole*, *Kasm Workspaces*, and *IsardVDI*), this list covers category leaders, browser-based access technologies, and privacy-respecting virtualization stacks.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The DaaS and application streaming market is undergoing consolidation, with Omnissa (formerly VMware Horizon) and Citrix remaining enterprise staples while hyperscalers like AWS and Microsoft push consumption-based models. IDC's 2026 MarketScape places AWS and Microsoft among the Leaders, reflecting the shift toward cloud-native delivery [citation:1]. Pricing varies widely: Azure Virtual Desktop operates on a consumption model with optional savings plans [citation:6], while Amazon AppStream 2.0 focuses specifically on application streaming rather than full desktops [citation:6].

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Amazon AppStream 2.0](https://aws.amazon.com/appstream2/)** ☁️ | Amazon | ~$2.0 Trillion | Pay-as-you-go (instance hours + storage) | AWS Free Tier does not cover AppStream; limited trial available | **Fully managed application streaming** — Delivers desktop apps to any HTML5 browser. Elastic scalability, no infrastructure management. AWS-recommended for ISVs delivering applications via the cloud [citation:6]. |
| **[Microsoft Azure Virtual Desktop](https://azure.microsoft.com/en-us/products/virtual-desktop/)** 🔷 | Microsoft | ~$3.90 Trillion | Consumption-based (compute + storage + networking) | 30-day free trial for Azure services; no permanent free tier | **Cloud VDI on Azure** — Multi-session Windows, native Entra ID integration, and flexible scaling. IDC MarketScape Leader for DaaS in 2026 [citation:1]. Best for Microsoft-first organizations [citation:6]. |
| **[Citrix DaaS](https://www.citrix.com/)** 🏢 | Cloud Software Group | Private | Custom enterprise licensing | Trial available on request | **Enterprise DaaS and app delivery** — Hybrid and multi-cloud VDI, application publishing, and Workspace access layer. IDC MarketScape Leader. Many organizations use Citrix primarily for app publishing rather than full VDI [citation:6]. |
| **[Omnissa Horizon Cloud](https://www.omnissa.com/)** 🔮 | Omnissa (formerly VMware) | Private | Custom enterprise pricing | Trial available on request | **Enterprise VDI platform** — Formerly VMware Horizon. Mature virtualization features, hybrid deployment options, strong scalability. IDC MarketScape Leader for DaaS in 2026 [citation:1]. |
| **[Nutanix Frame](https://www.nutanix.com/products/frame)** 🖼️ | Nutanix | ~$15 Billion | Pay-as-you-go (per-user or per-hour) | Free trial available (30 days) | **Cloud-native DaaS** — Runs on AWS, Azure, or Nutanix AHV. Browser-based access, GPU support, and application publishing. |
| **[Parallels RAS](https://www.parallels.com/products/ras/)** ⚡ | Parallels (Alludo) | Private | Custom per-user licensing | 30-day free trial | **Application and desktop delivery** — Simpler alternative to Citrix with strong application publishing. Azure integration and multi-cloud support. IDC MarketScape Leader for DaaS in 2026 [citation:1]. |
| **[Workspot](https://www.workspot.com/)** 🛠️ | Workspot | Private | Custom enterprise pricing | Demo available on request | **Cloud-native VDI** — Enterprise-grade desktop delivery with multi-cloud support. Positioned in IDC MarketScape Capabilities quadrant [citation:1]. |
| **[Cameyo](https://cameyo.com/)** 📦 | Cameyo (Acquired by Google) | Private | Free for up to 5 users; paid from ~$10/user/mo | Free tier available; trial for paid plans | **Application virtualization** — Publishes Windows apps to browsers without VDI. ChromeOS integration. |
| **[Kasm Workspaces](https://kasm.com/)** 🐳 | Kasm Technologies | Private | Community Edition: Free; Enterprise: Custom | **Community Edition free forever**; Enterprise trial available | **Containerized workspace streaming** — Open-source web-native rendering. Delivers Docker-based desktops and apps via browser. Images and streaming technology open-source [citation:5][citation:14]. |
| **[Apporto](https://apporto.com/)** 🍎 | Apporto | Private | Custom education/enterprise pricing | Demo available | **Cloud desktop for education** — Browser-based virtual labs and application delivery focused on universities and colleges. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Apache Guacamole](https://github.com/apache/guacamole-server)** [![Stars](https://img.shields.io/github/stars/apache/guacamole-server?style=social&color=white)](https://github.com/apache/guacamole-server/stargazers)  
  **Clientless remote desktop gateway**, Apache-2.0 licensed. ~3.5k+ stars. Supports standard protocols (VNC, RDP, SSH) through any HTML5 web browser. No plugins or client software required. Active community with commercial support options available [citation:4][citation:9][citation:18]. 🥑

- **[Kasm Workspaces](https://github.com/kasmtech/workspaces-images)** [![Stars](https://img.shields.io/github/stars/kasmtech/workspaces-images?style=social&color=white)](https://github.com/kasmtech/workspaces-images/stargazers)  
  **Containerized desktop and application streaming**, Community Edition free. ~2k+ stars for images repo. Web-native rendering technology delivers Docker-based workspaces. All images and streaming technology open-source on Docker Hub and GitHub [citation:5][citation:14]. 🐳

- **[IsardVDI](https://gitlab.com/isard/isardvdi)** [![Stars](https://img.shields.io/github/stars/isard/isardvdi?style=social&color=white)](https://gitlab.com/isard/isardvdi/stargazers)  
  **Open-source KVM virtual desktops**, AGPL-3.0 licensed. ~193 stars. GPU support (NVIDIA Grid), Docker-based installation, multiple viewers (SPICE, noVNC, RDP, Guacamole). Scalable hypervisor management with template-based desktop creation [citation:7][citation:11][citation:16]. 🖥️

- **[Selkies-GStreamer](https://github.com/selkies-project/selkies-gstreamer)** [![Stars](https://img.shields.io/github/stars/selkies-project/selkies-gstreamer?style=social&color=white)](https://github.com/selkies-project/selkies-gstreamer/stargazers)  
  **Low-latency Linux WebRTC HTML5 remote desktop**, MPL-2.0 licensed. ~2k+ stars. GPU/CPU-accelerated streaming at 60 FPS Full HD. Designed for containers, Kubernetes, and HPC. Started by Google engineers, expanded by academic researchers [citation:12][citation:17]. 🎮

- **[Ravada](https://github.com/UPC/ravada)** [![Stars](https://img.shields.io/github/stars/UPC/ravada?style=social&color=white)](https://github.com/UPC/ravada/stargazers)  
  **Remote virtual desktops manager**, AGPL-3.0 licensed. ~218 stars. KVM-based VDI solution with web interface. Simplified management for small to medium deployments [citation:16]. 🎯

- **[OpenUDS](https://github.com/VirtualCable/openuds)** [![Stars](https://img.shields.io/github/stars/VirtualCable/openuds?style=social&color=white)](https://github.com/VirtualCable/openuds/stargazers)  
  **Multiplatform connection broker**, AGPL-3.0 licensed. Open-source VDI broker from Virtualcable. Manages connections to virtual desktops across hypervisors [citation:16]. 🔗

- **[QVD](https://github.com/qindel/qvd)** [![Stars](https://img.shields.io/github/stars/qindel/qvd?style=social&color=white)](https://github.com/qindel/qvd/stargazers)  
  **Open-source VDI solution**, GPL-3.0 licensed. ~104 stars. Developed by Qindel Group. Safe and easy-to-manage virtual desktop infrastructure [citation:16]. 🖥️

- **[a-da](https://github.com/SpringStudent/a-da)** [![Stars](https://img.shields.io/github/stars/SpringStudent/a-da?style=social&color=white)](https://github.com/SpringStudent/a-da/stargazers)  
  **Distributed remote desktop control system**, MIT licensed. JavaCV + Netty + Swing based. Low-latency streaming with distributed media and clipboard modules. Windows/macOS support [citation:8]. 🎛️

- **[OSVDI (Open Source VDI)](https://gitlab.uni-freiburg.de/opensourcevdi)** [![Stars](https://img.shields.io/github/stars/opensourcevdi/opensourcevdi?style=social&color=white)](https://gitlab.uni-freiburg.de/opensourcevdi/stargazers)  
  **SPICE/QEMU with video stream support**, open-source. Active development by University of Freiburg. Complete remote desktop via virtualization with fully open software stack. Funded by DFG for digital sovereignty [citation:2]. 🔬

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new application streaming platforms or open-source VDI software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Streaming-Virtual-Desktop&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this application streaming repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers & IT administrators.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- DaaS and VDI platforms handle sensitive desktop sessions and corporate data. **Review security architecture, data residency, and compliance certifications** before deploying. 🔒
- Open-source solutions (Apache Guacamole, Kasm Workspaces, IsardVDI) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, 24/7 support, and managed infrastructure remain primarily commercial offerings. 🖥️

---

<p align="center">
  <b>Made with ❤️ for IT administrators, DevOps engineers, and open-source virtualization advocates.</b>
</p>
