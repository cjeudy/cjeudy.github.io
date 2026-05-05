---
layout: page
title: "Lattice Group Signatures, Revisited"
permalink: /publications/lattice_group_signatures_revisited
---

Co-authored with Paul Delhom, [Pierre-Alain Fouque](https://www.di.ens.fr/~fouque/), and [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226). 

Not yet published.  

<a href="https://eprint.iacr.org/2026/847" target="_blank" style="text-decoration: none;"><button class="mybutton" onmouseover="this.style.backgroundColor='#337076'; this.style.color='#FFFFFF'; this.querySelector('span').style.paddingRight = '16px'; this.querySelector('span').querySelector('span').style.opacity = '1'; this.querySelector('span').querySelector('span').style.right = '0';" onmouseout="this.style.backgroundColor='#FFFFFF'; this.style.color='#337076'; this.querySelector('span').style.paddingRight = '0'; this.querySelector('span').querySelector('span').style.opacity = '0'; this.querySelector('span').querySelector('span').style.right = '-20px';"><span style="cursor: pointer; display: inline-block; position: relative; transition: 0.5s; font-size: 16px;">ePrint <span style="position: absolute; opacity: 0; top: 0; right: -20px; transition: 0.5s;">&#xbb;</span></span></button></a>  

## Abstract
> Group signatures are one of the central privacy-preserving authentication mechanisms, offering an interesting trade-off between accountability and anonymity. Their versatility has led to many applications and even standardization at ISO/IEC. Unfortunately, they lack so far efficient quantum-safe constructions, despite several works implementing the seminal framework by Bellare, Micciancio and Warinschi (BMW) in the lattice setting.
> In this work, we propose an alternative lattice-based construction that departs from the BMW blueprint by trying to minimize the number of elements to conceal in zero-knowledge proofs, the latter being quite complex in this setting. Concretely, it relies on delegated lattice bases, while avoiding the complex OR-proofs of some previous attempts in that direction. Combined with some tricks leveraging the peculiarities of a recent lattice sampler, it results in an efficient scheme that yet retains all the BMW security properties while only relying on standard lattice assumptions. 
