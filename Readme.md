# 📺 Score Éditorial Anime 

## 📝 Présentation du Projet
Ce projet a été réalisé dans le cadre d'une étude de cas pour une plateforme de streaming. L'objectif est de fournir un outil d'aide à la décision pour les équipes éditoriales afin d'identifier les contenus à forte valeur ajoutée sans attendre les données d'engagement utilisateur.

## 🚀 Problématique & Objectif
* **Problématique** : Les données d'audience mettent plusieurs mois à être significatives. Comment choisir quels animés mettre en avant dès leur sortie ?
* **Objectif** : Identifier les animés à proposer prioritairement aux utilisateurs grâce à un score de qualité robuste.

## 📊 Méthodologie
Le projet suit une démarche de Data Science structurée :
1.  **Nettoyage des données** : Vérification des valeurs manquantes et traitement des types de données.
2.  **Calculs Statistiques** : 
    * **Écart** : Différence entre la note du meilleur et du pire épisode d'une série.
    * **Régularité** : Calculée par $10 - \text{Écart}$ pour mesurer la constance.
3.  **Calcul du Score Qualité** : Score composite pondéré selon la formule : $(Note\_Globale \times 0.7) + (Regularite \times 0.3)$.
4.  **Segmentation** : Classification du catalogue en segments (Chef-d'œuvre, Valeur Sûre, etc.) pour guider la stratégie de mise en avant.

## 📈 Résultats Clés
* **Validation des Hypothèses** : L'analyse démontre que la note globale seule est insuffisante car elle ne reflète pas la régularité de l'œuvre.
* **Distribution** : Une segmentation claire permettant d'isoler les "Chefs-d'œuvre" (comme *Frieren* ou *Steins;Gate*) pour une mise en avant prioritaire.

## 📁 Contenu du Rendu
* `projet_animes.ipynb` : Notebook Jupyter contenant le code source et l'analyse.
* `animes.csv` : Dataset brut contenant les métadonnées (Studio, Source, Nb épisodes).

---

**Auteur :** Maksen Benkerrou 
