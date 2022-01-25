# cours deeplearning
ici se trouve des notebooks pythons utilisés pour découvrir comment qu'on fait du deeplearning

les détails et explications se trouvent dans les notebooks

## fastai
exocode : découverte des outils et utilisation d'un modèle

exoprod : on apprend a créer les outils, modèles, poids, et d'exporter ça

## Keras
catdog : équivalent de exoprod mais sous keras

## Projet (fastai) : 
Créer une IA qui sera capable de classer une photo de champignon dans une des 4 catégories : 
*  champignon toxique
*  Sporocarpe toxique
*  champignon commestible
*  Sporocarpe commestible

[correction] maintenant il n'y a plus que champignon toxique et commestible

L'objectif étant d'aider au ramassage de champignon on va faire en sorte que l'ia ne se trompe quasi jamais en plaçant dans commestible au risque de mettre des champignons commestibles dans toxique ou mortel.

Je vais faire un dataset de champignons communs trouvables en france afin de limiter la difficulté et le taux d'erreur.

Cette IA sera pré entrainée depuis un notebook appelé mushroompicker et sera exportée afin de pouvoir l'utiliser.
