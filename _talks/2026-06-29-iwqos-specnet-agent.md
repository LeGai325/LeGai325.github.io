---
i18n_key: iwqos-specnet-agent
title: "SpecNet-Agent: Network-Aware Speculation Control for QoS in Agentic Generative AI Services"
collection: "talks"
layout: "archive"
author_profile: true
permalink: "/talks/2026-06-29-iwqos-specnet-agent/"
date: "2026-06-29"
display_date: "29 June 2026"
event: "IEEE/ACM IWQoS 2026 · NetGenAI Workshop"
short_title: "SpecNet-Agent: Network-Aware Speculation Control"
venue: "NetGenAI 2026 Workshop, co-located with IEEE/ACM IWQoS 2026"
type: "Workshop paper presentation"
location: "Istanbul, Türkiye"
excerpt: "Controlling speculative work in agentic AI services using workflow dependencies and network feedback to improve latency and reduce wasted communication."
resources:
  - label: "Paper"
    url: "https://ieeexplore.ieee.org/abstract/document/11661032/"
  - label: "Workshop program"
    url: "https://iwqos2026.ieee-iwqos.org/workshops-program"
photos: []
---

{% include talk-meta.html %}

I presented SpecNet-Agent in the Network for LLM Serving session of the NetGenAI 2026 Workshop, co-located with IEEE/ACM IWQoS 2026.

The talk examined how speculative retrieval and parallel tool requests affect quality of service when agentic AI workflows share constrained network resources. SpecNet-Agent uses workflow dependencies and network feedback to adjust speculative work at its source. I discussed the control design and evaluation of its effects on tail latency and wasted communication under congestion.

{% include talk-resources.html %}

{% include talk-photos.html %}

<!-- Add photos in the front-matter photos list. The first image also appears on /talks/. -->
