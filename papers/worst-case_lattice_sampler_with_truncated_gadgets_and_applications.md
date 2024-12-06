---
layout: page
title: "Worst-Case Lattice Sampler with Truncated Gadgets and Applications"
permalink: /papers/worst-case_lattice_sampler_with_truncated_gadgets_and_applications
---

Co-authored with [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226). 

Only available on [IACR ePrint](https://eprint.iacr.org/2024/1952) at the moment.  

The associated implementation is available [here](https://github.com/truncatedsampler/truncated-sampler) and is distributed under [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.html).

## Abstract
> Gadget-based samplers have proven to be a key component of several cryptographic primitives, in particular in the area of privacy-preserving mechanisms. Most constructions today follow the approach introduced by Micciancio and Peikert (MP) yielding preimages whose dimension linearly grows with that of the gadget. To improve performance, some papers have proposed to truncate the gadget but at the cost of an important feature of the MP sampler, namely the ability to invert _arbitrary_ syndromes. Technically speaking, they replace the _worst-case_ MP sampler by an _average-case_ sampler that can only be used in specific contexts. Far from being a mere theoretical restriction, it prevents the main applications of gadget-based samplers from using truncated variants and thus from benefiting from the associated performance gains.
In this paper, we solve this problem by describing a worst-case sampler that still works with truncated gadgets. Its main strength is that it retains the main characteristics of the MP sampler while providing flexibility in the choice of the truncation parameter. As a consequence, it can be used as a plug-in replacement for all applications relying on the MP sampler so far, leading to performance improvements up to 30% as illustrated by several examples in this paper. Our sampler is supported by a thorough security analysis that addresses the hurdles met by previous works and its practicality is demonstrated by a concrete implementation.