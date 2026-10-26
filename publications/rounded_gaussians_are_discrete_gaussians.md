---
layout: page
title: "Rounded Gaussians are Discrete Gaussians"
permalink: /publications/rounded_gaussians_are_discrete_gaussians
---

Not yet published.  

<a href="https://eprint.iacr.org/2026/2583" target="_blank" style="text-decoration: none;"><button class="mybutton" onmouseover="this.style.backgroundColor='#337076'; this.style.color='#FFFFFF'; this.querySelector('span').style.paddingRight = '16px'; this.querySelector('span').querySelector('span').style.opacity = '1'; this.querySelector('span').querySelector('span').style.right = '0';" onmouseout="this.style.backgroundColor='#FFFFFF'; this.style.color='#337076'; this.querySelector('span').style.paddingRight = '0'; this.querySelector('span').querySelector('span').style.opacity = '0'; this.querySelector('span').querySelector('span').style.right = '-20px';"><span style="cursor: pointer; display: inline-block; position: relative; transition: 0.5s; font-size: 16px;">ePrint <span style="position: absolute; opacity: 0; top: 0; right: -20px; transition: 0.5s;">&#xbb;</span></span></button></a>  

## Abstract
> Many lattice-based cryptographic schemes still require sampling integers following a Gaussian-like distribution. Depending on the application, this sampling should be generic to tackle variable (and possibly large) standard deviations and centers, with a low memory footprint, easily implementable in constant-time, and with the highest throughput. Combining all these features is very challenging, as shown by the numerous works on optimizing discrete Gaussian samplers. In contrast, the rounded Gaussian (and associated samplers), formalized by Hülsing, Lange and Smeets (PKC'18), seems to satisfy these criteria, but its formal definition makes security analyses of the schemes using it more complex, thus explaining why they are rarely used in practice.
In this paper, we show that a small correction on the parameter $$\sigma$$ of the rounded Gaussian yields a distribution that is close to a discrete Gaussian of parameter $$s$$. More formally, defining $$\sigma = s - 1/(24s)$$ yields a Rényi divergence between the two distributions evolving as $$1 + O(1/s^8)$$. As a result, for mild to large parameters $$s$$, one can use the corrected rounded Gaussian sampler, while still analyzing security with an ideal discrete Gaussian at a very mild loss. It then readily gives a discrete Gaussian sampler that benefits from all the features of rounded Gaussian samplers.

