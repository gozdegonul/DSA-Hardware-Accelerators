# 🚀 Domain-Specific Architecture (DSA) & Hardware Accelerator Analysis

> A research report on why computing moved from general-purpose CPUs to specialized hardware (GPUs, FPGAs, ASICs, TPUs, NPUs), what that buys in performance and energy, and what it costs in flexibility, money and security.

![Topic](https://img.shields.io/badge/Topic-Computer%20Architecture-0A66C2)
![Focus](https://img.shields.io/badge/Focus-DSA%20%7C%20Accelerators%20%7C%20Security-success)
![Type](https://img.shields.io/badge/Type-Research%20Report-orange)
![Format](https://img.shields.io/badge/Format-PDF%20%2F%20DOCX-lightgrey)

---

## 📖 Overview

As Moore's Law slowed and Dennard Scaling broke down, simply adding more transistors to general-purpose processors stopped delivering the speed-ups it once did. **Domain-Specific Architectures (DSAs)** respond to this by trading generality for hardware tailored to one class of workloads (machine learning, graphics, signal processing, cryptography), gaining speed and energy efficiency in return.

This report covers:

- the **history** that led to DSAs, from CPUs to GPUs, FPGAs/ASICs and TPUs/NPUs,
- how DSAs differ from **general-purpose architectures**,
- their **advantages** (performance, energy efficiency),
- their **vulnerabilities** (inflexibility, security, manufacturing cost, updatability), and
- **strategies to reduce** those security risks.

## 📄 Read the Report

| Format | Link |
|---|---|
| PDF | [DSA_Hardware_Accelerator_Analysis.pdf](./DSA_Hardware_Accelerator_Analysis.pdf) |
| Word | [DSA_Hardware_Accelerator_Analysis.docx](./DSA_Hardware_Accelerator_Analysis.docx) |

## 🧭 Contents

1. **Introduction** – computer architecture types; Moore's Law and the end of Dennard Scaling as the motivation for DSAs
2. **History & Evolution** – general-purpose CPUs → GPUs → FPGAs and ASICs → TPUs and NPUs
3. **Advantages of DSAs** – performance gains and energy efficiency
4. **Potential Vulnerabilities** – lack of flexibility, security weaknesses, manufacturing cost, updatability
5. **Vulnerability Reduction Strategies** – segmentation, access control, encryption, patching, scanning, training
6. **Conclusion & Future Outlook**

## 🔍 Key Findings

### The accelerator family

| Architecture | Role |
|---|---|
| **GPU** | One of the earliest DSAs; built for massively parallel graphics and compute |
| **FPGA** | Reconfigurable after manufacturing; avoids the cost of a custom chip |
| **ASIC** | Fixed to one task; maximum performance and efficiency, highest cost and least flexibility |
| **TPU** | Google's accelerator for machine learning workloads |
| **NPU** | Power-efficient AI inference, especially on mobile and edge devices |

### General-purpose vs. domain-specific

| | General-purpose CPU | DSA |
|---|---|---|
| Flexibility | High, handles many workloads | Low, tuned to one domain |
| Performance on target task | Moderate | Very high |
| Energy efficiency | Lower (instruction-handling overhead) | Higher (unneeded work removed) |
| Design cost | Mature tools and ecosystem | Expensive, specialized tooling |

### Vulnerabilities of DSAs

| Vulnerability | Why it matters |
|---|---|
| **Lack of flexibility** | Hard-coded logic cannot adapt if the algorithm or domain changes |
| **Security weaknesses** | Side-channel attacks, weak isolation in multi-tenant clouds, firmware and low-level API exposure |
| **Manufacturing cost** | ASIC R&D and photomask sets are very expensive (the report cites ~$100M for 7 nm design and ~$20M for a 5 nm mask set) |
| **Updatability** | Hardware changes require remanufacturing; only firmware and parameters can be patched |

### Reduction strategies

- **Network segmentation** – isolate zones to contain malware
- **Access control** – two-factor authentication and role-based access control (RBAC)
- **Encryption** – protect data in transit and at rest
- **Patch management** – apply vendor fixes regularly
- **Vulnerability scanning** – find weak points before attackers do
- **Security awareness training** – address the human factor

### Looking ahead

More flexible hardware and security built in from the start, serving AI, IoT and real-time data processing.

## 🛠️ Topics & Technologies Covered

`Domain-Specific Architecture` · `Moore's Law` · `Dennard Scaling` · `GPU` · `FPGA` · `ASIC` · `TPU` · `NPU` · `Hardware Accelerators` · `Energy Efficiency` · `Side-Channel Attacks` · `RBAC / 2FA` · `Patch Management`

## 📚 References

The report draws on 34 references, including Hennessy & Patterson (2018), Jouppi et al. (2017, 2018), Esmaeilzadeh et al. (2011), Hameed et al. (2010), Kuon & Rose (2007) and Putnam et al. (2014). The full list is in the report.

## 👩‍💻 Author

**Gözde Gönül**
GitHub: [@gozdegonul](https://github.com/gozdegonul)

---

<sub>⭐ If you found this useful, feel free to star the repository.</sub>
