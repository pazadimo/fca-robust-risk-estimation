# Factorized Context Aggregation for Robust Cancer Risk Estimation

Official repository for our **CVPR 2026** paper:

**Factorized Context Aggregation for Robust Cancer Risk Estimation via Soft Re-Ranked Retrieval and Hierarchical Anchors**

## Abstract

Multimodal models can improve cancer prognosis by combining histopathology with complementary information such as genomics and clinical reports. However, these models commonly assume that every modality is available during inference, which is often unrealistic in clinical practice.

We introduce a framework that uses routinely available histopathology as the primary input while leveraging complementary modalities during training. The method estimates survival-relevant proxy representations for unavailable modalities through soft re-ranked retrieval, factorized prognostic context aggregation, and hierarchical intra- and inter-modality anchors.

Across 24 tasks and eight cancer types, our approach achieves up to an 8% improvement over histology-only methods while remaining within 1.4% of fully multimodal models. It also demonstrates robust patient-risk stratification and generalizes under varying levels of missing data, supporting practical cancer-risk estimation in modality-incomplete clinical settings. :contentReference[oaicite:0]{index=0}

## Overview

Our work addresses a key challenge in multimodal cancer risk estimation: **missing modalities at inference time**.

The proposed framework leverages complementary modalities during training while requiring only histopathology at deployment, making multimodal prognostic modeling more practical for real-world clinical settings.

Across **eight cancer types and 24 tasks**, our method improves robustness to missing modalities and achieves performance close to fully multimodal models.

## Paper

Check out the paper here:

[CVPR 2026 Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Moghadam_Factorized_Context_Aggregation_for_Robust_Cancer_Risk_Estimation_via_Soft_CVPR_2026_paper.pdf)


## Code

The implementation, training instructions, and data-processing scripts will be released by the **end of June 2026**.

Stay tuned for updates.

## Citation

Please cite our paper if you find this work useful:

```bibtex
@inproceedings{moghadam2026factorized,
  title     = {Factorized Context Aggregation for Robust Cancer Risk Estimation
               via Soft Re-Ranked Retrieval and Hierarchical Anchors},
  author    = {Moghadam, Puria Azadi and
               Mirabadi, Ali Khajegili and
               Maneshgar, Behnam and
               Farahani, Hossein and
               Bashashati, Ali},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision
               and Pattern Recognition},
  year      = {2026}
}
