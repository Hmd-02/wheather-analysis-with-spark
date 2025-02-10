# Weather Analysis with Spark

Ce répertoire contient un projet d'analyse de données météorologiques non structurées en utilisant **Apache Spark**. L'objectif principal est d'évaluer l'impact des conditions météorologiques sur l'économie des pays en analysant trois secteurs clés :

- **Secteur de l'énergie** : Étude de l'impact du froid sur la consommation d'électricité.
- **Secteur des transports** : Analyse de l'impact des tempêtes sur le trafic maritime.
- **Secteur de l'agriculture** : Évaluation de l'impact des inondations sur le prix des denrées alimentaires.

## 📂 Structure du projet

```
weather-analysis-with-spark/
│— data/                     # Contient les données brutes et nettoyées
│— notebooks/                # Jupyter notebooks pour l'exploration des données
│— scripts/                  # Scripts Python pour le traitement et l'analyse des données
│   │— analysis.py           # Script principal d'analyse
│— results/                  # Résultats des analyses et visualisations
│— presentation.ppt          # Présentation des résultats
│— requirements.txt          # Liste des dépendances du projet
│— README.md                 # Documentation du projet
│— link.txt                  # Contient les liens vers le dashboard des résultats et les sources de données
```

##  Installation et Configuration

### Prérequis
Avant de commencer, assure-toi d'avoir installé :
- **Python (≥ 3.11)**
- **Apache Spark**
- **Jupyter Notebook**

### Étapes d'installation
1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/Hmd-02/weather-analysis-with-spark.git
   cd weather-analysis-with-spark
   ```
2. **Créer un environnement virtuel (optionnel)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Sur macOS/Linux
   venv\Scripts\activate      # Sur Windows
   ```
3. **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```

##  Utilisation

1. **Exécution de l'analyse**
   ```bash
   python scripts/analysis.py
   ```
2. **Exploration avec Jupyter Notebook**
   ```bash
   jupyter notebook notebooks/exploration.ipynb
   ```
3. **Accès aux résultats**
   - Les résultats et visualisations seront disponibles dans le dossier **results/**.
   - Un dashboard interactif est accessible via le lien fourni dans `link.txt`.

##  Technologies utilisées

- **Apache Spark** : Traitement et analyse de données massives.
- **Pandas / NumPy** : Manipulation des données.
- **Matplotlib / Seaborn** : Visualisation des résultats.
- **Streamlit** : Création du dashboard interactif (optionnel).

##  Méthodologie

1. **Collecte des données** : Extraction et transformation des données météorologiques.
2. **Prétraitement** : Nettoyage, traitement des valeurs manquantes et structuration des données.
3. **Analyse exploratoire** : Étude des tendances et corrélations.
4. **Modélisation et visualisation** : Génération de rapports et dashboards interactifs.

##  Déploiement

### Sur un serveur local
Si tu souhaites exécuter le projet en local, utilise Streamlit pour afficher les résultats :
```bash
streamlit run dashboard.py
```

---


