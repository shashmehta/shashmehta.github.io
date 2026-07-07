---
layout: page
title: SCRIBE
description: Explainable machine learning for single-cell RNA-seq biomarker discovery
img: assets/img/scribe_poster.jpg
importance: 0
category: Work
related_publications: false
detail_page: true
---

<div class="detail-page">
  <section class="detail-section detail-overview">
    <p>
      SCRIBE, the Single-Cell RNA Interpretable Biomarker Explorer, is a Python machine learning pipeline for identifying
      potential cancer biomarkers and therapeutic targets from single-cell RNA sequencing data.
    </p>
    <p>
      The pipeline converts raw GEO datasets into a standard AnnData format, merges datasets, corrects batch effects with
      ComBat or Harmony, trains interpretable Random Forest classifiers, and generates visual outputs such as UMAPs,
      volcano plots, differential expression summaries, and feature-importance rankings.
    </p>
    <div class="detail-actions" aria-label="SCRIBE project links">
      <a href="https://github.com/shashmehta/SCRIBE">View GitHub Repository</a>
      <a href="https://shashmehta-scribe.hf.space/">Open Hugging Face Demo</a>
    </div>
  </section>

  <section class="detail-section">
    <h2>Research Poster</h2>
    <div class="detail-poster">
      {% include figure.liquid path="assets/img/scribe_poster.jpg" title="SCRIBE research poster" alt="SCRIBE research poster" %}
    </div>
  </section>
</div>
