# 10_introduction_deep_learning

Introduction au Deep Learning

Ce bref exposé vise à acquérir les notions fondamentales nécessaires à la compréhension du fonctionnement des réseaux de neurones artificiels. Ces principes seront démontrés à travers deux études de cas concrets.

Contexte du Projet

Afin de maîtriser les concepts de base liés aux réseaux de neurones artificiels, l'objectif est de développer des supports pédagogiques permettant d'expliquer et d'illustrer ces concepts à un public de pairs. Pour ce faire, une veille pédagogique sera élaborée dans un notebook Jupyter, suivant le plan suivant :

Du neurone biologique au neurone artificiel : Présenter les analogies entre les neurones biologiques et artificiels.

Réseaux de neurones artificiels :

Perceptron : Définir ce qu'est un perceptron.
Perceptron multi-couche :
Détailler les notions de couches d'entrée, de couches cachées et de couches de sortie.
Expliquer le processus de régression avec un perceptron multi-couche.
Présenter l'architecture du réseau, y compris les dimensions des couches d'entrée, cachées et de sortie.
Aborder les fonctions d'activation de chaque couche.
Examiner la fonction de coût.
Expliquer le processus de classification (binaire et multiclasse) avec un perceptron multi-couche.
Reprendre l'architecture du réseau, les dimensions des couches et les fonctions d'activation, tout en discutant de la fonction de coût.
Qu'est-ce que le "Deep Learning" ou apprentissage profond ?

Illustration Pratique

La régression par un perceptron multi-couche sera démontrée dans un Jupyter Notebook, en utilisant l'exemple du Boston House Prices Dataset. S'inspirer de la ligne de code suivante (avec sklearn) :

MLPRegressor(hidden_layer_sizes='à définir', activation='à définir', solver='lbfgs', alpha=0.0001, max_iter=10000, random_state=0, max_fun=15000)

De même, la classification par un perceptron multi-couche sera illustrée dans un Jupyter Notebook, utilisant l'exemple du Breast Cancer Wisconsin (Diagnostic) Dataset. S'inspirer de la ligne de code suivante (avec sklearn) :

MLPClassifier(hidden_layer_sizes='à définir', activation='à définir', solver='lbfgs', alpha=0.0001, max_iter=10000, random_state=0, max_fun=15000)

Livrables

Une présentation sous forme de notebook markdown servant de veille pédagogique.
Deux Jupyter Notebooks distincts : l'un pour la classification (exemple du Breast Cancer Wisconsin (Diagnostic) Dataset) et l'autre pour la régression (exemple du Boston House Prices Dataset).





