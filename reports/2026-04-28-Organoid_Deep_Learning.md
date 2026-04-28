# arXiv 最新论文速报 · Organoid Deep Learning

> 生成时间：2026-04-28　|　共 5 篇　|　来源：arXiv（摘要为官网英文原文，无大模型翻译）

---

## 1. World-R1: Reinforcing 3D Constraints for Text-to-Video Generation

- **作者**：Weijie Wang, Xiaoxuan He, Youping Gu, Yifan Yang, Zeyu Zhang 等 12 位作者
- **发布日期**：2026-04-27
- **arXiv ID**：`2604.24764v1`
- **PDF**：<https://arxiv.org/pdf/2604.24764v1>

### 摘要（英文 · arXiv 原文）

Recent video foundation models demonstrate impressive visual synthesis but frequently suffer from geometric inconsistencies. While existing methods attempt to inject 3D priors via architectural modifications, they often incur high computational costs and limit scalability. We propose World-R1, a framework that aligns video generation with 3D constraints through reinforcement learning. To facilitate this alignment, we introduce a specialized pure text dataset tailored for world simulation. Utilizing Flow-GRPO, we optimize the model using feedback from pre-trained 3D foundation models and vision-language models to enforce structural coherence without altering the underlying architecture. We further employ a periodic decoupled training strategy to balance rigid geometric consistency with dynamic scene fluidity. Extensive evaluations reveal that our approach significantly enhances 3D consistency while preserving the original visual quality of the foundation model, effectively bridging the gap between video generation and scalable world simulation.

### 要点归纳

_未使用大模型自动提炼；请根据上文摘要自行整理要点。_

---

## 2. Tuna-2: Pixel Embeddings Beat Vision Encoders for Multimodal Understanding and Generation

- **作者**：Zhiheng Liu, Weiming Ren, Xiaoke Huang, Shoufa Chen, Tianhong Li 等 15 位作者
- **发布日期**：2026-04-27
- **arXiv ID**：`2604.24763v1`
- **PDF**：<https://arxiv.org/pdf/2604.24763v1>

### 摘要（英文 · arXiv 原文）

Unified multimodal models typically rely on pretrained vision encoders and use separate visual representations for understanding and generation, creating misalignment between the two tasks and preventing fully end-to-end optimization from raw pixels. We introduce Tuna-2, a native unified multimodal model that performs visual understanding and generation directly based on pixel embeddings. Tuna-2 drastically simplifies the model architecture by employing simple patch embedding layers to encode visual input, completely discarding the modular vision encoder designs such as the VAE or the representation encoder. Experiments show that Tuna-2 achieves state-of-the-art performance in multimodal benchmarks, demonstrating that unified pixel-space modelling can fully compete with latent-space approaches for high-quality image generation. Moreover, while the encoder-based variant converges faster in early pretraining, Tuna-2's encoder-free design achieves stronger multimodal understanding at scale, particularly on tasks requiring fine-grained visual perception. These results show that pretrained vision encoders are not necessary for multimodal modelling, and end-to-end pixel-space learning offers a scalable path toward stronger visual representations for both generation and perception.

### 要点归纳

_未使用大模型自动提炼；请根据上文摘要自行整理要点。_

---

## 3. Personalized Worked Example Generation from Student Code Submissions using Pattern-based Knowledge Components

- **作者**：Griffin Pitts, Muntasir Hoq, Peter Brusilovsky, Narges Norouzi, Arto Hellas 等 7 位作者
- **发布日期**：2026-04-27
- **arXiv ID**：`2604.24758v1`
- **PDF**：<https://arxiv.org/pdf/2604.24758v1>

### 摘要（英文 · arXiv 原文）

Adaptive programming practice often relies on fixed libraries of worked examples and practice problems, which require substantial authoring effort and may not correspond well to the logical errors and partial solutions students produce while writing code. As a result, students may receive learning content that does not directly address the concepts they are working to understand, while instructors must either invest additional effort in expanding content libraries or accept a coarse level of personalization. We present an approach for knowledge-component (KC) guided educational content generation using pattern-based KCs extracted from student code. Given a problem statement and student submissions, our pipeline extracts recurring structural KC patterns from students' code through AST-based analysis and uses them to condition a generative model. In this study, we apply this approach to worked example generation, and compare baseline and KC-conditioned outputs through expert evaluation. Results suggest that KC-conditioned generation improves topical focus and relevance to learners' underlying logical errors, providing evidence that KC-based steering of generative models can support personalized learning at scale.

### 要点归纳

_未使用大模型自动提炼；请根据上文摘要自行整理要点。_

---

## 4. The Optimal Sample Complexity of Multiclass and List Learning

- **作者**：Chirag Pabbaraju
- **发布日期**：2026-04-27
- **arXiv ID**：`2604.24749v1`
- **PDF**：<https://arxiv.org/pdf/2604.24749v1>

### 摘要（英文 · arXiv 原文）

While the optimal sample complexity of binary classification in terms of the VC dimension is well-established, determining the optimal sample complexity of multiclass classification has remained open. The appropriate complexity parameter for multiclass classification is the DS dimension, and despite significant efforts, a gap of $\sqrt{\text{DS}}$ has persisted between the upper and lower bounds on sample complexity.   Recent work by Hanneke et al. (2026) shows a novel algebraic characterization of multiclass hypothesis classes in terms of their DS dimension. Building up on this, we show that the maximum hypergraph density of any multiclass hypothesis class is upper-bounded by its DS dimension. This proves a longstanding conjecture of Daniely and Shalev-Shwartz (2014). As a consequence, we determine the optimal dependence of the sample complexity on the DS dimension for multiclass as well as list learning.

### 要点归纳

_未使用大模型自动提炼；请根据上文摘要自行整理要点。_

---

## 5. Conflict-Aware Harmonized Rotational Gradient for Multiscale Kinetic Regimes

- **作者**：Zhangyong Liang
- **发布日期**：2026-04-27
- **arXiv ID**：`2604.24745v1`
- **PDF**：<https://arxiv.org/pdf/2604.24745v1>

### 摘要（英文 · arXiv 原文）

In this paper, we propose a harmonized rotational gradient method, termed HRGrad, for simultaneously tackling multiscale time-dependent kinetic problems with varying small parameters.   These parameters exhibit asymptotic transitions from microscopic to macroscopic physics, making it a challenging multi-task problem to solve over all ranges simultaneously.   Solving tasks in different asymptotic regions often encounter gradient conflicts, which can lead to the failure of multi-task learning.   To address this challenge, we explicitly encode a hidden representation of these parameters, ensuring that the corresponding solving tasks are serialized for simultaneous training.   Furthermore, to mitigate gradient conflicts, we segment the prediction results to construct task losses and introduce a novel gradient alignment metric to ensure a positive dot product between the final update and each loss-specific gradient.   This metric maintains consistent optimization rates for all task losses and dynamically adjusts gradient magnitudes based on conflict levels.   Moreover, we provide a mathematical proof demonstrating the convergence of the HRGrad method, which is evaluated across a range of challenging asymptotic-preserving neural networks (APNNs) scenarios.   We conduct an extensive set of experiments encompassing the Bhatnagar-Gross-Krook (BGK) equation and the linear transport equation in all ranges of Knudsen number.   Our results indicate that HRGrad effectively overcomes the `failure modes' of APNNs in these problems.

### 要点归纳

_未使用大模型自动提炼；请根据上文摘要自行整理要点。_

---

_本报告由脚本根据 arXiv 数据自动生成，仅供学习研究参考。_