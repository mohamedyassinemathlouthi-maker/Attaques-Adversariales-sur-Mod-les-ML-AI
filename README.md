# Description GitHub & Référence Kaggle

Ce notebook présente une étude des attaques adversariales sur les modèles d'apprentissage automatique, en se concentrant sur les réseaux de neurones convolutionnels (CNN) appliqués à la classification d'images MNIST.

Objectifs :

Entraînement d'un Modèle Victime : Un CNN classique est entraîné sur le dataset MNIST pour la classification de chiffres.
Génération d'Attaques Adversariales (FGSM) : Utilisation de l'attaque Fast Gradient Sign Method (FGSM) pour créer des images adversariales à partir du jeu de test MNIST.
Développement d'un Détecteur Binaire : Conception et entraînement d'un modèle binaire capable de distinguer les images clean des images adversariales.
Entraînement d'un Classificateur de Chiffres Robuste : Un second classificateur est entraîné uniquement sur les images clean pour maintenir une haute précision sur les données non attaquées.
Évaluation du Système Complet : Analyse des performances du détecteur et du classificateur combinés sur un jeu de test incluant des images clean et adversariales.
Visualisation avec Grad-CAM : Utilisation de Grad-CAM pour visualiser les cartes d'activation du modèle victime sur des images clean et adversariales, afin de comprendre comment l'attaque modifie l'attention du modèle.
Dataset utilisé : MNIST : Le dataset de chiffres manuscrits, couramment utilisé pour les benchmarks en vision par ordinateur.

Kaggle : Ce projet peut être utilisé comme base pour des compétitions ou des challenges autour de la robustesse des modèles ML face aux attaques adversariales. Un dataset pertinent serait le jeu de données MNIST original, disponible sur Kaggle : MNIST Handwritten Digit Recognition. Description GitHub & Référence Kaggle Ce notebook présente une étude des attaques adversariales sur les modèles d'apprentissage automatique, en se concentrant sur les réseaux de neurones convolutionnels (CNN) appliqués à la classification d'images MNIST.

Objectifs : Entraînement d'un Modèle Victime : Un CNN classique est entraîné sur le dataset MNIST pour la classification de chiffres. Génération d'Attaques Adversariales (FGSM) : Utilisation de l'attaque Fast Gradient Sign Method (FGSM) pour créer des images adversariales à partir du jeu de test MNIST. Développement d'un Détecteur Binaire : Conception et entraînement d'un modèle binaire capable de distinguer les images clean des images adversariales. Entraînement d'un Classificateur de Chiffres Robuste : Un second classificateur est entraîné uniquement sur les images clean pour maintenir une haute précision sur les données non attaquées. Évaluation du Système Complet : Analyse des performances du détecteur et du classificateur combinés sur un jeu de test incluant des images clean et adversariales. Visualisation avec Grad-CAM : Utilisation de Grad-CAM pour visualiser les cartes d'activation du modèle victime sur des images clean et adversariales, afin de comprendre comment l'attaque modifie l'attention du modèle. Dataset utilisé :

MNIST : Le dataset de chiffres manuscrits, couramment utilisé pour les benchmarks en vision par ordinateur. Kaggle :

Ce projet peut être utilisé comme base pour des compétitions ou des challenges autour de la robustesse des modèles ML face aux attaques adversariales. Un dataset pertinent serait le jeu de données MNIST original, disponible sur Kaggle : MNIST Handwritten Digit Recognition.
