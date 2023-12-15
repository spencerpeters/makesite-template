"Logical Induction" (alternatively, Garrabrant induction) is one of the most remarkable things I've seen recently. (ht Andrew Critch's short talk at CHAI 2022)
https://arxiv.org/pdf/1609.03543.pdf
Logical induction was developed by the AI safety community, so I don't think it's very well known among academic researchers. A lot of ink has been spilled about it (for example, [this explainer](https://www.lesswrong.com/posts/y5GftLezdozEHdXkL/an-intuitive-guide-to-garrabrant-induction)), so I'll mostly just encourage you to check it out! The tl;dr: Probability theory (in particular, Bayesian updating) lets you resolve uncertainty by *observing* evidence for a hypothesis. But what about resolving uncertainty by *thinking*? The classic example: what if you had to bet on whether the 100th digit of pi is a 7? If I put a gun to your head, you'd probably bet $9 against my $1


You'd probably start by offering

The tl;dr is that probability theory lets


The tl;dr is that probability theory (in particular, Bayesian updating) deals with uncertainty in the state of


deals with uncertainty in. If you find something



Have you heard of "Garrabrant induction"?
One of the very coolest things I've seen recently, and it was developed by the AI safety community, so I don't think it's very well known among academic AI researchers. It's very reminiscent of Solomonoff induction, so I thought you might enjoy it. The goal is to manage uncertainty over logical (e.g., mathematical) statements. Roughly speaking, the Garrabrant inductor has access to a "slow" deductive process that proves theorems in a formal language, and it learns to outpace this process. That is, for any sequence of theorems that can merely be enumerated in polynomial time (but not necessarily proved!), it will learn to assign high probability to the theorem statements in polynomial time (Theorem 4.2.1). It also satisfies a number of other surprising properties: for example, it has accurate knowledge of its own beliefs, and it deals with self-referential paradoxes in a reasonable way. If you only have one coffee's worth of time to check it out, I'd recommend (1) the abstract, (2) the list of properties at the start of section 4.
