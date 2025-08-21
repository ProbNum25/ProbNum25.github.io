---
layout: default
title: "ProbNum25 : Accepted Papers"
header_image: Juan2.jpg
---
## Posters 

---
- **Nonlinear Bayesian Probabilistic Numerical Methods are not Computing Bayesian Posteriors**.
  - Marvin Pförtner. 
    <details>
    <summary><em>Abstract</em></summary>
    <p>Bayesian probabilistic numerical methods rely heavily on the notion of disintegration of measures to construct the posterior. However, due to the implicit nature of their definition, constructing disintegrations is often difficult. A folklore result in machine learning conflates the construction of a disintegration with the restriction of probability density functions onto the subset of events that are consistent with a given observation. We provide a comprehensive set of mathematical tools which can be used to construct disintegrations and apply these to find densities of disintegrations on differentiable manifolds. Using our results, we provide a disturbingly simple example in which the restricted density and the disintegration density drastically disagree. Motivated by applications in approximate Bayesian inference and Bayesian inverse problems, we further study the modes of disintegrations. We show that the recently introduced notion of a "conditional mode" does not coincide in general with the modes of the conditional measure obtained through disintegration, but rather the modes of the restricted measure. We also discuss the implications of the discrepancy between the two measures in practice, advocating for the utility of both approaches depending on the modelling context.</p>  </details>  
  
---
- **Bayesian Inference of Ordinary Differential Equations Accounting for Discretization Error**.
  - Shoji Toyota, Yuto Miyatake
    <details>
    <summary><em>Abstract</em></summary>
    <p> Bayesian inference for ordinary differential equation (ODE) parameters typically relies on numerical solvers; however, incorporating the discretization errors introduced by these solvers into uncertainty quantification is not straightforward. We propose a method to overcome this difficulty. Our approach explicitly models the discretization error as a random variable and jointly performs Bayesian inference on both the ODE parameters and the variance of the discretization error. We demonstrate the effectiveness of the proposed method using the FitzHugh–Nagumo equation model. </p>  </details>
    
---
- **Smoothness Estimation in Spherical Matérn Gaussian Processes**.
  - Subhendu Pramanick
    <details>
    <summary><em>Abstract</em></summary>
    <p> Matérn Gaussian processes are a cornerstone of spatial statistics and machine learning, offering flexible modeling of spatial phenomena through a tunable smoothness parameter. On the sphere-an essential model for global spatial data, two central challenges are: (1) the consistent estimation of the smoothness parameter, which governs the regularity of the process and impacts prediction accuracy, and (2) the quantification of uncertainty, as captured by posterior contraction rates in Bayesian inference. This poster surveys key theoretical advances up to 2025, including the consistent estimation of the smoothness parameter and the Bayesian learning of functions via posterior contraction rates.  Simultaneously, we demonstrate that the smoothness parameter can be consistently estimated from data observed at quasi-uniform points on the sphere, using the maximizer of the Gaussian likelihood—even when the underlying process is non-Gaussian. </p>  </details>

---
- **Bayesian Optimization with Inhomogeneous Smoothness**.
  - Olivier Dondjio
    <details>
    <summary><em>Abstract</em></summary>
    <p> Bayesian optimization (BO) is a popular global optimization technique that uses a Gaussian Process (GP) as a surrogate model for the objective function. Traditional BO methods often assume a stationary GP kernel, implying uniform smoothness across the input space. However, many real‑world objective functions exhibit heterogeneous smoothness. To address this limitation, we propose a BO framework that employs locally adaptive estimation of GP kernel hyperparameters, allowing the model to better capture smoothness variation between regions. </p>  </details>
    
---
- **Sparse Probabilistic Richardson Extrapolation**.
  - Chris Oates
    <details>
    <summary><em>Abstract</em></summary>
    <p> Almost every numerical task can be cast as extrapolation with respect to the fidelity or tolerance parameter of a consistent numerical method.  This perspective enables probabilistic uncertainty quantification and optimal experimental design functionality to be deployed, and also unlocks the potential for convergence of the numerical method to be accelerated.  Recent work established Probabilistic Richardson Extrapolation as a proof of concept, demonstrating how parallel multi-fidelity simulation can be used to accelerate simulation from a whole heart model.  However, the number of data was required to increase super-exponentially with dimension, limiting use in the multivariate context.  This new work develops the notion of `extrapolation sparsity', which is satisfied by most modern numerical methods and provides a promising route to reducing the data requirement.  Sparsity-exploiting methodology is developed that is simultaneously simpler and more powerful compared to earlier work, and this is accompanied by sharp theoretical guarantees. </p>  </details>
