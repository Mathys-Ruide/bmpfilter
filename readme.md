# PREMIER TP GIT B2

Bienvenue sur ce depot. Il s'agit d'un projet developpe en C dont l'objectif est de nous servir de support pour apprendre l'utilisation de git.


# A l'attention des collaborateurs

Pour realiser ce TP, nous allons suivre une organisation que je vais vous detailler.


## Repartition des taches :


Nous avons 5 filtres a realiser au total et nous sommes 4.

Je propose la repartition des taches suivante : 

**Gregoire** : 1 ou 2 filtres couleur

**Mathys** : 1 ou 2 filtres couleur

**Nicolas** : filtre miroir

**Hugo** : filtre blur


## Organisation du depot :


Une branche "dev" sera creee. Vous ne travaillerez pas directement sur cette branche, vous creerez pour chacun de vos filtres une branche a partir de la branche dev.


Si vous travaillez sur le filtre "blue", la marche a suivre est la suivante, a adapter selon le nom du filtre sur lequel vous travaillerez :

git checkout dev

git checkout -b blue


Une fois que vous jugez votre code satisfaisant et fonctionnel, vous pourrez effectuer une pull request sur la branche dev.

Une fois que les 5 filtres seront realises, nous fusionnerons la branche dev avec la branche master en ajoutant un nouveau tag.

## Format des commits :

Pour vos messages de commit **obligatoires**, vous devrez respecter la convention suivante. Selon la nature de votre commit, vous mettrez un mot cle different devant votre message.


Voici les mots cles a utiliser :

*feat* : a utiliser lorsque vous ajoutez une nouvelle fonctionnalite a votre code

*fix* : a utiliser lorsque vous resolvez un bug

*refactor* : a utiliser lorsque vous modifiez votre code sans changer de fonctionnalite

*style* : a utiliser lorsque vous changez le style de votre code


Ce mot cle est a suivre d'une breve explication des changements que vous aurez effectues.





