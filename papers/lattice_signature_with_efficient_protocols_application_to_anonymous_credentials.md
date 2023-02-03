---
layout: page
title: "Lattice Signature with Efficient Protocols, Application to Anonymous Credentials"
permalink: /papers/lattice_signature_with_efficient_protocols_application_to_anonymous_credentials
---

Co-authored with [Adeline Roux-Langlois](https://people.irisa.fr/Adeline.Roux-Langlois/), and [Olivier Sanders](https://crypto.orange-labs.fr/acg/people/peopleProfil.php?id=226).    

Get paper on [IACR ePrint](https://eprint.iacr.org/2022/509)

## Abstract
> Digital signature is an essential primitive in cryptography, which can be used as the digital analogue of handwritten signatures but also as a building block for more complex systems. In the latter case, signatures with specific features are needed, so as to smoothly interact with the other components of the systems, such as zero-knowledge proofs. This has given rise to so-called signatures with efficient protocols, a versatile tool that has been used in countless applications. Designing such signatures is however quite difficult, in particular if one wishes to withstand quantum computing. We are indeed aware of only one post-quantum construction, proposed by Libert et al. at Asiacrypt’16, yielding very large signatures and proofs.  
In this paper, we propose a new construction that can be instantiated in both standard lattices and structured ones, resulting in each case in dramatic performance improvements. In particular, the size of a proof of message-signature possession, which is one of the main metrics for such schemes, can be brought down to less than 650 KB. As our construction retains all the features expected from signatures with efficient protocols, it can be used as a drop-in replacement in all systems using them, which mechanically improves their own performance, and has thus a direct impact on many applications. It can also be used to easily design new privacy-preserving mechanisms. As an example, we provide the first lattice-based anonymous credentials system.