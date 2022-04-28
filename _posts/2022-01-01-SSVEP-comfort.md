---
toc: true
layout: post
description: Our latest research work on improving comfort with SSVEP-based BCI.
categories: [markdown]
title: High frequencies and low amplitude SSVEP
categories: [research, SSVEP]
image: images/onlineT9.png
---
# High frequencies and low amplitude SSVEP-based BCI

We believe that one of the major hurdle to disseminate BCI technology from laboratories to use in the wild by a a general audience is the poor user experience. For instance, Steady-States Visually Evoked Potentials (SSVEP) refer to the sustained rhythmic activity observed in surface electroencephalography (EEG) in response to the presentation of Repetitive Visual Stimuli (RVS). Due to their robustness and rapid
onset, SSVEP have been widely used in Brain Computer Interfaces (BCI). However, typical SSVEP stimuli are straining to the
eyes and present risks of triggering epileptic seizures. Reducing visual stimuli contrast or extending their frequency range
both appear as relevant solutions to address these issues. It however remains sparsely documented how BCI performance is
impacted by these features and to which extent user experience can be improved. In that respect, we have focused on the improvement of the user comfort by making SSVEP stimuli less instrutive.

## Reduction of stimuli depth

Our first results on SSVEP-BCI with reduction of stimuli depth can be found [here](https://hal.archives-ouvertes.fr/hal-03388285/document). Using two popular decoding algorithms, Canonical Correlation Analysis (CCA) and Task-Related Component Analysis (TRCA) we have demonstrated that a SSVEP-BCI is still operable with only 10% of amplitude depth. This large amplitude reduction provided a significant improvement in the subjective rating of comfort by our users.  

## High frequencies (>30Hz) SSVEP-BCI

We have then investigated the use of high frequencies and a combination with amplitude reduction. This work is currently under-review and will be published soon. The results revealed that although high frequency stimuli improve visual comfort, their classification performance were not competitive enough to design a reliable/responsive BCI. Importantly, we found that the amplitude depth reduction of low frequency RVS is an effective solution to improve user experience while maintaining high classification performance. These findings were further validated by an
online T9 SSVEP-BCI in which stimuli with 40% amplitude depth reduction achieved comparable results (>90% accuracy) to
full amplitude stimuli while significantly improving user experience.
