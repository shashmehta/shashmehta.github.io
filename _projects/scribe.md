---
layout: page
title: SCRIBE
description: Explainable machine learning for single-cell RNA-seq biomarker discovery
img: assets/img/scribe_poster.jpg
importance: 0
category: Research Projects
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
    <p>
      In April 2026, Pragnya Keerthivasan and I presented SCRIBE at the American Association for Cancer Research Annual
      Meeting in San Diego. The experience gave us the chance to share our work with cancer researchers, learn from
      other projects in the field, and see how AI and computational tools are becoming more important in cancer research.
    </p>
    <div class="detail-actions" aria-label="SCRIBE project links">
      <a href="https://github.com/shashmehta/SCRIBE">View GitHub Repository</a>
      <a href="https://shashmehta-scribe.hf.space/">Open Hugging Face Demo</a>
      <a href="https://www.linkedin.com/posts/shashvat-mehta_im-so-grateful-for-the-recent-opportunity-activity-7453844212317323264-XH4B">View AACR Post</a>
    </div>
  </section>

  <section class="detail-section">
    <h2>AACR Presentation</h2>
    <div class="detail-media-grid">
      <div class="detail-image">
        {% include figure.liquid path="assets/img/aacr_2026_1.jpg" title="AACR presentation photo" alt="Shashvat Mehta presenting SCRIBE at AACR" %}
      </div>
      <div class="detail-image">
        {% include figure.liquid path="assets/img/aacr_2026_2.jpg" title="AACR presentation photo" alt="SCRIBE presentation at AACR" %}
      </div>
      <div class="detail-image">
        {% include figure.liquid path="assets/img/aacr_2026_3.jpg" title="AACR presentation photo" alt="SCRIBE research poster at AACR" %}
      </div>
      <div class="detail-image">
        {% include figure.liquid path="assets/img/aacr_2026_4.jpg" title="AACR presentation photo" alt="AACR conference photo for SCRIBE" %}
      </div>
    </div>
  </section>

  <section class="detail-section">
    <h2>Research Poster</h2>
    <div class="detail-poster">
      {% include figure.liquid path="assets/img/scribe_poster.jpg" title="SCRIBE research poster" alt="SCRIBE research poster" %}
    </div>
  </section>
</div>
