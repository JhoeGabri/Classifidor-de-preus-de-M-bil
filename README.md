# Pràctica Kaggle APC UAB 2022-23
### Nom: Jhoe Gabriel Chirinos Sullcany ### DATASET: Mobile Price Classification
### URL: [Mobile Price Classification](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)
## Resum
Hem fet 2 tipus de preprocessats, en un utilitzem el dataset sencer i en l'altre utilitzem només un dataframe que dividim a través de fer un treshold amb la correlació dels atributs.
Totes les dades que tenim són numeriques i tenim un total de 2000 files per 21 columnes.
### Objectius del dataset
Classificar a partir de diferentes atributs les dades en un rang de preus.
## Experiments
Durant aquesta pràctica hem realitzat diferents experiments.
### Model

| Model| Accuracy |
|--|--|
| Regressió Logística | 78.5 |
| KNN | 93.5 |
| Random Forest | 85.75 |
| SVM - Linear | 97 |
| SVM - Polynomial | 96|
| SVM - RBF | 22 |
| SVM - Sigmoid | 18.5 |
| Arbre de decisió | 83 |
| Arbre de decisió - Hiperparamètres | 83 |

## Conclusions
El millor model que s'ha aconseguit ha estat el SVM ammb kernel lineal.
## Idees per treballar en un futur
Crec que seria interesant indagar més en una red neuronal, però com volia treballar amb diferents preprocessats ho deixaré per un futur.
