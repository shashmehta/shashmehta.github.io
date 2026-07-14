---
layout: page
title: SCRIBE
description: Co-developed an open-source Python pipeline that ranks biomarker candidates from single-cell RNA-seq data, then presented the work at AACR in April 2026.
tags: [Python, AnnData, Random Forests, scRNA-seq]
github: https://github.com/shashmehta/SCRIBE
demo: https://shashmehta-scribe.hf.space/
img: assets/img/scribe_poster.jpg
importance: 0
category: Research & Software
related_publications: false
detail_page: true
---

<div class="detail-page case-study">
  <section class="detail-section detail-overview">
    <p class="eyebrow">Open-source computational biology project</p>
    <h2>Overview</h2>
    <p>
      SCRIBE stands for Single-Cell RNA Interpretable Biomarker Explorer. It is an open-source Python machine-learning
      pipeline that analyzes single-cell RNA-sequencing data and ranks biomarker candidates for further investigation.
      It does not clinically validate biomarkers or therapeutic targets.
    </p>
  </section>

  <section class="detail-section">
    <h2>Problem</h2>
    <p>
      Public single-cell datasets can arrive in different structures and include batch effects that complicate comparison.
      SCRIBE creates a repeatable path from GEO data to standardized analysis outputs while keeping the model’s ranked
      features visible to researchers.
    </p>
  </section>

  <section class="detail-section">
    <h2>Shashvat’s contribution</h2>
    <p>
      I co-developed SCRIBE with Pragnya Keerthivasan, working on the machine-learning pipeline, data analysis, model evaluation, and interpretation of ranked biomarker candidates. I also helped create and present our poster at the AACR Annual Meeting.
    </p>
  </section>

  <section class="detail-section">
    <h2>Technical approach</h2>
    <ol class="detail-steps">
      <li>Convert GEO datasets into a standard AnnData format.</li>
      <li>Merge datasets for combined analysis.</li>
      <li>Correct batch effects using ComBat or Harmony. Both methods are supported, although Harmony generally performed better in our testing.</li>
      <li>Train interpretable Random Forest classifiers.</li>
      <li>Generate UMAPs, volcano plots, differential-expression summaries, and feature-importance rankings.</li>
    </ol>
  </section>

  <section class="detail-section">
    <h2>Limitations</h2>
    <ul class="detail-impact">
      <li>Feature rankings identify candidates for follow-up; they are not clinical conclusions.</li>
      <li>The ranked candidates are not wet-lab validated.</li>
    </ul>
  </section>

  <section class="detail-section">
    <h2>AACR poster presentation</h2>
    <p>
      We presented SCRIBE as a research poster at the AACR Annual Meeting in San
      Diego in April 2026. The work was presented in poster format.
    </p>
    <div class="detail-media-grid">
      <div class="detail-image">{% include figure.liquid path="assets/img/aacr_2026_1.jpg" title="AACR poster presentation" alt="Shashvat Mehta presenting the SCRIBE research poster at AACR" %}</div>
      <div class="detail-image">{% include figure.liquid path="assets/img/aacr_2026_2.jpg" title="AACR poster presentation" alt="Shashvat Mehta and Pragnya Keerthivasan with the SCRIBE poster at AACR" %}</div>
      <div class="detail-image">{% include figure.liquid path="assets/img/aacr_2026_3.jpg" title="SCRIBE research poster" alt="SCRIBE research poster displayed at AACR" %}</div>
    </div>
    <div class="detail-poster">{% include figure.liquid path="assets/img/scribe_poster.jpg" title="SCRIBE research poster" alt="Research poster describing the SCRIBE pipeline" %}</div>
    {% comment %}Add the Zenodo poster record and DOI after the upload is complete.{% endcomment %}
  </section>

  <section class="detail-section">
    <h2>Project links</h2>
    <div class="detail-actions" aria-label="SCRIBE project links">
      <a href="https://github.com/shashmehta/SCRIBE">GitHub repository</a>
      <a href="https://shashmehta-scribe.hf.space/">Hugging Face demo</a>
      <a href="https://www.linkedin.com/posts/shashvat-mehta_im-so-grateful-for-the-recent-opportunity-activity-7453844212317323264-XH4B">LinkedIn Post</a>
    </div>
  </section>
</div>
