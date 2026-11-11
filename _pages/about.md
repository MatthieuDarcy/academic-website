---
layout: about
title: About
permalink: /
subtitle: Machine Learning Research Scientist, <a href='https://www.basis.ai/'>Basis Research Institute</a>

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>New York, NY</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a machine learning research scientist at the [Basis Research Institute](https://www.basis.ai/) in New York.

I obtained my PhD in Computing and Mathematical Sciences from Caltech, where I was advised by [Houman Owhadi](http://users.cms.caltech.edu/~owhadi/index.htm).

[CV](https://github.com/MatthieuDarcy/AcademicRepo/blob/main/CV/CV_matthieu_darcy.pdf?raw=true) · [Google Scholar](https://scholar.google.com/citations?user=_KSmKigAAAAJ&hl=en)

<!-- Research areas: cards are generated from _data/research_areas.yml -->
<link rel="stylesheet" href="{{ '/assets/css/research-areas.css' | relative_url | bust_file_cache }}">
<div class="research-areas">
  <h2>Research areas</h2>
  <div class="ra-grid">
    {% for area in site.data.research_areas %}
      <a class="ra-card" href="{{ area.url | relative_url }}">
        <div class="ra-media">
          {% if area.video %}
            <video
              src="{{ area.video | relative_url }}"
              poster="{{ area.poster | relative_url }}"
              aria-label="{{ area.alt }}"
              autoplay
              muted
              loop
              playsinline
            ></video>
          {% elsif area.image %}
            <img src="{{ area.image | relative_url }}" alt="{{ area.alt }}" loading="lazy">
          {% endif %}
        </div>
        <div class="ra-head">
          <span class="ra-icon"><i class="{{ area.icon }}"></i></span>
          <h3 class="ra-title">{{ area.title }}</h3>
          <i class="fa-solid fa-chevron-right ra-chevron"></i>
        </div>
        <p class="ra-desc">{{ area.description }}</p>
        <div class="ra-tags">
          {% for tag in area.tags %}<span class="ra-tag">{{ tag }}</span>{% endfor %}
        </div>
      </a>
    {% endfor %}
  </div>
</div>
