# Atelier : Google Slides pas à pas

**⏱️ Durée estimée :** 30 minutes

**🎯 Objectifs :**
* Créer les fondations d'une présentation de projet data/ML sur Google Slides en appliquant un template.
* Construire ensemble les slides essentielles : Titre, Agenda (adapté à l'audience), une slide de contenu (structure en Z), une slide de screenshot (bonnes pratiques).
* Intégrer les bonnes pratiques : adaptation à l'audience (prof vs. pro, cultures), clarté des screenshots, nécessité des backups (vidéo), rôle des annexes.
* Introduire l'utilisation de ressources visuelles (Unsplash, Flaticon) et la prise de captures d'écran.
* Renforcer le réflexe de clarifier les attentes spécifiques de chaque professeur.

**🛠️ Matériel requis :**
* **Formateur :**
    * Accès à Google Drive / Google Slides.
    * Exemple de support de projet (ex: Notebook Kaggle sur un projet Deep Learning de classification d'images).
    * Énoncé du projet (si disponible).
    * Liens prêts vers [Unsplash](https://unsplash.com/) et [Flaticon](https://www.flaticon.com/).
* **Participants :**
    * Accès à leur propre Google Drive / Google Slides.

**⚙️ Préparation (avant l'atelier) :**
* Le formateur s'assure que les participants peuvent accéder à Google Slides.
* Le formateur a les liens et l'exemple de projet prêts à être montrés/utilisés.

**🚀 Déroulement (pas à pas) :**

1.  **[2 min] Introduction par le formateur :**
    * "Passons maintenant à la pratique ! L'objectif est de construire ensemble le squelette d'une présentation de projet sur Google Slides."
    * "Nous allons utiliser un exemple simple : un projet de Deep Learning pour classifier des images. Je vais vous guider pas à pas, et je vous invite à faire la même chose sur votre propre Drive."
    * "Pourquoi Google Slides ? C'est simple, collaboratif et rapide, idéal quand le temps manque avant une soutenance".

2.  **[3 min] Créer la présentation et appliquer un template (tous) :**
    * **Guide formateur :** "Allez sur votre Google Drive. Cliquez sur 'Nouveau' > 'Google Slides'. Une présentation vide s'ouvre."
    * "Sur la droite, Google vous propose des 'Thèmes' (templates). Choisissez-en un qui vous plaît et qui semble professionnel. Pourquoi utiliser un template ? Ça vous fait gagner un temps fou et assure une cohérence visuelle".
    * *Le formateur fait la manipulation en partageant son écran.*

3.  **[3 min] Slide 1 : Le titre (tous) :**
    * **Guide formateur :** "Sur la première slide, mettez les informations essentielles :
        * Le **titre** clair de votre projet (ex: 'Classification d'Images Deep Learning').
        * Vos **noms et prénoms** (important pour le prof).
        * La **date** de la soutenance.
        * (Optionnel mais recommandé) Le nom du professeur/cours/DU (SDA)."
    * *Le formateur remplit sa slide Titre.*

4.  **[6 min] Slide 2 : L'agenda et l'adaptation à l'audience (formateur + discussion) :**
    * **Guide formateur :** "Ajoutez une nouvelle slide (Ctrl+M ou Cmd+M). C'est notre agenda (ou sommaire)."
    * **Discussion clé (formateur) :** "C'est LA slide la plus stratégique. Votre plan dépend TOTALEMENT de votre audience."
        * **Contexte SDA vs. Pro :** "Pour votre soutenance SDA, votre audience principale est le professeur. Son but ? Vérifier que vous avez appliqué les concepts du cours et respecté l'énoncé. Votre plan doit refléter ça". "Pour un CEO, vous commenceriez par le ROI". "Pour un CTO, par la scalabilité".
        * **Attentes variables des profs :** "Certains profs veulent le résultat final tout de suite. D'autres veulent voir le détail de chaque outil (ex: MLflow, AWS, GitHub Actions)". "D'autres encore veulent une approche 'business case'". **Leçon : POSEZ LA QUESTION ! Profitez des suivis pour demander : 'Quel plan préférez-vous pour la soutenance ?'"**.
        * **Timing SDA :** "Typiquement, une soutenance SDA c'est 15 min de présentation + 5 min de questions. Votre agenda doit tenir dans ce temps".
    * *Le formateur écrit un exemple d'agenda adapté au projet DL et aux attentes *supposées* d'un prof SDA (ex: 1. Problème, 2. Données, 3. Modèle, 4. Résultats, 5. Démo).*

5.  **[4 min] Slide 3 : La structure d'une slide de contenu (formateur + tous) :**
    * **Guide formateur :** "Nouvelle slide. Imaginons qu'on présente notre modèle."
    * **Explication (formateur) :** "Rappelez-vous la lecture en 'Z'.
        * **Le titre :** Doit être la conclusion de la slide (ex: 'Notre CNN atteint 92% d'Accuracy').
        * **Le corps :** 2-3 points max pour supporter le titre (ex: Architecture du CNN, Métrique clé, Comparaison baseline). On peut utiliser des icônes de [Flaticon](https://www.flaticon.com/) ou des images d'[Unsplash](https://unsplash.com/) pour illustrer (Montrer rapidement comment insérer une image)."
        * **Le bas (optionnel) :** Une phrase de transition vers la slide suivante."
    * *Le formateur esquisse cette structure sur la slide.*

6.  **[5 min] Slide 4 : Les captures d'écran efficaces (formateur + tous) :**
    * **Guide formateur :** "Nouvelle slide. Très important pour vos projets techniques : montrer du code ou des résultats."
    * **Explication (formateur) :** "Le piège : coller un screenshot complet de votre notebook ou de VS Code. C'est illisible et inutile".
    * **Démonstration (formateur) :**
        1.  Montrer comment prendre une capture d'écran (outil système ou dédié).
        2.  Insérer la capture dans Google Slides.
        3.  **LA CLÉ : Ajouter un focus.** Utiliser les formes de Google Slides (rectangle rouge transparent) pour encadrer LA ligne de code ou LE chiffre important.
        4.  Ajouter une zone de texte à côté pour expliquer ce qu'on regarde et pourquoi c'est pertinent.
    * *Les participants essaient d'insérer une image (n'importe laquelle) et d'ajouter une forme dessus.*

7.  **[5 min] Slide 5 : Intégrer des diagrammes (formateur + discussion) :**
    * **Guide formateur :** "Nouvelle slide. Pour illustrer une architecture (Cloud, MLOps) ou un processus (flux de données), un diagramme est souvent indispensable."
    * **Explication (formateur) :** "Plusieurs options s'offrent à vous :"
        * **Option 1 : Fait main (très valorisant !) :** "N'hésitez pas à faire un schéma clair sur papier, à le prendre en photo et à l'insérer. Ça montre votre réflexion". "C'est souvent plus rapide et très bien perçu".
        * **Option 2 : Outils dédiés :** "Si vous avez besoin de quelque chose de plus formel, utilisez des outils comme [Draw.io](https://app.diagrams.net/) (gratuit, standard pro)" "ou d'autres outils comme Figma/FigJam mentionnés avant". "L'important est la clarté, pas la complexité de l'outil."
        * **Option 3 (Astuce IA) :** "Si vous avez fait un schéma à la main propre, vous pouvez même demander à Gemini de le 'coder en HTML' ou de le redessiner pour un rendu plus net" (Montrer rapidement un exemple si le temps le permet).
    * *Le formateur montre un exemple de diagramme (fait main photographié ou issu d'un outil).*

8.  **[3 min] Bonnes pratiques additionnelles (formateur) :**
    * **Le backup indispensable :** "Pour la démo de votre application/dashboard : préparez **toujours** des screenshots de chaque étape ET, idéalement, enregistrez une **vidéo courte** de la démo qui fonctionne. L'effet démo (quand ça plante le jour J) arrive toujours !".
    * **Les annexes : Votre filet de sécurité :** "Préparez des slides après votre conclusion (que vous ne montrerez pas) avec les détails techniques (code, formules, résultats secondaires). Si le prof pose une question pointue, vous pourrez switcher sur l'annexe correspondante. C'est très professionnel".

**💡 Points clés à retenir / Sébrief :**
* "Google Slides + template = rapidité et cohérence."
* "L'agenda est dicté par l'audience (le prof !). Demandez-lui ses attentes."
* "Structure en Z : Titre = Conclusion."
* "Screenshots : Focus (encadré rouge) + explication."
* "Diagrammes : Fait main (photo) c'est très bien ! Sinon Draw.io."
* "Préparez des backups (vidéo) et des annexes."

**✨ Variations / Conseils (optionnel) :**
* "Pour remplir le *contenu* des slides que nous venons de créer, vous vous baserez sur votre travail réel (le notebook Kaggle, vos scripts, etc.) en suivant le processus 'Narratif > TOM > Plan'."
* "Cet atelier se concentre sur Google Slides pour sa simplicité. Les mêmes principes s'appliquent à PowerPoint, Figma, etc."