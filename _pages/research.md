---
title: "Research"
permalink: /research/
---

Uncertainty plays an outsized role in our understanding of structures and materials, especially in extreme environments, but it can also have a life changing impact -- for example, natural hazards can affect a community, a city, and can often impact an entire country. Therefore, reducing uncertainty in the modeling of physical or structural systems is critical if we want to inform decision-making and enable engineering to move away from empirical <i>ad hoc</i> approaches into strategies that are based on scientifically grounded analyses.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/UQ.png"/>

In this context, uncertainty quantification (UQ) identifies the sources of uncertainty and quantifies their impact on the response of the model in order to enable robust predictions, perform reliability assessments (probability of failure) and sensitivity analyses (prioritization of sources of uncertainty). Even though much of the low-hanging fruit in UQ - such as simplified models that have low-dimensional uncertainties with known probability distributions - has been bagged, the vast majority of UQ methods are not applicable to real-world problems. Challenges that arise include:

* Parameter distributions must be inferred from small or noisy data
* Parameterized uncertainties may be extremely high dimensional
* Repeated evaluation of expensive computational models that may require days to execute

My research addresses these challenges by advancing foundational computational methodologies for <strong>uncertainty quantification</strong> and <strong>machine learning</strong> for a broad range of materials and engineering applications.  Specific projects include: 

* Manifold learning for latent representation of uncertainties
* Machine learning for surrogate modeling 
* Bayesian inference for inverse problems
* Structural reliability
* Active learning methods 
* Scientific software design and development

I am also the <strong>Lead Developer</strong> of the general-purpose, open-source <code>Python</code> package <a href='https://github.com/SURGroup/UQpy' target='_blank'><code>UQpy</code></a> that contains a wide variety of methods for inverse and forward propagation of uncertainty, surrogate modeling, reliability and sensitivity analysis. 