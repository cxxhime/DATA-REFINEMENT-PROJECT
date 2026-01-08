# ☕ Analyse des Ventes de Café - Data Cleaning & Exploration

## 📋 Description

Projet d'analyse de données réalisé dans le cadre de ma formation en **Bachelor Data & IA**. Ce projet démontre un workflow complet de data science : du nettoyage des données brutes à la visualisation des insights business.

**Dataset source :** [Cafe Sales Dirty Data - Kaggle](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

---

## Objectifs du projet

- Nettoyer et préparer des données brutes (gestion des valeurs manquantes, doublons, incohérences)
- Effectuer une analyse exploratoire approfondie (EDA)
- Créer des visualisations professionnelles pour dégager des insights business
- Appliquer les bonnes pratiques de structuration de projet data

---

## Insights clés découverts

### Top Performers
- **Salad** génère le plus de revenus avec un panier moyen élevé (~15€)
- Distribution équilibrée des ventes entre tous les produits (~1100-1150 ventes chacun)

### Analyse financière
- Chiffre d'affaires total analysé sur l'année 2025
- Identification des produits à forte valeur ajoutée
- Analyse de la distribution des montants dépensés par transaction

### Comportement client
- Quantité moyenne achetée : 2-4 unités par transaction
- Système de prix fixes sans promotions
- Stabilité des achats tout au long de l'année

---

## Structure du projet
```
DATA-REFINEMENT-PROJECT/
│
├── data/
│   ├── raw/                          
│   └── processed/                  
│
├── notebooks/
│   ├── 01-Exploration.ipynb         
│   ├── 02-Cleaning.ipynb            
│   └── 03-Transformation.ipynb    
│
├── env_cafe_sales/                   
├── requirements.txt                 
├── .gitignore                        
└── README.md                       
```

---

## Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| **Python 3.13** | Langage principal |
| **Pandas** | Manipulation et analyse de données |
| **NumPy** | Calculs numériques |
| **Matplotlib** | Visualisations de base |
| **Seaborn** | Visualisations statistiques avancées |
| **Jupyter Notebook** | Environnement de développement interactif |

---


## 🔄 Workflow de nettoyage des données

1. **Identification des problèmes**
   - Valeurs manquantes
   - Doublons
   - Incohérences de format
   - Types de données incorrects

2. **Nettoyage & Transformation**
   - Gestion des NaN (suppression ou imputation intelligente)
   - Standardisation des formats de dates
   - Conversion des types de données
   - Validation des données
   - Création de nouvelles features
   - Agrégations et groupements
   - Préparation pour la visualisation


## Licence

Ce projet est à usage éducatif dans le cadre de ma formation.


## Remerciements

- Dataset fourni par [Ahmed Mohamed](https://www.kaggle.com/ahmedmohamed2003) sur Kaggle
- Communauté Kaggle pour les datasets d'entraînement


## Contact

Pour toute question ou suggestion, n'hésitez pas à me contacter !


<div align="center">
  
**⭐ Si ce projet vous a plu, n'hésitez pas à mettre une étoile ! ⭐**

Made with ❤️ and ☕ by Nana

</div>
