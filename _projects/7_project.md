---
layout: page
title: Searching Engine for Standard Documents
description: 2024
img: assets/img/sw/searching_engine_flow.png
importance: 7
category: software development
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sw/searching_engine_flow.png" title="searching_engine_flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Automated Retrieval & Search System for Technical Standards
</div>

Developed an intelligent search and analysis pipeline to automate information retrieval from extensive standard documents.

By automating the full cycle of crawling, refining, and structured DB integration, this system significantly enhances data accessibility. Following the successful implementation of full-text keyword search, the framework is now evolving toward a RAG-powered system for sophisticated, context-aware query responses.

<br>

<h3><b>⚙️ Searching Engine for IEEE 802.11 standard documents</b></h3>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sw/searching_engine_80211_example.png" title="searching_engine_80211_example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example screen of searching engine for IEEE 802.11 standard documents (MongoDB Compass)
</div>

Developed an automated document retrieval and search system to efficiently manage and explore extensive IEEE 802.11 standard documents.

I built a comprehensive pipeline for web crawling, data refining, and downloading. By architecting a structured database in MongoDB, I enabled advanced keyword search capabilities that cover both document titles and full-text contents, significantly improving the accessibility of technical standards.

- <b>End-to-End Automation Pipeline</b>: Developed a comprehensive pipeline that automates the entire process of crawling, refining, and downloading IEEE 802.11 standard documents.

- <b>Web Scraping & Metadata Extraction</b>: Extract critical metadata, including DCN, Revision, Title, Author, and Affiliation from the IEEE Mentor site.

- <b>Advanced Data Post-processing</b>: Resolved data inconsistencies, such as varying affiliation names and revision tracking, ensuring high data integrity within the system.

- <b>Structured Database Architecture</b>: Designed and implemented a MongoDB schema to systematically organize documents by topic, session, and affiliation.

- <b>Full-Text Keyword Search</b>: Enhanced searchability by enabling keyword queries across both document titles and complete content bodies within the database.
