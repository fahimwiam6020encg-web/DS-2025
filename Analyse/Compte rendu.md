# Student Stress Analysis 

# Rapport d’analyse : Facteurs de Stress chez les Étudiants

## 1. Introduction

Le stress étudiant constitue aujourd’hui une problématique centrale dans les systèmes éducatifs modernes. Face à la pression académique, aux exigences sociales, aux difficultés financières et aux changements émotionnels, les étudiants sont régulièrement confrontés à une multitude de facteurs pouvant affecter leur santé mentale, leur performance académique et leur bien-être général. Analyser ces facteurs n’est donc pas seulement un exercice statistique, mais une étape essentielle pour comprendre l’environnement éducatif contemporain et proposer des actions visant à réduire la vulnérabilité psychologique des apprenants.

Le présent rapport propose une analyse détaillée du fichier Student Stress Factors.csv, qui regroupe plusieurs variables quantitatives liées aux sources de stress :

Stress académique

Charge de travail

Manque de sommeil

Anxiété

Pression familiale

Dépendance à la technologie

Soutien social

Performances académiques

Comportements compensatoires (nutrition, repos, activité physique)

L’objectif principal est de comprendre les relations entre ces variables, d’identifier les facteurs les plus influents, et d’offrir une lecture claire et scientifique du phénomène de stress chez les étudiants.
---

## 2. Description du jeu de données

Le fichier contient plusieurs variables évaluées sur une échelle numérique (souvent 1 à 5). Les colonnes principales sont :
- Qualité du sommeil 😴
- Fréquence des maux de tête 🤕
- Performance académique 👩‍🎓
- Charge de travail
- Activités extracurriculaires 🎾
- Niveau de stress ressenti

Toutes les variables sont numériques, facilitant l’analyse statistique et les corrélations.

---

## 3. Méthodologie et traitement des données (notebook)

1. Importation des bibliothèques
2. Chargement du CSV
3. Nettoyage et typage
4. Vérification des valeurs manquantes
5. Exploration (EDA)
6. Visualisations (barplots, heatmap)
7. Interprétation des relations entre variables

---

## 4. Résultats et analyses détaillées

### 4.1 Qualité du sommeil
Les étudiants dorment majoritairement assez mal (2–3/5).  
➡ Une mauvaise qualité de sommeil augmente fortement le stress.

### 4.2 Fréquence des maux de tête
1 à 3 fois/semaine pour la majorité.  
➡ Indicateur physique fort d’un stress élevé.

### 4.3 Performance académique
Scores moyens (2–4).  
➡ Les étudiants stressés ont une perception négative de leurs performances.

### 4.4 Charge de travail
Très corrélée au stress.  
➡ Plus la charge augmente, plus le stress monte.

### 4.5 Activités extracurriculaires
Plus les activités augmentent, plus le stress diminue.  
➡ Facteur protecteur important.

### 4.6 Corrélation (heatmap)
Relations principales :
- Sommeil ↓ → Stress ↑  
- Maux de tête ↑ → Stress ↑  
- Études ↑ → Stress ↑  
- Activités ↑ → Stress ↓  
- Performance ↑ → Stress ↓  

---


### 5.Facteurs protecteurs
- Activité physique
- Soutien social
- Gestion du temps
- Organisation des études

---

## 6. Recommandations

### Pour les étudiants
- Meilleure hygiène du sommeil  
- Activité physique régulière  
- Gestion du temps  
- Réduction du café et des écrans tardifs  

### Pour les établissements
- Diminuer la surcharge académique  
- Ateliers de gestion du stress  
- Soutien psychologique  
- Encouragement aux activités parascolaires  

---

## 7. Conclusion

Le stress étudiant résulte de plusieurs facteurs combinés : sommeil inadéquat, surcharge académique, symptômes physiques, faible performance perçue ou absence d’activités physiques.  
Une intervention multidimensionnelle (étudiants + établissements) est essentielle pour réduire les effets du stress et améliorer le bien-être général.

