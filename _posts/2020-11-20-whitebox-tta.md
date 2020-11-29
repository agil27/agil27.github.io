---
layout: post
title: White-box test-time augmentation
site: http://agil27.github.io/
---

Traditional test-time augmentation(TTA) like five-crop or ten-crop aims to reduce the variance during the test-phase. We proposed a novel white-box tta method that will enhance the test images with explainable transformations in order to get an optimized performance for a black-box deep learning model.

In our work, we model the TTA process as a simple optimization problem over a set of normalized continuous parameters that controls the intensity of the transformations, with identity transformation explicity included by initializing the parameters to be 0.5.

Inspired by the work of GES and other gradient estimation method, we propose a novel TTA optimization algorithm based on surrogate gradient estimation method.
