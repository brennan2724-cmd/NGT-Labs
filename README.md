# NGT Labs

**Hands-on Networking & Cybersecurity Labs**

`ngt-labs` is a centralized repository for documenting, organizing, and solving networking and cybersecurity lab challenges. Each lab or problem is maintained as an individual project, providing a structured record of the problem, methodology, tools, implementation, results, and technical lessons learned.

The goal is to turn theoretical knowledge into practical skills through experimentation, troubleshooting, security analysis, and repeatable lab exercises.

## 🎯 Objectives

- **Build practical skills:** Apply networking, systems administration, and cybersecurity concepts in hands-on environments.
- **Document solutions:** Maintain clear, reproducible write-ups for each lab and problem.
- **Develop technical proficiency:** Gain experience with industry-relevant tools, protocols, operating systems, and security methodologies.
- **Track progress:** Build an organized collection of completed labs, technical challenges, and projects.
- **Create a technical portfolio:** Demonstrate problem-solving ability, analytical thinking, and practical security knowledge.

## 🧪 Areas of Focus

The repository can include projects across the following domains:

| Domain | Topics |
| --- | --- |
| Networking | TCP/IP, OSI model, subnetting, routing, switching, DNS, DHCP |
| Network Analysis | Wireshark, packet captures, protocol analysis, traffic investigation |
| Reconnaissance | Network discovery, service enumeration, asset identification |
| Vulnerability Assessment | Security scanning, vulnerability identification, remediation |
| Network Security | Firewalls, ACLs, segmentation, IDS/IPS, VPNs |
| Linux & Windows | System administration, permissions, services, hardening |
| Ethical Hacking | Authorized enumeration, exploitation fundamentals, security validation |
| Cryptography | Encryption, hashing, certificates, PKI, TLS |
| Security Operations | Log analysis, threat detection, incident investigation |
| Digital Forensics | Evidence collection, artifact analysis, investigative workflows |
| Automation & Scripting | Python, Bash, PowerShell, repetitive task automation |

*The topics listed above describe the intended scope of the repository, not a claim that every area has already been completed.*

## 📁 Repository Structure

Each problem or lab is treated as a separate project with its own directory and documentation.

```text
ngt-labs/
├── README.md
├── networking/
│   └── lab-01/
│       ├── README.md
│       ├── configs/
│       ├── evidence/
│       └── scripts/
├── network-analysis/
│   └── lab-01/
│       ├── README.md
│       ├── captures/
│       └── evidence/
├── vulnerability-assessment/
│   └── lab-01/
│       ├── README.md
│       ├── scans/
│       └── evidence/
├── system-security/
│   └── lab-01/
│       ├── README.md
│       ├── configs/
│       └── evidence/
└── scripts/
```

*This is a suggested structure; directories can be added as projects are created.*

## 📚 Lab & Project Index

Each entry below should link to its corresponding project directory or README. Add entries as labs are introduced.

| Project | Domain | Status |
| --- | --- | --- |
| Lab 01 | Networking | Planned |
| Lab 02 | Network Analysis | Planned |
| Lab 03 | Vulnerability Assessment | Planned |
| Lab 04 | System Security | Planned |

Replace these example entries with actual lab names, descriptions, and links as projects are added.

## 🛠️ Tools & Technologies

Tools will vary depending on the requirements of each project. The repository may include work involving:

- **Network analysis:** Wireshark, tcpdump
- **Network discovery and assessment:** Nmap
- **Virtualization and lab environments:** VirtualBox, VMware, Docker
- **Operating systems:** Linux and Windows
- **Security testing:** Nmap, Metasploit, and other tools appropriate to authorized lab environments
- **Scripting and automation:** Python, Bash, PowerShell
- **Documentation and version control:** Markdown, Git, GitHub

Only list tools and technologies in an individual project's documentation when they are actually used.

## 📝 Project Documentation Standards

Each project should include a `README.md` describing the problem and the process used to solve it.

A typical project should document:

1. **Overview** — Lab name, objective, and problem statement.
2. **Scope & Environment** — Lab topology, operating systems, configurations, and assumptions.
3. **Tools & Requirements** — Software, utilities, dependencies, and prerequisites.
4. **Methodology** — The approach taken to investigate and solve the problem.
5. **Implementation** — Commands, configurations, scripts, and significant steps.
6. **Results & Evidence** — Relevant output, screenshots, packet captures, or other artifacts.
7. **Analysis** — Explanation of findings, root causes, and security implications.
8. **Remediation** — Recommended fixes, mitigations, or configuration improvements, where applicable.
9. **Lessons Learned** — Key takeaways, challenges, and areas for further exploration.

Documentation should prioritize clarity, reproducibility, and technical accuracy. Sensitive information, credentials, private keys, and unrelated personal data must never be committed to the repository.

## 🔐 Responsible Use

All experiments, scans, and security testing must be performed within authorized lab environments, systems owned by the operator, or targets for which explicit permission has been granted.

- Use isolated virtual machines, test networks, and intentionally vulnerable environments where appropriate.
- Do not conduct unauthorized scanning, exploitation, credential attacks, or disruption of third-party systems.
- Sanitize logs, packet captures, screenshots, and configuration files before publishing them.
- Document findings responsibly and prioritize defensive analysis, remediation, and security improvement.

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd ngt-labs
   ```

2. Browse the repository to find the lab or problem you want to explore.

3. Open the individual project's `README.md` and review its prerequisites, scope, and setup instructions.

4. Reproduce the lab in the documented environment.

5. Review the methodology, validate the results, and explore the lessons learned.

*Individual projects may have their own setup instructions and dependencies.*

## 📈 Progress & Continuous Learning

This repository is intended to evolve alongside continued learning and practical experimentation. Projects may range from foundational exercises to more advanced, multi-step investigations.

Each completed lab adds another documented example of technical problem-solving, contributing to a growing reference library of networking and cybersecurity knowledge.

## 📄 License

Unless otherwise specified, no license is implied by making this repository publicly accessible. Add a `LICENSE` file if you intend to grant others permission to use, modify, or distribute its contents.

---

**NGT Labs** — Learn by doing. Document the process. Build practical skills.
