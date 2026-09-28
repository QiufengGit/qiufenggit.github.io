---
permalink: /
title: "Xinxin Chen (陈鑫鑫)"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
## About me {#about}

### Biography

I am an M.S. student at the [Institute of Artificial Intelligence and Machine Perception](https://iip.whu.edu.cn/index.html), School of Remote Sensing and Information Engineering, Wuhan University, Wuhan, China, supervised by Professor [Zhenzhong Chen](https://zhenzhong-chen.github.io/).

My research focuses on learned video compression, video frame interpolation and neural network-based video coding.

### Education

* M.S. student, School of Remote Sensing and Information Engineering, Wuhan University, Sep. 2025–present.
* B.Eng., School of Remote Sensing and Information Engineering, Wuhan University, Sep. 2021–Jun. 2025.

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

## Standardization Proposals {#standardization}

{% assign standardization_page = site.pages | where: "proposal_source", true | first %}

<ol>
{% for proposal in standardization_page.proposals %}
<li>{{ proposal.citation | replace: "Xinxin Chen", "<strong>Xinxin Chen</strong>" }}{% if proposal.adopted %} <strong>[Adopted]</strong>{% endif %}</li>
{% endfor %}
</ol>

## Competitions

{% assign competitions_page = site.pages | where: "competition_source", true | first %}

<ol>
{% for item in competitions_page.competitions %}
{% assign rank = item | split: "," | first %}
<li><strong>{{ rank }}</strong>{{ item | remove_first: rank }}</li>
{% endfor %}
</ol>

## Honors

{% assign honors_page = site.pages | where: "honors_source", true | first %}

<ol>
{% for item in honors_page.honors %}
<li>{{ item }}</li>
{% endfor %}
</ol>
