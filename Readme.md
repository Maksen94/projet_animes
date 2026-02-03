# 📺 Score Éditorial Anime 

## 📝 Présentation du Projet
[cite_start]Ce projet a été réalisé dans le cadre d'une étude de cas pour une plateforme de streaming[cite: 5]. [cite_start]L'objectif est de fournir un outil d'aide à la décision pour les équipes éditoriales afin d'identifier les contenus à forte valeur ajoutée sans attendre les données d'engagement utilisateur[cite: 5, 6].

## 🚀 Problématique & Objectif
* [cite_start]**Problématique** : Les données d'audience mettent plusieurs mois à être significatives[cite: 6]. [cite_start]Comment choisir quels animés mettre en avant dès leur sortie[cite: 5]?
* [cite_start]**Objectif** : Identifier les animés à proposer prioritairement aux utilisateurs grâce à un score de qualité robuste[cite: 8, 9, 10].

## 📊 Méthodologie
Le projet suit une démarche de Data Science structurée :
1.  [cite_start]**Nettoyage des données** : Vérification des valeurs manquantes et traitement des types de données[cite: 13, 14, 15].
2.  **Calculs Statistiques** : 
    * [cite_start]**Écart** : Différence entre la note du meilleur et du pire épisode d'une série[cite: 54, 55].
    * [cite_start]**Régularité** : Calculée par $10 - \text{Écart}$ pour mesurer la constance[cite: 56, 57].
3.  [cite_start]**Calcul du Score Qualité** : Score composite pondéré selon la formule : $(Note\_Globale \times 0.7) + (Regularite \times 0.3)$[cite: 58, 59].
4.  [cite_start]**Segmentation** : Classification du catalogue en segments (Chef-d'œuvre, Valeur Sûre, etc.) pour guider la stratégie de mise en avant[cite: 77, 95].

## 📈 Résultats Clés
* [cite_start]**Validation des Hypothèses** : L'analyse démontre que la note globale seule est insuffisante car elle ne reflète pas la régularité de l'œuvre[cite: 52, 75].
* [cite_start]**Distribution** : Une segmentation claire permettant d'isoler les "Chefs-d'œuvre" (comme *Frieren* ou *Steins;Gate*) pour une mise en avant prioritaire[cite: 112].

## 📁 Contenu du Rendu
* [cite_start]`projet_animes.ipynb` : Notebook Jupyter contenant le code source et l'analyse[cite: 2].
* [cite_start]`animes.csv` : Dataset brut contenant les métadonnées (Studio, Source, Nb épisodes)[cite: 12].

---
[cite_start]**Auteur :** Maksen Benkerrou [cite: 3]