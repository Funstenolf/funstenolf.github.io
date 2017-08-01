Installation du CMS *Drupal*
============================

## Création du projet
> Source : <https://github.com/drupal-composer/drupal-project/blob/8.x/README.md>

Après avoir installé *Composer* il vous suffit de taper la commande suivante afin de créer le projet :

`composer create-project drupal-composer/drupal-project:8.x-dev NOM_PROJET --stability dev --no-interaction`

Où `NOM_PROJET` est le nom que prendra le dossier-racine du projet.

Vous pouvez désormais installer les différentes dépendances nécessaires au projet, en vous placant dans le dossier-racine de ce dernier.

`cd NOM_PROJET`

Il suffit ensuite de taper la commande suivante :

`composer require drupal/DEPENDANCE`