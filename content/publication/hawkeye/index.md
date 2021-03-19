---
title: "HAWKEYE: Adversarial Example Detection through Ensemble Detectors"
subtitle: ""
publication_types:
  - "1"
authors:
  - Ruqi Bai
  - Jinkyu Koo (NVIDIA)
  - Heron Teegarden
  - Michael Roth (Google)
  - Kevin Chan
  - David I. Inouye
  - Saurabh Bagchi
publication: SPIE
abstract: Adversarial examples (AEs) are images that can mislead deep neural
  network (DNN) classifiers via introducing slight perturbations into original
  images. Recent work has shown that detecting AEs can be more effective than
  making the DNN robust against AEs. However, the state-of-the-art AE detection
  shows a high false positive rate, thereby rejecting a considerable fraction of
  normal images, and appears easy to bypass through reverse engineering attacks.
  To address this issue, we propose HAWKEYE, which is a separate classifier that
  analyzes the output layer of the DNN and detects AEs by comparing to the
  output of a quantized version of the input image similar to prior work.
  However, instead of merely computing a simple statistic and then thresholding
  to detect AEs, we train a separate simple classifier to distinguish the
  variation characteristics of the difference between the DNN output on an input
  image and the quantized reference image. By using a classifier, the detection
  rate is higher, and thus we can cascade our AE detectors that are trained for
  different quantization step sizes to significantly reduce the false positive
  rate, while keeping the detection rate high. We provide extensive empirical
  evaluations of HAWKEYE under various scenarios including white-box attacks
  against the detector itself.
draft: false
featured: false
summary: ""
date: 2021-02-03T16:55:03.197Z
---
