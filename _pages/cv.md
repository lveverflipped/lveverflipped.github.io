---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* **Ph.D. in Robotics**, Shanghai Jiao Tong University (SJTU), 2024 – Present (Expected 2029)
  * Advisor: Prof. Zhongqiang Ren
* **B.S. in Mechanical Design, Manufacturing and Automation**, Huazhong University of Science and Technology (HUST), 2020 – 2024

## Research Interests
* Autonomous Exploration & Target Search
* Probabilistic Global Planning & Heuristic Search
* Multi-Robot Coordination & Distributed Planning
* Motion Planning with Theoretical Optimality Guarantees

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Research & Project Experience
* **RPT\*: Theoretical Global Planner for Probabilistic Target Search**
  * Formulated the Hamiltonian Path Problem with Probabilistic Terminals (HPP-PT).
  * Developed dynamic programming in transformed state spaces with admissible heuristics to break history dependency.
  * Deployed in the Hierarchical Autonomous Target Search (HATS) system for real-world and simulated unknown environment exploration.
* **MRPT\* / Multi-Robot Distributed Exploration**
  * Research on asynchronous multi-robot probabilistic target search and coverage planning under intermittent communication.

## Skills
* **Languages & Frameworks:** C++, Python, ROS / ROS2, Linux, Git, LaTeX
* **Core Domains:** Robot Motion Planning, SLAM, Combinatorial Optimization, Heuristic Search, Multi-Agent Systems
