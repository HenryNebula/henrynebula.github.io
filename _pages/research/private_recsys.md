---
title: "Private Cross Domain Recommender System"
layout: single
permalink: 'research/private_recsys'

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/cross-domain-framework.jpg

excerpt: "Cross-domain Location Recommendation With Privacy Protection"
---

## Objective
* Leveraging cross-domain dataset to overcome the cold-start and data sparsity problem, which is common in POI (point of interests) recommendation problems
* Protecting user privacy while preserving utility of data from the auxiliary domain

## Challenges
* No existing privacy protection model for cross-domain recommender system
* Decoding obfuscated data to improve the accuracy of recommendation requires novel decoding algorithm designs

## Solutions
* Generalized a powerful location-privacy preserving model, ​geo-indistinguishability, to restrict obfuscation within the same category of locations.
* Calculated a confidence score for each obfuscated interaction to reflect on what scale the collective matrix factorization (CMF) trusts each record.

## Publication
Accepted by IMWUT 2019 as a full paper **[[link]](https://dl.acm.org/doi/abs/10.1145/3314398)**.