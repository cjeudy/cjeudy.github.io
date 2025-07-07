---
layout: page
title: "Lattice EPID with Efficient Revocation"
permalink: /publications/lattice_epid_with_efficient_revocation
---

Co-authored with [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226). 

Not yet published.   

<a href="https://eprint.iacr.org/2025/1225" target="_blank" style="text-decoration: none;"><button class="mybutton" onmouseover="this.style.backgroundColor='#337076'; this.style.color='#FFFFFF'; this.querySelector('span').style.paddingRight = '16px'; this.querySelector('span').querySelector('span').style.opacity = '1'; this.querySelector('span').querySelector('span').style.right = '0';" onmouseout="this.style.backgroundColor='#FFFFFF'; this.style.color='#337076'; this.querySelector('span').style.paddingRight = '0'; this.querySelector('span').querySelector('span').style.opacity = '0'; this.querySelector('span').querySelector('span').style.right = '-20px';"><span style="cursor: pointer; display: inline-block; position: relative; transition: 0.5s; font-size: 16px;">ePrint <span style="position: absolute; opacity: 0; top: 0; right: -20px; transition: 0.5s;">&#xbb;</span></span></button></a>  

## Abstract
> Enhanced Privacy Identification (EPID) is one of the anonymous authentication mechanisms that found their way into the industry, being deployed in billions of chips and standardized at ISO. The linchpin of EPID lies in its decentralized revocation procedure that allows to revoke a signer by simply placing one of its signatures on a signature revocation list SRL. Each new signature must then include a proof that it has been generated with a key different from those used to produce the signatures on the SRL. This proof of non-revocation in current post-quantum schemes either relies on general-purpose NIZKs or on regular zero-knowledge proofs (ZKP) but with a witness dimension linear in the size of the SRL, which leads to large size and/or computational complexity. 
>
> In this paper, we rethink the standard approach of non-revocation so as to avoid its heavy reliance on ZKP. Our construction indeed combines features from different tools (such as Falcon signatures) that are unusual in this context to pull most elements out of the ZKP, leading to significant performance improvements. Providing all these elements unconcealed creates many security challenges for our construction but we yet manage to address all of them and prove security under well-understood lattice assumptions, and in the strong model of Sanders-Traoré (CT-RSA'21) allowing malicious SRLs.