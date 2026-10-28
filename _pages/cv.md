---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in Software Engineering, School of Computer Science and Engineering, Hunan University of Information Technology, Changsha, China (expected graduation: June 2027)

Research experience
======
* 2026–present: Undergraduate research on retrieval for local LLM systems
  * School of Computer Science and Engineering, Hunan University of Information Technology
  * Supervisor: Xin Xie
  * Work: unified-candidate-space offline evaluation of hybrid (BM25 + BGE-M3) retrieval with RRF fusion and per-source quotas, in a desktop RAG stack
  * Output: paper accepted at MLEIL 2026, with a public reproduction bundle

Skills
======
* Programming
  * Python (analysis and pipelines)
  * Rust (retrieval core)
  * TypeScript, Kotlin (application front ends)
* Systems
  * SQLite FTS5 full-text search
  * Local embedding inference and on-device deployment
  * Tauri desktop applications
* Evaluation methods
  * Paired bootstrap interval estimates
  * Multi-rater relevance labelling and inter-rater agreement
  * Frozen-input reproducibility practice
* Languages
  * Chinese (native)
  * English (technical reading and writing)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% if site.talks.size > 0 %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endif %}

{% if site.teaching.size > 0 %}
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
