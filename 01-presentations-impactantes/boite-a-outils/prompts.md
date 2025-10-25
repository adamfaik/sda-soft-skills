# Prompts pour créer vos présentations de projet

Ce guide rassemble des prompts-clés à utiliser avec des outils comme Gemini pour vous assister à chaque étape de la création de votre présentation, de la page blanche au feedback final.

---

## Étape 1 : Le "Narratif" (Commencer et Clarifier)

*Avant d'ouvrir PowerPoint, clarifiez votre pensée.*

### Pour démarrer (si vous êtes bloqué)

> "Je dois commencer à rédiger le narratif pour ma présentation de projet sur [mon modèle de prédiction de churn]. Pose-moi 5 questions clés sur mon projet (le problème, les données, le modèle, les résultats, l'impact) pour m'aider à structurer ma pensée et à ne rien oublier."

### Pour structurer une transcription (après dictée vocale)

> "Voici la transcription brute de mes pensées sur mon projet [d'analyse de sentiments]. Nettoie ce texte, corrige les fautes, supprime les hésitations et organise-le en un narratif cohérent qui explique le projet du début à la fin."

### Pour extraire d'un document technique (ex: `README.md`)

> "Analyse ce document (ex: `README.md` ou notebook Python) et extrais-en un résumé narratif de 300 mots qui explique le projet à un public non-technique.
> 
> [Coller le contenu du `README.md` ou du Notebook]"

---

## Étape 2 : Structuration et plan

*Transformer votre narratif en un squelette de présentation.*

### Pour définir le "TOM" (Thème, Objectif, Message)

> "Analyse le narratif suivant : [Coller votre narratif de l'étape 1].
> 
> Identifie les 3 points suivants :
> 1.  **Thème (T) :** Le sujet principal.
> 2.  **Objectif (O) :** Ce que je veux que l'audience fasse ou pense.
> 3.  **Message (M) :** Le message unique que l'audience doit retenir.
> 
> Propose ensuite un titre percutant pour la présentation basé sur ce message."

### Pour créer un plan (basé sur un document)

> "Je dois créer une présentation de 15 minutes (environ 10 slides) à partir de ce document. Propose-moi un plan de présentation (un agenda) logique.
> 
> [Coller le narratif ou le `README.md`]"

### Pour adapter le plan à l'audience

> "Je dois présenter mon projet [de pipeline MLOps] à différents auditoires.
> 
> Génère 3 plans de présentation (agendas) distincts pour :
> 1.  **Mon professeur (soutenance SDA) :** L'audience est technique et note la rigueur, l'utilisation de [MLflow, AWS, CI/CD] et la méthodologie.
> 2.  **Un CEO (Public Business) :** L'audience se soucie du ROI, du coût, de la valeur business et de l'impact sur les utilisateurs.
> 3.  **Une équipe de data scientists (public expert) :** L'audience s'intéresse aux choix techniques, à l'architecture du modèle, aux hyperparamètres et aux métriques de performance."

---

## Étape 3 : Création de contenu (slide par slide)

*Rédiger le contenu de chaque slide.*

### Pour rédiger le contenu d'une slide

> "Rédige le contenu pour une slide intitulée : 'Problème : Le défi de la détection de fraude en temps réel'.
> 
> * L'audience est [non-technique / business].
> * Utilise 3 points clés maximum.
> * Reste concis et évite le jargon."

### Pour simplifier un concept technique (vulgarisation)

> "Explique-moi ce qu'est [un Random Forest / un pipeline CI/CD / le data leakage] avec une analogie simple et visuelle qu'un public non-technique (manager, client) peut comprendre."

### Pour trouver un titre de slide percutant (structure "Z")

> "Voici le contenu de ma slide :
> 
> * Modèle de base (Régression Logistique) : Accuracy = 72%
> * Modèle optimisé (XGBoost) : Accuracy = 91%
> * Le modèle XGBoost a réduit les faux positifs de 40%.
> 
> Propose-moi 5 options de titres percutants pour cette slide, qui suivent la règle de 'la conclusion d'abord' (comme 'Notre modèle a atteint 93% de précision')."

### Pour décrire un visuel (diagramme/schéma)

> "Je dois présenter l'architecture de mon pipeline de données : [Ingestion depuis Kafka -> Traitement avec Spark -> Stockage sur S3 -> Entraînement du modèle sur SageMaker].
> 
> 1.  Décris-moi le schéma visuel idéal pour cette slide.
> 2.  (Optionnel) Génère le code [Mermaid ou HTML] pour ce diagramme."

---

## Étape 4 : Feedback et amélioration

*Utiliser l'IA comme un coach pour critiquer votre travail.*

### Pour un feedback critique (Le "Prof Sévère")

> "Je vais te donner le plan et le script de ma présentation. Agis comme un [**professeur de Machine Learning sévère** / **investisseur sceptique**].
> 
> Donne-moi un feedback critique et direct. Ne te contente pas de me dire ce qui est bien. Dis-moi précisément ce qui est faible, manque de clarté, ou quelles sont les faiblesses méthodologiques de mon projet."

### Pour vérifier la clarté et le jargon

> "Analyse le texte suivant (destiné à une slide) et identifie tout jargon technique. Propose une version plus simple et plus directe, sans perdre le sens.
> 
> [Coller le texte de la slide, ex: 'Nous avons implémenté une architecture RAG avec un embedding bi-directionnel pour optimiser la retrieval des documents...']"

### Pour vérifier la cohérence du "message" (TOM)

> "Voici l'intégralité de ma présentation (texte slide par slide). Mon **Message principal (M)** est : [Coller votre message, ex: 'Ce projet prouve que l'IA peut réduire nos coûts de support de 30%'].
> 
> 1.  Est-ce que chaque slide soutient ce message ?
> 2.  Laquelle est la plus faible ou hors-sujet ?
> 3.  L'ordre des slides est-il logique pour raconter cette histoire ?"

---

## Étape 5 : Préparation à l'oral

*Finaliser les slides et se préparer à parler.*

### Pour générer des notes d'orateur

> "Voici le contenu de ma slide (3 puces) :
> 
> * [Puce 1]
> * [Puce 2]
> * [Puce 3]
> 
> Rédige-moi des **notes d'orateur (speaker notes)**. Elles ne doivent pas répéter les puces, mais plutôt :
> 1.  Raconter une courte histoire ou donner du contexte.
> 2.  Expliquer le 'pourquoi' derrière ces points.
> 3.  Assurer une transition fluide vers la slide suivante."

### Pour anticiper les questions (Q&A)

> "Je présente mon projet [de classification d'images] à [un public technique / mon professeur].
> 
> Quelles sont les 5 questions les plus difficiles, pièges ou pointues qu'ils pourraient me poser ?
> 
> (ex: 'Avez-vous vérifié le data leakage ?', 'Pourquoi ce choix d'hyperparamètres ?', 'Quelle est la performance de votre baseline ?', 'Avez-vous géré le déséquilibre de classe ?').
> 
> Pour chaque question, aide-moi à préparer une réponse claire et concise."

### Pour créer des transitions fluides

> "J'ai une slide sur [les résultats de l'accuracy du modèle (91%)] et la slide suivante est [le déploiement du modèle via une API sur AWS].
> 
> Rédige 2-3 options de phrases de transition naturelles et logiques pour passer de l'une à l'autre."