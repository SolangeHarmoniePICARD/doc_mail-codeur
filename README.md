# DWWM DIJON 2022 - Configuration de l'environnement de travail

## Le Webmail Codeur Online

- Dans la barre d'adresse de votre navigateur Microsoft Edge, tapez `https://mail.codeur.online/roundcube/`.

- Vous arrivez sur une page de *warning*, ce n'est pas grave, cliquez sur `Advanced` :

![](screenshots/01.png)

- Puis sur « `Continue to mail.codeur.online (unsafe)` » : 

![](screenshots/02.png)

- Vous arrivez sur la page de *Login*, connectez-vous avec les informations de connexion qui vous ont été communiquées : 

![](screenshots/03.png)

- Si tout ce passe bien, vous arrivez sur cette page :

![](screenshots/04.png)

> Utilisez cette adresse pour toutes vos communications liée à la formation, pour vous inscrire à des Web Services, etc. : l'idée est de séparer au maximum votre vie professionnelle de votre vie privée.
>
> BONUS : Cette adresse email restera valable une fois la formation terminée, c'est une adresse qui fait « pro », à privilégier quand vous postulez pour un stage ou pour un emploi. 

## Transformez votre adresse Codeur Online en compte Microsoft

> Tout au long de la formation, vous travaillerez sur un environnement Windows. Autant tirer partie au maximum des services et outils proposés par Microsoft.

- Dans la barre d'adresse de votre navigateur Microsoft Edge, tapez `https://account.microsoft.com/account/` et choisissez « `Create account` » :

![](screenshots/05.png)

- Renseignez votre adresse Codeur Online :

![](screenshots/06.png)

- Vous devez créer un nouveau mot de passe, vous n'êtes pas obligé d'utiliser celui du service Codeur Online :

![](screenshots/07.png)

- ⚠️ Pour des raisons de sécurité, refusez l'enregistrement des mots de passe dans le navigateur. Nous découvrirons plus tard une solution pour gérer ses mots de passe de façon réellement *safe* :

![](screenshots/08.png)

- Vous devez entrer un code reçu sur votre adresse Codeur Online, allez le récupérer : 

![](screenshots/09.png)

- Et renseignez-le :

![](screenshots/10.png)

- Microsoft a besoin de quelques informations sur vous. Dans une perspective professionnelle, on évite les « jeux de rôle » (ce ne sont pas des informations très sensibles, par contre gérer son identité numérique est un vrai sujet qu'on abordera en cours de formation !) :

![](screenshots/12.png)

- Acceptez de rester connecté, vous utiliserez ce compte pour vous faire identifier par le navigateur, ce qui permettra la synchronisation sur d'autres appareils au besoin :

![](screenshots/13.png)

- Vous pouvez personnaliser un peu votre compte Microsoft (n'y passez pas trop de temps quand même) :

![](screenshots/14.png)


## Identifiez-vous sur votre session ACS avec votre Compte Microsoft

> Cette fonctionnalité est très utile pour compartimenter vie professionnelle et vie privée : vous pourrez créer une session Windows sur une votre machine personnelle, et utilisez OneDrive pour synchronier votre session entre vos machines.

- Dans le menu `Démarrer` de Windows 11, tapez `Settings` ou `Paramètres` :

![](screenshots/15.png)

- Dans « `Comptes` », choisissez « `Vos informations` » :

![](screenshots/16.png)

- Cliquez sur « `Se connecter avec un compte Microsoft` »

![](screenshots/17.png)

- Vous devrez entrer votre adresse Codeur Online :

![](screenshots/18.png)

- Puis le mot de passe de votre compte Microsoft que vous avez paramétré précédemment (qui peut donc être différent du mot de passe Codeur Online) :

![](screenshots/19.png)

- Enfin, tapez le mot de passe de la session Windows 11 actuelle :

![](screenshots/20.png)

- Vous recevez un mail sur votre adresse Codeur Online : 

![](screenshots/21.png)

## OneDrive

- Le mail contient un lien vers OneDrive, cliquez sur ce lien : 

![](screenshots/22.png)

- Vous serez invité à renseigner une adresse email : utilisez l'adresse Codeur Online et choissez de vous identifier, et non de créer un compte Microsoft, puisque vous l'avez déjà fait...

![](screenshots/23.png)

- Choisissez ensuite « Usage personnel » : 

![](screenshots/24.png)

- Renseignez le mot de passe de votre compte Microsoft :

![](screenshots/25.png)

- Inutile d'envoyer des données supplémentaires : 

![](screenshots/26.png)

- Conservez la config par défaut pour l'emplacement de OneDrive :

![](screenshots/27.png)

- Déselctionnez la synchronisation du « Bureau » : 

![](screenshots/28.png)

- Ne choisissez pas par l'offre Premium : 

![](screenshots/29.png)

- Et... vous pouvez télécharger l'app mobile si vous le souhaitez, mais aucune obligation !

![](screenshots/30.png)


- Vous pouvez accéder à votre dossier OneDrive depuis votre session Windows 11, et depuis n'importe où dans un navigateur !


![](screenshots/31.png)


## L'application Microsoft Courier

- Dans le menu « `Démarrer` » de Windows 11, tapez « `Mail` » ou « `Courier` » :

![](screenshots/32.png)

- Choisissez « `Configuration avancée` » :

![](screenshots/33.png)

- Puis l'option qui permet de configurer les protocoles `POP3` ou `IMAP`, mais pas « Exchange Active Sync » :

![](screenshots/34.png)

- Renseignez l'adresse Codeur Online, qui est aussi le nom d'utilisateur. Cette fois, c'est bien le mot de passe du Webmail Codeur Online, et non celui du compte Microsoft. Reproduisez la configuration suivante, en personnalisant avec vos informations :

![](screenshots/35.png)

- Pour le serveur entrant, tapez `mail.codeur.online:110` et choisissez `POP3`, pour le serveur sortant, tapez `mail.codeur.online:587`, et enfin, cochez toutes les cases, sauf le protocole SSL pour les mails entrant :

![](screenshots/36.png)

- Vous aurez un beau message de succès MAIS... ce n'est malheureusement pas aussi simple que ça !

![](screenshots/37.png)

- Normalement, la boîte de réception a dû se remplir. Sinon c'est que vous avez raté quelque chose :

![](screenshots/38.png)

- Essayez de vous envoyer un mail à vous même :

![](screenshots/39.png)

- Il reste bloqué dans la boîte d'envoi (cliquez sur « `Plus` » et ajoutez les autres boîtes en « favoris » pour qu'elle s'affichent), un symbole « Warning » indique que la synchronisation ne se fait pas (il faut parfois insister un peu pour qu'il apparaisse). Cliquez dessus : 

![](screenshots/40.png)

- Dites que vous voulez faire confiance à ce serveur :

![](screenshots/41.png)

- Il va vous répondre qu'il y a un problème. C'est normal : 

![](screenshots/42.png)

- Fermez l'application et relancez-là ! Vous constatez que vous avez enfin reçu le mail que vous vous êtes envoyé :

![](screenshots/43.png)

- Vous pouvez vous envoyer un second mail pour confirmer que tout va bien :

![](screenshots/44.png)

- 🎉 Vous avez réussi ! C'est terminé ! 🥳