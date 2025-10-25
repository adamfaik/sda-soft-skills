# Guide : Créer des présentations HTML avec l'assistant Gemini

Cet assistant Gem est un outil puissant pour générer rapidement des présentations au format HTML à partir de vos idées, plans ou documents existants.

---

## 1. Accès et configuration initiale

1.  **Accédez à l'assistant** via ce lien : [📺 Document to HTML Presentation Converter](https://gemini.google.com/gem/1ceG85dtOVdgsvqecXnKT3CS0zX9ZaHzU?usp=sharing)
2.  **Sélectionnez l'outil "Canvas"** : Assurez-vous que l'extension ou l'outil "Canvas" (ou un nom similaire lié à la génération visuelle/structurée) est bien activé dans l'interface Gemini.
3.  **Choisissez le Modèle 2.5 Pro** : Vérifiez que vous utilisez bien la version "2.5 Pro" du modèle pour bénéficier des capacités de génération structurée.

---

## 2. Fournir le contenu

Vous avez deux méthodes principales pour indiquer à Gemini ce que doit contenir votre présentation :

* **Description directe :** Écrivez directement dans la zone de prompt ce que vous souhaitez. Soyez le plus précis possible sur le sujet, l'audience, le nombre de slides souhaité et les points clés à aborder.
    * *Exemple :* "Crée une présentation HTML de 5 slides pour des étudiants en Data Science sur l'importance du nettoyage des données. Aborde : 1. Pourquoi c'est crucial, 2. Types courants de données 'sales', 3. Techniques de nettoyage de base, 4. Outils Python utiles, 5. Impact sur le modèle final."

* **Ajout de documents ou plan :**
    * **Pièces jointes :** Utilisez l'icône trombone (📎) ou équivalente pour attacher des fichiers (PDF, .txt, Google Docs...). Gemini analysera le contenu pour structurer la présentation.
    * **Coller un plan :** Vous pouvez simplement copier-coller un plan détaillé (comme un fichier Markdown ou une liste à puces) directement dans le prompt.

---

## 3. Génération et sortie

1.  **Lancez la génération :** Une fois votre input fourni, appuyez sur "Entrée" ou le bouton d'envoi.
2.  **Résultat :** Gemini va générer :
    * Une **prévisualisation** : Vous verrez un aperçu des différentes slides créées.
    * Le **code HTML** : Le code source complet de la présentation sera disponible.



---

## 4. Utilisation du code HTML

Le code HTML généré est directement utilisable :

1.  **Copiez** l'intégralité du code HTML.
2.  **Collez-le** dans un éditeur de code (comme VS Code, Notepad++, etc.).
3.  **Enregistrez** le fichier avec l'extension `.html` (par exemple, `ma_presentation.html`).
4.  **Ouvrez** ce fichier `.html` avec votre navigateur web (Chrome, Firefox, Edge...). Votre présentation s'affichera.

---

## 5. Itération et ajustements

La première version générée par Gemini n'est souvent qu'un point de départ. L'outil est conçu pour l'itération :

* **Feedback slide par slide :** Dans l'interface de prévisualisation Gemini, vous pouvez généralement donner des retours spécifiques sur chaque slide ("Cette slide est trop chargée", "Ajoute une image ici", "Reformule ce point clé"...).
* **Ajustements généraux :** Vous pouvez aussi demander des modifications globales ("Utilise un ton plus professionnel", "Simplifie le langage technique", "Ajoute une slide de conclusion").
* **Continuez à itérer** en dialoguant avec Gemini jusqu'à obtenir un résultat satisfaisant.

**Astuce :** Fournir un plan détaillé à l'étape 2 donne souvent de meilleurs résultats dès la première génération. N'hésitez pas à peaufiner le code HTML manuellement si vous avez des besoins de design très spécifiques.