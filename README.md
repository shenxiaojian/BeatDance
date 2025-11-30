# BeatDance: Generating Beat-Consistent 3D Dance with Hierarchical Spatial-Temporal Modeling

[![Paper Status](https://img.shields.io/badge/Paper-Under%20Review-blue.svg)](https://shenxiaojian.github.io/BeatDance/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Framework: Pytorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org)

---

## 🔗 Project & Resources

| Resource | Status | Link |
| :--- | :--- | :--- |
| 🌐 **Project Page** | **LIVE!** | **[Click Here for Visualizations](https://shenxiaojian.github.io/BeatDance/)** |
| 📜 **Paper** | Under Review | [arXiv/Preprint] *(Coming Soon)* |
| 💾 **Code** | **Coming Soon** | [See Release Plan](#-code-and-model-release-status) |

---

## ✨ Abstract

Generating realistic 3D dance from music is a challenging task that requires accurate synchronization with musical rhythms while capturing the spatial complexity of human motion. Although existing methods can generate physically plausible dance motions, they often struggle to achieve precise alignment with music, such as the beat. To address this limitation, we propose a novel diffusion-based framework, BeatDance, with two components: 1) We present a Hierarchical Decoupled Attention (HDA) module, which first disentangles the learning of human pose and temporal dynamics. A hierarchical structure is then employed to capture both short-term and long-term dependencies, thereby enhancing spatial-temporal modeling. 2) We adopt cycle-consistent learning by introducing an auxiliary dance-to-music module. During training, discrepancies between the reconstructed and original music induce a stronger loss signal, effectively encouraging the consistency property between the music and dance motion. Extensive experimental results demonstrate that our proposed approach outperforms recent competitive methods on two benchmark datasets.

## 👥 Authors

* Xiaojian Shen (Jilin University)
* Dahu Shi (Zhejiang University)
* Jianrong Zhang (University of Technology Sydney)
* Hai Li (Jilin University)
* Hongwei Zhao (Jilin University)
* Yunzhi Zhuge (Dalian University of Technology)
* Zhiliang Wu (Zhejiang University)

---

## 🔑 Code and Model Release Status

We are committed to full reproducibility and open science.

<p align="center">
    <img src="https://img.shields.io/badge/Code%20Release-UPON%20ACCEPTANCE-red?style=for-the-badge&logo=github" alt="Code Status">
</p>

The source code, trained models, and detailed setup instructions are currently withheld to preserve the integrity of the **academic peer-review process**.

**We guarantee that the complete repository contents (including training scripts and pretrained checkpoints) will be made publicly available immediately upon acceptance of the manuscript.**

## 🛠️ Requirements & Setup

*(Detailed installation guide and environment setup will be updated here once the code is released.)*

## 📝 Citation

If you find our work useful for your research, please consider citing our paper:

```bibtex
@article{BeatDance2025,
  title={BeatDance: Generating Beat-Consistent 3D Dance with Hierarchical Spatial-Temporal Modeling},
  author={Shen, Xiaojian and Shi, Dahu and Zhang, Jianrong and Li, Hai and Zhao, Hongwei and Zhuge, Yunzhi and Wu, Zhiliang},
  journal={Under Review},
  year={2025}
}
