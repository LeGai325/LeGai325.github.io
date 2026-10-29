---
lang: en
locale: en-US
translation_key: cv
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Le Gai (盖乐)

Ph.D. Student in Cyberspace Security  
Institute for Network Sciences and Cyberspace, Tsinghua University

**Email:** [gl25@mails.tsinghua.edu.cn](mailto:gl25@mails.tsinghua.edu.cn)  
**Homepage:** [legai325.github.io](https://legai325.github.io/)

## Research Interests

- AI agent and multi-agent system security, including protocol security, attack attribution, and workflow recovery.
- Network-aware scheduling, admission control, and quality of service for agentic AI systems.
- Internet measurement, IPv6 security, source address validation, and Internet-wide service discovery.
- Large language model distillation and learning-based malware detection.

## Education

**Tsinghua University**, Beijing, China  
Ph.D. in Cyberspace Security, **2025–Present**; expected graduation: **2030**  
Institute for Network Sciences and Cyberspace  
GPA: **4.0/4.0**

**Xidian University**, Xi'an, China  
B.Eng. in Network Engineering, **2021–2025**  
School of Cyber Engineering  
Department rank: **2/326**

## Research and Industry Experience

### Ant Group, Beijing

**Research Intern, Agent Security Team, Security Division**  
**June 2026–Present**; scheduled through December 2026

- Conduct research on multi-agent protocol and task-execution security in business agent systems, including Alipay's Abao, Qianwen Office, and Ant Digital Employees.
- Analyze security mechanisms and attack surfaces in agent communication protocols, including A2A and BCS, and design protocol-level defense modules.
- Validate task-execution security mechanisms in business scenarios and contribute to two research manuscripts on multi-agent system security.

### NSFOCUS, Beijing

**Intern, Network Asset Assessment**  
**June 2024–September 2024**

- Investigated efficient IPv4/IPv6 open-port scanning and service prediction, including feature transfer across scanning results.
- Analyzed IEEE address allocations and MAC vendor information, autonomous-system classifications, and protocol-stack distributions.

### NSFOCUS, Xi'an

**Security Testing Intern, Endpoint Security Technology Team**  
**June 2023–August 2023**

- Participated in testing a system for Multi-Level Protection Scheme 2.0 compliance.
- Developed a Python/Django application connected to the company database to automate compliance checks for domestic software platforms.
- Received an Outstanding Intern award and a direct graduate recruitment offer.

### Xidian University

**Undergraduate Research, Malware Detection**  
**September 2022–July 2025**

- Conducted research with Pengbin Feng in Prof. Jianfeng Ma's team, combining program analysis and machine learning for malware detection and network attack identification.
- Contributed to the DawnGNN paper in *Computers & Security* and two patent applications on malware detection and APK obfuscation analysis.

## Publications and Manuscripts

### Published or Accepted Papers

1. **Le Gai**, Zedong Jia, Lin He, et al. **TED: Abusing Tunnel Hosts and IPv6 Extension Headers for Pulsing DoS Attacks.** *USENIX Security 2026.*

2. Daguo Cheng, Zedong Jia, Ying Liu, Lin He, **Le Gai**, et al. **Divide, Predict, Conquer: Adaptive Internet-wide Service Discovery with Limited Seeds.** *IEEE INFOCOM 2026.*

3. **Le Gai**, Lin He, Chentian Wei, et al. **SpecNet-Agent: Network-Aware Speculation Control for QoS in Agentic Generative AI Services.** *IWQoS 2026, NetGenAI Workshop.* [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11661032/)

4. Pengbin Feng, **Le Gai**, et al. **DawnGNN: Documentation Augmented Windows Malware Detection using Graph Neural Network.** *Computers & Security*, 2024. [DOI](https://doi.org/10.1016/j.cose.2024.103788)

### Manuscripts Under Review

1. **Le Gai**, Chenxi Zhao, Ying Liu, Zhongmou Liu, et al. **CANTER: Coordinated Admission and Network Transmission by Execution Role for Timely Web Agents.** Under review at *The Web Conference (WWW) 2027*.

2. Xiuming Liu, **Le Gai**, Zhiyuan Chang, et al. **Agent-Canary-Mas: End-to-End Evaluation of Protocol Risk in Long-Horizon Multi-Agent Systems.** Under review at *USENIX Security 2027*. [arXiv](https://arxiv.org/abs/2610.15529)

3. Xuanfeng Yang, **Le Gai**, Jiaming Wang, Xuan Zhang. **Beyond Policy Discrepancy: Capability-Aware Multi-Teacher On-Policy Distillation.** Under review at *ICLR 2027*. [arXiv](https://arxiv.org/abs/2610.26950)

4. Zhongmou Liu, **Le Gai**, et al. **Woodpecker: Provenance-Guided Local Repair for Compromised Multi-Agent LLM Workflows.** Under review at *DAC 2027*.

5. **Le Gai**, Lin He, Jiaxing Guo, et al. **Peering into the Blind Spot: Measuring Source Address Validation with Internet Tunnels.** Under review at *IEEE Transactions on Networking*.

6. Daguo Cheng, **Le Gai**, Lin He, Ying Liu, et al. **Target-Aware Adaptive Scanning and Security Applications for Internet-Scale Open Port Discovery.** Under review at *IEEE INFOCOM 2027*.

## Research Projects

### Network-Aware Scheduling and QoS for Agentic AI

**SpecNet-Agent and CANTER** address congestion, redundant traffic, and tail latency in agentic services. SpecNet-Agent combines workflow dependencies with congestion feedback to adapt retrieval width, agent parallelism, and speculation budgets. CANTER coordinates request admission with execution-role-aware link scheduling inside the native tool loop.

- In heavy-load workflow replay, SpecNet-Agent reduced P99 latency by **94.3%** and wasted speculative bytes by **76.2%** relative to FIFO.
- In controlled overload experiments with identical role-aware scheduling, CANTER improved answer F1 over fixed admission by **5.84 percentage points on HotpotQA** and **5.46 points on Natural Questions**.
- Associated papers: **SpecNet-Agent** and **CANTER**, listed above.

### Protocol Risk Evaluation and Attribution in Multi-Agent Systems

**Agent-Canary-Mas** follows protocol attacks through long-horizon multi-agent tasks and connects local exploitation to downstream consequences. Its evaluation suite contains **975 matched malicious–benign task pairs** across A2A, ANP, and BCS in five business domains. Retaining cross-agent evidence increased macro-averaged problem-agent localization F1 from **29.7% to 95.5%** compared with native protocol logs.

### Provenance-Guided Recovery for Compromised Agent Workflows

**Woodpecker** uses semantic provenance to identify contaminated computation after a security alert, isolate affected workflow slices, and selectively replay them. In the reported evaluation, it repaired **87%** of compromised tasks, reduced replay computation by **25%**, and left no observed residual security risk in the evaluated cases.

### Capability-Aware Multi-Teacher Distillation

**CA-MOPD** merges reinforcement-learning specialists to initialize a shared student, then adjusts domain-level distillation strength using teacher–student capability gaps and detected student regression. Across six benchmarks covering mathematics, code generation, and instruction following, it improved the mean score over Open-MOPD by **0.83 percentage points**, including a **3.34-point** gain on IFBench.

### IP Tunnel and IPv6 Extension-Header Security

**TED** studies a network-layer pulsing denial-of-service mechanism arising from the interaction of IP tunnels and IPv6 extension-header processing. Internet-wide measurement identified **more than 1.9 million vulnerable tunnel hosts**. The work analyzes how asynchronous low-rate traffic can converge into a high-intensity pulse and evaluates the resulting security implications.

### Source Address Validation Measurement with Internet Tunnels

Developed a measurement method that uses open Internet tunnels to assess inbound and outbound source address validation in IPv4 and IPv6 networks without deploying vantage points inside the target networks. The study also analyzes how deployment varies with address-space size, autonomous-system type, and geography.

### Target-Aware Open-Port Discovery

**PortSeer** combines adaptive sampling of active hosts with a multigranularity dual-association graph to predict common ports and guide hierarchical scanning of the remaining ports. The reported IPv6 experiments achieved **7.1–78× scanning speedups** over the compared methods while reducing probing overhead.

### Internet-Wide Service Discovery with Limited Seeds

**SPADE** combines multilevel adaptive sampling with divide-and-conquer prediction of service-deployment features. It achieved **over 94% Top-1 hit rate and coverage** while using **0.15%–1%** of the seed volume required by the compared state-of-the-art methods. The reported discovery speedup was **219–805×**, with prediction over hundreds of millions of hosts completed in **seven minutes**.

### Active IPv6 Discovery and Geolocation

**Ongoing research with the Alibaba Security AGI Lab.** Combines active probing, address-pattern learning, passive observations, and machine learning for IPv6 discovery and geolocation. The project also explores LLM-assisted analysis and security attribution. Experiments and manuscript preparation are in progress.

## Undergraduate Research Projects

### Learning-Based Malware Detection

Combined program analysis and machine learning to identify malicious software under adversarial conditions. This work produced **DawnGNN** and patent applications on semantic malware detection for industrial Internet environments and APK obfuscation detection.

### Ransomware Detection with API Knowledge Graphs

**Cybersecurity Student Innovation Funding Program, May 2024–May 2025.** Used an LLM to construct an API behavior knowledge graph, applied RotatE embeddings to derive relational features, and incorporated those features into malware classifiers. The project evaluated detection improvements and generalization to ransomware variants. Selected as **one of two funded undergraduates at Xidian University** in that year's program.

### Cryptographic Acceleration on RISC-V

**June 2023–November 2024.** Implemented and optimized Chinese cryptographic algorithms on a RISC-V platform, including instruction-level optimization of bilinear-pairing and elliptic-curve operations and dedicated units for point multiplication and modular exponentiation. The project received a **National First Prize in the 8th National Cryptographic Technology Competition** and was presented at **CCF ChinaSoft 2024**.

### Federated Learning for In-Vehicle Speech Recognition

**National Undergraduate Innovation Project, January 2023–December 2023.** Led a project supervised by Prof. Junwei Zhang on secure and efficient in-vehicle speech recognition using federated learning. Completed the project with an excellent evaluation and contributed to patent application **CN116564339A**.

## Patents and Patent Applications

1. Pengbin Feng, **Le Gai**, Ning Xi. **Semantic-Enhanced Malware Detection Method for the Industrial Internet** (面向工业互联网的语义增强型恶意软件检测方法). Chinese patent application **CN202311455787.6**.

2. Pengbin Feng, Xuan Lv, **Le Gai**, et al. **APK Obfuscation Detection Based on Graph Attention Networks and NLP Word Embeddings** (基于图注意力网络与NLP词嵌入模型的APK混淆机制检测方法). Chinese patent application **CN202310897727.3**.

3. **Le Gai**, Yanbo Sun, Junwei Zhang. **Secure and Efficient In-Vehicle Speech Recognition Method and System Based on Federated Learning** (基于联邦学习的安全高效车机语音识别方法及系统). Chinese patent application publication **CN116564339A**.

## Selected Presentation

- Ning Zhang, **Le Gai**, Pengbin Feng. **Fast Calculation of National Commercial Cryptographic Algorithm Based on RISC-V Processing Core.** Oral presentation at **CCF ChinaSoft 2024**.

## Honors and Awards

### Scholarships and Academic Recognition

- National Scholarship.
- Tsinghua University First-Class Comprehensive Excellence Scholarship.
- Gratitude to Modern Chinese Scientists Scholarship.
- Lenovo Scholarship.
- QiAnXin Scholarship.
- National Encouragement Scholarship.
- Outstanding Student Leader and Outstanding Communist Youth League Member.

### Competitions

- **National First Prize**, China Undergraduate Mathematical Contest in Modeling.
- **National First Prize**, 8th National Cryptographic Technology Competition.
- **International Second Prize**, Mathematical Contest in Modeling.
- **National Second Prize**, 3rd IPv6 Technology Application Innovation Competition.
- **National Third Prize**, Chang'an Cup Collegiate Digital Forensics Competition.
- **Third Prize**, Xi'an Jiaotong University–NSFOCUS Joint CTF.
- **Grand Prize**, Spark Cup Student Academic and Technological Works Competition.
- **Second Prize**, Xidian University ACM Programming Competition.

## Leadership and Community

- **Core Member**, Tsinghua University Archery Association (礼射协会), September 2025–June 2026.
- **Core Member**, Youth League Committee, Institute for Network Sciences and Cyberspace, Tsinghua University, September 2025–June 2026.
- **President**, Xidian University Running Association, September 2022–June 2023.
- **Head of the Environmental Protection Department**, Xidian University Youth Volunteer Association, September 2022–June 2023.
- **Former Member, XDSEC**; joined in 2022 with a focus on Pwn challenges and binary exploitation.

## Technical Experience

- **Programming and web development:** Python, Django, database integration, and automated compliance testing.
- **Networking and security:** IPv4/IPv6 measurement, port scanning, service discovery, source address validation, protocol security, and malware analysis.
- **Machine learning:** graph neural networks, knowledge graphs, RotatE embeddings, LLM distillation, and federated learning.
- **Computer architecture and cryptography:** RISC-V and cryptographic algorithm acceleration.

## Technical Writing

Published **100+ technical articles and security write-ups** across GitHub, CSDN, and my personal website, with **1.5 million+ cumulative views** and **2,000+ followers** across platforms.
