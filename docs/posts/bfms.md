---
authors: 
  - prannay
  - glenn
date: 2025-04-04
categories:
  - Cognition
---

# A Primer on Brain Foundation Models

In the past few years, computational neuroscience and cognitive sciences have slowly been catching up to major developments in AI over the past decade, slowly adopting various technologies such as _variational autoencoders_ (1), _diffusion learning_ (2), and most recently, *foundation models*. This work has since led to the tremendous development of what we now call **brain foundation models**.
{ .annotate }

1. [Bethge et al.](https://arxiv.org/abs/2207.08002) used variational autoencoders to transform EEG data into a latent space representation to effectively understand various internal relationships.
2. [Zhou et al.](https://arxiv.org/abs/2407.03089) used diffusion learning to increase the resolution of EEG channels to translate to higher-resolution EEG data.

<!-- more -->

The promise of brain foundation models, or BFMs for short, is simple: generically modelling the relationship of various input channels via a *large* amount of *raw* data. Be it drivers on a simulator, or gamers playing Atari, be it athletes playing memory games, or traffic operators in their daily operations, we can collect data from all across this domain, from sensors far and wide, and feed them all into a foundation model, allowing it to learn and find relations that normal models accepting specific inputs simply cannot.