---
title: "Data-driven Reachability Visualization"
layout: single
permalink: 'research/reachability'

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/isochrone.jpg

excerpt: "Data-driven Reachability Research Using Isochrone Map"
---

## Objective
* Given a safety center (shown as a orange triangle or a red alert sign in the figure), find all areas that an ambulance leaving this safety center can reach, within a limited time in an emergency response scenario.
* Also, we want to provide new perspective to assess the placement of public services like hospitals and fire departments in urban planning.

## Challenges

* Choosing proper visualization model covering most reachable areas without introducing unreachable areas
* Proposing fast query data structures for online query and display

## Solutions & Results

* Proposed a novel visualization model which is purely data-driven, by creating a spatial buffer around each trajectory (shown as the orange area in the figure)
* Optimized query time through data preprocessing and creating indexes; demonstrated results in a user-friendly Node.js application

## Submission

* Accepted by MDM 19 as a short paper **[[link]](https://ieeexplore.ieee.org/abstract/document/8788795)**.

