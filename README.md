[![GitHub issues](https://img.shields.io/github/issues/tulip-lab/pattern-classification)](https://github.com/tulip-lab/pattern-classification/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/tulip-lab/pattern-classification)](https://github.com/tulip-lab/pattern-classification/pulls) [![GitHub stars](https://img.shields.io/github/stars/tulip-lab/pattern-classification.svg?style=social&label=Star)](https://github.com/tulip-lab/pattern-classification/stargazers/) [![Companion Lab](https://img.shields.io/badge/companion-Pattern_Classification_Lab-1f6feb?logo=github)](https://github.com/tulip-lab/pattern-classification-lab)

---

![FLIP Banner](https://raw.githubusercontent.com/tulip-lab/pattern-classification-lab/develop/Assets/images/flip-banner.png)

# FLIP: Pattern Classification

FLIP stands for **Fundamentals of Learning and Intelligent Processing**. This open course from [TULIP Lab](https://www.tulip.academy) develops the theory, implementation, and evaluation skills needed to build trustworthy statistical pattern-classification systems.

> The common core and Lab materials on the `develop` branches are under active development. An institution-specific offering becomes authoritative only when its offering page is explicitly marked active.

## Current offering

The current 2026 SEU offering is:

- [SEU Pattern Classification 2026](offerings/seu/pattern-classification/2026/README.md)

## Prerequisites

You should be comfortable with introductory probability and statistics, linear algebra, basic Python, and interpreting tables and visualisations. Prior machine-learning experience is useful but not required.

## Recommended textbooks

Listed from newest to oldest:

1. **Kevin P. Murphy (2023), *Probabilistic Machine Learning: Advanced Topics*.**
   [Author-hosted book and supporting code](https://probml.github.io/book2) · [MIT Press](https://mitpress.mit.edu/9780262048439/probabilistic-machine-learning/)
   The recommended current companion for probabilistic modelling, Monte Carlo inference, Gaussian processes, and decision making under uncertainty.
2. **David J. C. MacKay (2003), *Information Theory, Inference, and Learning Algorithms*.**
   [Author-hosted open book](https://www.inference.org.uk/itprnn/book.pdf) · [Cambridge University Press](https://www.cambridge.org/9780521642989)
   A conceptual bridge across information theory, Bayesian inference, sampling, coding, and learning algorithms.
3. **Richard O. Duda, Peter E. Hart, and David G. Stork (2001), *Pattern Classification*, 2nd ed.**
   [Wiley](https://www.wiley.com/en-gb/Pattern%2BClassification%2C%2B2nd%2BEdition-p-9780471056690)
   The classical course foundation for Bayesian decision theory, density estimation, discriminant functions, and classifier design.

## Companion lab site

The [Pattern Classification Lab](https://github.com/tulip-lab/pattern-classification-lab/tree/develop) is the practical companion to this course portal. This repository provides the common-core concepts, learning outcomes, module overviews, and offering links; the Lab provides the runnable notebooks, public data, implementation exercises, practical instructions, and reproducibility workflow.

Use the two sites together:

1. begin with the conceptual overview for a module in this portal;
2. open the matching practical from the module table below or the Lab's [module list](https://github.com/tulip-lab/pattern-classification-lab/tree/develop#modules);
3. run the baseline notebook before changing it;
4. inspect intermediate results and test edge, missing-information, and failure behaviour; and
5. restart and run the notebook from the top, then retain the requested evidence and limitations.

For curriculum design and contribution work, the Lab's [curriculum alignment and coverage map](https://github.com/tulip-lab/pattern-classification-lab/blob/develop/PRACTICAL-MAP.md) records how practical evidence aligns with the `M01`–`M11` common core and identifies known coverage gaps. Most notebook activities can be run in [Google Colab](https://colab.research.google.com) without a paid service or credential.

## Course outcomes

After completing the relevant modules, you should be able to:

1. **Explain** uncertainty, loss, risk, and decision boundaries in Bayesian pattern classification.
2. **Estimate** model parameters and probability densities using appropriate parametric, nonparametric, and stochastic methods.
3. **Implement and compare** selected generative and discriminative classifiers for appropriately scoped data problems.
4. **Evaluate** classification systems using suitable validation designs, metrics, error analysis, and evidence about uncertainty and limitations.
5. **Design and communicate** a reproducible pattern-classification solution with justified modelling choices and clear interpretation.
6. **Assess** privacy, fairness, provenance, responsible AI use, and other risks arising in pattern data and models.

## Modules

Linked lecture handouts are distributed as password-protected files. Download the relevant file first, then use the password supplied for that part of the course during class. Do not post or redistribute handout passwords publicly.

| Module | Conceptual overview | Public practical |
| --- | --- | --- |
| M01 | [Induction](M01-Induction/README.md) | [Orientation](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M01-Induction) |
| M02 | [Mathematical Foundations](M02-Foundations/README.md) | [Classification workflow and features](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M02-Foundations) |
| M03 | [Bayesian Decision Theory](M03-Decision-Theory/README.md) | [Bayesian decisions and boundaries](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M03-Decision-Theory) |
| M04 | [Parameter Estimation](M04-Parameter-Estimation/README.md) | [MLE, MAP, and EM](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M04-Parameter-Estimation) |
| M05 | [Parametric Models](M05-Parametric-Models/README.md) | [HMM and Naive Bayes](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M05-Parametric-Models) |
| M06 | [Nonparametric Methods](M06-Nonparametric-Methods/README.md) | [Parzen windows and KNN](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M06-Nonparametric-Methods) |
| M07 | [Stochastic Methods](M07-Stochastic-Methods/README.md) | [Simulation to decision](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M07-Stochastic-Methods) |
| M08 | [Discriminant Functions](M08-Discriminant-Functions/README.md) | [Optimisation and SVM](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M08-Discriminant-Functions) |
| M09 | [Model Evaluation](M09-Model-Evaluation/README.md) | [Model selection and generalisation](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M09-Model-Evaluation) |
| M10 | [Large Language Models and Agentic AI](M10-LLM-Agentic-AI/README.md) | [Selected Agentic AI practicals](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M10-LLM-Agentic-AI) |
| M11 | [Privacy](M11-Privacy/README.md) | [Privacy practical status](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M11-Privacy) |

The sequence moves from mathematical and decision foundations through estimation and model families to stochastic methods, discriminants, evaluation, large language models and agentic AI, and privacy-aware practice.

## Responsible practice

Never commit credentials, personal data, private course material, hidden assessment data, solutions, or unreviewed model output. Use approved public or synthetic data, validate inputs and results, test failure behaviour, and retain human review for consequential decisions.

Prepared by :tulip: **[TULIP Lab](https://www.tulip.academy), Australia**
