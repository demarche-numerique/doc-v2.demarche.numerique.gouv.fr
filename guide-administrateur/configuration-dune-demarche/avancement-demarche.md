# Informer l'usager sur l'état d'avancement de sa démarche

Il convient désormais de penser d’un point de vue usager à la vie de la démarche suite à la transmission du dossier. Dès à présent, il faut envisager les modalités d’information de l’usager sur l’état d’avancement de son dossier. Pour cela, **demarche.numerique.gouv.fr** envoie des e-mails dans lesquels vous pouvez communiquer les informations souhaitées.

## Les e-mails automatiques

Six modèles d’e-mail sont envoyés automatiquement à l’usager. Chacun correspond à un moment clé du dossier :

* **Accusé de réception** : après le dépôt du dossier. Une attestation de dépôt est jointe. L’usager peut encore modifier son dossier.
* **Accusé de passage en instruction** : lorsque l’instructeur passe le dossier en instruction, ou à la clôture automatique de la démarche si vous avez fixé une date limite de dépôt. L’usager ne peut plus modifier son dossier.
* **Accusé d’acceptation**, **Accusé de refus** et **Accusé de classement sans suite** : lorsque l’instructeur rend sa décision.
* **Réexamen du dossier** : lorsque l’instructeur repasse le dossier en instruction après qu’une décision a été rendue.

Ces e-mails sont entièrement personnalisables. Depuis la page de votre démarche, cliquez sur la tuile **« Modèles d’email »**. Pour chaque modèle, cliquez sur **« Modifier »** : vous pouvez alors rédiger l’objet et le corps de l’e-mail, et vérifier le résultat dans l’aperçu.

<figure><img src="../.gitbook/assets/Capture d’écran 2025-10-21 à 12.22.06.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (136).png" alt=""><figcaption><p>Personnaliser les email, en tant qu'administrateur</p></figcaption></figure>

Lorsque vous personnalisez votre mail, il est possible d’intégrer des balises de champs dans le corps du message en copiant le format de la balise dans le texte comme montré ci-dessus. **Pour chaque champ dans votre formulaire usager ou dans vos annotations privées, une balise existe**. Lorsque vous intégrez cette balise à votre message, l’information renseignée par l’usager pour le champ correspondant est automatiquement remontée dans le corps du mail.

Exemple : j’ai un champ adresse et j’utilise ma balise adresse dans mon corps de texte comme suit : Attendu que vous habitez au –adresse--. Si l’usager a renseigné comme adresse 20 avenue de Ségur, il recevra un mail avec écrit : attendu que vous habitez au 20 avenue de Ségur.

Les balises sont notamment utiles pour remonter les annotations privées car elles peuvent transmettre directement les commentaires renseignés par l’instructeur à l’usager.

<figure><img src="../.gitbook/assets/image (186).png" alt=""><figcaption><p>Exemple de balises possibles, en tant qu'administrateur</p></figcaption></figure>

### Démarche déclarative

Dans une démarche déclarative, le dossier passe automatiquement en instruction, ou au statut « accepté », dès son dépôt. Ce réglage se trouve dans les options avancées de la présentation de la démarche.

Pour que l’usager ne reçoive pas deux e-mails à la suite, l’accusé de réception est alors remplacé par un modèle combiné :

* **Accusé de réception avec passage automatique en instruction** ;
* **Accusé de réception avec passage automatique au statut « accepté »**.

Les autres modèles ne servent plus que si un instructeur intervient ensuite sur le dossier, par exemple pour le réexaminer. La description de chaque modèle, sur la page « Modèles d’email », précise quand il est envoyé.

{% hint style="warning" %}
Si vous changez le réglage « Démarche déclarative », l’accusé de réception que vous aviez personnalisé est supprimé et remplacé par le modèle adapté au nouveau réglage. Les autres modèles d’e-mail sont conservés. Un avertissement s’affiche lorsque vous modifiez ce réglage.
{% endhint %}

Certaines démarches déclaratives plus anciennes envoient encore l’accusé de réception classique suivi d’un second e-mail. Un bandeau le signale sur la page « Modèles d’email ». Cliquez sur **« Passer à la nouvelle version »** pour utiliser le modèle combiné : seul l’accusé de réception personnalisé est supprimé et remplacé par le modèle standard, vos autres modèles personnalisés sont conservés.

### Avec l’accusé de lecture

Si l’[accusé de lecture](config-accuse-lecture.md) est activé, les e-mails d’acceptation, de refus et de classement sans suite ne sont pas modifiables, afin que la décision finale reste masquée pour l’usager.

Dans une démarche déclarative avec passage automatique au statut « accepté », l’accusé de réception envoyé au dépôt annonce toutefois l’acceptation à l’usager.

## Les attestations

Vous pouvez paramétrer une attestation délivrée en cas **d'acceptation ou de refus du dossier**.

Les attestations sont des documents au format .pdf qui sont délivrés en pièce jointe des e-mails d’acceptation ou de refus. Celles-ci sont également disponibles en téléchargement sur l’espace personnel de l’usager. Comme pour les e-mails, l’attestation est entièrement personnalisable, notamment avec une signature et différentes balises envisageables.

<figure><img src="../.gitbook/assets/Capture d’écran 2025-10-17 à 15.29.09.png" alt=""><figcaption></figcaption></figure>

A la différence de la configuration des e-mails, celle de l’attestation est optionnelle. Pour l’activer, cliquer sur le bouton « Activer l’attestation », situé en haut de votre écran.

Désactiver cette option arrête immédiatement l’émission de nouvelles attestations.

<figure><img src="../.gitbook/assets/Capture d’écran 2025-10-17 à 15.33.37.png" alt=""><figcaption></figcaption></figure>

En activant l'attestation, vous pouvez alors :

* Choisir d'afficher ou non le logo de la Marianne
* **Indiquer l'intitulé de votre institution** ( obligatoire)
* Choisir **un logo additionnel** ( optionnel )
* Renseigner **l'intitulé de la direction** (optionnel )

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* **Rédiger le contenu de l’attestation**. Il est possible de remonter des éléments du dossier de l'usager et des annotations privées grâce à l'utilisation des balises de champs. Pour cela, tapez le caractère @ suivi du nom de la balise, ou cliquez sur les boutons dédiés aux balises et insérez les dans votre texte. Il faut veiller à ce que la balise du texte soit identique à celle située sous le corps de l'attestation, sinon celle-ci ne fonctionnera pas. **Les champs conditionnés ne sont pas disponibles en tant que balises.**

<figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

* **Choisir un tampon ou une signature** scanné qui sera présenté en fin de document. Cette fonctionnalité vous offre aussi la possibilité d'insérer un code QR dans votre attestation. Vous avez également la possibilité d'insérer un contenu en pied de page.

<figure><img src="../.gitbook/assets/Capture d’écran 2025-10-17 à 15.42.50.png" alt=""><figcaption></figcaption></figure>

L’attestation est automatiquement enregistrée à chaque modificatio&#x6E;**.**

<figure><img src="../.gitbook/assets/image (7) (1) (1).png" alt=""><figcaption></figcaption></figure>

Enfin, vous avez la possibilité de vérifier les éléments ajoutés dans votre attestation grâce à l’aperçu, ainsi que de la prévisualiser en taille réelle.

<figure><img src="../.gitbook/assets/image (8) (1) (1).png" alt=""><figcaption></figcaption></figure>
