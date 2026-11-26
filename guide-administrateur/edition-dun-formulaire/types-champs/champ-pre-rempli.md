# Champ pré-rempli non modifiable

Le champ **« Champ pré-rempli non modifiable »** reçoit une valeur fournie automatiquement. L'usager ne peut pas la saisir ni la modifier.

## Quand utiliser ce champ

Ce champ n'est utile que si sa valeur est fournie par l'un de ces moyens :

* un champ [Référentiel configurable (avancé)](referentiel-externe.md) du formulaire usager ou des annotations privées, configuré pour pré-remplir ce champ ;
* un dossier pré-rempli créé pour l'usager, par un lien ou par l'API de préremplissage.

Sinon, le champ reste vide.

## Configurer le champ

Dans le formulaire, choisissez le type **« Champ pré-rempli non modifiable »**, dans la catégorie Référentiel. Vous pouvez ensuite :

* renseigner les **« Valeurs du référentiel à utiliser pour le conditionnel »**, une valeur par ligne. Ces valeurs vous sont proposées quand vous utilisez le champ dans une condition. Elles ne limitent pas la valeur que le champ peut recevoir ;
* cocher **« Masquer ce champ dans le formulaire usager »**.

{% hint style="info" %}
Ce champ ne peut pas être rendu obligatoire.
{% endhint %}

## Ce que voient l'usager et les instructeurs

Si le champ n'est pas masqué, l'usager voit sa valeur dans le formulaire, sans pouvoir la modifier.

Si le champ est masqué, l'usager ne le voit ni dans le formulaire, ni dans son dossier, ni dans le PDF de son dossier. La valeur est conservée lors du dépôt.

Dans tous les cas, les instructeurs et les experts invités voient le champ et sa valeur dans le dossier.

## Utiliser le champ dans une condition

Le champ pré-rempli peut servir dans :

* les [logiques conditionnelles](../champs-conditionnel.md) ;
* les [règles d'inéligibilité](../../configuration-dune-demarche/ajouter-des-regles-dineligibilite.md) ;
* les règles de [routage](../../configuration-dune-demarche/routage.md), en configuration manuelle du routage uniquement.
