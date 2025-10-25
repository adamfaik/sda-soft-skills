# Suggestion de Plan Type : Soutenance de Projet

**Important :** Ce plan est une **suggestion de structure** issue des bonnes pratiques professionnelles et académiques. La règle d'or est de **toujours s'adapter aux consignes spécifiques de votre professeur**. Profitez des sessions de suivi pour poser des questions sur les attentes exactes du professeur.

La soutenance de projet est la preuve que votre équipe est capable de transformer un problème business en une solution technique fonctionnelle, en maîtrisant les étapes de la Data Science, du Cloud ou du Machine Learning.

---

## 1. La Règle d'Or : Valoriser la Démarche et la Valeur Business

Le jury attend de voir :
1.  **Le POC (Proof of Concept) :** La solution fonctionne-t-elle ? (Préparez la démo).
2.  **La Data :** Comment avez-vous géré et transformé les données, qui représentent 80% du travail ?
3.  **La Justification :** Pourquoi ce modèle/cette architecture et pas une autre ?

---

## 2. Structure Détaillée de la Présentation (Slide par Slide)

Le plan typique doit répondre aux questions : Quel est le problème ? Comment l'équipe l'a résolu techniquement ? Quel est le résultat business ?

### A. Phase d'Introduction (L'Amorce : 3 Slides)

| Slide N° | Nom de la Slide | Objectifs Clés | Contenu Impératif (Style "Pitch") |
| :--- | :--- | :--- | :--- |
| **S1** | **Titre / Couverture** | Afficher l'identité du projet et de l'équipe. | Titre du Projet. Noms, Prénoms de l'Équipe. Nom du Professeur/Encadrant. Date. |
| **S2** | **"Le Pitch" / Problème Business** | Accrocher immédiatement le jury. Énoncer la douleur. | **Le Problème** (sous forme d'un fait marquant, un chiffre). La perte de temps/d'argent actuelle. Le **Fil Conducteur** du projet. |
| **S3** | **Solution & Objectifs (TOM)** | Présenter la vision et le livrable. | **L'Objectif Métier** (Comment le projet résout le problème). **L'Objectif Technique** (Ce que vous avez réussi à faire/produire : un API, un dashboard, un modèle en production). |

### B. Phase de Démarche (Data & Technique : 5-6 Slides)

C'est là que vous construisez votre crédibilité technique.

| Slide N° | Nom de la Slide | Objectifs Clés | Contenu Impératif |
| :--- | :--- | :--- | :--- |
| **S4** | **Intercalaire "Notre Approche"** | Marquer une transition claire vers le "Comment". | Titre de section simple. |
| **S5** | **Data (Acquisition & Exploration)** | Montrer la gestion des données (le vrai travail). | **Source(s)** de la Data. **Taille** du jeu de données. **Défis** (Valeurs manquantes, Biais, etc.). **EDA** : Un graphique clé qui illustre une variable ou une corrélation importante. |
| **S6** | **Méthodologie & Prétraitement** | Justifier votre préparation de la donnée pour le modèle. | Schéma du flux de *feature engineering* (nettoyage, normalisation, encodage, split Train/Test). Ne pas lister tout le code, mais les **choix critiques**. |
| **S7** | **Architecture & Technologie** | Démontrer votre expertise technologique (Cloud/DevOps). | Schéma de l'architecture (une vue d'ensemble). Indiquer clairement les technos utilisées : **Cloud (AWS/GCP/Azure)**, **Modèle ML choisi** (Random Forest, BERT, etc.). Justification du choix. |
| **S8** | **Itération du Modèle (ML)** | Montrer que vous avez exploré plusieurs pistes. | **Comparaison** de 2 ou 3 modèles testés (ex: Modèle A vs Modèle B vs votre Solution finale). Pourquoi votre solution finale l'a emporté. |

### C. Phase de Validation (Preuve de Concept : 3 Slides)

L'audience veut voir la preuve que ça marche.

| Slide N° | Nom de la Slide | Objectifs Clés | Contenu Impératif |
| :--- | :--- | :--- | :--- |
| **S9** | **Résultats Techniques (Métriques)** | Afficher l'efficacité du modèle. | **Les Métriques Clés** (Accuracy, F1-Score, RMSE, etc.). Indiquer le seuil de performance visé et le score atteint. Utiliser un graphique clair (ex: Matrice de Confusion simplifiée). |
| **S10** | **Démonstration / Impact** | La preuve concrète du livrable. | **Capture d'écran de l'application**, du dashboard, ou du résultat d'API. Si possible : **vidéo de démo** très courte et fluide (max 30 secondes). |
| **S11** | **Bilan Business / ROI** | Traduire la performance technique en valeur métier. | Si l'Accuracy est de 95%, cela représente **X€ économisés** ou **Y heures gagnées**. Le seul chiffre que l'exécutif retiendra. |

### D. Phase de Conclusion & Projet (La Projection : 3 Slides)

| Slide N° | Nom de la Slide | Objectifs Clés | Contenu Impératif |
| :--- | :--- | :--- | :--- |
| **S12** | **Limites du Projet & Défis** | Montrer votre esprit critique et votre lucidité technique. | **Défis Techniques** rencontrés et non résolus. **Contraintes de Données** (ex: Biais, manque de données de temps réel). **Limites du Modèle** (quand échoue-t-il ?). |
| **S13** | **Perspectives & Roadmap** | Ouvrir la discussion vers le futur du projet. | Que feriez-vous si vous aviez 6 mois de plus ? (Ex: Intégration CI/CD, passage à un modèle plus complexe, tests A/B). |
| **S14** | **Conclusion & Remerciements** | Clore formellement et lancer la phase Q/R. | Synthèse de l'apport de l'équipe. Remerciements spécifiques. **GROS : Questions ?** |

---

## 3. Conseils Stratégiques pour la Soutenance

### 1. La Préparation d'Équipe

* **Rôles Clairs :** Définissez qui présente quelle section (Data, Technique, Résultats). Chaque orateur doit avoir un temps de parole bien délimité.
* **Les Intercalaires de Transition :** Utilisez les slides de transition (S4) pour marquer le changement d'orateur et de section, assurant une transition fluide.

### 2. Le Kit de Survie (Annexes)

Préparez des slides d'annexes pour la phase de questions/réponses :

* **Détails du Code :** La ligne de code critique qui gère le prétraitement complexe.
* **Graphiques non-montrés :** Graphiques d'évaluation des performances (Courbes ROC, etc.) ou d'autres visualisations de l'EDA.
* **FAQ :** Anticipez les 3 questions les plus probables du professeur (souvent sur les limites, les hypothèses, ou la justification technique).

### 3. La Gestion du Temps

* **Timing Strict :** Si vous avez 15 minutes, visez 13 minutes de parole pour vous laisser une marge.
* **Entraînement :** Répétez le *timing* de la présentation complète, transition d'orateur incluse, au moins deux fois avant le jour J.