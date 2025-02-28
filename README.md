# MALT: Improving Reasoning with Multi-Agent LLM Training

This repository contains the website for the [MALT paper](https://arxiv.org/abs/2412.01928), which introduces a novel post-training strategy for improving reasoning in Large Language Models (LLMs).

## Overview

MALT (Multi-Agent LLM Training) divides the reasoning process into three specialized agent roles:
- **Generator**: Creates initial solutions to problems
- **Verifier**: Evaluates and critiques candidate solutions
- **Refinement**: Improves solutions based on feedback

This approach enables more thorough reasoning exploration and self-correction capabilities. During training, MALT generates synthetic data through multi-agent interactions, propagating reward signals back through the pipeline to improve each specialized agent.

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
