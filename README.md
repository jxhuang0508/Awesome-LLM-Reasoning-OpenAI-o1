# Awesome Learning to Reason with LLMs: From Prompt Engineering to OpenAI o1 A Survey

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) 
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
![visitor badge](https://visitor-badge.lithub.cc/badge?page_id=jxhuang0508.awesome-llm-reasoning-openai-o1&left_text=Visitors)

This repository explores recent advancements in reasoning with LLMs, starting from conventional methods like Chain-of-Thought (CoT) prompting to the latest innovations, such as OpenAI's learning-based CoT reasoning in the o1 model series. It provides a comprehensive overview of how reasoning with LLMs has evolved, inlcuding recent advancements, key research papers, and discussions from blogs, social media, and expert talks. 

---
### Table of Contents 
- [Official OpenAI Documents](#official-openai-documents)
- [News about LLM Reasoning OpenAI o1](#news-about-llm-reasoning-openai-o1)
  - [Blogs](#blogs)
  - [Talks](#talks)
  - [Social Media Posts](#social-media-posts)
- [Awesome Papers](#awesome-papers)
  - [How to Contribute](#how-to-contribute)
  - [Learning-based Reasoning](#learning-based-reasoning)
  - [Prompt Engineering-based Reasoning](#prompt-engineering-based-reasoning)
---

## Official OpenAI Documents

- [**OpenAI o1 Hub**](https://openai.com/o1/)
  - Main page introducing the o1 series, including details about its capabilities, reasoning tasks, and usage limits.
- [**OpenAI o1 System Card**](https://assets.ctfassets.net/kftzwdyauwt9/67qJD51Aur3eIc96iOfeOP/71551c3d223cd97e591aa89567306912/o1_system_card.pdf)
  - A document outlining the safety evaluations, potential risks, and mitigations applied to the o1 model​.
- [**OpenAI Reasoning Guide**](https://platform.openai.com/docs/guides/reasoning)
  - A guide focusing on how OpenAI models can enhance reasoning tasks, explaining methods like chain-of-thought reasoning and how models handle complex problem-solving.

## News about LLM Reasoning OpenAI o1

### <ins>Blogs</ins>

- **[OpenAI]** [**Learning to Reason with LLMs**](https://openai.com/index/learning-to-reason-with-llms/)
  - Discuss advancements in improving reasoning with LLMs, focusing on how structured thinking processes, like chain-of-thought reasoning, can significantly enhance complex problem-solving.
- **[OpenAI]** [**OpenAI o1 Mini: Advancing Cost-Efficient Reasoning**](https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning/)
  - Introduce the OpenAI o1-mini model, a cost-effective solution optimized for coding and reasoning, offering a balance between performance and affordability.
- **[Nathan Lambert]** [**OpenAI’s Strawberry, LM self-talk, inference scaling laws, and spending more on inference**](https://www.interconnects.ai/p/openai-strawberry-and-inference-scaling-laws)
- **[Nathan Lambert]** [**Reverse engineering OpenAI’s o1**](https://substack.com/@natolambert/p-148935394)
- **[Nouha Dziri]** [**Have o1 Models Cracked Human Reasoning?**](https://substack.com/home/post/p-148782195)

### <ins>Talks</ins>

- **[Noam Brown (OpenAI)]** [**Parables on the Power of Planning in AI: From Poker to Diplomacy**](https://www.youtube.com/watch?app=desktop&v=eaAonE58sLU)
- **[Noam Brown, Ilge Akkaya and Hunter Lightman (OpenAI)]** [**Teaching LLMs to Reason Better**](https://www.youtube.com/watch?v=jPluSXJpdrA&t=1669s)

### <ins>Social Media Posts</ins>

#### Twitter

- **[OpenAI Developers]** [**Ask Me Anything**](https://x.com/OpenAIDevs/status/1834608585151594537) - [[Summary]](https://twitter-thread.com/t/1834686946846597281)
- **[Jason Wei]** [**Super excited to finally share what I have been working on at OpenAI!**](https://x.com/_jasonwei/status/1834278706522849788)

#### Reddit

- [**OpenAI's new model o1 really can reason**](https://www.reddit.com/r/ChatGPT/comments/1ffa5bb/openais_new_model_o1_really_can_reason_wow/)
- [**OpenAI releases o1, its first model with ‘reasoning’ abilities**](https://www.reddit.com/r/technology/comments/1ff8mey/openai_releases_o1_its_first_model_with_reasoning/)
- [**OpenAI announces o1**](https://www.reddit.com/r/singularity/comments/1ff7mod/openai_announces_o1/)



## Awesome Papers

### How to Contribute
* We welcome every researcher who contributes to this repository. Please feel free to pull requests or contact us if you find any related papers that are not included here.

The process to submit a pull request is as follows:
- a. Fork the project into your own repository.
- b. Add the Title, Paper link, Conference, Project/Code link in `README.md` using the following format:
```
  |[Title](Paper Link)|Venue|[Code](Code link)|
```
- c. Submit the pull request to this branch.

### Learning-based Reasoning

| Title                                             | Venue | Code |                                  
|---------------------------------------------------|:-----:|:----:|
|[**STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning**](https://arxiv.org/pdf/2203.14465)|NeurIPS 2022|[Code](https://www.catalyzex.com/paper/star-bootstrapping-reasoning-with-reasoning/code)|
|[**Large Language Models Can Self-Improve**](https://aclanthology.org/2023.emnlp-main.67/)|EMNLP 2023|-|
|[**Training Chain-of-Thought via Latent-Variable Inference**](https://arxiv.org/abs/2312.02179)|NeurIPS 2023|-|
|[**V-STaR: Training Verifiers for Self-Taught Reasoners**](https://arxiv.org/pdf/2402.06457)|COLM 2024|-|
|[**Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking**](https://arxiv.org/pdf/2403.09629)|arXiv 2024|-|
|[**MindStar: Enhancing Math Reasoning in Pre-trained LLMs at Inference Time**](https://arxiv.org/pdf/2405.16265)|arXiv 2024|-|
|[**Q\*: Improving Multi-step Reasoning for LLMs with Deliberative Planning**](https://arxiv.org/pdf/2406.14283)|arXiv 2024||




### Prompt Engineering-based Reasoning
| Title                                             | Venue |Code |                                  
|---------------------------------------------------|:------------:|:-----:|
|[**Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**](https://arxiv.org/abs/2201.11903)|NeurIPS 2022|-|
|[**Large Language Models are Zero-Shot Reasoners**](https://arxiv.org/pdf/2205.11916)|NeurIPS 2022|-|
|[**Automatic Chain of Thought Prompting in Large Language Models**](https://arxiv.org/abs/2210.03493)|arXiv 2022|[Code](https://github.com/amazon-research/auto-cot)|
|[**Self-Consistency Improves Chain of Thought Reasoning in Language Models**](https://arxiv.org/abs/2203.11171)|ICLR 2023|-|
|[**Tree of Thoughts: Deliberate Problem Solving with Large Language Models**](https://arxiv.org/abs/2305.10601)|NeurIPS 2023|[Code](https://github.com/princeton-nlp/tree-of-thought-llm)|
|[**Large Language Model Guided Tree-of-Thought**](https://arxiv.org/abs/2305.08291)|arXiv 2024|[Code](https://github.com/jieyilong/tree-of-thought-puzzle-solver)|
|[**ART: Automatic multi-step reasoning and tool-use for large language models**](https://arxiv.org/pdf/2303.09014)|arXiv 2023|-|
|[**Active Prompting with Chain-of-Thought for Large Language Models**](https://arxiv.org/pdf/2302.12246)|ACL 2024|[Code](https://github.com/shizhediao/active-prompt)|
|[**From Medprompt to o1: Exploration of Run-Time Strategies for Medical Challenge Problems and Beyond**](https://arxiv.org/abs/2411.03590)|arXiv 2024|[Code](https://github.com/microsoft/promptbase)|
















