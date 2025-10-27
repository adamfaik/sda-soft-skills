# Compte-rendu : Soft skills session 1 - Créer des présentations impactantes

**Promotion :** SDA 7

**Date :** 22 octobre 2025

**Revoir la session :** [Lien de l'enregistrement](https://pantheonsorbonne.zoom.us/rec/share/hG6pET3l8tUo3v9iMYyAXu36n93C5HhpzP49WfXP5iO86swVCvQ6UAEgAYE6yTM.l4jNge18Vs9u5YGt)

---

## Introduction et objectifs du cours

### 1. Le contexte par Dafnis

La session a débuté par une introduction de Dafnis, expliquant la nécessité de ce nouveau cours.

* **Le constat :** Au fil des années, il a été constaté que les présentations des étudiants ne sont souvent pas à la hauteur du travail technique (code) réalisé.
* **L'objectif :** Ce module de 4 cours vise à vous donner les "soft skills" nécessaires pour réaliser des présentations impactantes, gérer le travail en groupe (notamment en ML et IA) et structurer vos projets (Agile, Scrum).
* **L'importance :** Une présentation qui n'est pas à la hauteur est considérée comme un travail non fait, même si le code est excellent.

### 2. Le problème par Adam

* **Le problème :** De nombreux data scientists, même très avancés, ont du mal à communiquer leurs idées en entreprise.
* **La clé :** Discuter avec un expert technique est différent de discuter avec un preneur de décision.
* **L'objectif du cours :** Trouver la bonne communication adaptée à la personne que l'on vise et à l'objectif que l'on souhaite atteindre.

---

## Module 1 : La boîte à outils du présentateur

Cette section couvre les outils concrets pour créer vos supports de présentation.

### 1. Outils standards (Google Slides, PowerPoint)

* **Utilisez les templates !** Ne partez pas d'une page blanche. L'utilisation d'un template (modèle) vous fait gagner un temps précieux et assure une cohérence visuelle.
* **Slide 1 (titre) :** Doit contenir le nom du projet, la promo (SDA 7), le nom des participants et la date.

### 2. L'agenda : S'adapter à l'audience

Votre plan (l'agenda) ne doit pas refléter *votre* logique de travail, mais **la grille d'évaluation de votre auditoire**.

* **Audience = Professeur (soutenance SDA) :**
    * Demandez au professeur quelle est sa grille d'évaluation.
    * Votre agenda *doit* refléter les points qu'il attend (ex: "MLflow", "Services AWS", "CI/CD GitHub").
    * **Objectif :** Simplifier la vie du correcteur pour qu'il puisse "cocher les cases" de sa grille.

* **Audience = CEO (entreprise) :**
    * Commencez par l'impact business.
    * *Exemple de plan :* 1. ROI > 90%, 2. Coûts < 10k€, 3. Valeur Business.

* **Audience = Équipe technique :**
    * Concentrez-vous sur la robustesse.
    * *Exemple de plan :* 1. Stabilité, 2. Sécurité, 3. Scalabilité.

### 3. Outils de design et diagrammes

* **Inspiration et modèles :**
    * Des sites comme [Slidesgo.com](https://slidesgo.com/) ou [youexec.com](https://youexec.com/) fournissent des templates professionnels.
    * Analysez des [pitch decks de startups](https://slidebean.com/pitch-deck-template) (ex: le pitch d'Uber) pour voir les bonnes pratiques (peu de texte, une idée par slide).
* **Ressources visuelles :**
    * **Icônes :** [Flaticon](https://www.flaticon.com/).
    * **Images :** [Unsplash](https://unsplash.com/).
* **Diagrammes et schémas :**
    * **Fait main :** Un schéma fait main et photographié est très positif, il montre votre réflexion.
    * **Outils pro :** [Draw.io](https://app.diagrams.net/) est un standard en entreprise pour les diagrammes d'architecture.
    * **Outils IA :** [Napkin.ai](https://napkin.ai/) transforme rapidement du texte en schéma visuel.

### 4. Bonnes pratiques pour les captures d'écran (code)

* **Ne faites jamais :** Coller une capture d'écran complète de votre code (ex: VS Code). C'est illisible et n'est pas apprécié.
* **Bonne pratique :**
    1.  Insérez le screenshot.
    2.  Ajoutez un **focus** : un zoom ou un **encadré rouge** sur la partie *importante* du code (ex: la fonction clé, l'import spécifique).
    3.  Ajoutez une note textuelle qui explique *ce que* l'on regarde et *pourquoi* c'est important.

### 5. Outils d'IA (LLM) pour la création

* **[Gamma.app](https://gamma.app/) :**
    * Peut générer une présentation complète à partir d'un simple *prompt* ou d'un texte.
    * **Attention :** C'est rapide, mais l'IA peut "halluciner" ou partir dans une direction non souhaitée.
    * **Meilleure utilisation :** Donnez-lui un plan textuel précis (ex: "Slide 1 : Titre", "Slide 2 : Problème", etc.) qu'il se contente de mettre en forme.
* **L'IA fait-elle gagner du temps ?**
    * Elle réduit le temps de *création*, mais augmente massivement le temps de *vérification* et de *jugement*.
    * Parfois, le temps pour juger un contenu est équivalent au temps pour le produire soi-même.

### 6. ⚠️ Point de sécurité (TRÈS IMPORTANT)

* **Ne mettez JAMAIS de données confidentielles d'entreprise** dans des outils d'IA publics (Gamma, Napkin, etc.).
* Ces outils utilisent vos données pour s'entraîner.
* En entreprise, utilisez **uniquement** les outils validés et autorisés (ex: Copilot, ou Gemini si votre entreprise est sur Google Suite).

---

## Module 2 : L'anatomie d'une slide efficace

* **Règle n°1 : Une slide = Une seule idée.** Simplifiez pour amplifier.
* **Règle n°2 : Pas plus de 3 points clés.** L'audience ne retiendra pas plus.
* **La structure en "Z" :**
    * L'œil humain lit une slide en suivant un "Z".
    * **1. Le titre (Haut) :** Ce doit être votre message principal, votre conclusion.
        * *Mauvais titre :* "Résultats du modèle."
        * *Bon titre :* "Notre modèle de Deep Learning a une accuracy de 93%."
    * **2. Le corps (milieu) :** Les 3 points clés, graphiques ou icônes qui soutiennent votre titre. C'est ce que vous allez développer à l'oral.
    * **3. La conclusion (Bas) :** La transition ou le "Et alors ?".
        * *Exemple :* "J'ai donc décidé d'appliquer un Transfer Learning pour la suite."

---

## Module 3 : Structurer la narration (storytelling)

Une bonne présentation raconte une histoire.

* **Le voyage du héros (Joseph Campbell) :**
    * La structure de tous les grands récits (ex: Harry Potter) s'applique à un pitch.
    * *Monde normal* (Le problème actuel) ➡️ *Appel à l'aventure* (Le défi) ➡️ *Rencontre d'un mentor* (Votre solution) ➡️ *Épreuves* (Le marché, la compétition) ➡️ *Révélation* (Votre produit) ➡️ *Retour transformé* (Le succès).

* **Différences culturelles :**
    * **Style anglo-saxon (US/UK) :** **Résultat d'abord.**
        * *Structure :* 1. Résultat (la conclusion), 2. Explication A, 3. Explication B.
        * *Feedback :* Très poli, souvent indirect ("*c'est une super présentation... peut-être ajuster un hyperparamètre...*").
        * *Attention :* Une petite remarque polie peut cacher un problème majeur.
    * **Style Français :** **Processus d'abord.**
        * *Structure :* 1. Thèse (l'idée de départ), 2. Antithèse (les obstacles, les autres options), 3. Synthèse (le résultat).
        * *Feedback :* Direct, challengeant, confrontationnel ("*Montrez-moi votre VS Code !*").
        * **Important :** Si un prof ou un manager français vous pose des questions déstabilisantes, ce n'est **pas une agression**. C'est une **marque de respect et d'intérêt**.

---

## Module 4 : Le processus de création

**RÈGLE D'OR : NE COMMENCEZ JAMAIS PAR POWERPOINT !**
Commencer par l'outil (PowerPoint) "gèle" votre pensée et vous force à être concis trop tôt.

* **Étape 1 : Le "narratif" (feuille blanche).**
    * Ouvrez un Google Doc (ou autre éditeur de texte).
    * **Pro-tip :** Activez le micro (dictée vocale) et **racontez** votre projet à voix haute. "Au début, j'ai utilisé tel modèle, ça n'a pas marché. J'ai alors débuggé...". Laissez vos pensées couler sans filtre.
* **Étape 2 : Définir le "TOM".**
    * Une fois votre texte brut obtenu, distillez-le en 3 points :
        * **T**hème : Le sujet (ex: "Projet de Machine Learning").
        * **O**bjectif : Ce que vous voulez (ex: "Avoir une très bonne note").
        * **M**essage : L'idée unique que l'audience doit retenir (ex: "J'ai trouvé le modèle qui maximise le problème à résoudre").
    * Ce **Message** devient votre *fil rouge* (fil conducteur) de toute la présentation.
* **Étape 3 : Le plan (avec l'IA).**
    * Donnez votre "Narratif" (étape 1) à Gemini.
    * Demandez-lui : "Structure-moi ce texte en un plan de présentation logique."
    * Itérez sur ce plan jusqu'à ce qu'il soit solide.
* **Étape 4 : Les slides.**
    * *Maintenant seulement*, ouvrez Google Slides.
    * Prenez votre plan (étape 3) et transformez chaque point en une slide, en respectant la structure en "Z" (module 2).

---

## Module 5 : Utiliser les LLM (IA) pour les présentations

L'IA n'est pas un créateur, c'est un **assistant** à différentes étapes.

1.  **Assistant planificateur :** (Cf. module 4) Générer un plan à partir d'un narratif.
2.  **Assistant rédacteur :** Rédiger un premier brouillon.
3.  **Assistant traducteur/simplificateur :**
    * Très utile pour la vulgarisation.
    * *Prompt :* "Explique-moi ce qu'est un cluster AWS avec une analogie simple."
4.  **Assistant coach (feedback) :**
    * Donnez votre plan ou vos slides à l'IA.
    * **Pro-tip :** Évitez les réponses superficielles. L'IA a tendance à vous dire que "votre présentation est excellente".
    * *Prompt :* "Donne-moi un feedback critique sur cette présentation, comme le ferait un **professeur de Machine Learning sévère**."

---

## Module 6 : Études de cas (bons et mauvais exemples)

Nous avons analysé deux présentations réelles.

### Cas 1 : Mauvaise présentation (projet "recommandation de vin")

* **Problèmes identifiés :**
    * **Trop de texte** (généré par Gamma.app).
    * **Monotone :** Visuel "noir et blanc" sans âme pour un sujet convivial (le vin).
    * **Dense / monolithique :** Trop d'informations par slide.
    * **Pas d'agenda !** (Règle de base non respectée).
    * **Pas de transitions :** Sauts brutaux d'un sujet à l'autre (charge cognitive élevée pour l'audience).
    * **Risque de "l'effet démo" :** L'application live peut planter.
    * **Action :** Toujours avoir des screenshots ou une **vidéo** de la démo en backup.

### Cas 2 : Meilleure présentation (projet MLOps)

* **Points positifs :**
    * **Fil d'ariane :** Un "breadcrumb" (ex: 2/5) indique où on en est.
    * **Structure claire :** Sections bien définies.
    * **Simple :** Moins de texte, schémas épurés (un schéma simple vaut mieux qu'un schéma compliqué).
    * **Alignée avec le prof :** Les étapes de la démo (Data Ingestion, DAGs) correspondaient *exactement* aux exigences de l'énoncé (permet au prof de "checker").
    * **Utilisation de l'annexe :** La présentation principale était courte, mais des slides supplémentaires étaient en annexe (screenshots de code, etc.) pour répondre aux questions détaillées *au cas où*.

---

## Module 7 : Conclusion et conseils

* **Votre lien avec les slides : 0%**
    * Les slides ne sont qu'un **support**, un backup.
    * Si vous avez suivi le processus du "Narratif" (Module 4), vous ne *lisez pas* vos slides, vous *racontez votre histoire* (votre "TOM").
    * Si le prof vous dit "Laissez tomber les slides, montrez-moi le code dans VS Code", vous devez être capable de le faire sans perdre le fil.
* **La prise de parole :**
    * Une présentation est un **RDV** (Rendez-vous) : **R**egard, **D**os, **V**oix.
    * Pour la timidité : Il n'y a pas de secret, il faut pratiquer. Envisagez des cours d'art oratoire.
    * La clé est d'être **authentique** ("être soi-même").
* **Le message clé de la session :**
    * Le point le plus important est de **toujours penser à son audience**.
    * Adaptez votre agenda, votre style culturel et votre niveau de détail à la personne qui vous écoute.

---

## Module 8 : 📚 Ressources et lectures complémentaires

* **Livres clés :**
    * **[TED Talks: The Official TED Guide to Public Speaking](https://www.ted.com/read/ted-talks-the-official-ted-guide-to-public-speaking)** par Chris Anderson.
    * **[The Culture Map](https://erinmeyer.com/books/the-culture-map/)** par Erin Meyer (pour les différences culturelles).
    * **[Comment se faire des amis (How to Win Friends and Influence People)](https://en.wikipedia.org/wiki/How_to_Win_Friends_and_Influence_People)** par Dale Carnegie.
    * **[Vendre est humain (To Sell Is Human)](https://www.danpink.com/books/to-sell-is-human/)** par Daniel Pink.

* **Articles, essais et vidéos :**
    * **[La puissance des narratifs écrits d'Amazon](https://www.sachinrekhi.com/colin-bryar-working-backwards)** par Sachin Rekhi (sur le processus "Working Backwards").
    * **[Outils de coaching - Le narratif](https://www.svpg.com/coaching-tools-the-narrative/)** par Marty Cagan (pourquoi écrire avant de slider).
    * **[Comment convaincre les investisseurs](https://www.paulgraham.com/convince.html)** par Paul Graham.
    * **[Rendre votre pitch mémorable grâce au storytelling](https://review.firstround.com/tell-stories-like-this-to-take-your-fundraising-pitch-from-mediocre-to-memorable/)** par First Round Review.
    * **[Qu'est-ce qui fait un héros ?](https://youtu.be/Hhk4N9A0oCA?si=BMb5UvgZ458AoeoG)** par TED-Ed (sur le "voyage du héros").
    * **[Comment écrire un pitch deck de startup percutant ?](https://youtu.be/VapOhmvC8jk?si=Bcgl4Vvjs_9MnnLd)** par Slidebean.

* **Conférences à voir (modèles de prise de parole) :**
    * **[Les écoles tuent-elles la créativité ?](https://youtu.be/iG9CE55wbtY?si=BTNKGw_NvNEDZpsf)** par Sir Ken Robinson.
    * **[Le pouvoir de la vulnérabilité](https://youtu.be/X4Qm9cGRub0?si=AXuKpkfIbtKcI8D_)** par Brené Brown.
    * **[Discours de Steve Jobs à Stanford (2005)](https://youtu.be/UF8uR6Z6KLc?si=Um8XOHGwGSE-BO0Z)**.
    * **[Dans l'esprit d'un maître procrastinateur](https://youtu.be/arj7oStGLkU?si=zE4b6uJ25g20KwnM)** par Tim Urban.