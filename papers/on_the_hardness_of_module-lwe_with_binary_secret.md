---
layout: page
title: On the Hardness of Module-LWE with Binary Secret
permalink: /papers/on_the_hardness_of_module-lwe_with_binary_secret
---

Co-authored with [Katharina Boudgoust](https://katinkabou.github.io/), [Adeline Roux-Langlois](https://people.irisa.fr/Adeline.Roux-Langlois/), and [Weiqiang Wen](http://people.irisa.fr/Weiqiang.Wen/).   
In the proceedings of [CT-RSA 2021](https://sites.google.com/site/ctrsa2021/).  

Get paper on [IACR ePrint](https://eprint.iacr.org/2021/265) or [here](/assets/pub/BJRW21_Hardness_bin-MLWE.pdf)

## Abstract
> We prove that the Module Learning With Errors (M-LWE) problem with binary secrets and rank $$d$$ is at least as hard as the standard version of M-LWE with uniform secret and rank $$k$$, where the rank increases from $$k$$ to $$d \geq (k+1)\log_2 q + \omega(\log_2 n)$$, and the Gaussian noise from $$\alpha$$ to $$ \beta = \alpha \cdot \Theta(n^2\sqrt{d})$$, where $$n$$ is the ring degree and $$q$$ the modulus. Our work improves on the recent work by Boudgoust et al. in 2020 by a factor of $$\sqrt{md}$$ in the Gaussian noise, where $$m$$ is the number of given M-LWE samples, when $$q$$ fulfills some number-theoretic requirements. We use a different approach than Boudgoust et al. to achieve this hardness result by adapting the previous work from Brakerski et al. in 2013 for the Learning With Errors problem to the module setting. The proof applies to cyclotomic fields, but most results hold for a larger class of number fields, and may be of independent interest. 