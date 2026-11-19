---
layout: page
title: Yonsei Private 5G & AI-RAN Testbed
description: 2026
permalink: /projects/yonsei-private-5g/
img: assets/img/rf/yonsei-testbed-equipment.png
importance: 0
category: RF communication
related_publications: false
---

At Yonsei’s Robotic and Mobile Networks Laboratory (RAMO), our team tested how commercial devices connect to a GPU-accelerated private 5G network.

{% include figure.liquid loading="eager" path="assets/img/rf/yonsei-testbed-equipment.png" alt="A Yberg 5G core and Falcon PTP switch connect four indoor and outdoor configurations using DGX Spark or H100 servers, commercial radio units, and a Keysight radio simulator. Test devices include phones, a 5G modem, and a Jackal robot." class="img-fluid rounded" zoomable=true caption="The indoor and outdoor testbeds share a 5G core and timing switch. The bottom row shows the phones, modem, and robot used with the testbeds." %}

## Private 5G over the air

Our campus testbed uses NVIDIA Aerial to run physical-layer processing on a GPU. A commercial radio unit serves the campus on Korea’s 4.7 GHz private 5G band (n79). The team connected an iPhone over the air and streamed YouTube video through the network. [NVIDIA Aerial Community Showcase](https://docs.nvidia.com/aerial/testbed/latest/text/community_showcase/index.html#yonsei-university)

Yonsei University and LG Uplus tested network switching between Yonsei’s AI-RAN testbed and LG Uplus’s commercial 5G network. As radio conditions changed, a Point Mobile PM95 automatically selected a network and stayed connected. [LG Uplus announcement](https://news.lguplus.com/22640)
