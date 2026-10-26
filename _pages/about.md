---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Research @ Google</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>y5zhuang AT ucsd.edu</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder
---

**Hey, I'm Yufan Zhuang 庄宇凡**

I am a Research Scientist at [Google Cloud AI Research](https://research.google/teams/cloud-ai-research/) working on **making language models reason better and act more agentically**. I received my PhD from UC San Diego, advised by [Jingbo Shang](https://shangjingbo1226.github.io/).

📢 **I'm looking for motivated interns!** If you're interested in working on LLM reasoning and agents, feel free to [email me](mailto:{{ 'y5zhuang@ucsd.edu' | encode_email }}).

<section class="p-3 mb-4 rounded" aria-labelledby="ple-highlight" style="border: 2px solid var(--global-theme-color); background: var(--global-card-bg-color);">
  <p class="mb-1"><strong>Featured work · October 2026</strong></p>
  <h2 id="ple-highlight" class="mt-0">PLE: Physical-Engineering's Last Exam</h2>
  <p>Can AI agents deliver real engineering work? PLE tests agents on 85 long-horizon tasks across electrical, civil, structural, and mechanical engineering, from navigating project documents to producing complete engineering deliverables.</p>
  <p class="mb-0"><a href="https://ple-bench.com/">Project &amp; leaderboard</a> · <a href="https://arxiv.org/abs/2610.30537">Paper</a> · <a href="https://github.com/google-research/ple">Code</a></p>
</section>

### 🛠️ **Agents for Real-World Engineering**

**T2J-Bench** ([arXiv'26](https://arxiv.org/abs/2605.29054) · [Project](https://ft2023.github.io/T2j-web/) · [Code](https://github.com/google-research/t2j-bench)) - _Execution-Grounded PyTorch-to-JAX Repository Migration_

Evaluating coding agents on 63 whole-repository migrations across training and inference, with a torch-free verifier that measures functional equivalence rather than surface-level code similarity.

### 🔍 **LLM Reasoning and Agentic Learning**

**RRSI** ([arXiv'26](https://arxiv.org/abs/2609.24972)) - _Regularized Recursive Self-Improvement of Agent Harnesses_  
Regularizing how agent harnesses evolve to improve generalization beyond the tasks used during self-improvement, while reducing token costs.

**Register Tokens** ([arXiv'26](https://arxiv.org/abs/2609.16372)) - _Bounded-State Reasoning in Diffusion Language Models_  
Carrying reasoning progress across generation chunks in a fixed-size set of continuous register states, improving math and code reasoning without retaining all earlier generated text.

**EnvHarness** ([arXiv'26](https://arxiv.org/abs/2608.19880)) - _Awakening Static Worlds for Agent Learning_  
Adapting existing environments to agents' weaknesses through programmable components that preserve the original verifier, supporting targeted agent learning and reinforcement learning.

**Test-time Recursive Thinking** ([arXiv'26](https://arxiv.org/abs/2602.03094)) - _Self-Improvement without External Feedback_
Test-time Recursive Thinking improves model reasoning without external feedback. +10.4-14.8 pp on the most difficult problems of LiveCodeBench (accuracy), with pure test-time scaling.

**Knowledge Flow** ([Blog](https://yufanzhuang.notion.site/knowledge-flow)) - _Scaling Reasoning beyond Context Limit_  
Knowledge Flow scales reasoning beyond context limits, enabling open-source models to reach 100% on AIME-25 without training or tools or external feedbacks.

**Mixture of Inputs** ([NeurIPS'25](https://arxiv.org/abs/2505.14827)) - _Beyond Discrete Sampling_  
Exploring continuous mixture approaches that fundamentally improve how language models reason through complex problems by operating in continuous vector space rather than discrete tokens.

**Vector-ICL** ([ICLR'25](https://arxiv.org/abs/2410.05629)) - _Cross-Modal In-Context Learning_  
Enabling models to learn from any data modality in-context through continuous vector representations, breaking down traditional barriers between text, images, and other data types.

**AgenticLU** ([ACL'25](https://arxiv.org/abs/2502.15920)) - _Agentic Long Context Learning_  
Improving long-context capabilities through intelligent agentic approaches that can dynamically reason through complex, extended content with strategic planning.

**MetaTree** ([TMLR'24](https://arxiv.org/abs/2402.03774)) - _Tabular Data Processing with Transformers_  
Training transformers via meta-learning to directly produce strong decision trees, bridging classical ML algorithms with modern neural approaches for superior generalization.

**Deep Contamination** ([EMNLP'24](https://arxiv.org/abs/2406.13236)) - _Cross-lingual Data Contamination Study_  
Uncovering critical issues in how we evaluate contemporary LLMs, particularly around cross-lingual contamination that affects model reliability.

### 🔬 **AI for Software Engineering & Sociology**

**Signal-Aware Code Understanding** ([ACM TOSEM'23](https://dl.acm.org/doi/10.1145/3597202)) - _Trustworthy AI for Source Code_  
Developing signal-aware AI models for software vulnerability detection that focus on learning task-relevant source code features rather than spurious correlations, improving model robustness and reliability.

**Prediction-Preserving Input Minimization** ([ESEC/FSE'21](https://2021.esec-fse.org/details/fse-2021-papers/14/Probing-Model-Signal-Awareness-via-Prediction-Preserving-Input-Minimization)) - _Probing AI Model Understanding_  
Introducing P2IM approach to systematically evaluate AI models' signal awareness by reducing source code to minimal snippets needed to maintain predictions, revealing models' reliance on incorrect signals.

**Computational Social Science** ([Annals AAG'22](https://www.tandfonline.com/doi/abs/10.1080/24694452.2022.2042180)) - _Machine Learning for Sociological Analysis_  
Applying machine learning approaches to decipher heterogeneous representations and images of Chinese communities in North America, bridging computational methods with sociological research.

---

Prior to my PhD study, I worked at [IBM T. J. Watson Research Center](https://research.ibm.com/labs/yorktown-heights) as a research engineer helping to enhance software engineering with the power of AI and vice versa. I received my MS in Data Science from [Columbia](https://datascience.columbia.edu/), my BSc in Applied Math Minor in CS (with First Class Honors) from [Hong Kong Polytechnic University](https://www.polyu.edu.hk/ama/).
