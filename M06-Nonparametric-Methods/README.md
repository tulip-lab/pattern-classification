# M06 — Nonparametric Methods

This module estimates densities and class labels directly from neighbourhoods
in the observed data. It uses histograms, Parzen windows, and nearest
neighbours to make the bias-variance and dimensionality trade-offs visible.

## Learning outcomes

After completing this module, learners should be able to:

1. construct histogram and kernel estimates of a probability density;
2. explain how bin width, kernel bandwidth, distance, and neighbour count
   influence an estimate;
3. implement a nearest-neighbour density estimate or classifier; and
4. compare nonparametric alternatives using a common validation design.

## Topic sequence

- **M06A — Density estimation:** histograms, Parzen windows, kernels,
  bandwidth, bias and variance, and the effect of dimensionality.
- **M06B — Nearest neighbours:** local density estimates, k-nearest-neighbour
  classification, distance and scaling, decision regions, and model selection.

## Practicals

[Lab M06A — Nonparametric classification: Parzen and KNN](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M06-Nonparametric-Methods)
compares class-conditional kernel-density and nearest-neighbour classifiers
under the same data split and evaluation protocol.

## Lecture handouts

These downloadable PDFs are password-protected. The password is supplied in
class when the relevant handout is introduced.

- [Nonparametric Estimation I](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S05A.pdf)
- [Nonparametric Estimation II](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S05B.pdf)
