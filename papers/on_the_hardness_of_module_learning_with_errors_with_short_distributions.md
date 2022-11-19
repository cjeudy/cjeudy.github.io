---
layout: page
title: On the Hardness of Module Learning With Errors with Short Distributions
permalink: /papers/on_the_hardness_of_module_learning_with_errors_with_short_distributions
---

Co-authored with [Katharina Boudgoust](https://katinkabou.github.io/), [Adeline Roux-Langlois](https://people.irisa.fr/Adeline.Roux-Langlois/), and [Weiqiang Wen](http://people.irisa.fr/Weiqiang.Wen/). This paper introduces new results and generalizes the ones published at Asiacrypt 2020 [[1]](/papers/towards_classical_hardness_of_module-lwe_the_linear_rank_case) and CT-RSA 2021 [[2]](/papers/on_the_hardness_of_module-lwe_with_binary_secret).  
To appear in [IACR Journal of Cryptology](https://www.springer.com/journal/145).

Get paper [here](/assets/pub/BJRW22_Hardness_MLWE_with_Short_Distributions.pdf). 

## Abstract
> The Module Learning With Errors problem (M-LWE) is a core computational assumption of lattice-based cryptography which offers an interesting trade-off between guaranteed security and concrete efficiency. The problem is parameterized by a _secret_ distribution as well as an _error_ distribution. There is a gap between the choices of those distributions for theoretical hardness results (standard formulation of M-LWE, i.e., uniform secret modulo $$q$$ and Gaussian error) and practical schemes (small bounded secret and error). In this work, we make progress towards narrowing this gap. More precisely, we prove that M-LWE with $$\eta$$-bounded secret for any $$1 \leq \eta \ll q$$ and Gaussian error, in both its search and decision variants, is at least as hard as the standard formulation of M-LWE, provided that the module rank $$d$$ is at least logarithmic in the ring degree $$n$$. We also prove that the search version of M-LWE with large uniform secret and uniform $$\eta$$-bounded error is at least as hard as the standard M-LWE problem, if the number of samples $$m$$ is close to the module rank $$d$$ and with further restrictions on $$\eta$$. The latter result can be extended to provide the hardness of M-LWE with uniform $$\eta$$-bounded secret _and_ error under specific parameter conditions. Overall, the results apply to all cyclotomic fields, but most of the intermediate results are proven in more general number fields.