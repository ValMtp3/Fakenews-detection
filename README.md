# Détection de Fake News

Ce projet propose une pipeline de détection de fake news à partir de données textuelles. Il utilise des techniques de machine learning pour classifier des articles comme vrais ou faux.

## Structure du projet

- `fake_news_detection_pipeline.ipynb` : Notebook principal contenant l'analyse, le prétraitement, l'entraînement et l'évaluation du modèle.
- `archive/Fake.csv` : Articles de presse considérés comme fake news.
- `archive/True.csv` : Articles de presse considérés comme vrais.

## Prérequis

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- gradio

## Installation

Installez les dépendances du projet :

```bash
pip install -r requirements.txt
```

## Lancer le notebook Jupyter

Pour explorer et exécuter le pipeline :

```bash
pip install jupyter
jupyter notebook
```

Ouvrez ensuite le fichier `fake_news_detection_pipeline.ipynb` dans l'interface Jupyter.

## Jeux de données

Les fichiers `Fake.csv` et `True.csv` contiennent des articles de presse respectivement faux et vrais. Ils sont utilisés pour entraîner et évaluer le modèle de détection.

## Licence

Ce projet est proposé à des fins éducatives. Merci de citer la source si vous réutilisez ce travail.
