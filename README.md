# X-GS: An Extensible Framework for Perceiving and Thinking with 3D Gaussian Splatting

Yueen Ma, Zenglin Xu, Irwin King

> **Code is coming soon.** Stay tuned!

## About

3D Gaussian Splatting (3DGS) has emerged as a powerful technique for novel view synthesis and has since extended into many spatial AI applications. However, most existing 3DGS methods operate in isolation, each focusing on a specific domain.

**X-GS** is an extensible framework that integrates these previously isolated 3DGS methods into the perception module of a vision-language model (VLM) for spatial tasks. It has two major components:

- **Perceiver**: performs online 3DGS-based SLAM with semantic distillation, and outputs semantic Gaussians from unposed video streams. It leverages recent vision foundation models for stronger geometric priors, together with three novel optimizations that improve the efficiency of semantic distillation.
- **Thinker**: interfaces diverse VLMs with these semantic Gaussians, unlocking spatial multimodal capabilities such as 3D visual grounding and scene captioning.

Experiments on diverse benchmarks demonstrate the efficiency of X-GS and the newly unlocked multimodal capabilities.

## Release plan

- [ ] Perceiver (online 3DGS SLAM with semantic distillation)
- [ ] Thinker (VLM interface for 3D visual grounding and scene captioning)
- [ ] Evaluation scripts

## Related work from the authors

- [3D-MoE: Towards Spatial Intelligence with Mixture-of-Experts for 3D Reasoning and Action Generation](https://arxiv.org/abs/2501.16698)
- [A Survey on Vision-Language-Action Models for Embodied AI](https://arxiv.org/abs/2405.14093)

## Contact

Yueen Ma: mayueen@link.cuhk.edu.hk
