---
layout: archive
title: "Competitions"
permalink: /awards/
author_profile: true
competition_source: true
competitions:
  - "2nd Place, EventAid Frame Interpolation Challenge at the Event-Based Multimodal Vision: Imaging, Perception, and Understanding (EBMV) in conjunction with ECCV, 2026."
  - "1st Place, Extreme 16X Track of the High FPS Video Frame Interpolation Challenge at New Trends in Image Restoration and Enhancement (NTIRE) in conjunction with CVPR, 2026."
  - "1st Place, Classic Track of the High FPS Video Frame Interpolation Challenge at New Trends in Image Restoration and Enhancement (NTIRE) in conjunction with CVPR, 2026."
  - "National First Prize, \"Huawei Cup\" China Postgraduate Mathematical Contest in Modeling (CPMCM), 2025"
  - "Third Prize, in Provincial Division, Python Programming Category (Group A), the 16th Blue Bridge Cup, 2025."
  - "Finalist, Mathematical Contest in Modeling / Interdisciplinary Contest in Modeling (MCM/ICM), 2024"
  - "Second Prize, in Provincial Division, Python Programming Category (Group A), the 15th Blue Bridge Cup, 2024."
  - "National Second Prize, 2023 (16th) Chinese Collegiate Computing Competition (4C), 2023"
  - "Third Prize, in the University-Level Division, Non-Mathematics Category, the 14th Chinese Mathematics Competitions (CMC), 2023."
  - "Second Prize, in Provincial Division, Network Technology Challenge, China Collegiate Computing Contest (C4), 2023."
  - "Second Prize, in Provincial Division, China Undergraduate Mathematical Contest in Modeling (CUMCM), 2023."
---
## Competitions

<ol>
{% for item in page.competitions %}
{% assign rank = item | split: "," | first %}
<li><strong>{{ rank }}</strong>{{ item | remove_first: rank }}</li>
{% endfor %}
</ol>
