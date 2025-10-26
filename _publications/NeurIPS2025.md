---
title: "On the Hardness of Approximating Distributions with Tractable Probabilistic Models"
collection: publications
permalink: /publication/HardnessOfApproximatingTPMs
date: 2025-10-24
venue: "NeurIPS"
excerpt: "TLDR: We investigate the hardness of approximating distributions with TPMs. Our main results show
the NP-hardness of approximation with a bounded f-divergence for any model which can tractably marginalize,
and an exponential lower bound on the size of a deterministic, decomposable probabilisitic circuit representing a 
distribution exactly encoded by a decomposable probabilistic circuit. We also have a number of results related to bounded f-divergence
and approximate inference guarantees."
paperurl: "https://openreview.net/forum?id=0GvEaa9prl"
spotlight: "Spotlight (Acceptance Rate 688/21575 = 3.2%)"
---

TLDR: We investigate the hardness of approximating distributions with TPMs. Our main results show
the NP-hardness of approximation with a bounded f-divergence for any model which can tractably marginalize,
and an exponential lower bound on the size of a deterministic, decomposable probabilisitic circuit representing a 
distribution exactly encoded by a decomposable probabilistic circuit. We also have a number of results related to bounded f-divergence
and approximate inference guarantees.

Abstract: A fundamental challenge in probabilistic modeling is to balance expressivity and inference efficiency. Tractable probabilistic models (TPMs) aim to directly address this tradeoff by imposing constraints that guarantee efficient inference of certain queries while maintaining expressivity. In particular, probabilistic circuits (PCs) provide a unifying framework for many TPMs, by characterizing families of models as circuits satisfying different structural properties. Because the complexity of inference on PCs is a function of the circuit size, understanding the size requirements of different families of PCs is fundamental in mapping the trade-off between tractability and expressive efficiency. However, the study of expressive efficiency of circuits are often concerned with exact representations, which may not align with model learning, where we look to approximate the underlying data distribution closely by some distance measure. Moreover, due to hardness of inference tasks, exactly representing distributions while supporting tractable inference often incurs exponential size blow-ups. In this paper, we consider a natural, yet so far underexplored, question: can we avoid such size blow-up by allowing for some small approximation error? We study approximating distributions with probabilistic circuits with guarantees based on $f$-divergences, and analyze which inference queries remain well-approximated under this framework. We show that approximating an arbitrary distribution with bounded $f$-divergence is $\mathsf{NP}$-hard for any model that can tractably compute marginals. In addition, we prove an exponential size gap for approximation between the class of decomposable PCs and that of decomposable and deterministic PCs.
