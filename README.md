# Hi there, I'm Kerem!

<p align="center">
  <a href="https://turekkerem.github.io">
    <img src="https://img.shields.io/badge/%20Explore%20My%20Portfolio-turekkerem.github.io-3b82f6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Turekkerem&color=blueviolet&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Focus-Cybersecurity%20%7C%20Cryptography%20%7C%20Malware%20Dev-blue?style=flat-square&logo=security" alt="Focus" />
  <img src="https://img.shields.io/badge/Status-Continuous%20Learning-success?style=flat-square" alt="Status" />
</p>

---

## About Me

I am a passionate **Cybersecurity Researcher** with a deep-rooted fascination for the mechanics of offensive security, low-level system internals, and modern cryptography. My approach to security is rooted in the philosophy that to defend effectively, one must understand how systems break and how adversaries operate at the architectural level.

Currently, I spend my time engineering custom offensive tooling for research purposes, exploring the frontiers of **Post-Quantum Cryptography (PQC)**, and occasionally engaging in rapid, creative prototyping ("vibecoding") to test out new paradigms. 

---

## Core Areas of Expertise & Interest

### Offensive Security & Malware Research
* **Custom Tooling:** Developing bespoke red-teaming utilities from scratch (Python / C++) to understand API hooking, evasion, and stealth delivery mechanisms.
* **EDR/AV Evasion Research:** Analyzing telemetry generation, behavioral analysis, and how modern detection engineering responds to non-standard persistence and execution chains.
* **Windows Internals:** Deep working knowledge of the Windows API, NT internals, process injection techniques, and registry manipulation.

### Cryptography (Classical & Post-Quantum)
* **Classical & Traditional Cryptography:** Implementation and cryptanalysis of classical ciphers, symmetric encryption standards (AES), and asymmetric primitives (RSA, ECC).
* **Post-Quantum Cryptography (PQC):** Researching lattice-based cryptography, hash-based signatures, and migration strategies to secure systems against quantum adversaries (NIST PQC standards).
* **Crypto Downgrade & Protocol Flaws:** Studying downgrade vulnerabilities, implementation flaws, and cryptographic misconfigurations in enterprise software and operating systems and the most common: Block Cipher modes misuse.

---

## Featured Projects & Research

Here is a selection of projects showcasing my hands-on experience with low-level programming and system security:

### 1. Advanced Red Teaming Suite (Timestomp, Crypto Downgrade & Persistence)
* **Description:** A comprehensive, multi-module system utility built to evaluate endpoint visibility and configuration security on Windows environments.
* **Key Features:**
  * **Timestomping:** Advanced manipulation of NTFS Master File Table (MFT) attributes and file timestamps to disrupt forensic timelines.
  * **Registry-Based Crypto Downgrade:** Programmatically alters system and cryptographic protocol policies via the Windows Registry to force weak cipher suites and legacy protocols.
  * **Persistence Mechanisms:** Implements robust, multi-tier persistence strategies via scheduled tasks, registry run keys, and service creation to test detection resilience.
* **Tech Stack:** C++, Win32 API, Native NT APIs.

### 2. Educational Custom Ransomware Prototype
* **Description:** Developed strictly for research and academic purposes to study asymmetric encryption implementation, file-system traversal, and key exchange mechanics.
* **Key Features:**
  * Multi-threaded high-performance directory traversal and selective target enumeration.
  * Robust hybrid encryption model utilizing AES-256 for file payloads secured via public-key cryptography.
  * Memory-wiping routines to ensure cryptographic material does not persist unnecessarily in RAM.
* **Tech Stack:** C, Cryptographic APIs.

### 3. Low-Level Keylogger Framework
* **Description:** A proof-of-concept user-mode input monitoring framework designed to explore Windows hook mechanics and data exfiltration channels.
* **Key Features:**
  * Low-level keyboard hook implementation (`WH_KEYBOARD_LL`) with minimal performance footprint.
  * Dynamic context logging (active window tracking, timestamping).
  * Encrypted local buffer caching to protect captured telemetry in transit.
* **Tech Stack:** C++, Win32 API.

---

## Tech Stack & Tools

* **Languages:**  C++, Python, Bash
* **Operating Systems:** Windows (Win32 API), Linux (Kernel/Userspace)
* **Security Tooling:** Ghidra, x64dbg, Wireshark, Metasploit, Burp Suite
* **Cryptographic Libraries:** OpenSSL, OpenSSH, OpenPGP and implementations such as classical PyCryptoDome



---

## Connect With Me

* **GitHub:** [github.com/Turekkerem](https://github.com/Turekkerem)
* **Page** [turekkerem.github.io](turekkerem.github.io)
* **Focus:** Always open to discussing advanced cybersecurity research, malware analysis, or cryptographic implementations.

> *"He who does not uderstand how a system fails cannot claim to understand how it works."*
