---
layout: page
title: "Revisiting Preimage Sampling for Lattices"
permalink: /papers/revisiting_preimage_sampling_for_lattices
---

Co-authored with [Adeline Roux-Langlois](https://people.irisa.fr/Adeline.Roux-Langlois/), and [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226).    

Get paper on [IACR ePrint](https://eprint.iacr.org/2023/446)

## Abstract
> Preimage Sampling is a fundamental process in lattice-based cryptography whose performance directly affects the one of the cryptographic mechanisms that rely on it. In 2012, Micciancio and Peikert proposed a new way of generating trapdoors (and an associated preimage sampling procedure) with very interesting features. Unfortunately, in some applications such as digital signatures, the performance may not be as competitive as other approaches like Fiat-Shamir with Aborts.
In this work we revisit the Micciancio-Peikert preimage sampling algorithm with different contributions. We first propose a finer analysis of this procedure which results in interesting efficiency gains of around 20% on the preimage sizes without affecting security. It can thus be used as a drop-in replacement in every construction resorting to it.
We then reconsider the Lyubashevsky-Wichs sampler for Micciancio-Peikert trapdoors which leverages rejection sampling but suffered from strong parameter requirements that hampered performance. We propose an improved analysis which allows to obtain much more compact parameters. This leads to gains of up to 30% compared to the original Micciancio-Peikert sampling technique and opens promising perspectives for the efficiency of advanced lattice-based constructions relying on such mechanisms.
As an application of the latter, we give the first lattice-based aggregate signature supporting public aggregation and that achieves relevant compression compared to the concatenation of individual signatures. Our scheme is proven secure in the aggregate chosen-key model coined by Boneh et al. in 2003, based on the well-studied assumptions Module Learning With Errors and Module Short Integer Solution.  

**Note:** A preliminary version of this work has been published as [ePrint 2023/239](https://eprint.iacr.org/2023/239). Unintentionally, one of the contributions was significantly overlapping with the result of Lyubashevsky and Wichs at PKC 2015 ([ePrint 2014/1027](https://eprint.iacr.org/2014/1027)), leading us to withdraw the paper. This new version presents the other contributions and provides a thorough comparison with [ePrint 2014/1027](https://eprint.iacr.org/2014/1027), highlighting our actual contribution on this aspect.