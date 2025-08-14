---
layout: page
title: "Hardness of M-LWE with General Distributions and Applications to Leaky Variants"
permalink: /publications/hardness_of_mlwe_with_general_distributions_and_applications_to_leaky_variants
---

Co-authored with [Katharina Boudgoust](https://katinkabou.github.io/), [Erkan Tairi](https://erkantairi.com/), and [Weiqiang Wen](http://people.irisa.fr/Weiqiang.Wen/).  

Not yet published.   

<a href="https://eprint.iacr.org/2025/1472" target="_blank" style="text-decoration: none;"><button class="mybutton" onmouseover="this.style.backgroundColor='#337076'; this.style.color='#FFFFFF'; this.querySelector('span').style.paddingRight = '16px'; this.querySelector('span').querySelector('span').style.opacity = '1'; this.querySelector('span').querySelector('span').style.right = '0';" onmouseout="this.style.backgroundColor='#FFFFFF'; this.style.color='#337076'; this.querySelector('span').style.paddingRight = '0'; this.querySelector('span').querySelector('span').style.opacity = '0'; this.querySelector('span').querySelector('span').style.right = '-20px';"><span style="cursor: pointer; display: inline-block; position: relative; transition: 0.5s; font-size: 16px;">ePrint <span style="position: absolute; opacity: 0; top: 0; right: -20px; transition: 0.5s;">&#xbb;</span></span></button></a>  

## Abstract
> The Module Learning With Errors (M-LWE) problem has become a fundamental hardness assumption for lattice-based cryptography. It offers an attractive trade-off between strong robustness guarantees, sometimes directly based on worst-case lattice problems, and efficiency of the subsequent cryptographic primitives. Different flavors of M-LWE have then been introduced towards improving performance. Such variants look at different secret-error distributions and might allow for additional hints on the secret-error vector. Existing hardness results however only cover restricted classes of said distributions, or are tailored to specific leakage models. This lack of generality hinders the design of efficient and versatile cryptographic schemes, as each new distribution or leakage model requires a separate and nontrivial hardness evaluation.
> 
> In this work, we address this limitation by establishing the hardness of M-LWE under general distributions. As a first step, we show that M-LWE remains hard when the error vector follows an arbitrary bounded distribution with sufficient entropy, with some restriction on the number of samples. Building on this, we then reduce to the Hermite Normal Form (HNF) where the secret-error vector follows said arbitrary distribution. Overall, our result shows the actual shape of the distribution does not matter, as long as it keeps sufficient entropy. 
> 
> To demonstrate the versatility of our framework, we further analyze a range of leakage scenarios. By examining the residual entropy given the leakage, we show that our results of M-LWE with general distributions encompass various types of leakage. More precisely, we cover exact and approximate linear hints which are widely used in recent cryptographic designs, as well as quadratic, and even non-algebraic forms, some of which were not yet covered by any theoretical hardness guarantees. The generality of our results aims at facilitating future cryptographic designs and security analyses.