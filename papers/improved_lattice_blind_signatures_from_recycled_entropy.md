---
layout: page
title: "Improved Lattice Blind Signatures from Recycled Entropy"
permalink: /papers/improved_lattice_blind_signatures_from_recycled_entropy
---

Co-authored with [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226). 

Only available on [IACR ePrint](https://eprint.iacr.org/2024/1289) at the moment.  

The associated implementation is available [here](https://github.com/latticeblindsignature/lattice-blind-signature) and is distributed under [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.html).

## Abstract
> Blind signatures represent a class of cryptographic primitives enabling privacy-preserving authentication with several applications such as e-cash or e-voting. It is still a very active area of research, in particular in the post-quantum setting where the history of blind signatures has been hectic. Although it started to shift very recently with the introduction of a few lattice-based constructions, all of the latter give up an important characteristic of blind signatures (size, efficiency, or security under well-known assumptions) to achieve the others. In this paper, we propose another design which revisits the link between the two main procedures of blind signatures, namely issuance and showing, demonstrating that we can significantly alleviate the second one by adapting the former. Concretely, we show that we can harmlessly inject excess randomness in the issuance phase, and then recycle the entropy surplus during showing to decrease the complexity of the zero-knowledge proof which constitutes the main component of the signature. This leads to a blind signature scheme with small sizes, low complexity, and that still relies on well-known lattice assumptions.