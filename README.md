# Projet preuve de concept 🐟

Ce dépôt contient les fichiers de mon projet pour étudier et expérimenter avec le modèle de segmentation SAM. Le modèle SAM est un modèle qui vient d'être publié (voir [1]) par des chercheurs de Meta AI. C'est un modèle de segmentation d'image interactif : il suffit d'un clic de l'utilisateur pour sélectionner un objet sur une image.

Pour ce projet, j'ai étudié l'article [1]. Pour cela, j'ai dû me contextualiser dans le domaine de la segmentation d'image avec des réseaux de neurones. Ensuite j'ai cherché un ensemble de données différentes à celles évaluées dans l'article (voir [2]), et sur lesquelles j'ai appliqué l'algorithme. Pour évaluer les performances, j'ai cherché et expérimenté avec un modèle précédent comme baseline.

Les fichiers principaux sont: 

1. `plan_de_travail.md` : Le plan prévisionnel de travail fait au début du projet.
2. `segmentation_experience.ipynb` : Le code pour ce projet.
3. `rapport.pdf` : Le rapport écrit pour ce projet.
4. `slides.pdf` (à venir) : slides pour soutenance du projet.


## Notebooks
Partie du code des examples suivants ont été utilisé dans le code de ce projet:

* [Using SAM with prompts](https://github.com/facebookresearch/segment-anything/blob/main/notebooks/predictor_example.ipynb)

* [Automatically generating masks](https://github.com/facebookresearch/segment-anything/blob/main/notebooks/automatic_mask_generator_example.ipynb)

## Références

[1] Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., ... & Girshick, R. (2023). Segment anything. arXiv preprint [arXiv:2304.02643](https://arxiv.org/abs/2304.02643).

[2] [A Large Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset)