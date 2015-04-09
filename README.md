# Bienvenue sur le GitHub des gentils virus

La branche **master** de ce dépôt héberge le [site officiel des Gentils Virus](http://gentilsvirus.org/) .

Ce site est un site statique, développé en HTML avec [Jekyll](http://jekyllrb.com/). Jekyll est un générateur de site statique qui supporte un langage de template très basique (Liquid).

Jekyll est supporté nativement par GitHub, qui déploie et héberge le site pour nous, à chaque mise à jour de la branche **master** de ce dépôt. 

# Contribuer

## Cloner le site 

Tout le monde peut contribuer au site des GV. Pour ce faire, il vous suffit de faire un clone de la branche **gh-pages** de ce dépôt sur votre compte personnel GitHub.

Pour récupérer ce clone en local, vous pouvez utiliser soit un client Git natif (comme [Git Bash](http://git-scm.com/downloads) pour windows), ou bien le [client GitHub](https://windows.github.com/)

`git clone https://github.com/raphaeljolivet/GentilsVirusSite.git -b gh-pages`

## Prévisualiser vos changements sur github.io

GitHub déploie automatiquement  le contenu de la branche **gh-pages** sur `http://<votre-nom-d-utilisateur>.github.io/GentilsVirusSite/`

## Prévisualiser le site localement

Il est quand même recommandé d'installer Jekyll sur votre PC pour pouvoir débugger vos changements localement avant les les envoyer sur votre branche.

### Installation de Jekyll

#### Linux

Sous Linux, suivez simplement [les instructions officielles](http://jekyllrb.com/docs/installation/)

#### Windows

Jekyll n'est pas officiellement supporté sous Windows, et sa complication est plutôt compliquée.
Heureusement, un développeur a eu la bonne idée de complier et de distribuer une version précompilée [Portable Jekyll](https://github.com/madhur/PortableJekyll)

1. Téléchargez [Portable Jekyll] (patience plus de 1go !!)(https://github.com/madhur/PortableJekyll/archive/master.zip)
2. Dezippez l'ensemble de cette archive sur votre disque
3. Lancez une invite de commande (cmd.exe)
4. Rendez vous dans le répertoire ou vous avez décompressé l'archive (cd  ...)
5. éxécutez la commande `.\setpath.cmd`
6. Les chemins d'accès à Jekyll sont maintenant configurés **UNIQUEMENT DANS CETTE CONSOLE**. Ne la quittez pas pour la suite.

## Utilisation
Dans une console (celle utilisée précédemment pour Windows), rendez vous dans le répertoire contenant le clone du site. Puis lancez les commandes suivantes :

    jekyll build
    jekyll serve

à la deuxième commande, Jekyll lance un serveur web à cette adresse : `http//localhost:4000/`. Les modifications faites aux fichiers seront automatiquement réflétées sur ce site (après chaque refresh / F5).

## Soumettre vos changements

### Pull request
Commencez par faire une [Pull Request](https://help.github.com/articles/using-pull-requests/) (=demande d'intégration) depuis la branche **gh-pages** de votre dépôt local, vers la branche **master** du dépôt des GVs.

### Loomio

Rendez vous aensuite sur le [groupe Loomio](https://www.loomio.org/g/4kMliDc3/gentils-virus-officiel-graine-de-democratie-decisions-a-propos-du-site-gentilsvirus-org) et lancez une discussion pour approuver vos changements. Précisez :

* La liste des changements
* L'URL de votre version : `http://<login-github>.github.io/GentilsVirusSite/`

Après approbation (par vote), un admin se chargera d'intégrer les changements (merge).
