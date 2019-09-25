---
title: 'Project: FARSITE'
summary:
    format: short
---

#### Description

Recommender systems are pervasive in e-commerce and widely used in other applications, providing personalized suggestions to help users find items of interest in large online catalogs. As they have become more prevalent, recommender systems have moved from areas of consumer taste, such as music and movies, to areas with greater social impact and sensitivity, such as financial services, employment, and housing. In these areas, questions of fairness have come to the fore, and researchers have begun to develop and study fairness-aware recommendation algorithms. However, even with these recent developments, we are not yet able to reliably apply fairness-aware recommendation in practice. In particular, current research only considers a single dimension of fairness, while real applications require a more nuanced, intersectional, and multisided understanding. In addition, user acceptance of recommendations often hinges on the ability of the system to explain its results, but there has been little research on explanation for fairness-aware recommendation. Finally, researchers have noted significant challenges in reproducibility of recommender systems experiments. Individual stand-alone systems and experiments are not sufficient to secure scientific progress, particularly where the stakes are high and where fairness is important,  Advances in recommendation need to be demonstrated in benchmarkable open-source platforms, where experimental consistency and reproducibility can be achieved and with datasets that are easily shared. 

This project titled "Fairness-Aware Recommender Systems: Intersectionality, Tools and Explanations" (FARSITE) is a National Science Foundation funded project to create recommendation solutions better matched to the settings where real-world fairness issues reside. Once FARS are more compatible with the contexts in which recommendations are actually delivered and can be more reliably evaluated, there will be greater acceptance of this technology in organizations that need to deliver fair recommendations. 

The research has the following aims:

- *Aim 1:* Develop recommendation models and algorithms that can achieve high accuracy while preserving fairness in multiple, intersectional, dimensions and demonstrate their effectiveness in multiple fairness-critical domains.} Existing fairness-aware recommendation algorithms have, with few exceptions, been developed and evaluated in contexts where a single dimension of fairness, defining a single protected group, is considered. We will extend these algorithms to be sensitive to multiple protected features, and to incorporate multiple sides of the recommendation transaction.
    
- *Aim 2:* Develop explanation mechanisms for fairness-aware recommendation that support transparency in the application of fairness criteria. It is well known that explanations support users in their use of recommender systems, engendering greater trust. However, the greater complexity of FARS makes it difficult to produce explanations, and the introduction of fairness objectives may actually decrease trust in some users who may perceive the system as insufficiently responsive to their interests. We will develop FARS-specific explanations and determine their acceptability in end-user experiments.
    
- *Aim 3:* Develop techniques for generating grounded synthetic recommendation datasets containing demographic and / or content attributes. The demographic and content attributes that would be essential for exploring fairness in recommendation models are rarely included in public data sets used in recommendation, especially in sensitive areas. We will develop methods for the generation of synthetic data that are grounded in real datasets, and therefore useful for fairness-aware recommendation research. 
    
- Aim 4:* Build algorithms, metrics and methodologies for fairness-aware recommendation and distribute them in an open-source platform. Fairness metrics and fairness-aware algorithms are not available in the most popular open-source recommender systems  platforms. As a result, there is a profusion of different metrics and baselines, implemented in different ways, and a confusing thicket of claims regarding the benefits of different algorithmic approaches. We will implement a common suite of fairness-aware algorithms including our own algorithmic advances and develop standardized evaluation metrics and methodologies, all of which will be integrated into the widely-used open-source LibRec recommender systems platform.









