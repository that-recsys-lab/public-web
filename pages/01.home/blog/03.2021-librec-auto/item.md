---
title: '2021 librec-auto v0.2'
---

This week we released the latest version of `librec-auto`, a tool for automating batch-style recommender systems experiments. The GitHub repository is (https://github.com/that-recsys-lab/librec-auto). See also the [documentation](https://librec-auto.readthedocs.io/en/latest/). 

Among the new features available in this version are:

- Fairness-aware recommendation support: Version 0.2 has a variety of features to support experimentation with fairness in recommendation including fairness metrics and re-ranker support.
- Bayesian black-box optimization: This release contains a preliminary implementation of black-box parameter optimization for hyperparameters using the [`hyperopt`](http://hyperopt.github.io/hyperopt/) library.
- Setup wizard: A simple tool to help create new experimental studies, working from a data file supplied by the user.
- Saved split files: Cross-validation splits are now saved for debugging, reference and for the computation of statistics over training or test sets.
- Enhanced support for re-ranking: `librec-auto` has a number of built-in re-ranking algorithms for fairness-aware and diversity-aware recommendation, plus support for custom re-rankers.
- Python-side metrics: LibRec has a substantial library of recommendation metrics. However, it is now possible for experiments to implement their own metrics in Python and integrate them with recommendation experiments.

`librec-auto` can be installed using `pip`:

```
pip install librec-auto
```

You can also clone the source repository:

```
git clone https://github.com/that-recsys-lab/librec-auto.git
cd librec-auto
python setup.py install
```
