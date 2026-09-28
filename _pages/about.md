---
permalink: /
title: "Xinxin Chen (陈鑫鑫)"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
## About me

### Biography

I am a M.S. student at the School of Remote Sensing and Information Engineering, Wuhan University, Wuhan, China, supervised by Professor [Zhenzhong Chen](https://zhenzhong-chen.github.io/).

My research focuses on learned image compression, learned video compression, video frame interpolation and neural network-based video coding.

### Education

* M.S. student, School of Remote Sensing and Information Engineering, Wuhan University, Sep. 2025–present.
* B.Eng., School of Computer Science, Wuhan University, Sep. 2021–Jun. 2025.

## Publications

{% include base_path %}

### Journal Articles

{% assign journal_articles = site.publications | where: "category", "manuscripts" | sort: "date" | reverse %}
{% for post in journal_articles %}
  {% include archive-single.html %}
{% endfor %}

### Conference Papers

{% assign conference_papers = site.publications | where: "category", "conferences" | sort: "date" | reverse %}
{% for post in conference_papers %}
  {% include archive-single.html %}
{% endfor %}

## Standardization Proposals

{% assign standardization_page = site.pages | where: "proposal_source", true | first %}

<ol>
{% for proposal in standardization_page.proposals %}
<li>{{ proposal.citation | replace: "Xinxin Chen", "<strong>Xinxin Chen</strong>" }}{% if proposal.adopted %} <strong>[Adopted]</strong>{% endif %}</li>
{% endfor %}
</ol>

## Competitions

1. **1st Place**, CPU Track, 7th Challenge on Learned Image Compression (CLIC 2025), 2025.
2. **1st Place**, "AI + Image Coding" Track, 5th National Artificial Intelligence Competition (NAIC 2025), 2025.
3. **National Second Prize**, "Huawei Cup" China Postgraduate Mathematical Contest in Modeling, 2025.
4. **3rd Place**, 6th Challenge on Learned Image Compression (CLIC 2024), 2024.
5. **2nd Place**, 3rd Practical End-to-End Image Compression Challenge, 2024.
6. **National Second Prize**, "Huawei Cup" China Postgraduate Mathematical Contest in Modeling, 2024.
7. **National Second Prize**, China Undergraduate Mathematical Contest in Modeling (CUMCM), 2022.

## Honors

1. Outstanding Graduate Student Academic Scholarship (First Class), Wuhan University, 2024.
2. Outstanding Graduate Student, Wuhan University, 2024.
3. Outstanding Undergraduate Academic Scholarship (Third Class), Wuhan University, 2022.
4. Outstanding Undergraduate Academic Scholarship (Third Class), Wuhan University, 2021.
