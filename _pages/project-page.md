---
title: "Project"
layout: splash
permalink: /project-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/project_header.jpg
  # actions:
    # - label: "Download"
      # url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Here is the portfolio of my past projects."

intro: 
  - excerpt: 'Topics include recommender systems, data visualization and software engineering.'

project_row:
  - image_path: assets/images/spatial_plot.png
    alt: "recsys Yelp"
    title: "Local business recommendation"
    excerpt: "Implement several classic recommender system algorithms and conduct extensive experiments on Yelp dataset."
    url: "https://github.com/HenryNebula/Personalization_Final"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/edav_resized.jpg
    title: "NYC Citywide Mobility Visualization"
    excerpt: "Visualize citywide human mobility in the city of New York with analysis of travelling habit and growth of ride hail services"
    url: "https://skyetim.github.io/citywide_mobility_survey/"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/plantsvszombies_resized.jpg
    alt: "plant vs zombie (Java)"
    title: "Plants vs Zombies using Java"
    excerpt: "Project of java programming course, with multi-level difficulties and smooth animation. Powered by LibGDX framework."
    url: "/project/plantsvszombies"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="project_row"%}

<!-- {% include feature_row id="feature_row2" type="left" %} -->

<!-- {% include feature_row id="feature_row3" type="right" %} -->

<!-- {% include feature_row id="feature_row4" type="center" %} -->