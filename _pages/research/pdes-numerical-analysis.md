---
layout: page
permalink: /research/pdes-numerical-analysis/
title: PDEs & numerical analysis
description:
nav: false
---

I develop principled algorithms for PDEs that are out of reach of classical solvers, such as equations with rough forcing and functional PDEs posed on infinite-dimensional spaces. These kernel, Gaussian process and neural network methods come with convergence guarantees.

<link rel="stylesheet" href="{{ '/assets/css/research-pages.css' | relative_url | bust_file_cache }}">

#### Relevant research

<div class="publications">
{% bibliography --group_by none --query @*[key=baptista2026rough] %}
{% bibliography --group_by none --query @*[key=yang2025functional] %}
</div>
