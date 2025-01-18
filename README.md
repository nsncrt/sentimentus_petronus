# Sentimentus Petronus
Réalisé par *Flavian FERRÉ* et *Nathan SAINCOURT*  

Ce projet consiste à développer un modèle de réseau de neurones pour **prédire le sentiment des critiques cinématographiques (positive ou négatives)**. Les critiques peuvent contenir des éléments d'ironie, de tromperie ou d'ambiguïté, ce qui complique leur classification.

## Dataset

Pour ce projet, nous avons utilisés le dataset [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data) disponible sur Kaggle.

## Notre projet

```bash
sentimentus_petronus/
│
├── data/                           # Contains datasets used in the project
│   └── IMDB_dataset/               # Processed dataset
│
├── notebook/                       # Source code files
│   └── sentimentus_petronus.ipynb  # Main notebook of our project
│
├── preview/                        # Static exports of our project
│   └── sentimentus_petronus.html   # HTML export of the notebook
└── README.md                       # This file
```

Le notebook étant très long à s'exécuter en entier, la preview en HTML permet d'avoir une vue d'ensemble des outputs du notebook sans avoir à le réexécuter.