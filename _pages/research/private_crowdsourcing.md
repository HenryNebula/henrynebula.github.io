---
title: "Private Mobile Crowdsourcing"
layout: single
permalink: 'research/private_crowdsourcing'

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/crowdsourcing_system.jpeg

excerpt: "A Locally Differentially Private Framework of Participant Recruitment"
---

## Background 

Mobile crowdsourcing tasks send out participants with sensor-equipped smartphones and wish to collect urban-scale information with large spatial coverage. However, the number of participants is usually limited due to budget or time constraints. Also, participants risk their location privacy when reporting data with their actual sensing positions

## Objective

Creating a participant recruitment framework which not only preserves a participant’s privacy but also maximizes the spatial coverage of the collected data.

## Challenges

* The data collector is untrusted and that a malicious adversary could possess arbitrary ​side channel information.
* Existing decoding algorithms for privacy protection models were only able to detect heavy-hitters (e.g. RAPPOR).
* Even without the presence of noisy location data, the maximum coverage problem is a NP-hard combinatorial optimization problem

## Solutions

* Adopted ​randomized response, a Differential Privacy mechanism, as the privacy model best suited to meet our application requirements.
* Proposed a new decoding algorithm that utilized ​Bayesian Inference. Given obfuscated reports collected from a crowd of participants, it succinctly models the probability distribution whether each location can actually be covered.
* Proposed a heuristic that substituted a candidate between the chosen crowd and the unchosen crowd for higher posterior. It converges quickly to a near-optimal group of participants.

## Publication

Finished a poster and presented it at Sensys 2018 **[[link]](https://dl.acm.org/doi/10.1145/3274783.3275164)**.