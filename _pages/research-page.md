---
title: "Research"
layout: splash
permalink: /research-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/research_header.jpg
  # actions:
    # - label: "Download"
      # url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Here is the portfolio of my past research projects."

intro: 
  - excerpt: 'Topics include recommender systems, data privacy, data visualization and etc.'

research_row:
  - image_path: assets/images/crowdsourcing_system_resized.jpg
    alt: "placeholder image 1"
    title: "Private Mobile Crowdsourcing"
    excerpt: "Allocate location based crowdsourcing tasks to participants with privacy protection, while maximizing spatial coverage at the same time."
    url: "research/private_crowdsourcing"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/cross-domain-framework_resized.jpg
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Private Cross-Domain Recommender System"
    excerpt: "Provide a privacy preserving way to build recommender systems with sensitive auxiliary information."
    url: "research/private_recsys"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/isochrone_resized.jpg
    title: "Data-driven Reachability Visualization"
    excerpt: "Visualize reachability using isochrone map and taxi trajectory dataset. Construct an interactive web interface for user query."
    url: "research/reachability"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="research_row"%}

<h1><center>Publications</center></h1>

* **Chao Huang**, Fengli Xu, Yong Li, Xinlei Chen, Pei Zhang, Poster Abstract: Locally Differentially Private Participant Recruitment for Mobile Crowdsourcing, _In the Proceedings of the 16th ACM Conference on Embedded Networked Sensor Systems_

* Chen Gao, **Chao Huang**, Yue Yu, Huandong Wang, Yong Li, Depeng Jin, Privacy-preserving Cross-domain Location Recommendation, _In the Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, Volume 3 Issue 1, March 2019_

* Chrysovalantis Anastasiou, **Chao Huang**, Seon Ho Kim, Cyrus Shahabi, Time-Dependent Reachability Analysis: A Data-Driven Approach, _2019 20th IEEE International Conference on Mobile Data Management (MDM), Hong Kong, 2019_