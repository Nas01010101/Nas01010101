# Anas Elghoudane

<p align="left">
  <b>B.Sc. Mathematics & Computer Science</b> @ <a href="https://www.umontreal.ca/">Université de Montréal (UdeM)</a><br>
  Research focus: <b>ML Systems, Numerical Simulation, Formal Verification (Lean 4) & Sequential Decision-Making</b><br>
  📍 Montréal, QC, Canada &nbsp;|&nbsp; 🌐 <a href="https://nas01010101.github.io">nas01010101.github.io</a> &nbsp;|&nbsp; ✉️ <a href="mailto:anaselghoudane@gmail.com">anaselghoudane@gmail.com</a>
</p>

---

### 🔬 About Me

I am an undergraduate researcher in Mathematics & Computer Science at **Université de Montréal** (collaborating with researchers at **Mila** and **CRCHUM**). My work sits at the intersection of **rigorous mathematics, high-performance ML systems, and formal methods**.

* 🔭 **Current Research:** Theoretical reinforcement and imitation learning under distribution shift (Dept. of Math & Stats, UdeM / Mila) and clinical biostatistics (CRCHUM).
* ⚙️ **Core Tooling:** PyTorch, JAX, CUDA/C++, Rust, MuJoCo, NVIDIA Warp, Lean 4, SymPy.
* 🏆 **Scholarships:** Recipient of $17,000+ in competitive undergraduate research scholarships across educational technology, behavioural ML, and clinical biostatistics.

---

### 🚀 Upstream Open-Source Contributions

I actively contribute numerical fixes, optimizer internals, and performance patches to core machine learning and scientific computing infrastructure:

| Organization / Repository | Pull Request | Problem Solved & Technical Impact | Status |
| :--- | :--- | :--- | :--- |
| **Google DeepMind** (`mujoco`) | [#3301](https://github.com/google-deepmind/mujoco/pull/3301) | Corrected bounded-Jacobian finite-difference step direction against half-boxwidth, eliminating gradient divergence near box bounds. | **Merged** (`main`) |
| **Google DeepMind** (`dm_pix`) | [#112](https://github.com/google-deepmind/dm_pix/pull/112) | Made `pad_to_size` channel-axis aware for channels-first tensors in vision pipelines. | **Merged** |
| **NVIDIA** (`warp`) | [#1595](https://github.com/NVIDIA/warp/pull/1595) | Fixed `fp16` Adam optimizer state by retaining `fp32` moment buffers across parameter updates rather than discarding them. | **Merged** |
| **Huawei Noah's Ark** (`trustworthyAI`) | [#193](https://github.com/huawei-noah/trustworthyAI/pull/193) | Fixed causal-discovery metrics (`MetricsDAG`) reporting TPR > 1.0 due to double-counted bidirectional edges; added regression tests. | **Merged** |
| **Alibaba** (`ms-swift`) | [#9680](https://github.com/modelscope/ms-swift/pull/9680) | Exposed `optimizer_cuda_graph` in Megatron-SWIFT for CUDA-graph optimizer execution, reducing kernel launch latency in distributed LLM training. | **Merged** |
| **Alibaba** (`qwen-code`) | [#6288](https://github.com/QwenLM/qwen-code/pull/6288), [#6295](https://github.com/QwenLM/qwen-code/pull/6295) | Added timeout disabling (`timeout=0`) and registered `@-attached` files as pre-read in the agent execution loop. | **Merged** |
| **Google** (`jax`) | [#38631](https://github.com/jax-ml/jax/pull/38631) | Fixed truncated normal distribution CDF/SF edge cases and precision stability. | *Under Review* |
| **Hugging Face** (`diffusers`) | [#14026](https://github.com/huggingface/diffusers/pull/14026) | Resolved deprecated pipeline module resolution inside `from_pretrained`. | *Under Review* |
| **Lightning AI** (`pytorch-lightning`) | [#21769](https://github.com/Lightning-AI/pytorch-lightning/pull/21769) | Eliminated redundant per-step device transfers during training loops. | *Under Review* |

---

### 📦 Selected Projects

```
├── 📐 Formal Verification & Mathematics
│   ├── cas-lean-certifier           → Bridge SymPy symbolic outputs to verified Lean 4 certificate assertions
│   ├── lean4phys-dimension-solver   → Dimension-aware solver macro and unit arithmetic tactic for Lean 4 physics
│   ├── physlib-noether-symmetries   → Formalization of Noether's Theorem and spacetime symmetries in Lean 4
│   └── cupellation                  → Gate chain and verification receipt for machine-generated Lean 4 mathematics
│
├── 🤖 Robotics & Physics Simulation
│   ├── openspine-impact             → MuJoCo multibody spine model for impact loads with spinal fusion option
│   └── spine-metrics                → Kinematic extraction and validation ledger for biomechanical impact tests
│
└── 🛰️ Applied ML & Vision
    ├── arctic-rts                   → GeoAI Arctic Challenge: Multi-resolution Mask R-CNN ensembles for thaw slumps
    └── sced-vision                  → Computer vision classification of single-case experimental design (SCED) plots
```

---

### 🛠️ Languages & Tech Stack

* **Languages:** Python, C/C++, Rust, Lean 4, Go, TypeScript, R, SQL, Swift.
* **ML & Numerical Systems:** PyTorch, JAX / Flax, MuJoCo, NVIDIA Warp, Hugging Face Transformers, PyTorch Lightning, scikit-learn.
* **Infrastructure & Tooling:** CUDA, Docker, Git, Weights & Biases, Google Cloud (Multi-GPU / TPU), Linux.
* **Spoken Languages:** French (Native), English (Native), Arabic (Fluent), Spanish (Fluent), Mandarin (HSK1).

---

<p align="center">
  <a href="https://github.com/Nas01010101">
    <img src="https://img.shields.io/github/followers/Nas01010101?label=Follow&style=social" alt="Follow on GitHub">
  </a>
</p>
