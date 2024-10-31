# Sujet : Classification d'images avec le jeu de données CIFAR-10

## Bibliographie
Une bibliographie sera fournie pour vous inspirer dans vos recherches et le développement de votre projet.

## Contexte
Vous allez travailler sur le jeu de données CIFAR-10, qui contient 60 000 images de 10 classes différentes (aéronefs, automobiles, oiseaux, chats, cerfs, chiens, grenouilles, chevaux, navires, camions). L'objectif de ce projet est de tester divers modèles de réseaux de neurones pour la classification d'images et d'explorer l'influence des hyperparamètres sur les performances du modèle.

## Objectif
L'objectif principal est de tester les réseaux de neurones que je vous propose et d'analyser leurs performances. Vous aurez à explorer les différents modèles et les hyperparamètres, tels que le taux d'apprentissage, le nombre d'époques, la taille des lots, et d'autres variables. Vous utiliserez des fonctions de perte et de précision pour évaluer vos modèles.

## Tâches à réaliser
1. **Utilisation du notebook d'exemple :** Vous commencerez par un notebook d'exemple fourni [CIFAR10_classification.ipynb](classification/CIFAR10_classification.ipynb), qui contient des modèles minimaux à tester. L'idée sera de le faire évoluer pour en faire votre rendu. L'idéal est de l'exécuter sous Google Colab avec utilisation d'un GPU (ex. T4).


| :boom: DANGER              |
|:---------------------------|
| :exclamation: Deconnecter vous de votre  session d'execution quand vous ne faites pas de calcul sous risque de vous faire bannir temporemement de l'usage des GPUs  :exclamation:|

2. **Expérimentations avec les modèles :** Vous devrez tester les modèles proposés dans le notebook et ajuster les hyperparamètres pour voir comment cela impacte les performances.

 
 Au passage il faudra bien sur expliquer tous les paramaetres utilisés pour l'apprentissage . Il est aussi important de définir les critéres de performances . Vous expliciterez en particulier pourquoi les plus importants sont associés au jeux de données de test (par oppposition à celui d'apprentissage) 

3. **Analyse des couches :** Dans votre notebook, vous devrez expliquer les différentes couches utilisées dans les modèles (couches denses, couches de convolution, etc.) et leur rôle dans le traitement des données.

> [!IMPORTANT]
> La compréhension de cette partie  fera en particulier l'objet de l'examen

4. **Proposition d'améliorations :** Vous êtes invités à proposer des solutions pour obtenir le meilleur score possible. Si vous avez utilisé des ressources extérieures, veillez à les citer dans votre travail.

5. **Synthèse des résultats :** Votre rendu final devra inclure des tableaux de synthèse des performances des différents modèles et des courbes montrant l'influence des choix effectués.

6. **Explicabilité :** Une derniere partie s'interessera à l'explicabilité des résultats , en utilisant par exemple GradCAM++ implémenté sous [tf_keras_vis](https://keisen.github.io/tf-keras-vis-docs/examples/attentions.html#GradCAM++). Vous justifirez ou critiquerez mon choix. Proposez autres choses si ca vous semble plu pertinent . Dans tous les cas, on appliquera au modele et aux images utilisés dans le notebook.

## Rendu
- Le rendu doit être un unique fichier Jupyter Notebook, hébergé sur Gitlab est associé à votre rendu complet . L'avantage du format ipynb et qu'il contient le résulat de votre derniere execution avant sauvegarde mais il peut être aussi complétement regenerer avec les codes pythons
- Assurez-vous que votre notebook est bien documenté et que chaque section est clairement indiquée. Vous pouvez rédiger en francais ou en anglais 
