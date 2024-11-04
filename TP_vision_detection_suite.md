
# Sujet : Détection d'Objets avec TensorFlow

## Question 1 (Rappel)

 1.a Expliquer la différence entre la classification d’image, la détection d’image et la segmentation d’images

 1.b Quelles sont les grandes solutions de détection d’objets (voir par exemple [ici](https://developers.arcgis.com/python/guide/how-ssd-works/))

## Question 2

On s’intéresse à l’exemple suivant : [Exemple de détection d'objets avec TensorFlow Hub](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/hub/tutorials/tf2_object_detection.ipynb). 
COmmencer par Changer le modele d'eécution pour utiliser un GPU 
**On retrograde une version numpy 
Vous avez le message suivant : WARNING: The following packages were previously imported in this runtime:
  [numpy]
You must restart the runtime in order to use newly installed versions.
Relancer le runtime en cliquant sur le bouton proposé




### 2.a Quelles sont les classes reconnues par le réseau ?

### 2.b Quelle partie du code correspond au chargement du modèle de réseau ? Quels sont les modèles proposés ?

### 2.c Quelles sont les structures des modèles de réseaux sous-jacents ?

### 2.d Tester sur une douzaine d’images de votre choix (Essayez d'utiliser des images contenant le plus de classes reconnues possible) et faites un tableau comparatif.

## Question 3

### 3.a À quoi sert TensorFlow Hub, et existe-t-il des solutions équivalentes ?

### 3.b Combien de réseaux de détection d'objets trouve-t-on sur TensorFlow Hub ?

### 3.c Quelles sont les architectures de ces réseaux ?

### 3.d Quelles sont les classes reconnues ?

### 3.e Y a-t-il des exemples pour gérer une phase d’apprentissage ?

---

## Remarques sur le sujet

1. **Complexité des questions** : Les questions couvrent différents niveaux de difficulté, de la théorie (différences entre classification, détection, et segmentation) à la pratique (tester un modèle sur des images). Cela peut convenir à des élèves ayant une base en machine learning ou en traitement d’images.

2. **Référence à la documentation** : La question 2.b demande de comprendre le code et les modèles proposés sur TensorFlow Hub, ce qui peut nécessiter que les élèves soient à l'aise avec la lecture de documentation et le code Python.

3. **Exigences en ressources** : La question 2.d demande de tester des modèles sur plusieurs images, ce qui peut nécessiter des ressources informatiques adaptées (GPU, Google Colab avec ressources GPU activées, etc.).

4. **Autonomie requise pour la résolution de problèmes** : Noter que des erreurs de compatibilité peuvent survenir (d'où l'option de rétrograder `object_detection`). Ce point permet de tester la capacité des élèves à trouver et résoudre des problèmes de compatibilité.

5. **Pratique de la recherche sur des alternatives** : La question 3.a ouvre à l'exploration de solutions alternatives comme PyTorch Hub, ce qui pourrait être intéressant pour ceux qui souhaitent comparer plusieurs écosystèmes.
"""

# Define the file path
file_path = "/mnt/data/sujet_detection_objets_tensorflow.md"

# Write the markdown content to a file
with open(file_path, "w") as file:
    file.write(markdown_content)

file_path
