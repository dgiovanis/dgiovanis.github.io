---
title: "Research"
permalink: /research/
---

Uncertainty plays an outsized role in our understanding of structures and materials, especially in extreme environments, but it can also have a life changing impact -- for example, natural hazards can affect a community, a city, and can often impact an entire country. Therefore, reducing uncertainty in the modeling of physical or structural systems is critical if we want to <code>inform decision-making</code> and enable engineering to move away from empirical <i>ad hoc</i> approaches into strategies that are based on scientifically grounded analyses.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/UQ.png"/>

In this context, <code>uncertainty quantification (UQ)</code> identifies the sources of uncertainty and quantifies their impact on the response of the model in order to:

* Enable robust <code>predictions</code> (<u>forward UQ</u>).
* <code>Infer</code> uncertainties in the model from data (<u>inverse UQ</u>)
* Calculate <code>probability of failure</code> (<u>reliability analysis</u>)
* <code>Prioritize</code> the sources of uncertainty (<u>sensitivity analysis</u>)

Even though much of the low-hanging fruit in UQ - such as simplified models that have low-dimensional uncertainties with known probability distributions - has been bagged, the vast majority of UQ methods are not applicable to real-world problems. Challenges that arise include:

* Parameter distributions must be inferred from <u>small or noisy data</u>
* Parameterized uncertainties may be extremely <u>high dimensional</u>
* Repeated evaluation of <u>expensive computational models</u> that may require days to execute

My research addresses these challenges by advancing <code>foundational computational methodologies</code> for <code>uncertainty quantification</code> and <code>machine learning</code>.  Specific projects include: 

* <code>Manifold learning</code> for low-dimensional representation of uncertainties
* <code>Encoder-decoder</code> learning models for surrogate modeling
* <code>Active learning</code> for stochastic sampling
* <code>Reliability analysis</code> in the presence of small or incomplete data
* <code>Sensitivity</code> and <code>reliability analysis</code> on the manifold

I am also interested in <code>Scientific software design and development.</code> I am the <code>Lead Developer</code> of the general-purpose, open-source <code>Python</code> package <a href='https://github.com/SURGroup/UQpy' target='_blank'><code>UQpy</code></a> that contains a wide variety of methods for inverse and forward propagation of uncertainty, surrogate modeling, reliability and sensitivity analysis. 