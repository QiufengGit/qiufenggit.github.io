---
layout: archive
title: "Standardization"
permalink: /standardization/
author_profile: true
proposal_source: true
proposals:
  - citation: "Xinxin Chen and Zhenzhong Chen, “Crosscheck of JVET-AQ0049 (EE1-2.3: Deep reference frame generation for inter prediction enhancement with motion compensation),” JVET-AQ0134, 43rd JVET Meeting in Geneva, 7–15 Jul. 2026."
  - citation: "Philippe Bordes, Franck Galpin, Federico Lo-Bianco, Mattéo Paquiry, Xinxin Chen, Tian Shu, Junxi Zhang, and Zhenzhong Chen, “EE1-2.4: Combination of test 2.3 (deep reference frame generation with motion compensation) and tests 2.1 and 2.2,” JVET-AQ0050, 43rd JVET Meeting in Geneva, 7–15 Jul. 2026."
    adopted: true
  - citation: "Xinxin Chen, Junxi Zhang, and Zhenzhong Chen, “EE1-2.2: Improved H-DRF with weighted fusion and optimized YUV processing,” JVET-AQ0048, 43rd JVET Meeting in Geneva, 7–15 Jul. 2026."
    adopted: true
  - citation: "Tian Shu, Xinxin Chen, Wenzhuo Zhang, Nianxiang Fu, and Zhenzhong Chen, “EE1-2.1: Very small deep reference frame generation network for inter prediction enhancement,” JVET-AQ0047, 43rd JVET Meeting in Geneva, 7–15 Jul. 2026."
    adopted: true
  - citation: "Xinxin Chen, Junxi Zhang, and Zhenzhong Chen, “AhG14: SIMD improvements of operators in SADL library,” JVET-AP0053, 42nd JVET Meeting in Santa Eulària, 24 Apr.–1 May 2026."
    adopted: true
  - citation: "Xinxin Chen, Junxi Zhang, and Zhenzhong Chen, “AHG11: Improved H-DRF with weighted fusion and optimized YUV processing,” JVET-AP0052, 42nd JVET Meeting in Santa Eulària, 24 Apr.–1 May 2026."
  - citation: "Tian Shu, Xinxin Chen, Wenzhuo Zhang, Nianxiang Fu, and Zhenzhong Chen, “EE1-3.1: Very small deep reference frame generation network for inter prediction enhancement,” JVET-AP0051, 42nd JVET Meeting in Santa Eulària, 24 Apr.–1 May 2026."
  - citation: "Tian Shu, Xinxin Chen, Wenzhuo Zhang, Nianxiang Fu, and Zhenzhong Chen, “AHG11: Very small deep reference frame generation network for inter prediction enhancement,” JVET-AO0267, 41st JVET Meeting, by teleconference, 14–23 Jan. 2026."
  - citation: "Xinxin Chen, Wenzhuo Zhang, Nianxiang Fu, Junxi Zhang, and Zhenzhong Chen, “EE1-4.1: Deep reference frame generation for inter prediction enhancement with structural re-parameterization,” JVET-AO0108, 41st JVET Meeting, by teleconference, 14–23 Jan. 2026."
    adopted: true
  - citation: "Jingyun Liu, Xinxin Chen, Yiling Gao, Zhenzhong Chen, Yingwei Pan, Ting Yao, and Tao Mei, “AHG4/AHG17: AIGC test sequences,” JVET-AO0061, 41st JVET Meeting, by teleconference, 14–23 Jan. 2026."
  - citation: "Nianxiang Fu, Xinxin Chen, Luyi Qin, Wenzhuo Zhang, and Zhenzhong Chen, “EE1-related: FlowWarp operator for DRF integer inference optimization,” JVET-AN0319, 40th JVET Meeting in Geneva, 3–12 Oct. 2025."
  - citation: "Wenzhuo Zhang, Luyi Qin, Xinxin Chen, Nianxiang Fu, Haodong Qu, Wenzhuo Ma, Junxi Zhang, and Zhenzhong Chen, “[AHG17] Wuhan University’s response in joint call for evidence on video compression with capability beyond VVC,” JVET-AN0198, 40th JVET Meeting in Geneva, 3–12 Oct. 2025."
  - citation: "Wenzhuo Zhang, Nianxiang Fu, Luyi Qin, Xinxin Chen, and Zhenzhong Chen, “AHG14: Operator improvements in the SADL library,” JVET-AN0196, 40th JVET Meeting in Geneva, 3–12 Oct. 2025."
    adopted: true
  - citation: "Xinxin Chen, Nianxiang Fu, Wenzhuo Zhang, Wenzhuo Ma, Junxi Zhang, and Zhenzhong Chen, “EE1-3.5: Retrained DRF in NNVC-14.0,” JVET-AN0195, 40th JVET Meeting in Geneva, 3–12 Oct. 2025."
    adopted: true
  - citation: "Wenzhuo Zhang, Nianxiang Fu, Xinxin Chen, Wenzhuo Ma, Junxi Zhang, and Zhenzhong Chen, “EE1-3.1: Deep reference frame generation for inter prediction enhancement with structural re-parameterization,” JVET-AN0193, 40th JVET Meeting in Geneva, 3–12 Oct. 2025."
  - citation: "Wenzhuo Zhang, Chengzhuo Gui, Nianxiang Fu, Xinxin Chen, Wenzhuo Ma, and Zhenzhong Chen, “AHG11: Deep reference frame generation for inter prediction enhancement with structural re-parameterization,” JVET-AM0177, 39th JVET Meeting in Daejeon, 26 Jun.–4 Jul. 2025."
  - citation: "Xinxin Chen, Nianxiang Fu, Wenzhuo Zhang, Junxi Zhang, Ding Ding, Wenzhuo Ma, and Zhenzhong Chen, “EE1-3.2: Deep reference frame generation for inter prediction enhancement,” JVET-AM0175, 39th JVET Meeting in Daejeon, 26 Jun.–4 Jul. 2025."
    adopted: true
  - citation: "Ding Ding, Xinxin Chen, and Zhenzhong Chen, “EE1-related: Deep reference frame generation for inter prediction enhancement,” JVET-AL0184, 38th JVET Meeting, by teleconference, 26 Mar.–4 Apr. 2025."
  - citation: "Xinxin Chen, Junxi Zhang, Zhenzhong Chen, and Shan Liu, “[FCM] Solutions to the refinement parameter sharing discrepancy in FCTM under temporal resampling,” FCM-m71258, 149th MPEG Meeting in Geneva, 20–24 Jan. 2025."
  - citation: "Junxi Zhang, Xinxin Chen, Zhenzhong Chen, and Shan Liu, “[FCM] Updated syntax to support temporal extrapolation in FCTM,” FCM-m71256, 149th MPEG Meeting in Geneva, 20–24 Jan. 2025."
---

## Standardization Proposals

<ol>
{% for proposal in page.proposals %}
<li>{{ proposal.citation }}{% if proposal.adopted %} (Adopted){% endif %}</li>
{% endfor %}
</ol>
