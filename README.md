<div align="center">
<h1>BHaRNet</h1>
This repository provides the official implementation of

  *Body-Hand Modality Expertized Networks with Cross-attention for Fine-grained Skeleton Action Recognition* (IROS 2025)

  <a href="https://arxiv.org/abs/2503.14960"><img src="https://img.shields.io/badge/arXiv-2503.14960-b31b1b" alt="arXiv"></a>
   
  *BHaRNet: Reliability-Aware Body–Hand Modality Expertized Networks for Fine-grained Skeleton Action Recognition* 
   (arXiv 2026)
  
<a href="https://arxiv.org/abs/2601.00369"><img src="https://img.shields.io/badge/arXiv-2601.00369-b31b1b" alt="arXiv"></a> 

<a href="/LICENSE"><img src="https://img.shields.io/badge/license-Apache%20License%202.0-blue" alt="License"></a>

**[KAIST](https://sites.google.com/view/tkkim/home)**


[Seungyeon Cho](https://github.com/VinnyCSY), [Tae-Kyun Kim](https://sites.google.com/view/tkkim/home)
</div>

### Abstract
> In skeleton-based human action recognition, most existing methods primarily focus on full-body movements while overlooking subtle hand motions that are crucial for distinguishing fine-grained actions. We propose **BHaRNet** (**B**ody–**H**and **a**ction **R**ecognition **Net**work), a novel framework that augments a body-expert model with a complementary hand-expert model. BHaRNet includes diverse variants (BHaRNet-P, BHaRNet-E, BHaRNet-B, and BHaRNet-M), built upon a dual-stream network, and can be extended to lightweight configurations and multi-modal settings with RGB input. Experiments on large-scale benchmarks (NTU RGB+D 60, NTU RGB+D 120, PKU-MMD, and Northwestern-UCLA) and new benchmark NTU-Hand 11/27 show that BHaRNet achieves state-of-the-art or highly competitive performance with high efficiency.
<p align="center">
  <img src="graphical abstract.png" alt="Graphical Abstract" width="500"/>
</p>

## Demo
<p align="center">
  <img src="demo.gif" alt="Demo" width="600"/>
</p>



## Updates
- [March 19, 2025] "Body-Hand Modality Expertized Networks with Cross-attention for Fine-grained Skeleton Action Recognition" is uploaded in arXiv.
- [June 16, 2025] Honored to be accepted for publication in IROS 2025 as oral&poster presentation!
- [January 1, 2026] "BHaRNet: Reliability-Aware Body-Hand Modality Expertized Networks for Fine-grained Skeleton Action Recognition" is uploaded in arXiv.
- Journal extension in progress: Code and processed skeleton splits will be made publicly available upon publication.

## License
See the [LICENSE](./LICENSE) file for details about the license under which this code is made available.

```bibtex
@INPROCEEDINGS{11246883,
  author={Cho, Seungyeon and Kim, Tae-Kyun},
  booktitle={2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={Body-Hand Modality Expertized Networks with Cross-attention for Fine-grained Skeleton Action Recognition}, 
  year={2025},
  volume={},
  number={},
  pages={11614-11621},
  keywords={Hands;Accuracy;Target recognition;Inertial sensors;Dynamics;Redundancy;Skeleton;Computational efficiency;Human activity recognition;Intelligent robots},
  doi={10.1109/IROS60139.2025.11246883}
}
@article{cho2026bharnet,
  title={BHaRNet: Reliability-Aware Body-Hand Modality Expertized Networks for Fine-grained Skeleton Action Recognition},
  author={Cho, Seungyeon and Kim, Tae-kyun},
  journal={arXiv preprint arXiv:2601.00369},
  year={2026}
}
```
