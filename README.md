# Awesome-Multimodal-Reasoning

A comprehensive and up-to-date collection of state-of-the-art methods and benchmarks in **multimodal reasoning**. 🚀 Contributions and suggestions are highly encouraged!

## 📚 Table of Contents

- [Method](#-method)
  - [Prompt-Augmented Inference](#-prompt-augmented-inference)
  - [Reward-Guided Inference](#-reward-guided-inference)
  - [Supervised Fine-Tuning](#-supervised-fine-tuning)
  - [Reinforcement Fine-Tuning](#-reinforcement-fine-tuning)
  - [Think with Interleaved-Modal](#-think-with-interleaved-modal)
- [Benchmark](#-benchmark)
  - [General Reasoning](#-general-reasoning)
  - [Mathematical Reasoning](#-mathematical-reasoning)
  - [Scientific Reasoning](#-scientific-reasoning)
  - [Logical Reasoning](#-logical-reasoning)
  - [Spatial Reasoning](#-spatial-reasoning)
  - [Temporal Reasoning](#-temporal-reasoning)
  - [Chart Reasoning](#-chart-reasoning)
  - [Multi-Image Reasoning](#-multi-image-reasoning)
  - [Video Reasoning](#-video-reasoning)
  - [Audio Reasoning](#-audio-reasoning)
  - [Text-to-Image Reasoning](#-text-to-image-reasoning)
  - [Modal-Interleaved Reasoning](#-modal-interleaved-reasoning)
- [Survey](#-survey)
    
## 🔧 Method

### 💡 Prompt-Augmented Inference

+ **Inference Retrieval-Augmented Multi-Modal Chain-of-Thoughts Reasoning for Language Models**  [[Paper]](https://ieeexplore.ieee.org/document/10888701) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-ICL_Augmentation-blue)

+ **GNS: Solving Plane Geometry Problems by Neural-Symbolic Reasoning with Multi-Modal LLMs**  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/34679) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **CUE-M: Contextual Understanding and Enhanced Search with Multimodal Large Language Model**  [[Paper]](https://arxiv.org/abs/2411.12287) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Knowledge-brightgreen)![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Retrieval_Augmentation-blue)

+ **PKRD-CoT: A Unified Chain-of-Thought Prompting for Multi-Modal Large Language Models in Autonomous Driving**  [[Paper]](https://arxiv.org/abs/2412.02025) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Autonomous_Driving-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination**  [[Paper]](https://arxiv.org/abs/2411.12591) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **GeoCoder: Solving Geometry Problems by Generating Modular Code through Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2410.13510) ![](https://img.shields.io/badge/Oct-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **Beyond Lines and Circles: Unveiling the Geometric Reasoning Gap in Large Language Models**  [[Paper]](https://arxiv.org/abs/2402.03877) ![](https://img.shields.io/badge/Sep-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **Mutli-Step Chain-of-Thought in Geometry Problem Solving**  [[Paper]](https://ieeexplore.ieee.org/document/10800087) ![](https://img.shields.io/badge/Sep-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **A Picture Is Worth a Graph: A Blueprint Debate Paradigm for Multimodal Reasoning**  [[Paper]](https://arxiv.org/abs/2403.14972) ![](https://img.shields.io/badge/Aug-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **Retrieval Meets Reasoning: Even High-school Textbook Knowledge Benefits Multimodal Reasoning**  [[Paper]](https://arxiv.org/abs/2405.20834) ![](https://img.shields.io/badge/May-2024-red) ![](https://img.shields.io/badge/Task-Science-brightgreen)![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Retrieval_Augmentation-blue)

+ **Cantor: Inspiring Multimodal Chain-of-Thought of MLLM**  [[Paper]](https://arxiv.org/abs/2404.16033) ![](https://img.shields.io/badge/Apr-2024-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **Compositional Chain-of-Thought Prompting for Large Multimodal Models**  [[Paper]](https://arxiv.org/abs/2311.17076) ![](https://img.shields.io/badge/Apr-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Perception_Augmentation-blue)

+ **TextCoT: Zoom In for Enhanced Multimodal Text-Rich Image Understanding**  [[Paper]](https://arxiv.org/abs/2404.09797) ![](https://img.shields.io/badge/Apr-2024-red) ![](https://img.shields.io/badge/Task-Scene-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Method-Perception_Augmentation-blue)

+ **Retrieval-Augmented Multi-Modal Chain-of-Thoughts Reasoning for Large Language Models**  [[Paper]](https://arxiv.org/abs/2312.01714) ![](https://img.shields.io/badge/Mar-2024-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-ICL_Augmentation-blue)

+ **Scaffolding Coordinates to Promote Vision-Language Coordination in Large Multi-Modal Models**  [[Paper]](https://arxiv.org/abs/2402.12058) ![](https://img.shields.io/badge/Feb-2024-red) ![](https://img.shields.io/badge/Task-Compositional-brightgreen) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Method-Perception_Augmentation-blue)

+ **CoCoT: Contrastive Chain-of-Thought Prompting for Large Multimodal Models with Multiple Image Inputs**  [[Paper]](https://arxiv.org/abs/2401.02582) ![](https://img.shields.io/badge/Jan-2024-red) ![](https://img.shields.io/badge/Task-Logic-brightgreen) ![](https://img.shields.io/badge/Method-Perception_Augmentation-blue)

+ **DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models**  [[Paper]](https://arxiv.org/abs/2310.16436) ![](https://img.shields.io/badge/Oct-2023-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)

+ **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**  [[Paper]](https://arxiv.org/abs/2303.11381) ![](https://img.shields.io/badge/Mar-2023-red) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)
  
+ **See, Think, Confirm: Interactive Prompting Between Vision and Language Models for Knowledge-based Visual Reasoning**  [[Paper]](https://arxiv.org/abs/2301.05226) ![](https://img.shields.io/badge/Jan-2023-red) ![](https://img.shields.io/badge/Task-Knowledge-brightgreen) ![](https://img.shields.io/badge/Method-Reasoning_Structure_Augmentation-blue)


### 🎯 Reward-Guided Inference

#### Reward Modeling

+ **MM-PRM: Enhancing Multimodal Mathematical Reasoning with Scalable Step-Level Supervision** [[Paper]](https://arxiv.org/abs/2505.13427) ![](https://img.shields.io/badge/June-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)    ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **Athena: Enhancing Multimodal Reasoning with Data-efficient Process Reward Models** [[Paper]](https://arxiv.org/abs/2506.09532) ![](https://img.shields.io/badge/June-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen)     ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **R1-Reward: Training Multimodal Reward Model Through Stable Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2505.02835) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)   ![](https://img.shields.io/badge/Task-General-brightgreen)  ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)

+ **URSA: Understanding and Verifying Chain-of-Thought Reasoning in MultimodalMathematics** [[Paper]](https://arxiv.org/abs/2501.04686) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward Model** [[Paper]](https://arxiv.org/abs/2501.12368) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)


+ **VisualPRM: An Effective Process Reward Model for Multimodal Reasoning** [[Paper]](https://arxiv.org/abs/2503.10291) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)  ![](https://img.shields.io/badge/Method-Process_Reward-blue)

- **Unified Multimodal Chain-of-Thought Reward Model through Reinforcement Fine-Tuning** [[Paper]](https://arxiv.org/abs/2505.03318) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen)  ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)

- **Skywork-VL Reward: An Effective Reward Model for Multimodal Understanding and Reasoning** [[Paper]](https://arxiv.org/abs/2505.07263) ![](https://img.shields.io/badge/May-2025-red)  ![](https://img.shields.io/badge/Task-General-brightgreen)  ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)

- **Generative RLHF‑V: Learning Principles from Multi‑modal Human Preference** [[Paper]](https://arxiv.org/abs/2505.18531) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue) ![](https://img.shields.io/badge/Method-RL-blue) 

- **MR. Judge: Multimodal Reasoner as a Judge hkust** [[Paper]](https://arxiv.org/abs/2505.13403) ![](https://img.shields.io/badge/May-2025-red)![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue) ![](https://img.shields.io/badge/Method-SFT-blue)


+ **Benchmarking Multimodal CoT Reward Model Stepwise by Visual Program** [[Paper]](https://arxiv.org/abs/2504.06606) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)   ![](https://img.shields.io/badge/Task-General-brightgreen)  ![](https://img.shields.io/badge/Method-Process_Reward-blue)


+ **PRM-BAS: Enhancing Multimodal Reasoning through PRM-guided Beam Annealing Search** [[Paper]](https://arxiv.org/abs/2504.10222) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-Logic-brightgreen)  ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen)    ![](https://img.shields.io/badge/Method-Process_Reward-blue)

- **The devil is in the details: Tackling unimodal spurious correlations for generalizable multimodal reward models** [[Paper]](https://arxiv.org/abs/2503.03122) ![](https://img.shields.io/badge/Mar-2025-red)  ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue) ![](https://img.shields.io/badge/Method-SFT-blue)

+ **MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification** [[Paper]](https://arxiv.org/abs/2502.13383) ![](https://img.shields.io/badge/Feb-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)

+ **Progressive Multimodal Reasoning via Active Retrieval** [[Paper]](https://arxiv.org/abs/2412.14835) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)  ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **VLRMBench: A Comprehensive and Challenging Benchmark for Vision-Language Reward Models** [[Paper]](https://arxiv.org/abs/2503.07478) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **Multimodal RewardBench: Holistic Evaluation of Reward Models for Vision Language Models** [[Paper]](https://arxiv.org/abs/2502.14191) ![](https://img.shields.io/badge/Feb-2025-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **MM-RLHF: The Next Step Forward in Multimodal LLM Alignment** [[Paper]](https://arxiv.org/abs/2502.10391) ![](https://img.shields.io/badge/Feb-2025-red)  ![](https://img.shields.io/badge/Benchmark-blue)

+ **Improving Video Generation with Human Feedback** [[Paper]](https://arxiv.org/abs/2501.13918) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **VisionReward: Fine‑Grained Multi‑Dimensional Human Preference Learning for Image and Video Generation** [[Paper]](https://arxiv.org/abs/2412.21059) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **Align Anything: Training All‑Modality Models to Follow Instructions with Language Feedback** [[Paper]](https://arxiv.org/abs/2412.15838) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **MJ‑Bench: Is Your Multimodal Reward Model Really a Good Judge for Text‑to‑Image Generation?** [[Paper]](https://arxiv.org/abs/2407.04842) ![](https://img.shields.io/badge/Jul-2024-red)  ![](https://img.shields.io/badge/Benchmark-blue)

+ **GenAI‑Bench: Evaluating and Improving Compositional Text‑to‑Visual Generation** [[Paper]](https://arxiv.org/abs/2406.13743) ![](https://img.shields.io/badge/Jun-2024-red) ![](https://img.shields.io/badge/Benchmark-blue)

+ **MLLM‑as‑a‑Judge: Assessing Multimodal LLM‑as‑a‑Judge with Vision‑Language Benchmark** [[Paper]](https://arxiv.org/abs/2402.04788) ![](https://img.shields.io/badge/Feb-2024-red) ![](https://img.shields.io/badge/Benchmark-blue)


#### Search Strategy

+ **VReST: Enhancing Reasoning in Large Vision-Language Models through Tree Search and Self-Reward Mechanism** [[Paper]](https://arxiv.org/abs/2506.08691) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **Socratic-MCTS: Test-Time Visual Reasoning by Asking the Right Questions** [[Paper]](https://arxiv.org/abs/2506.08927) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **CyberV: Cybernetics for Test-time Scaling in Video Understanding** [[Paper]](https://arxiv.org/abs/2506.07971) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-BoN-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **Boosting Multimodal Reasoning with Automated Structured Thinking** [[Paper]](https://arxiv.org/abs/2502.02339) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen)![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue) ![](https://img.shields.io/badge/Method-Outcome_Reward-blue)

+ **PRM-BAS: Enhancing Multimodal Reasoning through PRM-guided Beam Annealing Search** [[Paper]](https://arxiv.org/abs/2504.10222) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Task-Logic-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-Beam_Search-blue) ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **VisuoThink: Empowering LVLM Reasoning with Multimodal Tree Search** [[Paper]](https://arxiv.org/abs/2504.09130) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-Spatial-brightgreen)  ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **From Trial to Triumph: Advancing Long Video Understanding via Visual
Context Sample Scaling and Self-reward Alignment** [[Paper]](https://arxiv.org/abs/2503.20472) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-BoN-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos** [[Paper]](https://arxiv.org/abs/2405.19209) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen)  ![](https://img.shields.io/badge/Method-Tree_Search-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)

+ **LLaVA-CoT: Let Vision Language Models Reason Step-by-Step** [[Paper]](https://arxiv.org/abs/2411.10440) ![](https://img.shields.io/badge/Feb-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Beam_Search-blue) ![](https://img.shields.io/badge/Method-Self_Reward-blue)
  
+ **Progressive Multimodal Reasoning via Active Retrieval** [[Paper]](https://arxiv.org/pdf/2412.14835) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Process_Reward-blue)

+ **Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search** [[Paper]](https://arxiv.org/abs/2412.18319) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Method-MCTS-blue) ![](https://img.shields.io/badge/Method-Process_Reward-blue)

### 🎓 Supervised Fine-Tuning

- **Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning** [[Paper]](https://arxiv.org/abs/2506.00318) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **VideoPath-LLaVA: Pathology Diagnostic Reasoning Through Video Instruction Tuning** [[Paper]](https://arxiv.org/abs/2505.22651) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Sherlock: Self-Correcting Reasoning in Vision-Language Models** [[Paper]](https://arxiv.org/abs/2505.22651) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Self_Correction-blue)

- **MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning** [[Paper]](https://arxiv.org/abs/2505.10557) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Weaving Context Across Images: Improving Vision-Language Models through Focus-Centric Visual Chains** [[Paper]](https://arxiv.org/abs/2504.20199) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Unsupervised Visual Chain-of-Thought Reasoning via Preference Optimization** [[Paper]](https://arxiv.org/abs/2504.18397) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-DPO-blue)

- **LongPerceptualThoughts: Distilling System-2 Reasoning for System-1 Perception** [[Paper]](https://arxiv.org/abs/2504.15362) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Perception-brightgreen) ![](https://img.shields.io/badge/Method-LongCoT_Distillation-blue)

- **SFT or RL? An Early Investigation into Training R1-Like Reasoning Large Vision-Language Models** [[Paper]](https://arxiv.org/abs/2504.11468) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **SoTA with Less: MCTS-Guided Sample Selection for Data-Efficient Visual Reasoning Self-Improvement** [[Paper]](https://arxiv.org/abs/2504.07934) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **ST-Think: How Multimodal Large Language Models Reason About 4D Worlds from Ego-Centric Videos** [[Paper]](https://arxiv.org/abs/2503.20752) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models** [[Paper]](https://arxiv.org/abs/2503.06749) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **MMC: Iterative Refinement of VLM Reasoning via MCTS-based Multimodal Critique** [[Paper]](https://arxiv.org/abs/2504.11009) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-MCTS-blue)

- **RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems?** [[Paper]](https://arxiv.org/abs/2501.11284) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-LongCoT_Distillation-blue)

- **Virgo: A Preliminary Exploration on Reproducing o1-like MLLM** [[Paper]](https://arxiv.org/abs/2501.01904) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-LongCoT_Distillation-blue)

- **Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search** [[Paper]](https://arxiv.org/abs/2412.18319) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-MCTS-blue)

- **Diving into Self-Evolving Training for Multimodal Reasoning** [[Paper]](https://arxiv.org/abs/2412.17451) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Self_Evolving-blue)

- **Geo-LLaVA: A Large Multi-Modal Model for Solving Geometry Math Problems with Meta In-Context Learning** [[Paper]](https://arxiv.org/abs/2412.10455#:~:text=Additionally%2C%20we%20propose%20a%20Large%20Multi-modal%20Model%20%28LMM%29,in-context%20learning%20%28ICL%29%20during%20inference%20to%20improve%20performance.) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RAG-blue) ![](https://img.shields.io/badge/Method-In_Context_Learning-blue)

- **Insight-V: Exploring Long-Chain Visual Reasoning with Multimodal Large Language Models** [[Paper]](https://arxiv.org/abs/2411.14432) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Multi_Agent-blue) ![](https://img.shields.io/badge/Method-DPO-blue)

- **Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization** [[Paper]](https://arxiv.org/abs/2411.10442) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-DPO-blue)

- **LLaVA-CoT: Let Vision Language Models Reason Step-by-Step** [[Paper]](https://arxiv.org/abs/2411.10440) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Vision-Language Models Can Self-Improve Reasoning via Reflection** [[Paper]](https://arxiv.org/abs/2411.00855) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Self_Reflection-blue)

- **Sparkle: Mastering Basic Spatial Capabilities in Vision Language Models Elicits Generalization to Spatial Reasoning** [[Paper]](https://arxiv.org/abs/2410.16162) ![](https://img.shields.io/badge/Oct-2024-red) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Improve Vision Language Model Chain-of-thought Reasoning** [[Paper]](https://arxiv.org/abs/2410.16198) ![](https://img.shields.io/badge/Oct-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-DPO-blue)

- **MAVIS: Mathematical Visual Instruction Tuning with an Automatic Data Engine** [[Paper]](https://arxiv.org/abs/2407.08739) ![](https://img.shields.io/badge/Jul-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **From the Least to the Most: Building a Plug-and-Play Visual Reasoner via Data Synthesis** [[Paper]](https://arxiv.org/abs/2406.19934) ![](https://img.shields.io/badge/Jun-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Math-LLaVA: Bootstrapping Mathematical Reasoning for Multimodal Large Language Models** [[Paper]](https://arxiv.org/abs/2406.17294) ![](https://img.shields.io/badge/Jun-2024-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Describe-then-Reason: Improving Multimodal Mathematical Reasoning through Visual Comprehension Training** [[Paper]](https://arxiv.org/abs/2404.14604) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **KAM-CoT: Knowledge Augmented Multimodal Chain-of-Thoughts Reasoning**  [[Paper]](https://arxiv.org/abs/2401.12863) ![](https://img.shields.io/badge/Jan-2024-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-RAG-blue) 

- **Video-of-Thought: Step-by-Step Video Reasoning from Perception to Cognition** [[Paper]](https://arxiv.org/abs/2501.03230) ![](https://img.shields.io/badge/May-2024-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue) ![](https://img.shields.io/badge/Method-Video_of_Thought-blue)

- **Measuring and Improving Chain-of-Thought Reasoning in Vision-Language Models** [[Paper]](https://arxiv.org/abs/2309.04461) ![](https://img.shields.io/badge/Sep-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **Multimodal Chain-of-Thought Reasoning in Language Models** [[Paper]](https://arxiv.org/abs/2302.00923) ![](https://img.shields.io/badge/Feb-2023-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

### 🤖 Reinforcement Fine-Tuning

- **Metis-RISE: RL Incentivizes and SFT Enhances Multimodal Reasoning Model Learning**  [[Paper]](https://arxiv.org/abs/2506.13056) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue) ![](https://img.shields.io/badge/Method-RL_&_SFT-blue)

- **Vision Matters: Simple Visual Perturbations Can Boost Multimodal Math Reasoning**  [[Paper]](https://arxiv.org/abs/2506.09736) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **Play to Generalize: Learning to Reason Through Game Play**  [[Paper]](https://arxiv.org/abs/2506.08011) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Game-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **WeThink: Toward General-purpose Vision-Language Reasoning via Reinforcement Learning**  [[Paper]](https://www.arxiv.org/abs/2506.07905) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO**  [[Paper]](https://arxiv.org/abs/2506.07464) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **Advancing Multimodal Reasoning Capabilities of Multimodal Large Language Models via Visual Perception Reward**  [[Paper]](https://arxiv.org/abs/2506.07218) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Vision-EKIPL: External Knowledge-Infused Policy Learning for Visual Reasoning**  [[Paper]](https://arxiv.org/abs/2506.06856) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **Advancing Multimodal Reasoning: From Optimized Cold Start to Staged Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2506.04207) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **SynthRL: Scaling Visual Reasoning with Verifiable Data Synthesis**  [[Paper]](https://arxiv.org/abs/2506.02096) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **SRPO: Enhancing Multimodal LLM Reasoning via Reflection-Aware Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2506.01713) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **GThinker: Towards General Multimodal Reasoning via Cue-Guided Rethinking**  [[Paper]](https://arxiv.org/abs/2506.01078) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **MoDoMoDo: Multi-Domain Data Mixtures for Multimodal LLM Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.24871) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Reinforcing Video Reasoning with Focused Thinking**  [[Paper]](https://arxiv.org/abs/2505.24718) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **VisualSphinx: Large-Scale Synthetic Vision Logic Puzzles for RL**  [[Paper]](https://arxiv.org/abs/2505.23977) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Puzzle-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Infi-MMR: Curriculum-based Unlocking Multimodal Reasoning via Phased Reinforcement Learning in Multimodal Small Language Models**  [[Paper]](https://arxiv.org/abs/2505.23091) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Mixed-R1: Unified Reward Perspective For Reasoning Capability in Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2505.24164) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Unsupervised Post-Training for Multi-Modal LLM Reasoning via GRPO**  [[Paper]](https://arxiv.org/abs/2505.22453) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Omni-R1: Reinforcement Learning for Omnimodal Reasoning via Two-System Collaboration**  [[Paper]](https://arxiv.org/abs/2505.20256) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Omni-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **One RL to See Them All: Visual Triple Unified Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.18129) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **SophiaVL-R1: Reinforcing MLLMs Reasoning with Thinking Reward**  [[Paper]](https://arxiv.org/abs/2505.17018) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Think or Not? Selective Reasoning via Reinforcement Learning for Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2505.16854) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue) ![](https://img.shields.io/badge/Method-Efficient_Reasoning-blue)

- **R1-ShareVL: Incentivizing Reasoning Capability of Multimodal Large Language Models via Share-GRPO**  [[Paper]](https://arxiv.org/abs/2505.16673) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.16421) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Web-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **UniVG-R1: Reasoning Guided Universal Visual Grounding with Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2505.14231) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Grounding-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **G1: Bootstrapping Perception and Reasoning Abilities of Vision-Language Model via Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.13426) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Game-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Seed1.5-VL Technical Report**  [[Paper]](https://arxiv.org/abs/2505.07062) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen)

- **Unlocking the Potential of Difficulty Prior in RL-based Multimodal Reasoning**  [[Paper]](https://arxiv.org/abs/2505.13261) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Filtering-blue)

- **VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning**  [[Paper]](https://arxiv.org/abs/2505.12434) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **EchoInk-R1: Exploring Audio-Visual Reasoning in Multimodal LLMs via Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.04623) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Omni-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **X-Reasoner: Towards Generalizable Reasoning Across Modalities and Domains**  [[Paper]](https://arxiv.org/abs/2505.03981) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Fast-Slow Thinking for Large Vision-Language Model Reasoning**  [[Paper]](https://arxiv.org/abs/2504.18458) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Skywork R1V2: Multimodal Hybrid Reinforcement Learning for Reasoning**  [[Paper]](https://arxiv.org/abs/2504.16656) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **NoisyRollout: Reinforcing Visual Reasoning with Data Augmentation**  [[Paper]](https://arxiv.org/abs/2504.13055) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **TinyLLaVA-Video-R1: Towards Smaller LMMs for Video Reasoning**  [[Paper]](https://arxiv.org/abs/2504.09641) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **VL-Rethinker: Incentivizing Self-Reflection of Vision-Language Models with Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2504.08837) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **SoTA with Less: MCTS-Guided Sample Selection for Data-Efficient Visual Reasoning Self-Improvement**  [[Paper]](https://arxiv.org/abs/2504.07934) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Filtering-blue)

- **VLM-R1: A Stable and Generalizable R1-style Large Vision-Language Model**  [[Paper]](https://arxiv.org/abs/2504.07615) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Grounding-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **VideoChat-R1: Enhancing Spatio-Temporal Perception via Reinforcement Fine-Tuning**  [[Paper]](https://arxiv.org/abs/2504.06958) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Skywork R1V: Pioneering Multimodal Reasoning with Chain-of-Thought**  [[Paper]](https://arxiv.org/abs/2504.05599) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Rethinking RL Scaling for Vision Language Models: A Transparent, From-Scratch Framework and Comprehensive Evaluation Scheme**  [[Paper]](https://arxiv.org/abs/2504.02587) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **SpaceR: Reinforcing MLLMs in Video Spatial Reasoning**  [[Paper]](https://arxiv.org/abs/2504.01805) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **Improved Visual-Spatial Reasoning via R1-Zero-Like Training**  [[Paper]](https://arxiv.org/abs/2504.00883) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Exploring the Effect of Reinforcement Learning on Video Understanding: Insights from SEED-Bench-R1**  [[Paper]](https://arxiv.org/abs/2503.24376) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Boosting MLLM Reasoning with Text-Debiased Hint-GRPO**  [[Paper]](https://arxiv.org/abs/2503.23905) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue)

- **Video-R1: Reinforcing Video Reasoning in MLLMs**  [[Paper]](https://arxiv.org/abs/2503.21776) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **UI-R1: Enhancing Efficient Action Prediction of GUI Agents by Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2503.21620) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-GUI-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning**  [[Paper]](https://arxiv.org/abs/2503.20752) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Perception-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization**  [[Paper]](https://arxiv.org/abs/2503.12937) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL_Algorithm-blue) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **Reinforcement Learning Outperforms Supervised Fine-Tuning: A Case Study on Audio Question Answering**  [[Paper]](https://arxiv.org/abs/2503.11197) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Audio-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization**  [[Paper]](https://arxiv.org/abs/2503.10615) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **MM-Eureka: Exploring the Frontiers of Multimodal Reasoning with Rule-based Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2503.07365) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Boosting the Generalization and Reasoning of Vision Language Models with Curriculum Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2503.07065) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **R1-Omni: Explainable Omni-Multimodal Emotion Recognition with Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2503.05379) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Omni-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **R1-Zero's "Aha Moment" in Visual Reasoning on a 2B Non-SFT Model**  [[Paper]](https://arxiv.org/abs/2503.05132) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Method-Training_Strategy-blue)

- **Visual-RFT: Visual Reinforcement Fine-Tuning**  [[Paper]](https://arxiv.org/abs/2503.01785) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Perception-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)

- **URSA: Understanding and Verifying Chain-of-thought Reasoning in Multimodal Mathematics**  [[Paper]](https://arxiv.org/abs/2501.04686) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Reward_Design-blue)



### 🔀 Think with Interleaved-Modal

#### Think with Images

- **Ego-R1: Chain-of-Tool-Thought for Ultra-Long Egocentric Video Reasoning**  [[Paper]](https://arxiv.org/abs/2506.13654) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue) ![](https://img.shields.io/badge/Method-Visual_Tool-blue) 

- **VideoDeepResearch: Long Video Understanding With Agentic Tool Using**  [[Paper]](https://arxiv.org/pdf/2506.10821) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) ![](https://img.shields.io/badge/Method-Visual_Tool-blue) 

- **Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing**  [[Paper]](https://arxiv.org/abs/2506.09965) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Spatial-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue) ![](https://img.shields.io/badge/Method-Visual_Drawing-blue) 

- **Multi-Step Visual Reasoning with Visual Tokens Scaling and Verification**  [[Paper]](https://arxiv.org/abs/2506.07235) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen)![](https://img.shields.io/badge/Method-DPO-blue)  ![](https://img.shields.io/badge/Method-Visual_Token-blue)

- **MINT-CoT: Enabling Interleaved Visual Tokens in Mathematical Chain-of-Thought Reasoning**  [[Paper]](https://arxiv.org/abs/2506.05331) ![](https://img.shields.io/badge/Jun-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue) ![](https://img.shields.io/badge/Method-Visual_Token-blue) 

- **SATORI-R1: Incentivizing Multimodal Reasoning with Spatial Grounding and Verifiable Rewards**  [[Paper]](https://arxiv.org/abs/2505.19094) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-VQA-brightgreen) ![](https://img.shields.io/badge/Method-Visual_Grounding-blue)

- **Thinking with Generated Images** [[Paper]](https://arxiv.org/abs/2505.22525) ![](https://img.shields.io/badge/May-2025-red)

- **Visual Thoughts: A Unified Perspective of Understanding Multimodal Chain-of-Thought**  [[Paper]](https://arxiv.org/abs/2505.15510) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Visual_Generation-blue)

- **OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.08617) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Chart-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue)  ![](https://img.shields.io/badge/Method-Visual_Tool-blue) 

- **Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.15966) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue) 

- **GRIT: Teaching MLLMs to Think with Images**  [[Paper]](https://arxiv.org/abs/2505.15879) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) 

- **VTool-R1: VLMs Learn to Think with Images via Reinforcement Learning on Multimodal Tool Use**  [[Paper]](https://arxiv.org/abs/2505.19255) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Structured_Image_Understanding-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) ![](https://img.shields.io/badge/Method-Visual_Programming-blue)

- **DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.14362) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) ![](https://img.shields.io/badge/Method-Zoom_In-blue)

- **VRAG-RL: Empower Vision-Perception-Based RAG for Visually Rich Information Understanding via Iterative Reasoning with Reinforcement Learning**  [[Paper]](https://arxiv.org/abs/2505.22019) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-RAG-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) ![](https://img.shields.io/badge/Method-Zoom_In-blue) 

- **Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding**  [[Paper]](https://arxiv.org/abs/2505.18079) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Video-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **Chain-of-Focus: Adaptive Visual Search and Zooming for Multimodal Reasoning via RL**  [[Paper]](https://arxiv.org/abs/2505.15436) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue)

- **AgentThink: A Unified Framework for Tool-Augmented Chain-of-Thought Reasoning in Vision-Language Models for Autonomous Driving**  [[Paper]](https://arxiv.org/pdf/2505.15298) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Autonomous_Driving-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-SFT_&_RL-blue) 

- **Visual Planning: Let's Think Only with Images**  [[Paper]](http://export.arxiv.org/abs/2505.11409) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) 

- **MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning**  [[Paper]](https://www.arxiv.org/abs/2505.10557) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **VisualToolAgent (VisTA): A Reinforcement Learning Framework for Visual Tool Selection**  [[Paper]](https://arxiv.org/abs/2505.20289#:~:text=We%20introduce%20VisTA%2C%20a%20new%20reinforcement%20learning%20framework,from%20a%20diverse%20library%20based%20on%20empirical%20performance.) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) 

- **Don't Look Only Once: Towards Multimodal Interactive Reasoning with Selective Visual Revisitation**  [[Paper]](https://arxiv.org/abs/2505.18842) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Math-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **VLM-R3: Region Recognition, Reasoning, and Refinement for Enhanced Multimodal Chain-of-Thought**  [[Paper]](https://arxiv.org/abs/2505.16192) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-RL-blue)

- **Grounded Reinforcement Learning for Visual Reasoning**  [[Paper]](https://arxiv.org/abs/2505.23678v1) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method--blue) 

- **Visual Agentic Reinforcement Fine-Tuning**  [[Paper]](https://arxiv.org/abs/2505.14246v1) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue) 

- **Active-O3: Empowering Multimodal Large Language Models with Active Perception via GRPO**  [[Paper]](https://arxiv.org/abs/2505.21457) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-RL-blue)

- **Perception in Reflection**  [[Paper]](https://arxiv.org/abs/2504.07165) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) 

- **Grounded Chain-of-Thought for Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2503.12799) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **DyFo: A Training-Free Dynamic Focus Visual Search for Enhancing LMMs in Fine-Grained Visual Understanding**  [[Paper]](https://arxiv.org/abs/2504.14920) ![](https://img.shields.io/badge/Apr-2025-red) ![](https://img.shields.io/badge/Task-Spaial_Reasoning-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **ReFocus: Visual Editing as a Chain of Thought for Structured Image Understanding**  [[Paper]](https://arxiv.org/abs/2501.05452) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Task-Structured_Image_Understanding-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **Imagine while Reasoning in Space: Multimodal Visualization-of-Thought**  [[Paper]](https://arxiv.org/abs/2501.07542) ![](https://img.shields.io/badge/Jan-2025-red) ![](https://img.shields.io/badge/Task-Spatial_Reasoning-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **TACO: Learning Multi-modal Action Models with Synthetic Chains-of-Thought-and-Action**  [[Paper]](https://arxiv.org/abs/2412.05479) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **Perception Tokens Enhance Visual Reasoning in Multimodal Language Models**  [[Paper]](https://arxiv.org/abs/2412.03548) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Counting-brightgreen) ![](https://img.shields.io/badge/Method-Perception_Tokens-blue)

- **PKRD-CoT: A Unified Chain-of-thought Prompting for Multi-Modal Large Language Models in Autonomous Driving**  [[Paper]](https://arxiv.org/abs/2412.02025) ![](https://img.shields.io/badge/Dec-2024-red) ![](https://img.shields.io/badge/Task-Autonomous_Driving-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue)

- **Interleaved-Modal Chain-of-Thought**  [[Paper]](https://arxiv.org/abs/2411.19488) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **ZoomEye: Enhancing Multimodal LLMs with Human-Like Zooming Capabilities through Tree-Based Image Exploration**  [[Paper]](https://arxiv.org/abs/2411.16044) ![](https://img.shields.io/badge/Nov-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models**  [[Paper]](https://arxiv.org/abs/2406.09403) ![](https://img.shields.io/badge/Jun-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) ![](https://img.shields.io/badge/Method-Code_Generation-blue)

- **Chain-of-Spot: Interactive Reasoning Improves Large Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2403.12966) ![](https://img.shields.io/badge/Mar-2024-red) ![](https://img.shields.io/badge/Task-SFT-brightgreen) ![](https://img.shields.io/badge/Method-Visual_QA-blue) 

- **CogCoM: A Visual Language Model with Chain-of-Manipulations Reasoning**  [[Paper]](https://arxiv.org/abs/2402.04236) ![](https://img.shields.io/badge/Feb-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)
  
- **MLLM-Tool: A Multimodal Large Language Model For Tool Agent Learning**  [[Paper]](https://arxiv.org/abs/2401.10727) ![](https://img.shields.io/badge/Jan-2024-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs**  [[Paper]](https://arxiv.org/abs/2312.14135) ![](https://img.shields.io/badge/Dec-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **Multi-modal Latent Space Learning for Chain-of-Thought Reasoning in Language Models**  [[Paper]](https://arxiv.org/abs/2312.08762) ![](https://img.shields.io/badge/Dec-2023-red) ![](https://img.shields.io/badge/Task-Science-brightgreen) ![](https://img.shields.io/badge/Method-Image_Generation-blue) 

- **Visual Program Distillation: Distilling Tools and Programmatic Reasoning into Vision-Language Models**  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_Visual_Program_Distillation_Distilling_Tools_and_Programmatic_Reasoning_into_Vision-Language_CVPR_2024_paper.pdf) ![](https://img.shields.io/badge/Dec-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue) 

- **LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents**  [[Paper]](https://arxiv.org/abs/2311.05437) ![](https://img.shields.io/badge/Nov-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**  [[Paper]](https://arxiv.org/abs/2305.18752) ![](https://img.shields.io/badge/May-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**  [[Paper]](https://arxiv.org/abs/2303.11381) ![](https://img.shields.io/badge/Mar-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue)

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**  [[Paper]](https://arxiv.org/abs/2303.17580) ![](https://img.shields.io/badge/Mar-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue)

- **ViperGPT: Visual Inference via Python Execution for Reasoning**  [[Paper]](https://arxiv.org/abs/2303.08128) ![](https://img.shields.io/badge/Mar-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**  [[Paper]](https://arxiv.org/abs/2303.04671) ![](https://img.shields.io/badge/Mar-2023-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 

- **Visual Programming: Compositional visual reasoning without training**  [[Paper]](https://arxiv.org/abs/2211.11559) ![](https://img.shields.io/badge/Nov-2022-red) ![](https://img.shields.io/badge/Task-General-brightgreen) ![](https://img.shields.io/badge/Method-Prompt-blue) 


#### Image Generation with Reasoning

- **ControlThinker: Unveiling Latent Semantics for Controllable Image Generation through Visual Reasoning** [[Paper]](https://arxiv.org/abs/2506.03596) ![](https://img.shields.io/badge/Jun-2025-red)

- **UniRL: Self‑Improving Unified Multimodal Models via Supervised and Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2505.23380) ![](https://img.shields.io/badge/May-2025-red)

- **Delving into RL for Image Generation with CoT: A Study on DPO vs. GRPO** [[Paper]](https://arxiv.org/abs/2505.17017) ![](https://img.shields.io/badge/May-2025-red)

- **Self‑Reflective Reinforcement Learning for Diffusion‑based Image Reasoning Generation** [[Paper]](https://arxiv.org/abs/2505.22407) ![](https://img.shields.io/badge/May-2025-red)

- **GoT-R1: Unleashing Reasoning Capability of MLLM for Visual Generation with Reinforcement Learning** [[Paper]](https://arxiv.org/abs/2505.17022) ![](https://img.shields.io/badge/May-2025-red)
- **T2I Diffusion Model Fine-tuning** [[Paper]](https://arxiv.org/abs/2505.19196) ![](https://img.shields.io/badge/May-2025-red)

- **ReasonGen‑R1: CoT for Autoregressive Image Generation models through SFT and RL** [[Paper]](https://arxiv.org/abs/2505.24875) ![](https://img.shields.io/badge/May-2025-red) ![](https://img.shields.io/badge/Task-Text_to_Image-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue)

- **T2I-R1: Reinforcing Image Generation with Collaborative Semantic-level and Token-level CoT** [[Paper]](https://arxiv.org/abs/2505.00703) ![](https://img.shields.io/badge/May-2025-red)

- **UniGen: Enhanced Training & Test-Time Strategies for Unified Multimodal Understanding and Generation** [[Paper]](https://arxiv.org/abs/2505.14682) ![](https://img.shields.io/badge/May-2025-red)

- **Delving into RL for Image Generation with CoT: A Study on DPO vs. GRPO** [[Paper]](https://arxiv.org/abs/2505.17017) ![](https://img.shields.io/badge/May-2025-red)

- **DanceGRPO: Unleashing GRPO on Visual Generation** [[Paper]](https://arxiv.org/abs/2505.07818) ![](https://img.shields.io/badge/May-2025-red)

- **SimpleAR: Pushing the Frontier of Autoregressive Visual Generation through Pretraining, SFT, and RL** [[Paper]](https://arxiv.org/abs/2504.11455) ![](https://img.shields.io/badge/Apr-2025-red)

- **Complex-Edit: CoT‑Like Instruction Generation for Complexity‑Controllable Image Editing Benchmark** [[Paper]](https://arxiv.org/abs/2504.13143) ![](https://img.shields.io/badge/Apr-2025-red)

- **ImageGen-CoT: Enhancing Text-to-Image In-context Learning with Chain-of-Thought Reasoning** [[Paper]](https://arxiv.org/abs/2503.19312) ![](https://img.shields.io/badge/Mar-2025-red) ![](https://img.shields.io/badge/Task-Text_to_Image-brightgreen) ![](https://img.shields.io/badge/Method-Data_Synthesis-blue) ![](https://img.shields.io/badge/Method-SFT-blue)

- **I Think, Therefore l Diffuse: Enabling Multimodal In-Context Reasoning in Diffusion Models** [[Paper]](https://arxiv.org/abs/2502.10458) ![](https://img.shields.io/badge/Feb-2025-red) ![](https://img.shields.io/badge/Task-Text_to_Image-brightgreen) ![](https://img.shields.io/badge/Method-SFT-blue)

- **Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step** [[Paper]](https://arxiv.org/abs/2501.13926) ![](https://img.shields.io/badge/Jan-2025-red)


- **IMAGINE-E: Image Generation Intelligence Evaluation of State‑of‑the‑art Text‑to‑Image Models** [[Paper]](https://arxiv.org/abs/2501.13920) ![](https://img.shields.io/badge/Jan-2025-red)

- **Reason-before-Retrieve: One-Stage Reflective Chain-of-Thoughts for Training-Free Zero-Shot Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2412.11077) ![](https://img.shields.io/badge/Dec-2024-red)

- **SketchAgent: Language-Driven Sequential Sketch Generation** [[Paper]](https://arxiv.org/abs/2411.17673) ![](https://img.shields.io/badge/Nov-2024-red)



## 🧪 Benchmark

### 🧠 General Reasoning

- **MMMR: Benchmarking Massive Multi-Modal Reasoning Tasks**  [[Paper]](https://arxiv.org/abs/2505.16459) [[Dataset]](https://huggingface.co/datasets/csegirl/MMMR) ![](https://img.shields.io/badge/May-2025-red) 

- **RBench-V: A Primary Assessment for Visual Reasoning Models with Multi-modal Outputs**  [[Paper]](https://arxiv.org/abs/2505.16770) [[Dataset]](https://huggingface.co/datasets/R-Bench/R-Bench-V) ![](https://img.shields.io/badge/May-2025-red) 

- **ChartMuseum: Testing Visual Reasoning Capabilities of Large Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2505.13444) [[Dataset]](https://huggingface.co/datasets/lytang/ChartMuseum) ![](https://img.shields.io/badge/May-2025-red) 

- **MIRAGE: A Multi-modal Benchmark for Spatial Perception, Reasoning, and Intelligence**  [[Paper]](https://arxiv.org/abs/2505.10604) [[Dataset]](https://huggingface.co/datasets/Mmoment/Mirage_Multimodal_Benchmark) ![](https://img.shields.io/badge/May-2025-red) 

- **On Path to Multimodal Generalist: General-Level and General-Bench**  [[Paper]](https://arxiv.org/abs/2505.04620) [[Dataset]](https://huggingface.co/General-Level) ![](https://img.shields.io/badge/May-2025-red) 

- **R-Bench: Graduate-level Multi-disciplinary Benchmarks for LLM & MLLM Complex Reasoning Evaluation**  [[Paper]](https://arxiv.org/abs/2505.02018) [[Dataset]](https://huggingface.co/datasets/R-Bench/R-Bench) ![](https://img.shields.io/badge/May-2025-red) 

- **VisuLogic: A Benchmark for Evaluating Visual Reasoning in Multi-modal Large Language Models**  [[Paper]](https://arxiv.org/abs/2504.15279) [[Dataset]](https://huggingface.co/datasets/VisuLogic/VisuLogic) ![](https://img.shields.io/badge/Apr-2025-red) 

- **MDK12-Bench: A Multi-Discipline Benchmark for Evaluating Reasoning in Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2504.05782) [[Dataset]](https://github.com/LanceZPF/MDK12?tab=readme-ov-file#-datasets) ![](https://img.shields.io/badge/Apr-2025-red)

- **MME-Unify: A Comprehensive Benchmark for Unified Multimodal Understanding and Generation Models**  [[Paper]](https://arxiv.org/abs/2504.03641) [[Dataset]](https://huggingface.co/datasets/wulin222/MME-Unify) ![](https://img.shields.io/badge/Apr-2025-red) 

- **MME-CoT: Benchmarking Chain-of-Thought in Large Multimodal Models for Reasoning Quality, Robustness, and Efficiency**  [[Paper]](https://arxiv.org/abs/2502.09621) [[Dataset]](https://huggingface.co/datasets/CaraJ/MME-CoT) ![](https://img.shields.io/badge/Feb-2025-red) 

- **MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models**  [[Paper]](https://arxiv.org/abs/2502.00698) [[Dataset]](https://huggingface.co/datasets/huanqia/MM-IQ) ![](https://img.shields.io/badge/Feb-2025-red) 

- **Can MLLMs Reason in Multimodality? EMMA: An Enhanced MultiModal ReAsoning Benchmark**  [[Paper]](https://arxiv.org/abs/2501.05444) [[Dataset]](https://huggingface.co/datasets/luckychao/EMMA) ![](https://img.shields.io/badge/Jan-2025-red) 

- **MEGA-Bench: Scaling Multimodal Evaluation to over 500 Real-World Tasks**  [[Paper]](https://arxiv.org/abs/2410.10563) [[Dataset]](https://huggingface.co/datasets/TIGER-Lab/MEGA-Bench) ![](https://img.shields.io/badge/Oct-2024-red) 

- **MMMU-Pro: A More Robust Multi-discipline Multimodal Understanding Benchmark**  [[Paper]](https://arxiv.org/abs/2409.02813) [[Dataset]](https://huggingface.co/datasets/MMMU/MMMU_Pro) ![](https://img.shields.io/badge/Sep-2024-red)

- **GAOKAO-MM: A Chinese Human-Level Benchmark for Multimodal Models Evaluation** [[Paper]](https://arxiv.org/abs/2402.15745) [[Dataset]](https://github.com/OpenMOSS/GAOKAO-MM) ![](https://img.shields.io/badge/Aug-2024-red) 

- **MLLM-CompBench: A Comparative Reasoning Benchmark for Multimodal LLMs**  [[Paper]](https://arxiv.org/abs/2407.16837) [[Dataset]](https://compbench.github.io/) ![](https://img.shields.io/badge/Jul-2024-red) 

- **M3CoT: A Novel Benchmark for Multi-Domain Multi-step Multi-modal Chain-of-Thought**  [[Paper]](https://arxiv.org/abs/2405.16473) [[Dataset]](https://huggingface.co/datasets/LightChen2333/M3CoT) ![](https://img.shields.io/badge/May-2024-red) 

- **Are We on the Right Way for Evaluating Large Vision-Language Models?**  [[Paper]](https://arxiv.org/abs/2403.20330) [[Dataset]](https://huggingface.co/datasets/Lin-Chen/MMStar) ![](https://img.shields.io/badge/Mar-2024-red)

- **Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning**  [[Paper]](https://arxiv.org/abs/2403.16999) [[Dataset]](https://huggingface.co/datasets/deepcs233/Visual-CoT) ![](https://img.shields.io/badge/Mar-2024-red)

- **CMMMU: A Chinese Massive Multi-discipline Multimodal Understanding Benchmark**  [[Paper]](https://arxiv.org/abs/2401.11944) [[Dataset]](https://huggingface.co/datasets/m-a-p/CMMMU) ![](https://img.shields.io/badge/Jan-2024-red) 

- **SEED-Bench-2: Benchmarking Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2311.17092) [[Dataset]](https://huggingface.co/datasets/AILab-CVC/SEED-Bench-2) ![](https://img.shields.io/badge/Nov-2023-red) 

- **MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI**  [[Paper]](https://arxiv.org/abs/2311.16502) [[Dataset]](https://huggingface.co/datasets/MMMU/MMMU) ![](https://img.shields.io/badge/Nov-2023-red) 


### ➗ Mathematical Reasoning

- **MATP-BENCH: Can MLLM Be a Good Automated Theorem Prover for Multimodal Problems?**  [[Paper]](https://arxiv.org/abs/2506.06034) [[Dataset]](https://github.com/Zhitao-He/MATPBench) ![](https://img.shields.io/badge/Jun-2025-red)

- **MMATH: A Multilingual Benchmark for Mathematical Reasoning**  [[Paper]](https://arxiv.org/abs/2505.19126) [[Dataset]](https://github.com/RUCAIBox/MMATH) ![](https://img.shields.io/badge/May-2025-red) 

- **MPBench: A Comprehensive Multimodal Reasoning Benchmark for Process Errors Identification**  [[Paper]](https://arxiv.org/abs/2503.12505) [[Dataset]](https://mpbench.github.io/) ![](https://img.shields.io/badge/Mar-2025-red) 
 
- **MV-MATH: Evaluating Multimodal Math Reasoning in Multi-Visual Contexts**  [[Paper]](https://arxiv.org/abs/2502.20808) [[Dataset]](https://github.com/eternal8080/MV-MATH) ![](https://img.shields.io/badge/Feb-2025-red)

- **MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models**  [[Paper]](https://arxiv.org/abs/2502.00698) [[Dataset]](https://github.com/AceCHQ/MMIQ) ![](https://img.shields.io/badge/Feb-2025-red) 

- **DynaMath: A Dynamic Visual Benchmark for Evaluating Mathematical Reasoning Robustness of Vision Language Models**  [[Paper]](https://arxiv.org/abs/2411.00836) [[Dataset]](https://github.com/DynaMath/DynaMath) ![](https://img.shields.io/badge/Oct-2024-red)

- **Is Your Model Really A Good Math Reasoner? Evaluating Mathematical Reasoning with Checklist**  [[Paper]](https://arxiv.org/abs/2407.08733) [[Dataset]](https://github.com/PremiLab-Math/MathCheck) ![](https://img.shields.io/badge/Oct-2024-red)

- **We-Math: Does Your Large Multimodal Model Achieve Human-like Mathematical Reasoning?**  [[Paper]](https://arxiv.org/abs/2407.01284) [[Dataset]](https://github.com/We-Math/We-Math) ![](https://img.shields.io/badge/Jul-2024-red) 

- **Math-LLaVA: Bootstrapping Mathematical Reasoning for Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2406.17294) [[Dataset]](https://github.com/HZQ950419/Math-LLaVA) ![](https://img.shields.io/badge/Jun-2024-red)

- **MM-MATH: Advancing Multimodal Math Evaluation with Process Evaluation and Fine-grained Classification**  [[Paper]](https://arxiv.org/abs/2404.05091) [[Dataset]](https://github.com/ZrrSkywalker/MathVerse) ![](https://img.shields.io/badge/Apr-2024-red) 

- **MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems?**  [[Paper]](https://arxiv.org/abs/2403.14624) [[Dataset]](https://github.com/ZrrSkywalker/MathVerse) ![](https://img.shields.io/badge/Mar-2024-red)

- **NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2403.01777) [[Dataset]](https://github.com/lizhouf/NPHardEval4V) ![](https://img.shields.io/badge/Mar-2024-red) 

- **Measuring Multimodal Mathematical Reasoning with MATH-Vision Dataset**  [[Paper]](https://arxiv.org/abs/2402.14804) [[Dataset]](https://github.com/mathllm/MATH-V) ![](https://img.shields.io/badge/Feb-2024-red) 

- **OlympiadBench: A Challenging Benchmark for Promoting AGI with Olympiad-Level Bilingual Multimodal Scientific Problems**  [[Paper]](https://arxiv.org/abs/2402.14008) [[Dataset]](https://github.com/OpenBMB/OlympiadBench) ![](https://img.shields.io/badge/Feb-2024-red) 

- **MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts**  [[Paper]](https://arxiv.org/abs/2310.02255) [[Dataset]](https://github.com/lupantech/MathVista) ![](https://img.shields.io/badge/Oct-2023-red) 

- **Are Deep Neural Networks SMARTer than Second Graders?**  [[Paper]](https://arxiv.org/abs/2212.09993) [[Dataset]](https://smartdataset.github.io/smart101/) ![](https://img.shields.io/badge/Dec-2022-red)


### 🔬 Scientific Reasoning

- **SciVerse: Unveiling the Knowledge Comprehension and Visual Reasoning of LMMs on Multi-modal Scientific Problems**  [[Paper]](https://arxiv.org/abs/2503.10627) [[Dataset]](https://huggingface.co/datasets/ZiyuG/SciVerse) ![](https://img.shields.io/badge/Mar-2025-red) 

- **VisScience: An Extensive Benchmark for Evaluating K12 Educational Multi-modal Scientific Reasoning**  [[Paper]](https://arxiv.org/abs/2409.13730) [[Dataset]](https://github.com/THUDM/VisScience) ![](https://img.shields.io/badge/Sep-2024-red)

- **SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers**  [[Paper]](https://arxiv.org/abs/2407.09413) [[Dataset]](https://huggingface.co/datasets/google/spiqa) ![](https://img.shields.io/badge/Jul-2024-red)

- **OlympiadBench: A Challenging Benchmark for Promoting AGI with Olympiad-Level Bilingual Multimodal Scientific Problems**  [[Paper]](https://arxiv.org/abs/2402.14008) [[Dataset]](https://huggingface.co/datasets/Hothan/OlympiadBench) ![](https://img.shields.io/badge/Jun-2024-red) 

- **SceMQA: A Scientific College Entrance Level Multimodal Question Answering Benchmark**  [[Paper]](https://arxiv.org/abs/2402.05138) [[Dataset]](https://huggingface.co/datasets/Haozy/SceMQA-main/tree/main) ![](https://img.shields.io/badge/Feb-2024-red)

+ **SciGraphQA: A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs**  [[Paper]](https://arxiv.org/abs/2308.03349) [[Dataset]](https://huggingface.co/datasets/alexshengzhili/SciCapInstructed-graph-only-qa) ![](https://img.shields.io/badge/Aug-2023-red)

- **Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering**  [[Paper]](https://arxiv.org/abs/2209.09513) [[Dataset]](https://scienceqa.github.io/) ![](https://img.shields.io/badge/Oct-2022-red) 

### 🧩 Logical Reasoning

+ **PUZZLEWORLD: A Benchmark for Multimodal, Open-Ended Reasoning in Puzzlehunts** [[Paper]](https://arxiv.org/abs/2506.06211) [[Dataset]](https://huggingface.co/datasets/hzli1202/PuzzleWorld) ![](https://img.shields.io/badge/Jun-2025-red)

+ **MME-Reasoning: A Comprehensive Benchmark for Logical Reasoning in MLLMs** [[Paper]](https://arxiv.org/abs/2505.21327) [[Dataset]](https://huggingface.co/datasets/U4R/MME-Reasoning) ![](https://img.shields.io/badge/May-2025-red)

+ **Reasoning-OCR: Can Large Multimodal Models Solve Complex Logical Reasoning Problems from OCR Cues?** [[Paper]](https://arxiv.org/abs/2505.12766) [[Dataset]](https://github.com/Hxyz-123/ReasoningOCR) ![](https://img.shields.io/badge/May-2025-red)

+ **VisuLogic: A Benchmark for Evaluating Visual Reasoning in Multi-modal Large Language Models** [[Paper]](https://arxiv.org/abs/2504.15279) [[Dataset]](https://huggingface.co/datasets/VisuLogic/VisuLogic) ![](https://img.shields.io/badge/Apr-2025-red)

+ **VisualPuzzles: Decoupling Multimodal Reasoning Evaluation from Domain Knowledge** [[Paper]](https://arxiv.org/abs/2504.10342) [[Dataset]](https://huggingface.co/datasets/neulab/VisualPuzzles) ![](https://img.shields.io/badge/Apr-2025-red)

+ **LogicVista: Multimodal LLM Logical Reasoning Benchmark in Visual Contexts** [[Paper]](https://arxiv.org/abs/2407.04973) [[Dataset]](https://github.com/Yijia-Xiao/LogicVista) ![](https://img.shields.io/badge/Jul-2024-red)

+ **MARVEL: Multidimensional Abstraction and Reasoning through Visual Evaluation and Learning** [[Paper]](https://arxiv.org/abs/2404.13591) [[Dataset]](https://huggingface.co/datasets/kianasun/MARVEL) ![](https://img.shields.io/badge/Apr-2024-red)

+ **PuzzleVQA: Diagnosing Multimodal Reasoning Challenges of Language Models with Abstract Visual Patterns** [[Paper]](https://arxiv.org/abs/2403.13315) [[Dataset]](https://huggingface.co/datasets/declare-lab/puzzlevqa) ![](https://img.shields.io/badge/Mar-2024-red)

+ **AlgoPuzzleVQA: Diagnosing Multimodal Reasoning Challenges of Language Models with Algorithmic Multimodal Puzzles** [[Paper]](https://aclanthology.org/2025.naacl-long.486/) [[Dataset]](https://github.com/declare-lab/LLM-PuzzleTest) ![](https://img.shields.io/badge/Mar-2024-red)

+ **Are deep neural networks SMARTer than second graders?** [[Paper]](https://arxiv.org/abs/2212.09993) [[Dataset]](https://smartdataset.github.io/smart101/) ![](https://img.shields.io/badge/Sep-2023-red)

+ **Lora: A logical reasoning augmented dataset for visual question answering** [[Paper]](https://openreview.net/forum?id=bW1uwPV3im) [[Dataset]](https://lora-vqa.github.io/) ![](https://img.shields.io/badge/Sep-2023-red)

+ **Multimodal Analogical Reasoning over Knowledge Graphs** [[Paper]](https://arxiv.org/abs/2210.00312) [[Dataset]](https://github.com/zjunlp/MKG_Analogy) ![](https://img.shields.io/badge/Oct-2022-red)

+ **RAVEN: A Dataset for Relational and Analogical Visual rEasoNing** [[Paper]](https://arxiv.org/abs/1903.02741) [[Dataset]](http://wellyzhang.github.io/project/raven.html) ![](https://img.shields.io/badge/Mar-2019-red)

### 🧭 Spatial Reasoning

+ **OmniSpatial: Towards Comprehensive Spatial Reasoning Benchmark for Vision Language Models** [[Paper]](https://arxiv.org/abs/2506.03135) [[Dataset]](https://huggingface.co/datasets/qizekun/OmniSpatial) ![](https://img.shields.io/badge/Jun-2025-red)

+ **Can MLLMs Guide Me Home? A Benchmark Study on Fine-Grained Visual Reasoning from Transit Maps** [[Paper]](https://arxiv.org/abs/2505.18675) [[Dataset]](https://huggingface.co/datasets/FSCCS/ReasonMap) ![](https://img.shields.io/badge/Jun-2025-red)

+ **LEGO-Puzzles: How Good Are MLLMs at Multi-Step Spatial Reasoning?** [[Paper]](https://arxiv.org/abs/2503.19990) [[Dataset]](https://huggingface.co/datasets/KexianTang/LEGO-Puzzles) ![](https://img.shields.io/badge/Jun-2025-red)

+ **Spatial457: A Diagnostic Benchmark for 6D Spatial Reasoning of Large Multimodal Models** [[Paper]](https://arxiv.org/abs/2502.08636) [[Dataset]](https://huggingface.co/datasets/RyanWW/Spatial457) ![](https://img.shields.io/badge/Jun-2025-red)

+ **STI-Bench: Are MLLMs Ready for Precise Spatial-Temporal World Understanding?** [[Paper]](https://arxiv.org/abs/2503.23765) [[Dataset]](https://huggingface.co/datasets/MINT-SJTU/STI-Bench) ![](https://img.shields.io/badge/May-2025-red)

+ **MMSI-Bench: A Benchmark for Multi-Image Spatial Intelligence** [[Paper]](https://arxiv.org/abs/2505.23764) [[Dataset]](https://huggingface.co/datasets/RunsenXu/MMSI-Bench) ![](https://img.shields.io/badge/May-2025-red)

+ **Multi-SpatialMLLM: Multi-Frame Spatial Understanding with Multi-Modal Large Language Models** [[Paper]](https://arxiv.org/abs/2505.17015) [[Dataset]](https://github.com/facebookresearch/Multi-SpatialMLLM?tab=readme-ov-file) ![](https://img.shields.io/badge/May-2025-red)

+ **3DSRBench: A Comprehensive 3D Spatial Reasoning Benchmark** [[Paper]](https://arxiv.org/abs/2412.07825) [[Dataset]](https://huggingface.co/datasets/ccvl/3DSRBench) ![](https://img.shields.io/badge/May-2025-red)

+ **V-STaR : Benchmarking Video-LLMs on Video Spatio-Temporal Reasoning** [[Paper]](https://arxiv.org/abs/2503.11495) [[Dataset]](https://huggingface.co/datasets/V-STaR-Bench/V-STaR) ![](https://img.shields.io/badge/Mar-2025-red)

+ **Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces** [[Paper]](https://arxiv.org/abs/2412.14171) [[Dataset]](https://huggingface.co/datasets/nyu-visionx/VSI-Bench) ![](https://img.shields.io/badge/Dec-2024-red)

+ **Towards Foundation Models for 3D Vision: How Close Are We?** [[Paper]](https://arxiv.org/pdf/2410.10799) [[Dataset]](https://github.com/princeton-vl/UniQA-3D) ![](https://img.shields.io/badge/Dec-2024-red)

+ **Multi-modal Situated Reasoning in 3D Scenes** [[Paper]](https://arxiv.org/abs/2409.02389) [[Dataset]](https://msr3d.github.io/) ![](https://img.shields.io/badge/Nov-2024-red)

+ **SpatialRGPT: Grounded Spatial Reasoning in Vision Language Model** [[Paper]](https://arxiv.org/abs/2406.01584) [[Dataset]](https://huggingface.co/datasets/a8cheng/OpenSpatialDataset) ![](https://img.shields.io/badge/Oct-2024-red)

+ **V ∗ : Guided Visual Search as a Core Mechanism in Multimodal LLMs** [[Paper]](https://arxiv.org/abs/2312.14135) [[Dataset]](https://huggingface.co/datasets/craigwu/vstar_bench) ![](https://img.shields.io/badge/Dec-2023-red)

+ **What's "up" with vision-language models? Investigating their struggle with spatial reasoning** [[Paper]](https://arxiv.org/abs/2310.19785) [[Dataset]](https://github.com/amitakamath/whatsup_vlms) ![](https://img.shields.io/badge/Oct-2023-red)

+ **Are deep neural networks SMARTer than second graders?** [[Paper]](https://arxiv.org/abs/2212.09993) [[Dataset]](https://smartdataset.github.io/smart101/) ![](https://img.shields.io/badge/Sep-2023-red)

### ⏱️ Temporal Reasoning

+ **STI-Bench: Are MLLMs Ready for Precise Spatial-Temporal World Understanding?** [[Paper]](https://arxiv.org/abs/2503.23765) [[Dataset]](https://huggingface.co/datasets/MINT-SJTU/STI-Bench) ![](https://img.shields.io/badge/May-2025-red)

+ **V-STaR : Benchmarking Video-LLMs on Video Spatio-Temporal Reasoning** [[Paper]](https://arxiv.org/abs/2503.11495) [[Dataset]](https://huggingface.co/datasets/V-STaR-Bench/V-STaR) ![](https://img.shields.io/badge/Mar-2025-red)

+ **Lost in Time: A New Temporal Benchmark for VideoLLMs** [[Paper]](https://arxiv.org/abs/2410.07752) [[Dataset]](https://huggingface.co/datasets/FunAILab/TVBench) ![](https://img.shields.io/badge/Mar-2025-red)
  
+ **Mtbench: A multimodal time series benchmark for temporal reasoning and question answering** [[Paper]](https://arxiv.org/abs/2503.16858) [[Dataset]](https://github.com/Graph-and-Geometric-Learning/MTBench) ![](https://img.shields.io/badge/Mar-2025-red)

+ **Can Multimodal LLMs do Visual Temporal Understanding and Reasoning? The answer is No!** [[Paper]](https://arxiv.org/abs/2501.10674) [[Dataset]](https://huggingface.co/datasets/fazliimam/temporal-vqa) ![](https://img.shields.io/badge/Feb-2025-red)

+ **TOMATO: Assessing Visual Temporal Reasoning Capabilities in Multimodal Foundation Models** [[Paper]](https://arxiv.org/abs/2410.23266) [[Dataset]](https://huggingface.co/datasets/yale-nlp/TOMATO) ![](https://img.shields.io/badge/Oct-2024-red)

+ **VITATECS: A Diagnostic Dataset for Temporal Concept Understanding of Video-Language Models** [[Paper]](https://arxiv.org/abs/2311.17404) [[Dataset]](https://huggingface.co/datasets/lscpku/VITATECS) ![](https://img.shields.io/badge/Sep-2024-red)

+ **ReXTime: A Benchmark Suite for Reasoning-Across-Time in Videos** [[Paper]](https://arxiv.org/abs/2406.19392) [[Dataset]](https://huggingface.co/datasets/ReXTime/ReXTime) ![](https://img.shields.io/badge/Jul-2024-red)

+ **EgoSchema: A Diagnostic Benchmark for Very Long-form Video Language Understanding** [[Paper]](https://arxiv.org/abs/2308.09126) [[Dataset]](https://egoschema.github.io/) ![](https://img.shields.io/badge/Aug-2023-red)

### 📊 Chart Reasoning

+ **ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning** [[Paper]](https://arxiv.org/abs/2402.12185) [[Dataset]](https://huggingface.co/datasets/U4R/ChartX/viewer) ![](https://img.shields.io/badge/Apr-2025-red)

+ **ChartQAPro: A More Diverse and Challenging Benchmark for Chart Question Answering** [[Paper]](https://arxiv.org/abs/2504.05506) [[Dataset]](https://huggingface.co/datasets/ahmed-masry/ChartQAPro) ![](https://img.shields.io/badge/Apr-2025-red)

+ **MultiChartQA: Benchmarking Vision-Language Models on Multi-Chart Problems** [[Paper]](https://arxiv.org/abs/2410.14179) [[Dataset]](https://github.com/Zivenzhu/Multi-chart-QA) ![](https://img.shields.io/badge/Feb-2025-red)

+ **ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation** [[Paper]](https://arxiv.org/pdf/2406.09961) [[Dataset]](https://huggingface.co/datasets/ChartMimic/ChartMimic) ![](https://img.shields.io/badge/Feb-2025-red)

+ **ChartBench: A Benchmark for Complex Visual Reasoning in Charts** [[Paper]](https://arxiv.org/abs/2312.15915) [[Dataset]](https://huggingface.co/datasets/SincereX/ChartBench) ![](https://img.shields.io/badge/Jun-2024-red)

+ **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs** [[Paper]](https://arxiv.org/abs/2406.18521) [[Dataset]](https://huggingface.co/datasets/princeton-nlp/CharXiv) ![](https://img.shields.io/badge/Jun-2024-red)

+ **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning** [[Paper]](https://arxiv.org/abs/2311.10774) [[Dataset]](https://huggingface.co/datasets/xywang1/MMC) ![](https://img.shields.io/badge/Apr-2024-red)

+ **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** [[Paper]](https://arxiv.org/abs/2203.10244) [[Dataset]](https://huggingface.co/datasets/ahmed-masry/ChartQA) ![](https://img.shields.io/badge/Mar-2022-red)

### 🖼️ Multi-Image Reasoning

+ **Evaluating MLLMs with Multimodal Multi-image Reasoning Benchmark** [[Paper]](https://www.arxiv.org/abs/2506.04280) [[Dataset]](https://huggingface.co/datasets/HarrytheOrange/MMRB) ![](https://img.shields.io/badge/Jun-2025-red)



+ **MV-MATH: Evaluating Multimodal Math Reasoning in Multi-Visual Contexts** [[Paper]](https://arxiv.org/abs/2502.20808) [[Dataset]](https://huggingface.co/datasets/PeijieWang/MV-MATH) ![](https://img.shields.io/badge/May-2025-red)



+ **MLLM-CompBench: A Comparative Reasoning Benchmark for Multimodal LLMs** [[Paper]](https://arxiv.org/abs/2407.16837) [[Dataset]](https://compbench.github.io/) ![](https://img.shields.io/badge/Jan-2025-red)



+ **MANTIS: Interleaved Multi-Image Instruction Tuning** [[Paper]](https://arxiv.org/abs/2405.01483) [[Dataset]](https://huggingface.co/datasets/TIGER-Lab/Mantis-Eval) ![](https://img.shields.io/badge/Nov-2024-red)



+ **MEGA-Bench: Scaling Multimodal Evaluation to over 500 Real-World Tasks** [[Paper]](https://arxiv.org/abs/2410.10563) [[Dataset]](https://huggingface.co/datasets/TIGER-Lab/MEGA-Bench) ![](https://img.shields.io/badge/Nov-2024-red)

  

+ **MIBench: Evaluating Multimodal Large Language Models over Multiple Images** [[Paper]](https://arxiv.org/abs/2407.15272) [[Dataset]](https://huggingface.co/datasets/StarBottle/MIBench) ![](https://img.shields.io/badge/Oct-2024-red)



+ **MuirBench: A Comprehensive Benchmark for Robust Multi-image Understanding** [[Paper]](https://arxiv.org/abs/2406.09411) [[Dataset]](https://huggingface.co/datasets/MUIRBENCH/MUIRBENCH) ![](https://img.shields.io/badge/Jul-2024-red)



+ **Benchmarking Multi-Image Understanding in Vision and Language Models: Perception, Knowledge, Reasoning, and Multi-Hop Reasoning** [[Paper]](https://arxiv.org/abs/2406.12742) [[Dataset]](https://huggingface.co/datasets/VLLMs/MIRB) ![](https://img.shields.io/badge/Jun-2024-red)



+ **ReMI: A Dataset for Reasoning with Multiple Images** [[Paper]](https://arxiv.org/abs/2406.09175) [[Dataset]](https://huggingface.co/datasets/mehrankazemi/ReMI) ![](https://img.shields.io/badge/Jun-2024-red) 



+ **SEED-Bench-2: Benchmarking Multimodal Large Language Models** [[Paper]](https://arxiv.org/abs/2311.17092) [[Dataset]](https://huggingface.co/datasets/AILab-CVC/SEED-Bench-2) ![](https://img.shields.io/badge/Nov-2023-red)

### 🎥 Video Reasoning

### 🔊 Audio Reasoning

+ **MMAR: A Challenging Benchmark for Deep Reasoning in Speech, Audio, Music, and Their Mix** [[Paper]](https://arxiv.org/abs/2505.13032) [[Dataset]](https://huggingface.co/datasets/BoJack/MMAR) ![](https://img.shields.io/badge/May-2025-red)

+ **MAVERIX: Multimodal Audio-Visual Evaluation Reasoning IndeX** [[Paper]](https://arxiv.org/abs/2503.21699) [[Dataset]](https://maverix-benchmark.github.io/) ![](https://img.shields.io/badge/Mar-2025-red)

+ **AVTrustBench: Assessing and Enhancing Reliability and Robustness in Audio-Visual LLMs** [[Paper]](https://arxiv.org/abs/2501.02135)  ![](https://img.shields.io/badge/Jan-2025-red)

+ **MMAU: A Massive Multi-Task Audio Understanding and Reasoning Benchmark** [[Paper]](https://arxiv.org/abs/2410.19168) [[Dataset]](https://github.com/Sakshi113/mmau) ![](https://img.shields.io/badge/Oct-2024-red)

+ **MuChoMusic: Evaluating Music Understanding in Multimodal Audio-Language Models** [[Paper]](https://arxiv.org/abs/2408.01337) [[Dataset]](https://zenodo.org/records/12709974) ![](https://img.shields.io/badge/Aug-2024-red)


### 🎨 Text-to-Image Reasoning

+ **MMMG: A Massive, Multidisciplinary, Multi-Tier Generation Benchmark for Text-to-Image Reasoning** [[Paper]](https://arxiv.org/abs/2506.10963) [[Dataset]](https://huggingface.co/datasets/MMMGBench/MMMG) ![](https://img.shields.io/badge/Jun-2025-red)

- **KRIS‑Bench: Benchmarking Next‑Level Intelligent Image Editing Models** [[Paper]](https://arxiv.org/abs/2505.16707) ![](https://img.shields.io/badge/May-2025-red)

 
+ **GPT-ImgEval: A Comprehensive Benchmark for Diagnosing GPT4o in Image Generation** [[Paper]](https://arxiv.org/abs/2504.02782) [[Dataset]](https://github.com/PicoTrex/GPT-ImgEval) ![](https://img.shields.io/badge/May-2025-red)

+ **Can MLLMs Perform Text-to-Image In-Context Learning?** [[Paper]](https://arxiv.org/abs/2402.01293) [[Dataset]](https://github.com/UW-Madison-Lee-Lab/CoBSAT?tab=readme-ov-file) ![](https://img.shields.io/badge/Jul-2024-red)

 
### 🔀 Modal-Interleaved Reasoning

+ **ViC-Bench: Benchmarking Visual-Interleaved Chain-of-Thought Capability in MLLMs with Free-Style Intermediate State Representations** [[Paper]](https://arxiv.org/abs/2505.14404) [[Dataset]](https://huggingface.co/datasets/meituan/ViC-Bench) ![](https://img.shields.io/badge/May-2025-red)

+ **PointArena: Probing Multimodal Grounding Through Language-Guided Pointing**  [[Paper]](https://arxiv.org/abs/2505.09990) [[Dataset]](https://github.com/pointarena/pointarena) ![](https://img.shields.io/badge/May-2025-red)

+ **ChartMuseum: Testing Visual Reasoning Capabilities of Large Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2505.13444) [[Dataset]](https://github.com/Liyan06/ChartMuseum) ![](https://img.shields.io/badge/May-2025-red)

+ **Can MLLMs Guide Me Home? A Benchmark Study on Fine-Grained Visual Reasoning from Transit Maps**  [[Paper]](https://arxiv.org/abs/2505.18675) [[Dataset]](https://github.com/fscdc/ReasonMap) ![](https://img.shields.io/badge/May-2025-red)

+ **PhyX: Does Your Model Have the "Wits" for Physical Reasoning?**  [[Paper]](https://arxiv.org/abs/2505.15929) [[Dataset]](https://github.com/NastyMarcus/PhyX) ![](https://img.shields.io/badge/May-2025-red)

+ **WorldScore: A Unified Evaluation Benchmark for World Generation**  [[Paper]](https://arxiv.org/abs/2504.00983) [[Dataset]](https://github.com/haoyi-duan/WorldScore) ![](https://img.shields.io/badge/Apr-2025-red)

+ **MME-Unify: A Comprehensive Benchmark for Unified Multimodal Understanding and Generation Models**  [[Paper]](https://arxiv.org/abs/2504.03641) [[Dataset]](https://github.com/MME-Benchmarks/MME-Unify) ![](https://img.shields.io/badge/Apr-2025-red)

+ **CrossWordBench: Evaluating the Reasoning Capabilities of LLMs and LVLMs with Controllable Puzzle Generation**  [[Paper]](https://arxiv.org/abs/2504.00043) [[Dataset]](https://github.com/SeanLeng1/CrossWordBench) ![](https://img.shields.io/badge/Mar-2025-red)

+ **CoMT: A Novel Benchmark for Chain of Multi-modal Thought on Large Vision-Language Models** [[Paper]](https://arxiv.org/abs/2412.12932) [[Dataset]](https://huggingface.co/datasets/czh-up/comt) ![](https://img.shields.io/badge/Dec-2024-red)

+ **ARC Prize 2024: Technical Report**  [[Paper]](https://arxiv.org/abs/2412.04604) [[Dataset]](https://arxiv.org/abs/2412.04604) ![](https://img.shields.io/badge/Dec-2024-red)

+ **Vgbench: Evaluating large language models on vector graphics understanding and generation**  [[Paper]](https://arxiv.org/abs/2407.10972) [[Dataset]](https://github.com/vgbench/VGBench) ![](https://img.shields.io/badge/Jul-2024-red)

+ **m&m's: A Benchmark to Evaluate Tool-Use for multi-step multi-modal Tasks**  [[Paper]](https://arxiv.org/abs/2403.11085) [[Dataset]](https://github.com/RAIVNLab/mnms) ![](https://img.shields.io/badge/Mar-2024-red)

+ **A Cognitive Evaluation Benchmark of Image Reasoning and Description for Large Vision-Language Models**  [[Paper]](https://arxiv.org/abs/2402.18409) [[Dataset]](https://github.com/X-LANCE/CogBench) ![](https://img.shields.io/badge/Feb-2024-red)

## 🗂️ Survey

- **Reinforcement Fine-Tuning Powers Reasoning Capability of Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2505.18536) ![](https://img.shields.io/badge/May-2025-red)

- **Perception, Reason, Think, and Plan: A Survey on Large Multimodal Reasoning Models**  [[Paper]](https://arxiv.org/abs/2505.04921) ![](https://img.shields.io/badge/May-2025-red)

- **Reinforced MLLM: A Survey on RL-Based Reasoning in Multimodal Large Language Models**  [[Paper]](https://arxiv.org/abs/2504.21277) ![](https://img.shields.io/badge/Apr-2025-red)

- **A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond**  [[Paper]](https://arxiv.org/abs/2503.21614) ![](https://img.shields.io/badge/Mar-2025-red)

- **Mind with Eyes: from Language Reasoning to Multimodal Reasoning**  [[Paper]](https://arxiv.org/abs/2503.18071) ![](https://img.shields.io/badge/Mar-2025-red)

- **Multimodal Chain-of-Thought Reasoning: A Comprehensive Survey**  [[Paper]](https://arxiv.org/abs/2503.12605) ![](https://img.shields.io/badge/Mar-2025-red)

- **Towards Reasoning Era: A Survey of Long Chain-of-Thought for Reasoning Large Language Models**  [[Paper]](https://arxiv.org/abs/2503.09567) ![](https://img.shields.io/badge/Mar-2025-red)

- **From System 1 to System 2: A Survey of Reasoning Large Language Models**  [[Paper]](https://arxiv.org/abs/2502.17419) ![](https://img.shields.io/badge/Feb-2025-red)
  
- **MME-Survey: A Comprehensive Survey on Evaluation of Multimodal LLMs**  [[Paper]](https://arxiv.org/abs/2411.15296) ![](https://img.shields.io/badge/Nov-2024-red)

- **Exploring the Reasoning Abilities of Multimodal Large Language Models (MLLMs): A Comprehensive Survey on Emerging Trends in Multimodal Reasoning** [[Paper]](https://arxiv.org/abs/2401.06805) ![](https://img.shields.io/badge/Jan-2024-red)
