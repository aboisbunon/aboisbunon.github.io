+++ 
title = "Codes"
draft = false
slug = "code"
+++ 

Vous trouverez ici quelques programmes [Matlab](http://www.mathworks.fr/products/matlab/) et [Python](https://www.python.org/).

### Python Optimal Transport (POT)

J'ai contribué à cette superbe librairie Python library pour le transport optimal, essentiellement développée par [Rémi Flamary](http://remi.flamary.com/), [Nicolas Courty](https://people.irisa.fr/Nicolas.Courty/) et [Alexandre Gramfort](http://alexandre.gramfort.net/). J'ai écrit un article Medium avec un exemple simple introduisant le transport optimal, à consulter [ici](https://towardsdatascience.com/hands-on-guide-to-python-optimal-transport-toolbox-part-1-922a2e82e621).

[[Dépôt Git]](https://github.com/PythonOT/POT)

### Model Selection Toolbox (MST)
J'ai développé cette boite à outils Matlab pendant ma thèse pour comparer de nombreuses méthodes de la littérature, à la fois pour la construction de collections de modèles (Lasso, Adalasso, Elastic net, MCP, ...), et pour la sélection du meilleur modèle de la collection (estimateurs de coût, AIC, AIC3, AICc, Cp, BIC, CV, SRM, slope heuristics, ...).

[[Dépôt Git]](https://github.com/aboisbunon/mst)


### Algorithmes de chemin de régularisation pour le LARS et le MCP
La Pénalité Concave Minimax (MCP) est une méthode développée par Zhang gardant la sélection du Lasso tout en corrigeant son biais d'estimation. Bien qu'elle corresponde à un problème d'optimisation non convexe et non différentiable, l'utilisation des différentielles de Clarke permet de calculer les conditions d'optimalité et nous avons ainsi pu proposé un algorithme de chemin de régularisation similaire à celui du Lasso. 

[[Matlab MCP]](http://aurelie.boisbunon.free.fr/downloads/monMCP.m)
[[Matlab Lasso]](http://aurelie.boisbunon.free.fr/downloads/monLAR.m)
[[Exemple]](http://aurelie.boisbunon.free.fr/downloads/ex_reg_path_MCP.m)

 
### Génération aléatoire de vecteurs à symétrie sphérique
Les lois à symétrie sphérique sont une généralisation de la lois gaussienne sphérique multidimensionnelle où l'hypothèse d'indépendance est relâchée. J'ai développé ce code pour générer des vecteurs aléatoires à symétrie sphérique. 
Le fichier pdf présente les principales propriétés de cette famille de lois ainsi que les algorithmes utilisés pour générer des vecteurs aléatoire sphériques. 

[[Matlab code]](http://aurelie.boisbunon.free.fr/downloads/randSS.m)
[[Example]](http://aurelie.boisbunon.free.fr/downloads/ex_random_gener.m)
[[PDF]](http://aurelie.boisbunon.free.fr/downloads/loisSS.pdf)


