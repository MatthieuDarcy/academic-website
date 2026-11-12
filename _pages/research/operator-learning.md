---
layout: page
permalink: /research/operator-learning/
title: Operator learning
description:
nav: false
---

I study methods for learning maps between infinite-dimensional function spaces, such as the solution operators of PDEs. These models serve as fast surrogates for expensive simulations in engineering and the sciences, from design and uncertainty quantification to many-query and real-time settings, and can be pushed to machine precision.

<link rel="stylesheet" href="{{ '/assets/css/research-pages.css' | relative_url | bust_file_cache }}">

#### Relevant research

<div class="publications">
{% bibliography --group_by none --query @*[key=batlle2024kernel] %}

  <!-- Tutorial: same row markup as a bibliography entry so it picks up the publication styling -->
  <ol class="bibliography">
    <li>
      <div class="row">
        <div class="col col-sm-2 abbr">
          <figure>
            <img
              class="preview z-depth-1 rounded"
              src="{{ '/assets/img/research/tutorial-darcy-fields.png' | relative_url }}"
              alt="Darcy flow: input coefficient field and output solution field"
              width="100%"
              loading="lazy"
            >
          </figure>
        </div>
        <div id="operator-tutorial" class="col-sm-8">
          <div class="title">Tutorial: Kernels and FNO for operator learning</div>
          <div class="periodical">
            Gaussian processes and Fourier neural operators applied to Burgers' equation and to an elliptic coefficient-to-solution map.
          </div>
          <div class="links">
            <a href="https://github.com/MatthieuDarcy/OperatorLearningTutorial/" class="btn btn-sm z-depth-0" role="button">Code</a>
            <a
              href="https://github.com/MatthieuDarcy/OperatorLearningTutorial/blob/main/presentations/Research_presentation_berne.pdf"
              class="btn btn-sm z-depth-0"
              role="button"
              >Slides</a
            >
          </div>
        </div>
      </div>
    </li>
  </ol>

{% bibliography --group_by none --query @*[key=bacho2025machine] %}
</div>
