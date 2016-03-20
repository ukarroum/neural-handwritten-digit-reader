# Lecteur de chiffre via reseau de neurones .

## Introduction 
Ce programme permet de lire des chiffres écrits à la main, c'est un tp que j'ai réalisé dans le cours de [Machine learning](https://www.coursera.org/learn/machine-learning) .

Le taux de reussite étant de *97.52%* .

Il utilise le reseau de neurones pour pouvoir entrainer 10 classificateurs (1 classificateur par chiffre) et choisit la réponse ayant la plus grande probabilité .

Les valeurs de Theta ont été fourni avec le TP le programme suivant ne les calcule pas .

  
Pour plus d'informations : [Réseau de neurones artificiels](https://fr.wikipedia.org/wiki/R%C3%A9seau_de_neurones_artificiels) .

Les classificateurs ont été entrainé par le [MNIST Database Of Handwritten digits](http://yann.lecun.com/exdb/mnist/)

## Fichiers du projet
Le TP contient en gros 6 fichiers :

* **displayData.m** : Permet d'afficher un echantillon du training Set .
* **ex3 nn.m** : Le programme principale calcule le taux de reussite de l'algorithme sur le dataset et fait une démonstration en appliquant l'algorithme sur des echantillons aléatoires .
* **predict** : La fonction qui se charge de lire le digit, en gros elle renvoie le chiffre dont la probabilité est la plus grande .
* **sigmoid.m** : Calcule [La fonction Sigmoid](https://fr.wikipedia.org/wiki/Sigmo%C3%AFde_%28math%C3%A9matiques%29) .
* **ex3data1.mat** : Contient le dataset sous forme de deux matrices, l'une representant les images (en grayscale normalisé a [-1, 1] ) l'autre les labels representé par chaque image .
* **ex3weight.mat** : contient les valeurs des poids Theta (fourni avec le TP) .


