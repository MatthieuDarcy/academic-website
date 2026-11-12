---
layout: page
permalink: /research/dynamical-systems/
title: Dynamical systems
description:
nav: false
---

I develop and implement algorithms to simulate, learn and control dynamical systems: inferring their states and parameters from noisy, partial observations, and choosing actions that steer them toward a goal. With Dynestyx, our open-source probabilistic programming library, a model is written once and can then be simulated, filtered, smoothed, calibrated or controlled, across discrete- and continuous-time, deterministic and stochastic systems.

#### Relevant research

<div class="publications">
  <!-- Software: same row markup as a bibliography entry so it picks up the publication styling -->
  <ol class="bibliography">
    <li>
      <div class="row">
        <div class="col col-sm-4 abbr">
          <figure>
            <video
              class="preview z-depth-1 rounded"
              src="{{ '/assets/video/dynestyx-logo.mp4' | relative_url }}"
              poster="{{ '/assets/img/research/dynestyx-logo.png' | relative_url }}"
              aria-label="dynestyx logo"
              width="100%"
              autoplay
              muted
              loop
              playsinline
            ></video>
          </figure>
        </div>
        <div class="col-sm-8">
          <div class="title">Dynestyx: an open source library for dynamical systems</div>
          <div class="periodical">
            Probabilistic programming for dynamical systems, built on NumPyro: deterministic and stochastic, discrete- and continuous-time models.
          </div>
          <div class="links">
            <a href="https://www.basis.ai/blog/dynestyx/" class="btn btn-sm z-depth-0" role="button">Blog</a>
            <a href="https://github.com/BasisResearch/dynestyx" class="btn btn-sm z-depth-0" role="button">Code</a>
            <a href="https://basisresearch.github.io/dynestyx/" class="btn btn-sm z-depth-0" role="button">Docs</a>
          </div>
        </div>
      </div>
    </li>
  </ol>

{% bibliography --group_by none --query @*[key=darcy2023oneshot] %}
{% bibliography --group_by none --query @*[key=darcy2025kernelflows] %}
{% bibliography --group_by none --query @*[key=batlle2025alzheimer] %}

</div>
