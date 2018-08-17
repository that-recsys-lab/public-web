---
title: 'Personalizing Fairness-aware Re-ranking'
summary:
    format: short
---

#### Abstract

Personalized recommendation brings about novel challenges in ensuring fairness, especially in scenarios in which users are not the only stakeholders involved in the recommender system. For example, the system may want to ensure that items from different providers have a fair chance of being recommended. To solve this problem, we propose a Fairness-Aware Re-ranking algorithm (FAR) to balance the ranking quality and multi-sided fairness. We iteratively generate the ranking list by trading off between accuracy and the coverage for the providers. Although fair treatment of providers is desirable, users may differ in their receptivity to the addition of this type of diversity. Therefore, personalized user tolerance towards provider diversification is incorporated. Experiments are conducted on both synthetic and real-world data. The results show that our proposed re-ranking algorithm can significantly promote fairness with a slight sacrifice in accuracy and can do so while being attentive to individual user differences.

===

#### Reference
Liu, Weiwen, and Robin Burke. "Personalizing Fairness-aware Re-ranking." FATRec Workshop on Responsible Recommendation. 2018

#### Bibtex
```
@inproceedings{liu2018personalizing,
  title={Personalizing Fairness-aware Re-ranking},
  author={Liu, Weiwen and Burke, Robin},
  booktitle={FATRec Workshop on Responsible Recommendation},
  pages={to appear},
  year={2018}
}
```
