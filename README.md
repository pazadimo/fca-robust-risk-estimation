# Factorized Context Aggregation for Robust Cancer Risk Estimation

Official repository for our **CVPR 2026** paper:

**Factorized Context Aggregation for Robust Cancer Risk Estimation via Soft Re-Ranked Retrieval and Hierarchical Anchors**

<p align="center">
  <img src="[assets/framework_overview.png](https://github.com/pazadimo/fca-robust-risk-estimation/blob/main/overview_v4.pdf)" width="95%" alt="Overview of the Factorized Context Aggregation framework">
</p>

<p align="center">
  <em>
    Overview of existing approaches for handling missing modalities and our proposed
    soft re-ranked retrieval, prognostic context aggregation, and hierarchical anchor framework.
  </em>
</p>

## Abstract

Accurate cancer risk assessment is critical for personalized treatment planning. While multimodal models that integrate histopathology with complementary data modalities, such as genomics and clinical reports, exhibit superior prognostic capability, they typically assume full data availability, which is unrealistic in real-world clinical settings.

We propose a framework that uses routinely available histopathology as the primary input while leveraging complementary modalities during training. The model dynamically estimates survival-associated proxy representations for modalities that are unavailable at inference time using soft re-ranked retrieval, factorized prognostic context aggregation, and hierarchical anchors.

Across **24 tasks and eight cancer types**, our method achieves up to an **8% improvement** over models trained solely with histopathology while maintaining only a **1.4% performance gap** compared with fully multimodal models. It also demonstrates robust risk stratification and generalization under varying levels of modality missingness.

## Overview

Our work addresses a key challenge in multimodal cancer risk estimation: **missing modalities at inference time**.

The proposed framework leverages complementary modalities during training while requiring only histopathology at deployment, making multimodal prognostic modeling more practical for real-world clinical settings.

Across **eight cancer types and 24 tasks**, our method improves robustness to missing modalities and achieves performance close to fully multimodal models.

## Paper

Check out the paper here:

[CVPR 2026 Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Moghadam_Factorized_Context_Aggregation_for_Robust_Cancer_Risk_Estimation_via_Soft_CVPR_2026_paper.pdf)


## Code

The implementation, training instructions, pretrained models, and data-processing scripts will be released by the **end of June 2026**.

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
