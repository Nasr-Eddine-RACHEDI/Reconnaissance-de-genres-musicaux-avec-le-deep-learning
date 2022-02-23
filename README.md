# Reconnaissance-de-genres-musicaux-avec-le-deep-learning


La musique est complètement partie prenante de notre vie quotidienne. Selon un rapport de la Fédération
Internationale de l’Industrie Phonographique (IFPI) publié en 2019, nous consommons
en moyenne 18 heures de musique par semaine. Face à cet engouement, de nouveaux services
ont fait leur apparition, à l’instar des systèmes de recommandation de musique ou encore des
générateurs de playlists. Ces services innovants se basent en partie sur la reconnaissance de sons
et plus précisément, l’indexation de contenus audio.
C’est dans ce cadre là que s’inscrit notre projet. Il a pour objectif de classer des morceaux
musicaux suivant leurs genres, à travers la mise en pratique des techniques d’apprentissage automatique
profond visant une performance aussi bonne voire meilleure que celle de l’oreille humaine.
Il est à noter que plusieurs approches existent pour la classification de genres (machines à vecteurs
de support multi classe, K-moyennes, K plus proches voisins) mais nous nous concentrerons
dans ce projet uniquement sur les réseaux de neurones Feedforward et convolutifs.
Dans un premier temps, nous nous intéresserons au traitement des données qui serviront d’entrée
au réseau de neurones (section 2) puis, nous détaillerons l’architecture des modèles employés
pour la classification (section 3). Enfin, nous terminerons sur une discussion des résultats obtenus
avant de conclure.
L’intégralité de notre projet peut être schématisé par la figure 1.

![image](https://user-images.githubusercontent.com/74628056/155401473-0c912ce7-8e1c-45b0-b19b-6666da3f66de.png)
