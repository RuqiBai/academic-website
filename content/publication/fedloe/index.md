---
title: FedLOE Federated Domain Generalization via Locally Overfit Ensemble
subtitle: ""
publication_types:
  - "3"
authors:
  - Ruqi Bai
  - David I. Inouye
publication: ""
abstract: In federated learning (FL), clients typically access data from just one distribution. Ideally, the learned models would generalize to out-of-distribution (OOD), i.e., domain generalization (DG). However, centralized DG methods cannot easily be adapted in the domain separation context and prior federated DG methods perform poorly when the number of clients is large. To address these challenges, we revisit the classic mixture-of-experts (MoE) idea by viewing each client as an expert on its own dataset. From this perspective, simple federated averaging can be seen as a type of iterative MoE, where the amount of local training determines the strength of each expert.
Contrast to the FL communication-performance trade-off, we theoretically demonstrate that in linear cases and empirically validate in deep models that reducing communication frequency can effectively enhance DG performance, surpassing their centralized counterparts. Building on this, we further propose an additional MoE strategy to combine the client-specific classifier heads via standard DG objectives.
Our proposed method empirically outperforms multiple centralized and federated baselines for domain generalization on several real datasets.
draft: false
featured: false
summary: ""
date: 2023-02-03T17:18:59.197Z
---
