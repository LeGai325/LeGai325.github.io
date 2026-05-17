---
title: "TED: Abusing Tunnel Hosts and IPv6 Extension Headers for Pulsing DoS Attacks"
collection: publications
category: conferences
date:  2026-5-18 
venue: 'USENIX Security 2026'
citation: 'Le Gai, Zedong Jia, Lin He, Daguo Cheng, Chentian Wei, Ying Liu. &quot;TED: Abusing Tunnel Hosts and IPv6 Extension Headers for Pulsing DoS Attacks.&quot; <i>USENIX Security 2026</i>.'
---

IP tunneling mechanisms are widely deployed to facilitate the Internet's transition from IPv4 to IPv6, yet their security implications remain insufficiently scrutinized. In this paper, we present TED, a novel pulsing denial-of-service attack that exploits structural vulnerabilities in IP tunneling and IPv6 Extension Headers (EHs) processing. Unlike prior amplification attacks that depend on application-layer services, TED operates entirely at the network layer, requiring no victim interaction, prolonged traffic accumulation, or protocol-specific dependencies. Delay lines are constructed by TED through nested EHs, capitalizing on the tunnel hosts' blind forwarding logic and lack of deep packet inspection. These artificial delay lines allow attackers to solve the send-time schedule problem, converging asynchronous, low-rate traffic into a destructive, high-magnitude pulse at the victim. Our Internet-wide measurement identified over 1.9 million vulnerable tunnel hosts acting as unwitting relays, including hosts within critical satellite infrastructure. Evaluation results demonstrate that TED achieves an effective amplification factor exceeding 180×× while successfully evading existing low-rate and pulsing attack detection mechanisms based on specific application layer protocols. We discuss the root causes of these transitional vulnerabilities and possible mitigation strategies for network operators and equipment vendors.
