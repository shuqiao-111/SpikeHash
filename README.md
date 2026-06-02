# SpikeHash

> **Code coming soon.**  
> This repository will host the official implementation of **SpikeHash: Learning Binary Codes with Spiking Neural Networks for Cross-Modal Hashing Retrieval**.

<p align="center">
  <a href="https://shuqiao-111.github.io/">Project Page</a> ·
  <a href="https://shuqiao-111.github.io/SpikeHash/">Code Page</a> ·
  <a href="https://arxiv.org/pdf/2606.00740">Paper</a> ·
  <a href="#citation">Citation</a>
</p>

---

Paper page:

```text
https://arxiv.org/pdf/2606.00740
```

## Overview

SpikeHash is an unsupervised spiking computation framework for cross-modal hashing retrieval. It reformulates binary hash-code generation as an event-driven process that integrates:

- multi-step spike encoding,
- shared spiking hash-state evolution,
- directional cross-modal spiking gated interaction,
- positive-negative spike competition readout.

The implementation is being cleaned and verified before public release.

## Current Status

The code is not yet ready for release. We are preparing:

- training and evaluation scripts,
- dataset preprocessing instructions,
- model configuration files,
- reproducible benchmark commands,
- pretrained / released checkpoints when available,
- documentation for MIRFlickr, NUS-WIDE, and MSCOCO evaluation.

## Release Plan

| Component | Status |
|---|---|
| Core SpikeHash model | Coming soon |
| Training pipeline | Coming soon |
| Evaluation scripts | Coming soon |
| Dataset preprocessing | Coming soon |
| Configuration files | Coming soon |
| Checkpoints / logs | Coming soon |

## Expected Repository Structure

```text
SpikeHash/
├── configs/
├── datasets/
├── models/
├── scripts/
├── tools/
├── train.py
├── evaluate.py
├── requirements.txt
└── README.md
```

## Citation

```bibtex
@misc{zhang2026spikehashlearningbinarycodes,
      title={SpikeHash: Learning Binary Codes with Spiking Neural Networks for Cross-Modal Hashing Retrieval}, 
      author={Yukuan Zhang and Jiarui Zhao and Shangqing Nie and Shengsheng Wang},
      year={2026},
      eprint={2606.00740},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2606.00740}, 
}
```

## Contact

For questions about the release schedule, please open an issue after the repository is initialized or contact the authors through the project page.

---

This placeholder page is temporary and will be replaced by the full code documentation after release.
