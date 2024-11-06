
# Sujet : Détection d'Objets avec TensorFlow

## 1. Question 1 (Rappel)

  1.a. Expliquer la différence entre la classification d’image, la détection d’image et la segmentation d’images
  1.b. Quelles sont les grandes solutions de détection d’objets (voir par exemple [ici](https://developers.arcgis.com/python/guide/how-ssd-works/))

## 2. Question 2

On s’intéresse à l’exemple suivant : [Exemple de détection d'objets avec TensorFlow Hub](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/hub/tutorials/tf2_object_detection.ipynb). 
> [!TIP]
>Commencer par changer le modele d'exécution pour utiliser un GPU, sinon vous risquez de perdre du temps

> [!CAUTION]
> On retrograde une version numpy 
Vous avez le message suivant : WARNING: The following packages were previously imported in this runtime:
  [numpy]
You must restart the runtime in order to use newly installed versions.
> 
>**Relancer le runtime en cliquant sur le bouton proposé**




 2.a Quelles sont les classes reconnues par le réseau ?

 2.b Quelle partie du code correspond au chargement du modèle de réseau ? Quels sont les modèles proposés ?

 2.c Quelles sont les structures des modèles de réseaux sous-jacents ?

 2.d Tester sur une douzaine d’images de votre choix (Essayez d'utiliser (ou de générer)  des images contenant le plus de classes reconnues possible) et faites un tableau comparatif.

 ## 3. Question 3

 3.a À quoi sert TensorFlow Hub, et existe-t-il des solutions équivalentes ?

 3.b Combien de réseaux de détection d'objets trouve-t-on sur TensorFlow Hub ?

 3.c Quelles sont les architectures de ces réseaux ?

 3.d Quelles sont les classes reconnues ?

 3.e Y a-t-il des exemples pour gérer une phase d’apprentissage ?

 ## 4. Question 4
 

4.a Quel est le format d'entrée d'un réseau de détection ?

4.b Comment peut-on transformer une architecture de classifieur en une architecture de détecteur ? (donner un exemple sur le reseau de votre choix)

4.c À quoi ressemblerait, dans ce cas, la phase d'apprentissage ?

4.d Est-il possible d'intégrer un réseau de classifieur déjà entraîné pour en faire un détecteur ?

4.e Dans ce cas, doit-on procéder à un *fine-tuning* ? Si oui, comment procéder et quel serait le format du jeu de données ?

