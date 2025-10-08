---
layout: page
title: Lectures & Reading
permalink: /lectures/
---

### Lectures & Readings

The course is divided into two main parts. The first part consists of instructor-led lectures to establish foundational concepts. The second part is a student-led seminar where we will critically analyze key research papers.


-----

#### Part I: Foundations (Instructor-Led)

**Week 1: Introduction & Transformer Basics** (Completed)
  * *Topics:* Course administration, autoregressive probabilistic models, and the basics of the Transformer architecture.
  * *Readings:*
      * "Attention Is All You Need" (Vaswani, Shazeer, Parmar, Uszkoreit, Jones, Gomez, Kaiser, & Polosukhin, 2017) [[Link](https://arxiv.org/abs/1706.03762)]
      * "Formal Algorithms for Transformers" (Phuong and Hutter, 2022) [[Link](https://arxiv.org/abs/2207.09238)]
      * "An Overview of Large Language Models for Statisticians" (Ji et al., 2025) [[Link](https://arxiv.org/abs/2502.17814)]

**Week 2: A Language for Transformers: RASP & RASP-L**
  * *Topics:* 
  A detailed look at the Transformer architecture and their training including training with RL for the purpose of making them better at reasoning; 
  Modeling transformer computation with the RASP language; 
  The RASP-L conjecture for predicting length generalization.
  * *Readings:*
      * "Thinking Like Transformers" (Weiss, Goldberg, & Yahav, 2021) [[Link](https://arxiv.org/abs/2106.06981)]
      * "What Algorithms can Transformers Learn? A Study in Length Generalization" (Zhou et al., 2024) [[Link](https://openreview.net/forum?id=AssIuHnmHX)]

**Week 3: Computational Limits of Transformers**
  * *Topics:* Computational Universality of Transformers with scaffolding; The Transformer as a circuit and its relation to the complexity class TC0.
  * *Readings:*
      * "Memory Augmented Large Language Models are Computationally Universal" (Schuurmans, 2023) [[Link](https://arxiv.org/abs/2301.04589)]
      * "Autoregressive Large Language Models are Computationally Universal" (Schuurmans, Dai, & Zanini, 2024) [[Link](https://arxiv.org/abs/2410.03170)]
      * "Saturated Transformers are Constant-Depth Threshold Circuits" (Merrill, Sabharwal, & Smith, 2022) [[Link](https://aclanthology.org/2022.tacl-1.49/)]
      * "What Formal Languages Can Transformers Express? A Survey" (Lena Strobl, William Merrill, Gail Weiss, David Chiang, Dana Angluin, 2024) [[Link](https://arxiv.org/abs/2311.00208)]
      * "Chain of Thought Empowers Transformers to Solve Inherently Serial Problems" (Zhiyuan Li, Hong Liu, Denny Zhou, Tengyu Ma, 2024) [[Link](https://arxiv.org/abs/2402.12875)]

**Week 4: Language Learnability**
  * *Topics:* Formal learnability of programming languages and its connection to natural language acquisition.
  * *Readings:*
      * "Learning theory and natural language" (Osherson, Stob, & Weinstein, 1984) [[Link](https://doi.org/10.1016/0010-0277(84)90040-4)]
      * "Density Measures for Language Generation" (Kleinberg, & Wei, 2025) [[Link](https://arxiv.org/abs/2504.14370)]
      * "Language Generation in the Limit" (Kleinberg & Mullainathan, 2024) [[Link](https://openreview.net/forum?id=FGTDe6EA0B)]
      * "Generation through the lens of learning theory" (Li, Raman, & Tewari, 2024) [[Link](https://arxiv.org/abs/2410.13714)]
      * "On Union-Closedness of Language Generation" (Hanneke,  Karbasi,  Mehrotra & Velegkas, 2025) [[Link](https://arxiv.org/abs/2506.18642)]
      * "Language Generation in the Limit: Noise, Loss, and Feedback" (Bai, Panigrahi, & Zhang, 2025) [[Link](https://arxiv.org/abs/2507.15319)]

**Week 5 (short): From Reasoning to Exact Learning**
  * *Topics:* The fundamental misalignment between statistical learning and sound reasoning; Why exact learning is essential for general intelligence; A case study in learning exact algorithmic instructions.
  * *Readings:*
      * "Beyond Statistical Learning: Exact Learning Is Essential for General Intelligence" (György, Lattimore, Lazić, & Szepesvári, 2025) [[Link](https://arxiv.org/abs/2506.23908)]
      * "Learning to Add, Multiply, and Execute Algorithmic Instructions Exactly with Neural Networks" (Back de Luca, Giapitzakis, & Fountoulakis, 2025) [[Link](https://arxiv.org/abs/2502.16763)]

-----

#### Part II: Student-Led Research Seminar Readings

Student pairs will select from the following papers for their presentations, beginning in Week 6.

  * **Theme 1: Provable Reasoning & Algorithmic Solutions**
      * "From Reasoning to Super-Intelligence: A Search-Theoretic Perspective" (Shalev-Shwartz & Shashua, 2025) [[Link](https://arxiv.org/abs/2507.15865)]
      * "The Expressive Power of Transformers with Chain of Thought" (Feng, Li, & Ma, 2024) [[Link](https://arxiv.org/abs/2402.08164)]
      * "Transformers Provably Solve Parity Efficiently with Chain of Thought" (Kim & Suzuki, 2024) [[Link](https://arxiv.org/abs/2410.08633)]
      * "Multi-Head Transformers Provably Learn Symbolic Multi-Step Reasoning via Gradient Descent" (Yang, Huang, Liang, & Chi, 2025) [[Link](https://arxiv.org/abs/2508.08222)]
      * "Metastable Dynamics of Chain-of-Thought Reasoning: Provable Benefits of Search, RL and Distillation" (Kim, Wu, Lee, & Suzuki, 2025) [[Link](https://arxiv.org/abs/2502.01694)]
      * "Learning Compositional Functions with Transformers from Easy-to-Hard Data" (Wang et al., 2025) [[Link](https://arxiv.org/abs/2505.23683)]
      * "A Theory of Learning with Autoregressive Chain of Thought" (Joshi et al., 2025) [[Link](https://arxiv.org/abs/2503.07932)]
      * "Sub-Task Decomposition Enables Learning in Sequence to Sequence Tasks" (Wies, Levine, & Shashua, 2022) [[Link](https://arxiv.org/abs/2204.02892)]
      * "How Transformers Learn Causal Structure with Gradient Descent" (Nichani,  Damian, & Lee 2024) [[Link](https://arxiv.org/abs/2402.14735)]


  * **Theme 2: Hardness, Limitations & Trade-offs**
      * "Hardness of Learning Fixed Parities with Neural Networks" (Shoshani & Shamir, 2025) [[Link](https://arxiv.org/abs/2501.00817)]
      * "How Far Can Transformers Reason? The Globality Barrier and Inductive Scratchpad" (Abbe et al., 2024) [[Link](https://arxiv.org/abs/2406.06467)]
      * "Theoretical Limitations of Multi-Layer Transformer" (Chen, Peng, & Wu, 2024) [[Link](https://arxiv.org/abs/2412.02975)]
      * "Computational-Statistical Tradeoffs at the Next-Token Prediction Barrier: Autoregressive and Imitation Learning under Misspecification." (Rohatgi et al., 2025) [[Link](https://arxiv.org/abs/2502.12465)]
      * "Trade-Offs in Data Memorization via Strong Data Processing Inequalities" (Feldman, Kornowski, & Lyu, 2025) [[Link](https://arxiv.org/abs/2506.01855)]
      * "Why Cannot Large Language Models Ever Make True Correct Reasoning?" (Cheng, 2025) [[Link](https://arxiv.org/abs/2508.10265)]
      * "On Limitations of the Transformer Architecture" (Binghui Peng, Srini Narayanan, Christos Papadimitriou 2024) [[Link](https://arxiv.org/abs/2402.08164)]
      * "Quantitative Bounds for Length Generalization in Transformers" (Zachary Izzo, Eshaan Nichani, Jason D. Lee, 2025) [[Link](https://openreview.net/forum?id=DgGPgVLrRX)]

  * **Theme 3: Generalization & Robustness**
      * "Understanding the Failure Modes of Out-of-Distribution Generalization" (Nagarajan, Andreassen, & Neyshabur, 2020) [[Link](https://arxiv.org/abs/2010.15775)]
      * "Self-Improving Transformers Overcome Easy-to-Hard and Length Generalization Challenges" (Lee et al., 2025) [[Link](https://arxiv.org/abs/2502.01612)]
      * "Transformation-Invariant Learning and Theoretical Guarantees for OOD Generalization" (Montasser, Shao, & Abbe, 2024) [[Link](https://arxiv.org/abs/2410.23461)]
      * "Provable Advantage of Curriculum Learning on Parity Targets with Mixed Inputs" (Abbe, Cornacchia, & Lotfi, 2023) [[Link](https://arxiv.org/abs/2306.16921)]

  * **Theme 4: Representation & Semantics**
      * "Large Language Models Encode Semantics in Low-Dimensional Linear Subspaces" (Saglam et al., 2025) [[Link](https://arxiv.org/abs/2507.09709)]
      * "The Geometry of Truth: Emergent Linear Structure in Large Language Model Representations of True/False Datasets" (Marks & Tegmark, 2023) [[Link](https://arxiv.org/abs/2310.06824)]
      * "On the Minimal Degree Bias in Generalization on the Unseen for Non-Boolean Functions" (Pushkin, Berthier, & Abbe, 2024) [[Link](https://arxiv.org/abs/2406.06354)]

-----

#### Background & Supplementary Readings

This section contains materials for context, including historical perspectives, key empirical results, and related theoretical work. These are not required readings for presentations but are highly recommended for a deeper understanding.

  * **Historical & Philosophical Context**
      * "Connectionism and Cognitive Architecture: A Critical Analysis" (Fodor & Pylyshyn, 1988) 
      * "Linguistics and Natural Logic" (Lakoff, 1970) [[Link](https://doi.org/10.1007/bf00413602)]
      * "Mathematics, Word Problems, Common Sense, and Artificial Intelligence" (Davis, 2024) [[Link](https://arxiv.org/abs/2301.09723)]

  * **Key Empirical Papers & Surveys**
      * "Stop Anthropomorphizing Intermediate Tokens as Reasoning/Thinking Traces!" (Kambhampati, Stechly, & Valmeekam, 2025) [[Link](https://arxiv.org/abs/2504.09762)]
      * "Natural Language Reasoning, A Survey" (Yu, Zhang, Tiwari, & Wang, 2024) [[Link](https://doi.org/10.1145/3664194)]
      * "Universal Transformers" (Dehghani et al., 2018) [[Link](https://arxiv.org/abs/1807.03819)]
      * "REASONING GYM: Reasoning Environments for Reinforcement Learning with Verifiable Rewards" (Stojanovski et al., 2025) [[Link](https://arxiv.org/abs/2505.24760)]
      * "Comment on The Illusion of Thinking..." (Lawsen, 2025) [[Link](https://arxiv.org/abs/2506.09250)]
      * "(How) Do Reasoning Models Reason?" (Kambhampati, Stechly & Valmeekam, 2025) [[Link](http://arxiv.org/abs/2504.09762)]
      * "Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving" (Lin, .., Arora, Jin, et al. 2025) [[Link](http://arxiv.org/abs/2502.07640)]
"

  * **Related Theoretical/Empirical Work**
      * "Learning to Reason with Neural Networks: Generalization, Unseen Data and Boolean Measures" (Abbe et al., 2022) [[Link](https://arxiv.org/abs/2205.13647)]
      * "The Surprising Agreement between Convex Optimization Theory and Learning-Rate Scheduling for Large Model Training" (Schaipp et al., 2025) [[Link](https://arxiv.org/abs/2501.18965)]
      * "Features at Convergence Theorem: a first-principles alternative to the Neural Feature Ansatz for how networks learn representations" (Boix-Adsera,  Mallinar, Simon, & Belkin) [[Link](https://arxiv.org/abs/2507.05644)]
      * "On the Role of Initialization in the Training of Recurrent Neural Networks" (Sutskever, Martens, Dahl, & Hinton, 2013) [[Link](https://proceedings.mlr.press/v28/sutskever13.html)]
      * "Dynamic Chunking for End-to-End Hierarchical Sequence Modeling." (Sukjun, Hwang, Wang Brandon, and Gu Albert. 2025) [[Link](http://arxiv.org/abs/2507.07955)]
