<div align="center">

# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>


---
  <section id="section-1">
    <h2>📌 Project Overview</h2>
 
  <p>
This project focuses on setting up a **virtual cybersecurity and penetration-testing laboratory** using VirtualBox and Kali Linux.

The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.</p>
  </section>


---


<!-- Table of Contents -->
<nav>
  <h2>Table of Contents</h2>
  <ul>
    <li><a href="#section-1"> 📌 Project Overview</a></li>
    <li><a href="#section-2">🎯 Objectives</a></li>
    <li><a href="#section-3">🛡 Purpose of the Lab</a></li>
    <li><a href="#section-4">🏗 Lab Architecture</a></li>
    <li><a href="#section-5">⚙ Lab Configuration</a></li>
    <li><a href="#section-6">🪜 Lab Setup Procedure</a></li>
    <li><a href="#section-7">🔎 Lab Verification</a></li>
    <li><a href="#section-8">🐞 Problems Encountered & Solutions</a></li>
    <li><a href="#section-9">💡 What I Learned</a></li>
    <li><a href="#section-10">🔐 Security & Ethical Use</a></li>
    <li><a href="#section-11">🔗 Tools & Resources</a></li>
    <li><a href="#section-12">Author</a></li>
  </ul>
</nav>

<hr> <!-- Visual separator line -->

<!-- Main Document Content -->
<main>

  <section id="section-2">
    <h2>🎯 Objectives</h2>
    <p>
      The main objectives of this project are to:

- Install and configure VirtualBox.
- Install/import Kali Linux as a virtual machine.
- Create a private **NAT Network** for the cybersecurity lab.
- Configure network connectivity for Kali Linux.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the complete setup process.
- Prepare the environment for future cybersecurity projects.

    </p>
  </section>
---
  <section id="section-3">
    <h2>  🛡️ Purpose of the Lab</h2>
    <p>
 

The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

- Network reconnaissance
- Port scanning
- Vulnerability assessment
- Packet analysis
- Web security testing
- Exploitation practice
- Security-tool experimentation

⚠️ **Important:** This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.
    </p>
  </section>

  <section id="section-4">
    <h2>🏗️ Lab Architecture</h2>
    <p>
      <img width="2560" height="1600" alt="lab architecture" src="https://github.com/user-attachments/assets/5c920114-2e7e-41af-b508-00bcf2f969dd" />


      Additional target machines can be added to the same virtual network in future projects.
    </p>
  </section>

<section id="section-4">
    <h2>⚙️ Lab Configuration</h2>
    <p>
| 🧩 Component       | ⚙️ Configuration  |
| ------------------ | ----------------    |
| 🖥️ Host OS         | Windows 11         |
| 🧠 Host RAM        | 32 GB              |
| ⚡ Processor       | Intel Core i7      |
| 🧰 Hypervisor      | VirtualBox 7.2  |
| 🐉 Security OS     | Kali Linux 2026.2  |
| 🧠 Kali RAM        | 2048 MB            |
| 🌐 Virtual Network | NAT Network        |
| 📡 Network Address | 10.0.0.0/24        |
| 🐧 Kali IP Address | 10.0.0.2/24        |
| 🚪 Default Gateway | 10.0.0.1           |
| 🌍 DNS Server      | 8.8.8.8            |
| 🔮 Future VM Range | 10.0.0.3–10.0.0.99 |
    </p>
  </section>

  <section id="section-4">
    <h2>🪜 Lab Setup Procedure</h2>
    <p>
      Step 1. Install 7-Zip

7-Zip was installed to extract the Kali Linux virtual-machine package, which may be distributed as a `.7z` archive.

**Tool:** 7-Zip

---

Step 2. Install VirtualBox

VirtualBox was installed as the hypervisor.

---

Step 3. Create the NAT Network

A dedicated NAT Network was created in VirtualBox.

Configuration:
Network Name: NatNetwork
IPv4 Prefix:  10.0.0.0/24
DHCP:         Enabled
IPv6:         Disabled

    </p>
  </section>


  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>


  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>


  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>


  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>

  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>

  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>


  <section id="section-4">
    <h2>Conclusion</h2>
    <p>This is the final summary conclusion.</p>
  </section>
</main>

