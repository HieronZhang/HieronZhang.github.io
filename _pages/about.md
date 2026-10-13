---
layout: about
title: about
permalink: /
subtitle: PhD candidate in Computer Science at <a href="https://illinois.edu">UIUC</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false
latest_posts:
  enabled: false
---

<style>
  .profile { max-width: 170px; }
  .post article h2 { margin-top: 2.2rem; margin-bottom: 0.6rem; }
</style>

I am a PhD candidate at the University of Illinois Urbana-Champaign, advised by [Prof. Minjia Zhang](https://minjiazhang.github.io/). My research is on efficient systems for AI on emerging hardware (e.g., CPU--GPU superchips), in particular how LLM serving and training interact with the memory hierarchy, interconnects, and GPU kernels. I previously worked on memory and storage systems.

[CV](/files/haoyang_phd_CV.pdf) / [Google Scholar](https://scholar.google.com/citations?user=_K6YgAkAAAAJ) / [GitHub](https://github.com/HieronZhang)

## News

{% include news.liquid limit=true %}

## Selected Publications

{% include selected_papers.liquid %}

Two more papers on ML systems are under review; details on request. See all [publications](/publications/).

## Open Source

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo.liquid repository="torch-spyre/torch-spyre" %}
</div>

I contributed the analytical cost model to torch-spyre ([PR #3572](https://github.com/torch-spyre/torch-spyre/pull/3572), [documentation](https://github.com/torch-spyre/torch-spyre/blob/main/docs/source/compiler/cost_model.md)).

## Industry Experience

<div class="row mb-2"><div class="col-sm-3 text-muted">May--Aug 2026</div><div class="col-sm-9"><b>IBM Research</b>, Yorktown Heights, NY. Research Intern, Hybrid Cloud (mentor: David Grove). Built an analytical cost model as a compiler pass for the Spyre AI accelerator in open-source <a href="https://github.com/torch-spyre/torch-spyre/pull/3572">torch-spyre</a>.</div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">Jul--Aug 2021</div><div class="col-sm-9"><b>T-Head Division, Alibaba Cloud</b>, Hangzhou, China. Software R&amp;D Intern. Optimized the JPEG library for RISC-V vector processors.</div></div>

## Education

<div class="row mb-2"><div class="col-sm-3 text-muted">2022--2028 (expected)</div><div class="col-sm-9"><b>University of Illinois Urbana-Champaign</b>. Ph.D., Computer Science. Advisor: <a href="https://minjiazhang.github.io/">Prof. Minjia Zhang</a>.</div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">2020--2022</div><div class="col-sm-9"><b>University of Michigan</b>. B.S.E., Computer Engineering (dual degree).</div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">2018--2022</div><div class="col-sm-9"><b>Shanghai Jiao Tong University</b>. B.S.E., Electrical and Computer Engineering (dual degree).</div></div>

## Talks

<div class="row mb-2"><div class="col-sm-3 text-muted">Mar 2025</div><div class="col-sm-9">SkyByte at NVMW 2025 and HPCA 2025, Las Vegas. <a href="/files/SkyByte-talk.pdf">Slides</a></div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">Mar 2024</div><div class="col-sm-9">G10 at NVMW 2024, San Diego. <a href="/files/G10-talk-nvmw.pdf">Slides</a></div></div>

## Honors, Teaching & Service

<div class="row mb-2"><div class="col-sm-3 text-muted">Honors</div><div class="col-sm-9">MICRO 2023 Travel Grant; Roger King Scholarship (2021), University Honors (2021), and Dean's List (2020, 2021), University of Michigan.</div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">Teaching</div><div class="col-sm-9">UIUC: Graduate TA, Computer Architecture (CS 233), FA 2024, SP 2025, FA 2025.<br>SJTU: TA, Computer Architecture (VE 470), SU 2022; Honors Physics (VP 160), SU 2020.</div></div>
<div class="row mb-2"><div class="col-sm-3 text-muted">Service</div><div class="col-sm-9">Artifact Evaluation Committee, <a href="https://hpca-conf.org/2025/">HPCA 2025</a>.</div></div>
