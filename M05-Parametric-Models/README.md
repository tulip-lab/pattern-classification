# M05 — Parametric Probabilistic Models

This module uses compact probabilistic structures to represent dependencies in
sequential and multivariate data. The emphasis is on interpreting assumptions
and performing inference, not merely naming model families.

## Learning outcomes

After completing this module, learners should be able to:

1. express state transitions and observation probabilities in a Markov or
   hidden Markov model;
2. use the Viterbi recurrence to recover a most likely hidden-state sequence;
3. interpret conditional independence in a Bayesian network; and
4. compare the assumptions and appropriate uses of sequential, naive, and
   graphical probabilistic models.

## Topic sequence

- **M05A — Markov and hidden Markov models:** the Markov property, transition
  models, emissions, sequence likelihood, state decoding, and the Viterbi
  algorithm.
- **M05B — Bayesian networks:** directed acyclic graphs, conditional
  independence, factorisation of a joint distribution, inference, and
  reasoning under uncertainty.

## Practicals

[Lab M05A — Probabilistic models: HMM and Naive Bayes](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M05-Parametric-Models)
contrasts conditional-independence assumptions and implements log-space
Viterbi decoding. A Bayesian-network practical remains a recorded coverage
gap.

## Public handouts

- [Parametric Models I](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S04A.pdf)
- [Parametric Models II](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S04B.pdf)
