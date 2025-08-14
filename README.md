# Introduction Pratique au Filtre de Kalman Filter 
Ce projet contient deux simulations en Python conçues pour faciliter la compréhension du filtre de Kalman. Deux exemples sont proposés. Un cas d'école très simple à une application plus réaliste, afin de construire une compréhension solide et intuitive.


# Objectif du Projet
Fournir des exemples de code clairs, commentés et fonctionnels pour aider étudiants, ingénieurs et curieux à comprendre le filtre de Kalman non seulement en théorie, mais surtout en pratique.


# Exemples
## Exemple 1 : suivi 1D
* Scénario : Suivi d'un objet se déplaçant en ligne droite à vitesse constante, observé par un capteur bruité (bruti gaussien parfait).
* Concepts clés : introduction au cycle Prédiction-Correction, au vecteur d'état x, à la matrice de covariance P et à l'influence des bruits Q et R.
## Exemple 2 : Le Robot Mobile 2D 
* Scénario : Pilotage d'un robot en 2D suivant une trajectoire balistique (courbe), avec des mesures de position GPS bruitées.
* Concepts clés : Passage à un état multi-dimensionnel, introduction d'une commande externe (u et B), et utilisation d'un modèle de bruit de processus Q physiquement plus rigoureux.


# Prérequis 
pip install numpy matplotlib
