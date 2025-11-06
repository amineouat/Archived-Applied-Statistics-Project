# Projet d’Exploration de Données : Observations d’Oiseaux en Martinique (2012–2025)
Par: CHABANE Oualid, KERMADJ Zineddine et OUATMANI Amine

## Objectif du projet

Ce projet s’inscrit dans le cadre du cours de statistiques appliquées et a pour objectif de réaliser une analyse exploratoire et statistique d’un jeu de données regroupant des observations d’oiseaux en Martinique entre 2012 et 2025.  
L’étude vise à mieux comprendre la distribution des espèces, leurs dynamiques temporelles, ainsi que certains indicateurs biologiques et écologiques à partir des données disponibles.

---

## Contenu du dépôt

| Fichier / Dossier | Description |
|-------------------|-------------|
| `data_exploration.ipynb` | Notebook Jupyter contenant l’intégralité de l’analyse exploratoire et statistique. |
| `final_project_assignment.pdf` | Énoncé du projet précisant les objectifs et les critères d’évaluation. |
| `data/` | Jeu de données utilisé pour l’analyse (observations d’oiseaux). |
| `output/` | L'ensemble des figures trouvées durant l'analyse. |
| `README.md` | Ce document descriptif. |

---

## Structure du notebook

Le notebook `data_exploration.ipynb` est organisé en quatre grandes parties :

### 1. Chargement et préparation des données
- Importation du jeu de données d’observations d’oiseaux collectées en Martinique entre 2012 et 2025.  
- Vérification et correction des valeurs manquantes ou incohérentes.  
- Conversion des formats de date, harmonisation des noms d’espèces et préparation des variables pour l’analyse.

### 1.bis. Analyse exploratoire et indicateurs statistiques
- Étude descriptive des principales variables (espèce, date, lieu, nombre d’individus observés, etc.).  
- Visualisations : distributions, comparaisons temporelles et spatiales, corrélations entre variables.  
- Déduction de relations. 

### 2. Indicateurs biologiques 
- Calcul d’indicateurs biologiques (richesse spécifique, abondance moyenne, etc.).  
- Estimation d’intervalles de confiance et exploration de la variabilité interannuelle.

### 3. Suivi d’espèces et discussion écologique
- Focus sur certaines espèces remarquables ou indicatrices.  
- Suivi de leur évolution temporelle et spatiale à partir des données.  
- Discussion écologique sur les tendances observées : variations saisonnières, influence de l’habitat, pressions anthropiques, etc.

### 4. Synthèse et conclusion
- Résumé des principaux résultats obtenus.  
- Interprétation écologique et mise en perspective des tendances.  
- Pistes de prolongement : affinement du suivi, modélisation ou intégration de données environnementales complémentaires.

---