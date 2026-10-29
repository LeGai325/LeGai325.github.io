---
i18n_key: usenix-security-ted
title: "TED: Abusing Tunnel Hosts and IPv6 Extension Headers for Pulsing DoS Attacks"
collection: "talks"
layout: "archive"
author_profile: true
permalink: "/talks/2026-08-12-usenix-security-ted/"
date: "2026-08-12"
display_date: "12–14 August 2026"
event: "USENIX Security ’26"
short_title: "TED: Tunnel Hosts, IPv6 Extension Headers, and Pulsing DoS"
venue: "35th USENIX Security Symposium"
type: "Conference paper presentation"
location: "Baltimore, Maryland, USA"
excerpt: "A study of how IP tunneling and IPv6 Extension Header processing can concentrate low-rate traffic into disruptive pulses, with Internet-wide measurements and mitigation implications."
resources:
  - label: "Paper & presentation"
    url: "https://www.usenix.org/conference/usenixsecurity26/presentation/gai"
  - label: "Technical program"
    url: "https://www.usenix.org/conference/usenixsecurity26/technical-sessions"
photos:
  - src: "/images/talks/security26.jpg"
    alt: "TED: Tunnel Hosts, IPv6 Extension Headers, and Pulsing DoS"
    caption: "Baltimore · USENIX Security 2026."
---

{% include talk-meta.html %}

I presented TED, our study of a pulsing denial-of-service threat arising from the interaction between IP tunneling and IPv6 Extension Header processing. The talk explained how forwarding behavior and packet-processing delays can combine to concentrate otherwise low-rate traffic into disruptive bursts.

I covered the underlying protocol weaknesses, our Internet-wide measurement of exposed tunnel hosts, and the implications for network operators and equipment vendors. The discussion focused on reducing unsafe forwarding behavior and strengthening the handling of encapsulated traffic.

{% include talk-resources.html %}

{% include talk-photos.html %}

<!-- Add photos in the front-matter photos list. The first image also appears on /talks/. -->
