---
layout: page
title: "Towards Classical Hardness of Module-LWE: The Linear Rank Case"
permalink: /papers/towards_classical_hardness_of_module-lwe_the_linear_rank_case
---

Co-authored with [Katharina Boudgoust](https://katinkabou.github.io/), [Adeline Roux-Langlois](https://people.irisa.fr/Adeline.Roux-Langlois/), and [Weiqiang Wen](http://people.irisa.fr/Weiqiang.Wen/).   
In the proceedings of [Asiacrypt 2020](https://link.springer.com/chapter/10.1007/978-3-030-64834-3_10).  

Get paper on [IACR ePrint](https://eprint.iacr.org/2020/1020) or [here](/assets/pub/BJRW20_Towards_Classical_Hardness_MLWE_Linear_Rank.pdf)

<a href="/assets/pub/BJRW20_Towards_Classical_Hardness_MLWE_Linear_Rank.pdf" target="_blank" style="text-decoration: none;">
    <button class="button" style="display: inline-block; border-radius: 25px; background-color: #337076; border: none; color: #FFFFFF; text-align: center; font-size: 10px; padding: 10px 10px; width: 60px; transition: all 0.5s; cursor: pointer; margin: 5px; vertical-align:middle;" onmouseover="this.style.backgroundColor='#2DA1AD'; this.querySelector('span').style.paddingRight = '10px'; this.querySelector('span').querySelector('span').style.opacity = '1'; this.querySelector('span').querySelector('span').style.right = '0';" onmouseout="this.style.backgroundColor='#337076'; this.querySelector('span').style.paddingRight = '0'; this.querySelector('span').querySelector('span').style.opacity = '0'; this.querySelector('span').querySelector('span').style.right = '-20px';">
        <span style="cursor: pointer; display: inline-block; position: relative; transition: 0.5s;">PDF <span style="position: absolute; opacity: 0; top: 0; right: -20px; transition: 0.5s;">&#xbb;</span></span>
    </button>
</a>

## Abstract
> We prove that the module learning with errors (M-LWE) problem with arbitrary polynomial-sized modulus $$p$$ is classically at least as hard as standard worst-case lattice problems, as long as the module rank $$d$$ is not smaller than the number field degree $$n$$. Previous publications only showed the hardness under quantum reductions. We achieve this result in an analogous manner as in the case of the learning with errors (LWE) problem. First, we show the classical hardness of M-LWE with an exponential-sized modulus. In a second step, we prove the hardness of M-LWE using a binary secret. And finally, we provide a modulus reduction technique. The complete result applies to the class of power-of-two cyclotomic fields. However, several tools hold for more general classes of number fields and may be of independent interest. 