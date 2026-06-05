# Factorized Context Aggregation for Robust Cancer Risk Estimation

Official repository for our **CVPR 2026** paper:

**Factorized Context Aggregation for Robust Cancer Risk Estimation via Soft Re-Ranked Retrieval and Hierarchical Anchors**

## Overview

Multimodal learning can improve cancer risk estimation by combining histopathology with complementary information such as genomic data and pathology reports. However, these additional modalities are often unavailable during real-world clinical deployment.

Our work addresses the challenge of **missing modalities at inference time**. The proposed framework leverages complementary modalities during training while requiring only histopathology at inference, making multimodal prognostic modeling more practical for clinical settings.

Across **eight cancer types and 24 tasks**, our method improves robustness to missing modalities and achieves performance close to fully multimodal models.

## Paper

Check out the paper here:

[CVPR 2026 Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Moghadam_Factorized_Context_Aggregation_for_Robust_Cancer_Risk_Estimation_via_Soft_CVPR_2026_paper.pdf)

## Poster Presentation

- **Conference:** CVPR 2026
- **Date:** Sunday, June 7, 2026
- **Time:** 1:45 PM–3:45 PM EDT
- **Room:** ExHall F
- **Poster:** 510

## Code

The implementation, training instructions, pretrained models, and data-processing scripts will be published soon.

Stay tuned for updates.

## Citation

Please cite our paper if you find this work useful:

```bibtex
@inproceedings{moghadam2026factorized,
  title={Factorized Context Aggregation for Robust Cancer Risk Estimation via Soft Re-Ranked Retrieval and Hierarchical Anchors},
  author={Moghadam, Puria Azadi and others},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2026}
}
