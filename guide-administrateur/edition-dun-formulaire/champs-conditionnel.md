# Ajouter des logiques conditionnelles

Vous pouvez conditionner vos champs en fonction des réponses des champs précédents.

Cela vous permet en tant qu’administrateur d’avoir un formulaire plus simple, plus concis, et qui cible mieux vos usagers.

C’est également un gain de temps pour les usagers car ils se focaliseront uniquement sur les questions qui les concernent.

Le conditionnel est activé automatiquement sur tous les formulaires.

Voici un exemple d’utilisation du conditionnel :

1\) Le premier champ : le conditionnel ne s’applique pas sur le premier champ. La conditionnalité s’affichera à partir du deuxième champ.

Une condition peut porter sur **n’importe quel champ placé avant** la question conditionnée, et pas seulement sur le champ qui la précède. Ce champ doit être de l’un des types suivants :

* Oui/Non
* Case à cocher seule
* Nombre entier
* Nombre décimal
* Choix simple
* Choix multiple
* Adresse
* Communes
* Départements
* Régions
* Pays
* EPCI
* Champ pré-rempli

Les autres types de champ ne peuvent pas servir de condition.

{% hint style="info" %}
Un champ « Choix simple » ou « Choix multiple » dont les options sont importées depuis un référentiel ne peut pas servir de condition.
{% endhint %}

Voici un exemple en utilisant un champ oui/non

Le champ oui/non est le premier champ, il va permettre d’activer le conditionnel sur le deuxième champ.

<figure><img src="../.gitbook/assets/Conditionnel 1.png" alt=""><figcaption></figcaption></figure>

2\) Deuxième champ :

Nous souhaitons faire apparaître la deuxième question en fonction de la question précédente.

* Étape 1 : créer un nouveau champ avec les informations nécessaires
* Étape 2 : activer la logique conditionnelle : « cliquer pour activer »

<figure><img src="../.gitbook/assets/Conditionnel 2.png" alt=""><figcaption></figcaption></figure>

Etape 3 : Sélectionner le champ cible (la question) que vous souhaitez conditionner ainsi que l’opérateur

<figure><img src="../.gitbook/assets/Conditionnel 3.png" alt=""><figcaption></figcaption></figure>

Sélectionnez la valeur qui conditionne le champ (oui pour afficher la question, non pour ne pas l’afficher)

## Combiner plusieurs conditions

Vous pouvez ajouter plusieurs conditions sur un même champ. À partir de la deuxième condition, choisissez comment elles se combinent :

* **ET** : le champ s’affiche si toutes les conditions sont remplies ;
* **OU** : le champ s’affiche si au moins une des conditions est remplie.

Le même choix, ET ou OU, s’applique à toutes les conditions du champ.
