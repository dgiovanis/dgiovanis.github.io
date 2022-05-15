---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Funded projects
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
 <h4>Machine Learning Metallic Glass Structure-Property Relations (2020-present)</h4>

<strong>Funding Source</strong>: <a href="https://www.sandia.gov" target="_blank">Sandia National Laboratories</a><br>
<strong>Role</strong>: Co-PI<br>
<strong>Amount</strong>: $200,000


Optimization of material strength, failure tolerance, and formability requires a capacity to predict mechanical response on the continuum or meso-scale based on quantification of a material's microstructure on the atomic scale. In this project we use machine learning to build a robust bridge between atomic scale data and the development of meso-scale models suitable for predicting the response of metallic glasses. Metalic glasses are a type of amorphous material that exhibit failure through extreme shear deformation during strain localization, but also exhibit massive delocalized shear in the form of superplasticity at elevated temperatures. Specific tasks include:

* Manifold learning (e.g., diffusion maps) for nonlinear dimension reduction of the atomistic data to identify machine learned descriptors of the material microstructure, followed by learning the relationship between the data-driven descriptors and the physically-motivated descriptors (e.g., Local yield stress).
* Deep learning to derive meso-scale constitutive models / evolution equations that predict the evolution of the microstructure and the development of plastic flow resulting in failure.

</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/SandiaProject.png" width="500px"/>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>Natural Hazards Engineering Research Infrastructure: Computational Modeling and Simulation Center (2021-2025)</h4>

<strong>Funding Source</strong>: <a href="https://www.nsf.gov" target="_blank">National Science Foundation</a><br>
<strong>Role</strong>: Co-PI<br>
<strong>Amount</strong>: $100,000


The goal of the <a href="https://simcenter.designsafe-ci.org" target="_blank">SimCenter</a> is to promote advanced modeling and simulation technologies for natural hazards engineering (NHE) researchers and practitioners to understand and quantify the effects of earthquakes, hurricanes, tsunamis, and other natural hazards on buildings, lifelines, and communities. In this project the state-of-the-art uncertainty quantification methods will be integrated with SimCenter tools for hazard modelers, efforts for enhancing detailed modeling, expansion of regional capabilities to include new hazards and interfaces with urban planning and modeling tools. My role in SimCenter is to guide development and application efforts for UQ approaches, i.e., identify/articulate UQ issues and consistent methodologies to characterize and propagate uncertainties ranging from natural hazards (earthquakes, hurricane, tsunami, water and wind effect), to effects on individual structures and large regional inventories. 

</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/SimCenter.png" width="500px"/>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
 <h4>Manifold Learning for Rapid Post Wildfire Debris Flow Hazard Assessment (2022-2026)</h4>

 <strong>Funding Source</strong>: <a href="https://www.nsf.gov" target="_blank">National Science Foundation</a> (Pending)<br>
  <strong>Role</strong>: Co-PI<br>
 <strong>Amount</strong>: $433,000

Wild fires significantly increase the susceptibility of steep terrain to rainfall-induced debris flows. These fast moving, dense flows are initiated during short, intense rainfall and are often triggered with little-to-no warning, making them especially dangerous for communities situated down slope of recently burned terrain. Is is well known that uncertainties in soil properties,rainfall,and triggering mechanisms play a crucial role in risk analysis. The focus of this project is to develop a mechanics-based and data-driven approach for assessing post-wildfire debris flow hazard both in terms of triggering and areal extent by comprehensively incorporating the spatial and temporal variability and uncertainty in material properties and triggering characteristics. To this end, we develop manifold learning-based surrogate modeling approaches both for triggering and runout analysis.

</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/debris.png" width="500px"/>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
 <h4>Data-driven uncertainty quantification for energetic materials (2022-2023)</h4>


 <strong>Funding Source</strong>: <a href="https://hemi.jhu.edu" target="_blank">Hopkins Extreme Materials Institute</a> (Pending)<br>
  <strong>Role</strong>: PI<br>
 <strong>Amount</strong>: $25,000

Energetic materials such as propellants, explosives, and pyrotechnics are key performance components in a wide range of defense applications, including solid rocket motors and munitions. Considering the immense scope of these functional materials, designing them with reduced sensitivity (e.g., the tendency to detonation) to accidental stimulation has become a topic of
interest within energetic materials research. It has long been understood that the sensitivity of energetic materials to loading (e.g., shock) is critically dependent on the heterogeneities of the microstructure. Given its inherently stochastic nature, in order to understand, predict and control the shock-to-detonation or shock-to-deflagration transition, it is crucial to conduct uncertainty quantification. In this project, I develop manifold learning-based surrogate models that will accelerate UQ. The material system is a quasi-2D sample of porous RDX (cyclotrimethylene trinitramine) with randomly distributed cylindrical pores of random size. 


</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/energetic.png" width="500px"/>
</div>
</div>
</div>

## Engagement in other on-going projects

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>Low-dimensional manifold learning for uncertainty quantification in complex multi-scale stochastic sytems (2019-2024)</h4>

<strong>Funding Source</strong>: <a href="https://www.energy.gov" target="_blank">Department of Energy</a><br>

This work is primarily focused on the mathematical development of dimension reduction methods for uncertainty quantification. Within a multiscale setting, active learning methods are employed at each length-scale to develop physically-informed surrogate models that can be used for prediction at each length-scale and across length scales. The surrogates at each scale are trained to be predictive while maintaining the physical interpretation of the solution. In other words, these surrogates are not simply arbitrary curve-fits but are also not fully developed reduced-order models (ROMs) in the sense that they solve the governing equations on a reduced number of degrees of freedom (which requires new solvers for the reduced equations). For this reason, we refer to them as pseudo-ROMs (P-ROMs).


</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/mPCE.png" width="500px"/>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>OptiSimCVD: a data-driven framework for prediction, sensitivity analysis and uncertainty quantification in Chemical Vapor Deposition (CVD) reactors (2021-2024)</h4>

<strong>Funding Source</strong>: <a href="https://www.ceratizit" target="_blank">CERATIZIT</a>, <a href="https://www.fnr.lu" target="_blank">Luxembourgh National Research Fund</a><br>

The project OptiSimCVD proposes a data-driven framework for prediction, sensitivity analysis and uncertainty quantification in industrial-scale processes used to produce hard coatings and wear protection. The core of the production process is Chemical Vapor Deposition (CVD) reactors with different set up but with a common goal: uniform coatings with strict limits of variability. Data from this process are utilized to identify clusters of reactors with different set-up but similar qualitative characteristics of the coating. Then regression models will be developed for each one of the clusters, that will correlate inputs (features) with the output. Finally, surrogate models will be used in the context of forward uncertainty quantification and sensitivity analysis to eventually develop a tool that will contribute to process efficiency by reducing scrap rate (30%) and improve quality by enhancing homogeneity (15%).

</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/video.mov" width="500px"/>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>MSEE: A University Research Alliance for Materials Science in Extreme Environments (2020-2029)</h4>

<strong>Funding Source</strong>: <a href="https://www.dtra.mil" target="_blank">Defence Threat Reduction Agency</a><br>


An alliance of 18 research institutions led by the Johns Hopkins University in collaboration with the Defense Threat Reduction Agency (DTRA) to advance fundamental science to reduce the threat of weapons of mass destruction. My role is to lead UQ efforts together with Prof. Shields. Current applications include:

* Bayesian Inference to learn uncertainties from experimental data, that are used to inform canonical model, laser-driven, experiments spanning the parameter space that constrain uncertainties in material properties. 
* Development of validated constitutive models for deformation, flow, and thermal fields in sand and sandstone, considering uncertainties.
* Optimizing/controlling the time evolution of a molecular system under the influence of electromagnetic radiation (i.e., a laser pulse or an external light source).


</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/MSEE.png" width="500px"/>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>Data-driven Uncertainty Quantification in Computational Human Head Models (2020-2022)</h4>

<strong>Funding Source</strong>: <a href="https://www.ninds.nih.gov" target="_blank">National Institute of Neurological Disorders and Stroke of the National Institutes of Health (NIH)</a><br>

Computational models of the human head are promising tools for estimating the impact-induced response of brain, and thus play an important role in the prediction of traumatic brain injury. Modern biofidelic head model simulations are associated with very high computational cost, and high-dimensional inputs and outputs, which limits the applicability of traditional uncertainty quantification (UQ) methods on these systems. In this study, a two-stage, data-driven manifold learning-based framework is proposed for UQ of computational head models. 

</div>
<div class="col-md-12 col-sm-12" style="background-color:transparent" >
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/head1.png" width="500px"/>
</div>
</div>
</div>

## Past projects

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>An initial investigation of structural reliability from sparse data (2018-2019)</h4>

<strong>Funding Source</strong>: <a href="https://www.onr.navy.mil/" target="_blank">Office of Naval Research</a><br>
<strong>Role</strong>: Postdoctoral Researcher

In this project I applied methods for imprecise probability in the context of structural reliability in
order to realistically assess the uncertainty in probability of failure estimates. More specifically, I proposed a framework that couples Subset simulation (SuS) and First-order reliability method with Bayesian/information theoretic multi-model inference.
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>Efficient stochastic simulation-based computational modeling for structural design, reliability and life-cycle assessment  (2016-2019)</h4>

<strong>Funding Source</strong>: <a href="https://www.onr.navy.mil/" target="_blank">Office of Naval Research</a><br>
<strong>Role</strong>: Postdoctoral Researcher

In this project I developed novel adaptive stochastic collocation methods. More specifically, the proposed method is based on the concept of multi-element stochastic collocation methods and is capable of dealing with very high-dimensional models whose solutions are expressed as a vector, a matrix, or a tensor. 
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4>Mastering the Computational Challenges in Numerical
Modeling and Optimum Design of Carbon Nanotube Reinforced Materials (2012-2017)</h4>

<strong>Funding Source</strong>: <a href="https://erc.europa.eu/funding/advanced-grants" target="_blank">European Research Council</a><br>
<strong>Role</strong>: Ph.D Researcher

In this project I applied machine learning (e.g., artificial neural networks in the framework of multiscale analysis of composite materials with Carbon nanotubes (CNTs)). Moreover, I developed an adaptive version of Spectral Stochastic Finite Element Method, introducing a nonlinear formulation and introducing novel solution schemes.

