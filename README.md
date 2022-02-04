
#########################
1 Analyse des sentiments
########################
#################
1.1 Introduction
#################
L’analyse de sentiment - ou de la tonalité - est une technologie clé pour mener une analyse qualitative des discussions en ligne. Elle permet de comprendre automatiquement la perception et les émotions derrière des messages sociaux ou des articles de presse sur un sujet précis,
comme une marque, un produit ou une tendance.

#################
1.2 Défnition
#################
L’analyse de sentiment est un procédé technologique utilisé pour comprendre l’attitude de l’auteur à l’égard d’un sujet.
L’analyse de sentiment détermine si un texte est positif, négatif ou neutre en extrayant des mots ou des phrases particulières. Son principal avantage est de pouvoir analyser une grande quantité de données pour comprendre le ressenti général d’une communauté.
Elle a été conçue pour donner un aperçu de la façon dont une marque, une campagne ou un sujet est perçu par son audience. Ces mesures sont utilisées pour aider à comprendre la réputation
de votre entreprise, la perception de vos concurrents dans votre marché ou la compréhension globale de la façon dont le message que vous avez choisi a été bien reçu.

#################
1.3Le jeu de données
#################
Pour entraîner nos algorithmes, il est important de disposer de données bien annotées. Pour ce faire, il nous fournies les données sur la plateforme en ligne Inside Airbnb ont été obtenues
à partir d’informations publiquement disponibles sur le site original d’Airbnb, selon les informations générales fgurant sur le site Web d’Inside Airbnb. Les données ont été nettoyées et
formatées par les créateurs du site sous une forme conviviale et visuellement attrayante. Le site Web contient des ensembles de données relatives aux annonces Airbnb dans des lieux relativement peuplés et touristiques du monde entier, tels que Pékin, Berlin, Copenhague et Los
Angeles. Pour les besoins de notre projet, nous nous concentrerons sur le jeu de données des annonces Airbnb sur la ville Berlin en Germany. Le jeux de données ont été le 21 October, 2021.

################################
2.les étapes de l'implimentation
################################
##################################################
2.2 Préparation et prétraitement du jeu de données
##################################################
2.2.1 Obtention et visualisation des données
2.2.2 Traitement des valeurs manquantes
2.2.3 Supprimer les colonnes inutiles
2.2.4 Fusionner les deux table
2.2.5 Détection des langues
2.2.6 Concaténer les commentaire qui ont même "ID"
2.2.7 Nettoyage de texte
##################################################
2.3 Méthodes appliquées avant la classifcation
##################################################
2..3.1 Classer le texte comme positif et négatif
2.3.2 Comparaison de texte négatif et positif
2.3.3 Séparer les données d’apprentissage et de test
2.3.4 La méthodes de L’extraction de caractéristiques

##################################################
2.4 Classifcation par les règles bayesiènes naïves
