# Plan de travail projet preuve de concept 

[Ana Bernal, avril 2023]

La segmentation d'image est la classification de parties d'une image dans des groupes différents. Pour ce projet je vais étudier un article **[1]** très récent par des chercheurs de [Meta AI](https://ai.facebook.com/) (facebook). Dans cet article les auteurs proposent un modèle de segmentation d'image interactif très prometteur.

## Plan prévisionnel

0. Bref étude des définitions et état de l'art en segmentation d'image. En utilisant l'article **[2]** et l'article de blog **[3]**.
   
1. Lecture de l'article principal **[1]**, et article de blog correspondant **[4]**.
   
2. Application du modèle (SAM) de l'article principal **[1]** aux images de chiens du [Stanford dog dataset](vision.stanford.edu/aditya86/ImageNetDogs/).
   
3. Évaluation des performances sur ce dataset en utilisant :
    * **Baseline:** modèle RITM **[5]** ([lien github](https://github.com/SamsungLabs/ritm_interactive_segmentation))
    * **Métriques:** Basés sur le point 0. Décider quelle métrique est approprié pour comparer les performances. Une première piste est **mIoU** mean intersection-over-union.

## Références 

Ci dessous les articles dont je vais me servir 

|   |Type de référence | Titre et lien | Date de publication |
|---|---|---|---|
|**[1]**| article de recherche | [Segment Anything](https://arxiv.org/abs/2304.02643) | 05-04-2023 |
|**[2]**| article de recherche | [Image Segmentation Using Deep Learning: A Survey](https://arxiv.org/abs/2001.05566) | 2021 | 
|**[3]**| article de blog | [Introduction to Image Segmentation with K-Means clustering](https://www.kdnuggets.com/2**019**/08/introduction-image-segmentation-k-means-clustering.html) | 09-08-2019 | 
|**[4]**| article de blog |[Introducing Segment Anything: Working toward the first foundation model for image s**egm**entation](https://ai.facebook.com/blog/segment-anything-foundation-model-image-segmentation/) | 05-04-2023 | 
|**[5]**| article de recherche| [Reviving Iterative Training with Mask Guidance for Interactive Segmentation](https://arxiv.org/abs/2102.06583) | 12-02-2021 | 
## Citations (articles)

**[1]** Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., ... & Girshick, R. (2023). Segment anything. arXiv preprint arXiv:2304.02643.

**[2]** Minaee, S., Boykov, Y., Porikli, F., Plaza, A., Kehtarnavaz, N., & Terzopoulos, D. (2021). Image segmentation using deep learning: A survey. IEEE transactions on pattern analysis and machine intelligence, 44(7), 3523-3542.

**[5]** Sofiiuk, K., Petrov, I. A., & Konushin, A. (2022, October). Reviving iterative training with mask guidance for interactive segmentation. In 2022 IEEE International Conference on Image Processing (ICIP) (pp. 3141-3145). IEEE.
