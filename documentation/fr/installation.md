# Installation
Le mimimum nécessaire pour installer Pabana est un serveur Web et une copie de Pabana, et c'est tout :)

## Conditions requises
 - Serveur web (HTTP) : Par exemple: Apache ou nginx.
 - PHP 5.6 ou plus

## Conditions facultatives
- Activer l'url rewriting sur votre serveur web. Par exemple: mod_rewriting pour Apache.
- Un moteur de base de données. Par exemple : Mysql.

## Installer Pabana

L'installation de Pabana peut s'effectuer de deux façon :

 - Via composer (recommandé)
 - En téléchargent une archive contenant Pabana et un exemple d'application.

### Installation via Composer (recommandé)
Veuillez commencer par installer [Composer](https://getcomposer.org/download/), qui est un outil de gestion de dépendances pour PHP.
Puis exécuter la commande suivantes en remplaçant "my_app_name" par le nom de l'application que vous souhaitez créer.

    composer self-update && composer create-project --prefer-dist pabana/app my_app_name
Cette commande a pour effet de télécharger Pabana et un squelette d'application vous permettant de faire fonctionner Pabana.

### Installation via archive
Vous pouvez télécharger une archive contenant Pabana et un squelette d'application depuis la [page de téléchargement](https://pabana.futurasoft.fr/download/) du site web de Pabana.