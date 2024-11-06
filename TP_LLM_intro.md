### LLM et Fine-tuning

---

## Question 1

On s’intéresse au code suivant :  
[Colab LLM Fine-tuning](https://colab.research.google.com/drive/1wvhDmAnTGQE4YvCS123xw8twFPNMEfaf)

**1.a** À quoi correspond le site Hugging Face Hub cité dans le document ? Créez-vous un compte.

**1.b** Concernant les tutoriels disponibles, ils sont très nombreux. Si le sujet vous intéresse, vous pourrez les regarder, mais cela n’est pas demandé :
- [Cours de NLP](https://huggingface.co/learn/nlp-course/)
- [Classification de séquence](https://huggingface.co/docs/transformers/tasks/sequence_classification)
- [Classification de token](https://huggingface.co/docs/transformers/tasks/token_classification)
- [Question answering](https://huggingface.co/docs/transformers/tasks/question_answering)
- [Modélisation de langage](https://huggingface.co/docs/transformers/tasks/language_modeling)
- [Modélisation de langage masqué](https://huggingface.co/docs/transformers/tasks/masked_language_modeling)
- [Traduction](https://huggingface.co/docs/transformers/tasks/translation)
- [Résumé automatique](https://huggingface.co/docs/transformers/tasks/summarization)
- [Tutoriel LLM](https://huggingface.co/docs/transformers/llm_tutorial)

**1.c** Quel est le nom du modèle de réseau sous-jacent ? Quelle est sa taille et son architecture ?

**1.d** Le modèle est-il déjà entraîné ou est-ce simplement une structure de réseau ?

**1.e** Si le modèle est déjà entraîné, sur quels datasets a-t-il été formé ?

**1.f** Qu’est-ce qu’un LoRA ? Expliquez ses 3 paramètres.

**1.g** Qu’est-ce qu’un Transformer ? Expliquez son usage dans le cadre d’un LLM.

**1.h** Si ce n’est pas déjà fait, lancez l’exécution de l’ensemble du code (cela prend environ 30 minutes).

---

## Question 2

En quoi consiste la notion de *token* ? Donnez des exemples de tokens dans notre cas.

---

## Question 3

Le but de ce code est de procéder à un *fine-tuning* du modèle.

**3.a** De quoi parle-t-on ici ?

**3.b** Quel est le dataset utilisé ? Montrez des exemples et indiquez sa taille. Quelle puissance de calcul en TFlops a été nécessaire pour le *fine-tuning* ? A-t-on modifié la taille du modèle après apprentissage ?

---

## Question 4

**4.a** Testez différents prompts. Que pensez-vous de ses performances ? Comparez les résultats avec ChatGPT.

---

## Question 5

Refaites les tests en partant du même modèle sans le *fine-tuning*. Comment procéder ? Que pensez-vous de la différence ?

---

## Question 6

La dernière partie du modèle sauvegarde votre modèle *fine-tuné*. Créez un code Python qui l’utilise directement.

---

## Question 6 (Exploratoire)

Proposez un *fine-tuning* particulier en trouvant un dataset original. Montrez en quoi les résultats sont mauvais avant le *fine-tuning*, puis montrez le résultat après. Êtes-vous satisfait ?
