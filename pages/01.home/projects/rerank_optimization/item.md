---
title: 'Project: Reranking Optimiztaion'
summary:
    format: short
---

#### Description

In this project, we are exploring the characteristics of recommendation results that have been reranked for fairness concerns and their differences under pipelined versus joint optimization. Pipelined optimization is one of the most common approaches and leaves the recommender system to be optimized for accuracy and tunes the reranker separately for the best tradeoff between accuracy and fairness. Prior work leaves open the possibility that better fairness / accuracy are possible if the reranker and recommendation algorithm are jointly optimized. We have experimented with multiple data sets, base algorithms and rerankers. We are evaluating these results using NDCG to measure accuracy and Partial Statistical Fairness to measure fairness. Additionally, we are using Kendall’s tau, Ranked Bias Overlap, and a metric considering the lowest protected item to be promoted from the original recommendations to better understand the behavior of the reranker. 
