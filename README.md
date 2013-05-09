Xampp Homepage
==============

## Qu'est-ce que c'est ?
Xampp Homepage est une page d'accueil de substitution à celle d'origine pour le serveur Web Xampp. 
Un peu plus jolie et plus complète, entre autres. Un atout par rapport à d'autres pages que vous pourrez trouver : elle reste "one-file", telle l'`index.php` d'origine.
Cette page est une adaptation de HomeWamp développée par Alex-D qui est prévu pour le serveur Web WAMP (https://github.com/Alex-D/HomeWAMP)

Voilà à quoi ressemble Xampp Homepage :

![Screenshot de Xampp Homepage](https://raw.github.com/Zicguy/Xampp-Homepage/master/xampp-homepage.jpg "Screenshot de Xampp Homepage")

## Installation
1. Renommez votre `index.php` en `index.old.php`, de façon à avoir un backup si besoin
2. Placez simplement le fichier index.php dans votre dossier `/htdocs/`
3. Admirez et profitez !

## Administration
Il y a une page nommée "Administration" accessible depuis l'onglet en haut à droite qui vous permet d'accéder à la configuration du serveur, versions, alias et vous pouvez en rajouter à votre guise en éditant le code.
Vous pourrez également voir sur cette page un statut de chaque service fourni avec Xampp (MySQL, SMTP, FTP, ...).

## Liste blanche d'admnistrateurs
Vous trouverez une liste blanche d'IP pour l'accès à l'admin en début de fichier dans une variable `$admin_ip`

## Screenshots & favicon
Pour voir un screenshot de votre site, ajoutez simplement un fichier `screenshot.jpg` dans le dossier du projet. Les dimentions recommandées sont `150x100px`.
En ce qui concerne les favicons, Xampp Homepage recherchera de lui-même s'il existe un `favicon.ico` ou `favicon.png` à la racine ou dans `/web/` pour les projets Symfony2.

## Auteur
A l'origine, cette page pour WAMP a été créée par Alex-D (http://alex-d.fr/). Utilisant Xampp de mon côté, je l'ai adapté pour qu'elle fonctionne avec ce serveur Web. Vous pouvez me suivre sur http://www.deepevening.fr. N'hésitez pas à contribuer si vous voyez des améliorations à faire...

-------

## Aller plus loin
Vous pouvez changer la navigation dans les dossiers par défaut d'apache par celle-ci : http://larsjung.de/h5ai/ qui rajoute un peu d'esthétique en rajoutant, entre autre, un arbre à gauche et un fil d'Arianne en haut.
