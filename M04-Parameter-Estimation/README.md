# M04 — Parameter Estimation

This module studies how model parameters can be learned from data. It connects
maximum likelihood and maximum a posteriori estimation to latent-variable
models through the expectation-maximisation algorithm.

## Learning outcomes

After completing this module, learners should be able to:

1. formulate and optimise a likelihood or log-likelihood for a simple model;
2. compare maximum likelihood and maximum a posteriori estimates;
3. explain the role of a prior as information and as regularisation; and
4. apply the E-step and M-step of EM and diagnose convergence or sensitivity to
   initialisation.

## Topic sequence

- **M04A — MLE and MAP:** sampling assumptions, likelihood, log-likelihood,
  parameter estimates, priors, posterior objectives, and estimation bias.
- **M04B — Expectation maximisation:** latent variables, responsibilities,
  alternating expectation and maximisation, Gaussian mixtures, convergence,
  and local optima.

## Practicals

[Lab M04A — Parameter estimation: MLE, MAP, and EM](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M04-Parameter-Estimation)
compares likelihood-only and prior-regularised estimates before fitting a
Gaussian mixture and testing EM initialisation sensitivity.

## Lecture handouts

These downloadable PDFs are password-protected. The password is supplied in
class when the relevant handout is introduced.

- [Parameter Estimation I](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S03A.pdf)
- [Parameter Estimation II](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S03B.pdf)
