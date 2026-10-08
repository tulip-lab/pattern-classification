# M09 — Model Evaluation

This module separates model development from final assessment. It develops an
evidence-based workflow for estimating generalisation, selecting metrics,
comparing alternatives, and communicating uncertainty and limitations.

## Learning outcomes

After completing this module, learners should be able to:

1. design train, validation, cross-validation, and test procedures without
   information leakage;
2. select metrics that reflect class balance, decision costs, and the intended
   use of a classifier;
3. interpret confusion matrices, threshold curves, and variability across
   resamples; and
4. compare models without using the final test set for selection.

## Topic sequence

- generalisation and the purpose of an independent test set;
- leave-one-out and k-fold cross-validation;
- accuracy, precision, recall, specificity, F-score, and cost-sensitive
  interpretation;
- confusion matrices, score thresholds, ROC analysis, and model comparison;
- uncertainty, leakage, limitations, and defensible reporting.

## Practicals

[Lab M09A — Model selection and generalisation](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/M09-Model-Evaluation)
uses a complete pipeline, nested separation of selection and assessment,
validation and learning curves, and a held-out evaluation. Formal
PAC-learning activities remain optional extension work rather than a
prerequisite for this practical.

## Lecture handout

This downloadable PDF is password-protected. The password is supplied in class
when the handout is introduced.

- [Model Evaluation](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S08D.pdf)
