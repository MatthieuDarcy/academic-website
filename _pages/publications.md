---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>preprints</h2>

{% bibliography --query @misc %}

<h2>journal articles</h2>

{% bibliography --query @article %}

</div>
