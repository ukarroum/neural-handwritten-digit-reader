# Lecteur de chiffre via reseau de neurones .

## Introduction 
Ce programme permet de lire des chiffres écrits à la main, c'est un tp que j'ai réalisé dans le cours de [Machine learning](https://www.coursera.org/learn/machine-learning) .

Le taux de reussite étant de *95.36%* .

Il utilise le reseau de neurones pour pouvoir entrainer 10 classificateurs (1 classificateur par chiffre) et choisit la réponse ayant la plus grande probabilité .

Les valeurs de Theta ont été entrainé via [Backpropagation](https://fr.wikipedia.org/wiki/R%C3%A9tropropagation_du_gradient) .

Pour plus d'informations : [Réseau de neurones artificiels](https://fr.wikipedia.org/wiki/R%C3%A9seau_de_neurones_artificiels) .

Les classificateurs ont été entrainé par le [MNIST Database Of Handwritten digits](http://yann.lecun.com/exdb/mnist/)

## Fichiers du projet
Le TP contient en gros 6 fichiers :

* **displayData.m** : Permet d'afficher un echantillon du training Set .
* **ex4.m** : Le programme principale calcule le taux de reussite de l'algorithme sur le dataset .
* **predict** : La fonction qui se charge de lire le digit, en gros elle renvoie le chiffre dont la probabilité est la plus grande .
* **sigmoid.m** : Calcule [La fonction Sigmoid](https://fr.wikipedia.org/wiki/Sigmo%C3%AFde_%28math%C3%A9matiques%29) .
* **ex4data1.mat** : Contient le dataset sous forme de deux matrices, l'une representant les images (en grayscale normalisé a [-1, 1] ) l'autre les labels representé par chaque image .
* **ex4weight.mat** : contient les valeurs des poids Theta (fourni avec le TP) .
* **checkNNGradients.m** : Permet de vérifier les gradients calculé par BackPropagation via une méthode analytique .
* **computeNumericalGradient.m** : Calcule les gradients analytiquement .
* **nnCostFunction.m** : Se charge de calculer le Cost et ses gradients via BackPropagation .
* **randInitializeWeights.m** : Se charge d'initialiser les poids du réseau à des valeurs aléatoires .
* **sigmoidGradient.m** : Calcule le Gradient de la fonction de Sigmoid .



