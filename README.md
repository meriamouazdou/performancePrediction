# performancePrediction
Fonctionnement du Code
Ce script utilise Python pour analyser des données d'un fichier CSV appelé AI-Data.csv. Son objectif est d'explorer visuellement les relations entre les classes de notes des étudiants et plusieurs variables (genre, nationalité, section, etc.) et d'évaluer la précision de différents modèles de classification.

Importation et Préparation des Données : Le fichier AI-Data.csv est chargé avec pandas, puis certaines colonnes sont supprimées pour simplifier le modèle. Des valeurs catégoriques sont ensuite encodées en valeurs numériques.

Visualisation des Données : Une fonction permet de générer plusieurs graphiques (par classe, semestre, genre, etc.), facilitant ainsi l'analyse visuelle des tendances.

Classification et Évaluation des Modèles : Le script utilise différents modèles de machine learning (arbre de décision, forêt aléatoire, perceptron, régression logistique et réseau de neurones) pour classer les données. Les modèles sont entraînés sur 70 % des données et évalués sur les 30 % restants, et la précision de chaque modèle est affichée avec des rapports de classification.

Prédiction : L'utilisateur peut tester une prédiction spécifique en entrant manuellement des valeurs pour chaque attribut. Les prédictions des différents modèles sont ensuite affichées.
