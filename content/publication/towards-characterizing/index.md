---
title: Towards Characterizing Domain Counterfactuals for Invertible Latent Causal Models
subtitle: ""
publication_types:
  - "1"
authors:
  - Ruqi Bai**
  - Zeyu Zhou*
  - Sean Kulinski*
  - Murat Kocaoglu
  - David I. Inouye
publication: "ICLR 2024"
abstract: Answering counterfactual queries has many important applications such as knowledge discovery and explainability, but is challenging when causal variables are unobserved and we only see a projection onto an observation space, for instance, image pixels. One approach is to recover the latent Structural Causal Model (SCM), but this typically needs unrealistic assumptions, such as linearity of the causal mechanisms. Another approach is to use na\"ive ML approximations, such as generative models, to generate counterfactual samples; however, these lack guarantees of accuracy. In this work, we strive to strike a balance between practicality and theoretical guarantees by focusing on a specific type of causal query called \emph{domain counterfactuals}, which hypothesizes what a sample would have looked like if it had been generated in a different domain (or environment). Concretely, by only assuming invertibility, sparse domain interventions and access to observational data from different domains, we aim to improve domain counterfactual estimation both theoretically and practically with less restrictive assumptions. We define \emph{domain counterfactually equivalent} models and prove necessary and sufficient properties for equivalent models that provide a tight characterization of the domain counterfactual equivalence classes. Building upon this result, we prove that every equivalence class contains a model where all intervened variables are at the end when topologically sorted by the causal DAG. This surprising result suggests that a model design that only allows intervention in the last $k$ latent variables may improve model estimation for counterfactuals. We then test this model design on extensive simulated and image-based experiments which show the sparse canonical model indeed improves counterfactual estimation over baseline non-sparse models.
draft: false
url_pdf: 'https://openreview.net/forum?id=v1VvCWJAL8'
featured: false
summary: ""
date: 2024-01-16T19:59:24.197Z
---
