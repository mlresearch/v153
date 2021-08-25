---
title: Learning DFAs by Evolving Short Sequences of Merges
abstract: The grammatical inference community has been studying evolutionary methods
  for DFA learning for almost three decades. These methods typically operate by learning
  a representation of the target DFA either as a partitioning the states of a prefix
  tree acceptor or as an encoding of its transition matrix. In this paper, we present
  an alternative approach for learning random DFAs over binary alphabets from sparse
  training data. We first conducted several experiments on thousands of problem instances
  to study their behaviour and to better understand the conditions under which state
  merging algorithms succeed or fail. Motivated by these observations, we implemented
  an evolutionary algorithm in which the chromosomes encode short sequences of merges
  selected from a subset of high state-reduction merges. The fitness of a chromosome
  is then measured by extending it using the EDSM heuristic and the size of the final
  hypothesis is used to score the entire sequence. To improve runtime performance,
  we use a method that can reliably estimate the fitness of a sequence of merges without
  extending it completely. We use the state-of-the-art EDSM algorithm as a baseline
  to compare our results to and observe that we can find low-error hypotheses or the
  exact target DFAs with a considerably higher likelihood.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: guillaumier21a
month: 0
tex_title: Learning DFAs by Evolving Short Sequences of Merges
firstpage: 217
lastpage: 236
page: 217-236
order: 217
cycles: false
bibtex_author: Guillaumier, Kristian and Abela, John
author:
- given: Kristian
  family: Guillaumier
- given: John
  family: Abela
date: 2021-08-25
address:
container-title: Proceedings of the Fifteenth International Conference on Grammatical
  Inference
volume: '153'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 8
  - 25
pdf: https://proceedings.mlr.press/v153/guillaumier21a/guillaumier21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
