# 🎓 Student Success Analytics : Prédiction de la Réussite Étudiante

Bienvenue sur mon projet d'analyse de données et de Machine Learning appliqué à l'éducation. 

Dans ce dépôt, je m'intéresse à la réussite des étudiants en ligne en analysant leurs comportements, leurs interactions et leurs résultats académiques. L'objectif principal de mon projet est de construire un modèle prédictif capable d'anticiper les risques d'échec ou d'abandon le plus tôt possible au cours d'un semestre.

### 🎯 Objectifs du projet

Dans ce notebook, je réalise plusieurs étapes clés de la Data Science :
* **Nettoyage et structuration des données** (gestion des valeurs manquantes, renommage des variables).
* **Analyse exploratoire visuelle (EDA)** pour comprendre les facteurs clés de la réussite (ex: impact de la date d'inscription, régularité des connexions).
* **Feature Engineering** pour calculer les moyennes pondérées et créer des indicateurs d'engagement.
* **Modélisation prédictive (Machine Learning)** pour classifier les étudiants à risque d'abandon.

### 🛠️ Technologies utilisées

* **Langage :** Python 3
* **Librairies principales :** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Environnement :** Jupyter Notebook

---

### 📊 Jeu de données (Dataset)

Pour ce projet, j'utilise l'**OULAD (Open University Learning Analytics Dataset)**. J'ai récupéré l'intégralité de ces données directement sur Kaggle. 

Si vous souhaitez reproduire mes analyses, vous pouvez télécharger le jeu de données via ce lien :

🔗 [OULAD Dataset sur Kaggle](https://kaggle.com)

**Note pour l'exécution :** Après avoir téléchargé l'archive, j'ai placé l'ensemble des fichiers CSV dans un dossier nommé `Datasets/` à la racine de mon projet pour que mes scripts fonctionnent correctement.

### 📁 Description des fichiers du jeu de données

Voici le rôle et le contenu de chaque fichier CSV présent dans mon dossier `Datasets/` :

*   **assessments.csv (Évaluations) :** Contient les informations sur les examens et les devoirs à rendre (le type de devoir, la date limite de rendu officielle et son coefficient/poids dans la note finale).
*   **courses.csv (Cours/Modules) :** Liste l'ensemble des modules disponibles ainsi que les sessions de cours (présentations) proposées pour chaque semestre.
*   **studentAssessment.csv (Notes des étudiants) :** Regroupe les notes obtenues par chaque étudiant à ses différentes évaluations, ainsi que la date exacte à laquelle il a rendu son devoir.
*   **studentInfo.csv (Profils des étudiants) :** Contient les données démographiques et le résultat final de chaque étudiant (genre, région, niveau d'études, tranche d'âge, score de précarité, et s'il a réussi, échoué ou abandonné le cours).
*   **studentRegistration.csv (Inscriptions) :** Enregistre la date à laquelle l'étudiant s'est inscrit à un module (souvent un nombre de jours négatif avant le début officiel) et sa date de désinscription s'il a abandonné.
*   **studentVle.csv (Interactions VLE/Moodle) :** C'est le fichier le plus volumineux. Il enregistre chaque clic de chaque étudiant sur la plateforme en ligne (la date du clic, la page visitée et le nombre de fois qu'il a cliqué ce jour-là).
*   **vle.csv (Matériel pédagogique) :** Répertorie toutes les ressources disponibles sur la plateforme en ligne (fichiers PDF, pages HTML, forums, quiz, URL externes).

