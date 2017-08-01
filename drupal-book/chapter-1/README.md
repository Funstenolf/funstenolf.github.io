Installation du CMS *Drupal*
============================

## Installation de *Composer*
> Source : <https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx>

### Localement
Installer Composer localement consiste simplement en lancer l’installateur dans le dossier de votre projet. Aller sur la page [*Download*](https://getcomposer.org/download/) pour voir les instructions.

L’installateur va vérifier vos paramètres PHP puis télécharger le fichier `composer.phar` à votre dossier courant. Il s’agit d’une archive PHP dans laquelle se situent les commandes composer.

Vous pouvez désormais lancer la commande `php composer.phar` pour lancer Composer.

### Globalement
Vous pouvez placer le PHAR *Composer* partout où vous le souhaitez. Si vous le mettez dans un répertoire faisant partie de votre `PATH` vous pourrez y accéder de façon globale. Sur les systèmes UNIX, vous pouvez même le rendre exécutable et l’invoquer sans utiliser l’interpréteur `php`.