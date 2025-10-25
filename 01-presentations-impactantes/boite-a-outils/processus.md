# Le Processus de Création : De la Page Blanche à la Présentation

Ce document décrit le workflow complet pour créer une présentation impactante, en se concentrant sur la clarté de la pensée *avant* le design de l'outil.

---

## La Règle d'Or : Ne Commencez Jamais par PowerPoint !

La règle la plus importante est de **ne pas commencer par un PowerPoint** (ou Google Slides).

Commencer directement par l'outil "gèle" votre pensée. Les slides sont un format très restreint qui vous force à être concis avant même d'avoir structuré votre idée.

## Étape 1 : Le "Narratif" (La Feuille Blanche)

*Le but : Vider votre cerveau et clarifier votre pensée.*

1.  **Ouvrez un document texte** (Google Doc, Word, Notion, etc.).
2.  **Racontez votre projet** du début à la fin. Écrivez tout ce qui vous passe par la tête : les difficultés, les succès, les étapes techniques.
3.  **Pro-Tip (Dictée Vocale) :** Activez le micro de votre ordinateur ou téléphone et **parlez** de votre projet à voix haute. C'est souvent plus naturel et plus fluide que d'écrire. Vous obtiendrez un long texte brut, ce qui est parfait.

## Étape 2 : Le "TOM" (Clarifier le Fil Rouge)

*Le but : Distiller votre narratif en un message unique.*

Une fois que vous avez votre texte brut (Étape 1), analysez-le pour trouver votre "TOM" :

* **T (Thème) :** Quel est le sujet global ? (ex: "Projet de Deep Learning sur la classification d'images").
* **O (Objectif) :** Quel est votre but ? (ex: "Avoir une très bonne note", "Convaincre le CEO de financer le projet").
* **M (Message) :** Quelle est LA SEULE chose que l'audience doit retenir ? (ex: "J'ai trouvé le modèle qui maximise l'accuracy pour ce problème").

Ce **Message (M)** devient votre "fil rouge". Chaque slide de votre présentation devra, d'une manière ou d'une autre, soutenir ce message.

## Étape 3 : Le Plan (Adapté à l'Audience)

*Le but : Structurer votre histoire pour la personne qui vous écoute.*

C'est une étape cruciale. Votre plan (l'agenda) ne doit pas suivre votre logique de travail, mais **la "grille d'évaluation" de votre auditoire**.

Demandez-vous toujours : "Qui est mon audience ?"

* **Audience = Professeur (Soutenance)**
    * **Objectif :** Simplifier sa correction.
    * **Action :** Demandez-lui sa grille d'évaluation ou basez-vous sur l'énoncé.
    * **Plan type :** Doit refléter les attendus (ex: "1. Déploiement MLflow", "2. Infrastructure AWS", "3. CI/CD GitHub").

* **Audience = CEO (Business)**
    * **Objectif :** Démontrer la valeur.
    * **Plan type :** Commencez par le ROI, les coûts, la valeur business, la concurrence.

* **Audience = Équipe Technique**
    * **Objectif :** Démontrer la robustesse.
    * **Plan type :** Concentrez-vous sur la stabilité, la sécurité, l'architecture, la scalabilité.

## Étape 4 : La Création des Slides (L'Outil)

*Le but : Mettre en forme votre plan de manière visuelle.*

*Maintenant seulement*, vous pouvez ouvrir Google Slides ou PowerPoint.

1.  **Utilisez un template** pour gagner du temps et assurer une cohérence visuelle.
2.  Créez une slide pour chaque point de votre plan (Étape 3).
3.  Pour chaque slide, appliquez les bonnes pratiques (voir le fichier `aide-memoire.md`) :
    * 1 slide = 1 idée
    * Le titre est la conclusion
    * Structure en "Z"
    * Bonnes pratiques pour les screenshots de code

## Étape 5 : Le Feedback et l'Itération

*Le but : Améliorer votre présentation avant le jour J.*

Votre premier jet (draft) n'est jamais parfait.

1.  **Auto-Feedback (Outil Coach) :** Uploadez votre PDF sur le **Gemini Coach IA** pour obtenir un feedback automatisé slide par slide.
2.  **Feedback IA (Prompts) :** Utilisez des prompts spécifiques comme "Agis comme un professeur de ML sévère et critique mon plan" pour obtenir un retour plus direct.
3.  **Feedback Humain :** Envoyez votre présentation à vos pairs ou à votre instructeur pour une relecture.