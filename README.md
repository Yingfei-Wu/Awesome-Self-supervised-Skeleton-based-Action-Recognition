# Awesome-Self-supervised-Skeleton-based-Action-Recognition
Following the updates from [Awesome Skeleton-based Action Recognition](https://github.com/firework8/Awesome-Skeleton-based-Action-Recognition?tab=readme-ov-file), organize and summarize the current performance of Awesome-Self-supervised-Skeleton-based-Action-Recognition.

(✅ indicates the presence of code, ❌ indicates no code available temporarily and 🚧 indicates an empty code repository. )



**2025

❌[Heterogeneous CVPR'2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Heterogeneous_Skeleton-Based_Action_Representation_Learning_CVPR_2025_paper.pdf)

✅[USDRL AAAI'2025](https://ojs.aaai.org/index.php/AAAI/article/view/32899) [[code](https://github.com/wengwanjiang/USDRL)]

❌[Rethinking AAAI'2025](https://ojs.aaai.org/index.php/AAAI/article/view/32324)

❌[PASTD ICASSP'2025](https://ieeexplore.ieee.org/abstract/document/10890079)

🚧[MaskSem IROS'2025](https://arxiv.org/abs/2508.12948)[[code](https://github.com/JayEason66/MaskSem)]

✅[USDRL+ TPAMI'2025](https://ieeexplore.ieee.org/abstract/document/11130651)[[code](https://github.com/wengwanjiang/FoundSkelModel)]

❌[ActCLR+ TPAMI'2025](https://ieeexplore.ieee.org/abstract/document/11123705)

❌[ACA²Net TCSVT'2025](https://ieeexplore.ieee.org/abstract/document/10843295)

❌[U-FEFP TCSVT'2025](https://ieeexplore.ieee.org/abstract/document/10879058)

🚧[STJD TBOIM'2025](https://ieeexplore.ieee.org/document/10981864)[[code](https://github.com/ShanakaRG/STJD-Spatio-Temporal-Joint-Density-Driven-Learning-for-Skeleton-Based-Action-Recognition)]

✅[MS-CLR arxiv'2025](https://arxiv.org/abs/2508.14889)[[code](https://github.com/3Dwe-ai/ms-clr)]

**2024

✅[MacDif ECCV'2024](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03727.pdf)[[code](https://github.com/LehongWu/MacDiff)]

🚧[IGM ECCV'2024](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03717.pdf)[[code](https://github.com/LanglandsLin/IGM)]

❌[S-JEPA ECCV'2024](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04755.pdf)

✅[SCD-Net AAAI'2024](https://ojs.aaai.org/index.php/AAAI/article/view/28409)[[code](https://github.com/cong-wu/SCD-Net)]

❌[MideCLR TIP'2024](https://ieeexplore.ieee.org/abstract/document/10462918)

🚧[C²VL TMM'2024](https://ieeexplore.ieee.org/abstract/document/10812782)[[code](https://github.com/cseeyangchen/C2VL?tab=readme-ov-file)]

❌[KTCL TMM'2024](https://ieeexplore.ieee.org/abstract/document/10539295)

❌[Skeleton-logoCLR TCSVT'2024](https://ieeexplore.ieee.org/abstract/document/10551297)

❌[MMFR TCSVT'2024](https://ieeexplore.ieee.org/abstract/document/10562342)

✅[AimCLR++ PR'2024](https://www.sciencedirect.com/science/article/pii/S0031320324000840)[[code](https://github.com/Levigty/AimCLR-v2)]

❌[RMMD Neurocomputing'2024](https://www.sciencedirect.com/science/article/pii/S0925231224002662)

✅[STARS arxiv'2024](https://arxiv.org/abs/2407.10935)[[code](https://github.com/TaatiTeam/STARS)]

✅[HA-CM arxiv'2024](https://arxiv.org/abs/2409.17951)[[code](https://github.com/YinxPeng/HA-CM-main)]

🚧[Skeleton2vec arxiv'2024](https://arxiv.org/abs/2401.00921)[[code](https://github.com/Ruizhuo-Xu/Skeleton2vec)]












This section presents the current accuracy and other information related to the Awesome-Self-supervised-Skeleton-based-Action-Recognition work.
## 📊 Accuracy of Linear evaluation  (Sorted by NTU RGB+D xsub of single joint % ↑)

| Method          | Year               | Learning Paradigm | NTU RGB+D xsub (%) | NTU RGB+D xview (%) | NTU RGB+D 120 xsub (%) | NTU RGB+D 120 xset (%) | PKU-MMD Part II (%) |
|-----------------|--------------------|-----------|---------------------|----------------------|------------------------|------------------------|----------------------|
| LongT GAN       | AAAI'2018          | MSM       | 39.1 | 48.1 | -    | -    | 26.0 |
| P&C             | CVPR'2020          | MSM       | 50.7 | 76.3 | 42.7 | 41.7 | 25.5 |
| MS²L            | ACMMM'2020         | MSM&CL    | 52.6 |   -  | -    | -    | 27.6 |
| SkeletonCLR     | CVPR'2021          | CL        | 68.3 | 76.4 | 56.8 | 55.9 | -    |
| AimCLR          | AAAI'2022          | CL        | 74.3 | 79.7 | 63.4 | 63.4 | 38.5 |
| SkeletonMAE     | ICME'2023          | MSM       | 74.8 | 77.7 | 72.5 | 73.5 | 36.1 |
| ISC             | ACMMM'2021         | CL        | 76.3 | 85.2 | 67.1 | 67.9 | 36.0 |
| AimCLR++        | PR'2024            | CL        | 77.2 | 81.5 | 65.5 | 67.8 | -    |
| HYSP            | ICLR'2023          | CL        | 78.2 | 82.6 | 61.8 | 64.6 | -    |
| ActCLR          | CVPR'2023          | CL        | 80.9 | 86.7 | 69.0 | 70.5 | -    |
| SkeAttnCLR      | IJCAI'2023         | CL        | 80.3 | 86.1 | 66.3 | 74.5 | 52.9 |
| SSRL            | TCSVT'2024         | CL        | 80.4 | 82.0 | 68.0 | 68.6 | -    |
| HiCo-Transformer| AAAI'2023          | CL        | 81.1 | 88.6 | 72.8 | 74.1 | 49.4 |
| PCM³            | ACMMM'2023         | MSM&CL    | 83.9 | 90.4 | 76.5 | 77.5 | 51.5 |
| MideCLR         | TIP'2024           | CL        | 83.9 | 90.3 | 75.7 | 77.2 | -    |
| USDRL(STTR)     | AAAI'2025          | CL        | 84.2 | 90.8 | 76.0 | 76.9 | 51.8 |
| MAMP            | ICCV'2023          | MSM       | 84.9 | 89.1 | 78.6 | 79.1 | 53.8 |
| DDC             | PR'2025            | MSM&CL    | 84.9 | 90.7 | 77.7 | 79.2 | 53.2 |
| USDRL(DSTE)     | AAAI'2025          | CL        | 85.2 | 91.7 | 76.6 | 78.1 | 54.4 |
| ACA²Net         | TCSVT'2025         | MSM       | 86.0 | 89.6 | 79.1 | 79.8 | 53.7 |
| SCD-Net         | AAAI'2024          | CL        | 86.6 | 91.7 | 76.9 | 80.1 | 54.0 |
| U-FEFP          | TCSVT'2025         | Other&CL  | 86.7 | 91.2 | 78.3 | 79.6 | 54.2 |
| MEMC            | -                  |     -     | 86.8 | 90.4 | 79.2 | 80.5 | 56.4 |
|Heterogeneous    |CVPR'2025           |     -     | 80.2 | 88.0 | 70.7 | 73.5 | 47.7 |
|Rethinking       |AAAI'2025           |     -     | 86.9 | 91.0 | 80.0 | 81.5 | 55.3 |
|PASTD            |ICASSP'2025         |     -     | 86.8 | 91.8 | 77.3 | 80.6 | 54.6 |
|MaskSem          |IROS'2025           |     -     | 85.9 | 90.8 | 77.5 | 79.3 | 55.8 |
|USDRL+           |TPAMI'2025          |     -     | 85.8 | 91.8 | 77.5 | 78.8 | 54.7 |
|ActCLR+          |TPAMI'2025          |     -     | 82.3 | 88.2 | 70.9 | 73.2 |   -  |
|ACA²Net          |TCSVT'2025          |     -     | 86.0 | 89.6 | 79.1 | 79.8 | 53.7 |
|U-FEFP(ST-GCN)   |TCSVT'2025          |     -     | 85.8 | 90.1 | 77.3 | 78.5 |   -  |
|U-FEFP(CTRGCN)   |TCSVT'2025          |     -     | 86.7 | 91.2 | 78.3 | 79.6 | 54.2 |
|STJD-CL          |TBOIM'2025          |     -     | 82.3 | 87.9 | 70.5 | 72.8 | 51.5 |
|STJD-MP          |TBOIM'2025          |     -     | 85.4 | 90.2 | 79.1 | 80.4 |   -  |
|MS-CLR           |arxiv'2025          |     -     | 86.6 | 93.2 | 74.3 | 73.8 |   -  |
|MacDif           |ECCV'2024           |     -     | 86.4 | 91.0 | 79.4 | 80.2 |   -  |
|IGM              |ECCV'2024           |     -     | 86.2 | 91.2 | 80.0 | 81.4 |   -  |
|S-JEPA           |ECCV'2024           |     -     | 85.3 | 89.8 | 79.6 | 79.9 | 53.5 |
|SCD-Net          |AAAI'2024           |     -     | 86.6 | 91.7 | 76.9 | 80.1 | 54.0 |
|MideCLR          |TIP'2024            |     -     | 83.9 | 90.3 | 75.7 | 77.2 |   -  |
|C²VL             |TMM'2024            |     -     | 84.4 | 89.8 | 76.0 | 78.7 | 52.6 |
|KTCL             |TMM'2024            |     -     | 82.4 | 89.4 | 74.4 | 74.5 | 55.5 |
|Skeleton-logoCLR |TCSVT'2024          |     -     | 82.4 | 87.2 | 72.8 | 73.5 | 54.7 |
|MMFR             |TCSVT'2024          |     -     | 84.2 | 89.5 | 77.1 | 78.8 | 54.4 |
|AimCLR++         |PR'2024             |     -     | 77.2 | 81.5 | 65.5 | 67.8 |   -  |
|RMMD             |Neurocomputing'2024 |     -     | 83.0 | 90.5 | 75.2 | 75.8 | 50.6 |
|STARS-2stages    |arxiv'2024          |     -     | 87.1 | 90.9 | 79.9 | 80.8 | 52.7 |
|STARS-3stages    |arxiv'2024          |     -     | 86.3 | 90.7 | 79.3 | 80.6 | 52.2 |
|HA-CM            |arxiv'2024          |     -     | 86.3 | 91.2 | 78.9 | 80.2 | 50.9 |
|Skeleton2vec     |arxiv'2024          |     -     | 85.7 | 90.3 | 79.7 | 81.3 | 55.6 |
| | |     -     | | | | | |
| | |     -     | | | | | |
| | |     -     | | | | | |
| | |     -     | | | | | |








