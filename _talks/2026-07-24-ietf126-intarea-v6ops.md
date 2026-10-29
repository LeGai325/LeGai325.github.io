---
i18n_key: ietf126-intarea-v6ops
title: "IP Tunnel Security and IPv6 Extension Header Measurements at IETF 126"
collection: "talks"
layout: "archive"
author_profile: true
permalink: "/talks/2026-07-24-ietf126-intarea-v6ops/"
date: "2026-07-24"
display_date: "22 & 24 July 2026"
event: "IETF 126"
short_title: "IP Tunnel Security and IPv6 Extension Header Measurements"
venue: "IETF 126 — INTAREA and V6OPS Working Groups"
type: "Two working-group presentations"
location: "Vienna, Austria"
excerpt: "Two presentations on individual Internet-Drafts: security requirements for IP tunnel nodes and observations of IPv6 Extension Header reachability and filtering behavior."
resources:
  - label: "INTAREA session"
    url: "https://datatracker.ietf.org/meeting/126/session/intarea"
  - label: "V6OPS session"
    url: "https://datatracker.ietf.org/meeting/126/session/v6ops"
photos:
  - src: "/images/talks/ietf126-v6ops-presentation.jpg"
    alt: "Conference room during the IETF 126 V6OPS presentation"
    caption: "V6OPS presentation · Vienna · 24 July 2026."
  - src: "/images/talks/ietf126-group-photo.jpg"
    alt: "Group photograph outside the IETF 126 venue in Vienna"
    caption: "IETF 126 group photo · Vienna · July 2026."
---

{% include talk-meta.html %}

At IETF 126, I gave two working-group presentations on individual Internet-Drafts that I co-authored, connecting our network-security research with discussions of operational requirements and measurement practice.

## INTAREA · 22 July 2026

Security Requirements for IP Tunnel Nodes. I presented proposed safeguards for tunnel nodes, including peer authorization, source-address validation, limits on encapsulation and forwarding, and handling of IPv6 Extension Headers. The discussion helped refine the scope of the draft and its relationship to existing guidance.

[Internet-Draft](https://datatracker.ietf.org/doc/draft-gai-intarea-ip-tunnel-node-security/) · [Meeting slides](https://datatracker.ietf.org/meeting/126/materials/slides-126-intarea-security-requirements-for-ip-tunnel-nodes-00)

## V6OPS · 24 July 2026

Observations on the Reachability and Evasion of Packets with IPv6 Extension Headers on the Internet. I shared measurements of packet reachability and filtering behavior across Extension Header configurations. The discussion addressed the interpretation of the results, including protocol selection, vantage-point coverage, and measurement bias.

[Internet-Draft](https://datatracker.ietf.org/doc/draft-zedongjia-v6ops-ipv6eh-measurement/) · [Meeting slides](https://datatracker.ietf.org/meeting/126/materials/slides-126-v6ops-observations-on-the-reachability-and-evasion-of-packets-with-ipv6-extension-headers-on-the-internet-00)

{% include talk-resources.html %}

{% include talk-photos.html %}

<!-- Add photos in the front-matter photos list. The first image also appears on /talks/. -->
