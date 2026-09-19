#  Inventaire des données de séquençage liées à CDH2 — Cancer de la prostate

Projet interdisciplinaire — Université de Strasbourg 2025-2026  
**Dimitrina Ivanova & Faten Tinzaghti** — Encadré par Bruno Kieffer

##  Description
Pipeline bioinformatique automatisé pour l'inventaire et l'annotation 
des données ChIP-seq liées à CDH2, en intégrant collecte GEO, 
enrichissement PubMed et recherche sémantique.

##  Contenu du dépôt
- `Projet_interdisciplinaireDimitrina.ipynb` — Pipeline complet de collecte et structuration des données
- `keyword_fixed.ipynb` — Outil de recherche sémantique
- `Research_Database.xlsx` — Base de données finale
- `search_results.xlsx` — Exemple de résultats de recherche

##  Installation
pip install biopython pandas openpyxl keybert sentence-transformers scikit-learn

##  Utilisation
1. Télécharger tous les fichiers dans le même dossier
2. Ouvrir `keyword_fixed.ipynb`
3. Suivre les instructions dans le notebook
4. Lancer la cellule RELOAD puis entrer votre requête

##  Technologies utilisées
- Python, Jupyter Notebook
- Biopython (API NCBI Entrez)
- KeyBERT, spaCy (NLP)
- SentenceTransformers (recherche sémantique)
- pandas, openpyxl
