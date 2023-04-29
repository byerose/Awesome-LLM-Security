> 🚩 Recently, there have been significant advances in generative models, including the diffusion model in the field of image processing, large language models in the field of text processing, and even diffusion models that have been extended to speech and video processing. The rapid development of generative models has forced us to consider their security issues. This repository primarily focuses on the security issues arising from generative models and how to use generative models to address the problems of adversarial machine learning.

# Table of Contents
- [Survey](#Survey)
- [Awesome](#Awesome)
- [Representative Model](#Representative-Model)
- [Risks of Model](#Risks-of-Model)
  - [Prompt Injection](#Prompt-Injection)
  - [Poisoning](#Poisoning)
  - [Privacy](#Privacy)
  - [Malicious Content](#Malicious-Content)
- [Evaluation on Content](#Evaluation-on-Content)
- [Application](#Application)
  - [For Adversarial Robustness](#For-Adversarial-Robustness)
- [Workshop](#Workshop)

# Survey
- [A Survey of Large Language Models](http://arxiv.org/abs/2303.18223) [[Link]](https://github.com/RUCAIBox/LLMSurvey) <img src="https://img.shields.io/badge/nlp-orange" alt="" />
- [Diffusion Models: A Comprehensive Survey of Methods and Applications](https://arxiv.org/abs/2209.00796) [[Link]](https://github.com/YangLing0818/Diffusion-Models-Papers-Survey-Taxonomy) <img src="https://img.shields.io/badge/cv-green" alt="" />

# Awesome
- Tracking Papers on Diffusion Models [[Link]](https://vsehwag.github.io/blog/2023/2/all_papers_on_diffusion.html) <img src="https://img.shields.io/badge/cv-green" alt="" />
- Awesome-LLM-Uncertainty-Reliability-Robustness [[Link]](https://github.com/jxzhangjhu/Awesome-LLM-Uncertainty-Reliability-Robustness)<img src="https://img.shields.io/badge/nlp-orange" alt="" />

# Representative Model
- Improved Denoising Diffusion Probabilistic Models [[ICML '21]](https://arxiv.org/abs/2102.09672) [[code]](https://github.com/openai/improved-diffusion) <img src="https://img.shields.io/badge/cv-green" alt="" />
- InCoder: A Generative Model for Code Infilling and Synthesis [[ICLR '23]](http://arxiv.org/abs/2204.05999) [[code]](https://github.com/dpfried/incoder) <img src="https://img.shields.io/badge/nlp-orange" alt="" />
- CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis [[ICLR '23]](https://arxiv.org/abs/2203.13474) [[code]](https://github.com/salesforce/CodeGen) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

# Risks of Model

## Prompt Injection

- More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models [[ArXiv '23]](https://arxiv.org/abs/2302.12173) [[code]](https://github.com/greshake/lm-safety) <img src="https://img.shields.io/badge/nlp-orange" alt="" />
  <details><summary></summary>

## Poisoning

- BadGPT: Exploring Security Vulnerabilities of ChatGPT via Backdoor Attacks to InstructGPT [[NDSS '23 Poster]](https://arxiv.org/abs/2304.12298) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

- Analyzing And Editing Inner Mechanisms of Backdoored Language Models [[ArXiv '23]](http://arxiv.org/abs/2302.12461) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

## Privacy
- Multi-step Jailbreaking Privacy Attacks on ChatGPT [[ArXiv '23]](http://arxiv.org/abs/2304.05197) <img src="https://img.shields.io/badge/nlp-orange" alt="" />
- Extracting training data from diffusion models [[ArXiv '23]](https://arxiv.org/abs/2301.13188)  <img src="https://img.shields.io/badge/cv-green" alt="" />
- Extracting Training Data from Large Language Models [[USENIX '21]](https://arxiv.org/abs/2012.07805) [[code]](https://github.com/ftramer/LM_Memorization) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

## Malicious Content
- Controlling Large Language Models to Generate Secure and Vulnerable Code [[ArXiv '23]](https://arxiv.org/abs/2302.05319) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

# Evaluation on Content
- LEVER: Learning to Verify Language-to-Code Generation with Execution [[ArXiv]](https://arxiv.org/abs/2302.08468) [[code]](https://github.com/niansong1996/lever) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

- Holistic Evaluation of Language Models [[ArXiv '22]](https://arxiv.org/abs/2211.09110) [[code]](https://github.com/stanford-crfm/helm) [[project]](https://crfm.stanford.edu/helm/latest/) <img src="https://img.shields.io/badge/nlp-orange" alt="" />
 
- How Secure is Code Generated by ChatGPT? [[ArXiv '22]](https://arxiv.org/abs/2304.09655) [[code]](https://github.com/raphaelkhoury/programsgeneratedbychatgpt) <img src="https://img.shields.io/badge/nlp-orange" alt="" />

# Application
## For Adversarial Robustness 
- DensePure: Understanding Diffusion Models towards Adversarial Robustness [[ICLR '23]](https://arxiv.org/abs/2211.00322) [[code]](https://github.com/Jayfeather1024/DensePure) <img src="https://img.shields.io/badge/cv-green" alt="" />
  
- DiffSmooth: Certifiably Robust Learning via Diffusion Models and Local Smoothing [[USENIX '23]](https://www.usenix.org/conference/usenixsecurity23/presentation/zhangjiawei) <img src="https://img.shields.io/badge/cv-green" alt="" />

- Expunging Clean-label Invisible Poisons via Pre-trained Diffusion Models [[cvpr '23]] [[code]] <img src="https://img.shields.io/badge/cv-green" alt="" />

- Defending against Adversarial Audio via Diffusion Model [[CVPR '23]](https://openreview.net/forum?id=5-Df3tljit7) [[code]](https://github.com/cychomatica/AudioPure) <img src="https://img.shields.io/badge/audio-blue" alt="" />
  
- Diffusion Models for Adversarial Purification [[ICML '22]](https://arxiv.org/abs/2205.07460) [[code]](https://github.com/NVlabs/DiffPure) <img src="https://img.shields.io/badge/cv-green" alt="" />

- Better Diffusion Models Further Improve Adversarial Training [[ICML '23]](https://arxiv.org/abs/2302.04638) [[code]](https://github.com/wzekai99/dm-improves-at) <img src="https://img.shields.io/badge/cv-green" alt="" />

- Denoising Diffusion Probabilistic Models as a Defense against Adversarial Attacks [[ArXiv '22]](https://arxiv.org/abs/2301.06871) [[code]](https://github.com/ankile/adversarial-diffusion) <img src="https://img.shields.io/badge/cv-green" alt="" />

- Threat Model-Agnostic Adversarial Defense using Diffusion Models [[ArXiv '22]](https://arxiv.org/abs/2207.08089) [[code]](https://github.com/tsachiblau/Threat-Model-Agnostic-Adversarial-Defense-using-Diffusion-Models) <img src="https://img.shields.io/badge/cv-green" alt="" />

- Robust Learning Meets Generative Models: Can Proxy Distributions Improve Adversarial Robustness? [[ICLR '22]](https://github.com/inspire-group/proxy-distributions) [[code]]() <img src="https://img.shields.io/badge/cv-green" alt="" />

# Workshop
- Challenges of Deploying Generative AI [[ICML '23]](https://deployinggenerativeai.github.io/index)
