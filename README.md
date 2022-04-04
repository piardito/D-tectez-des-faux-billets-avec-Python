Ce projet a été réalisé dans le cadre de la formation Data Analyst, sur la plateforme OpenClassrooms.

# Détection des faux billets avec Python

Dans le cadre de ce projet, j'ai créé deux algorithmes capables de détecter si un billet est faux à partir de ses dimensions.

J'ai exploré les données d'apprentissage fournies contenant les dimensions et les labels de 1500 billets fictifs. J'ai analysé les corrélations entre les variables pour déterminer les plus discriminantes en effectuant des analyses univariées, bivariées et une ACP. De plus j'ai effectué une régression linéaire multiple afin d'imputer les données manquantes pour la dimension margin_low. J'ai ensuite comparé un algorithme de classification non supervisée les K-means avec un algorithme de classification supervisée la régresssion logistique. J'ai divisé le jeu donné en train/test pour tester l'efficacité des deux modèles.

Ensuite, j'ai créé deux algorithmes pour prédire si un billet est vrai ou faux à l'aide des deux modèles.
