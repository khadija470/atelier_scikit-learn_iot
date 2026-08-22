# Atelier Scikit-learn — Prédiction de l'état d'un capteur IoT

Classification (KNN) de l'état d'un capteur (OK / ALERTE / ERREUR)
à partir de la température, l'humidité, la pression et la consommation.

## Structure
- `data/mesures_capteurs.csv` — jeu de données
- `notebooks/atelier_scikit-learn_iot.ipynb` — atelier complet (Parties 0 à 10)
- `models/modele_capteur.joblib` et `models/modele_capteur.pkl` — modèle sauvegardé

## Lancer
```bash
pip install scikit-learn pandas seaborn matplotlib joblib
jupyter notebook notebooks/atelier_scikit-learn_iot.ipynb
```
