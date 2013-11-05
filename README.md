locale-2.x
==========

Ce projet propose des fichiers de traduction du coeur de
CakePHP en langue française.

**Version de la branche master : (CakePHP 2.4.1)**

**Avancement actuel : **

  - cake : 86/86 messages traduits.
  - cake_dev : 22/269 messages traduits.
  - cake_console : 0/541.


Installation
------------

Pour installer la traduction française du coeur de PHP dans votre application,
ajoutez les fichiers de ce depôt dans le répertoire app/Locale de votre
application.

Il vous faudra ensuite configurer CakePHP en français, en faisant par exemple
Configure::write('Config.language', 'fra');

Pour plus d'informations sur l'internationalisation voir la documentation du
framework :
[http://book.cakephp.org/2.0/fr] (http://book.cakephp.org/2.0/fr/core-libraries/internationalization-and-localization.html "Cookbook sur Internationalisation")

Contributions et Organisation
-----------------------------

Depuis la mise en place de ce projet sur cakephp-fr, un autre projet propose
de gérer les traductions du coeur de CakePHP dans différentes langues,
sous forme de plugin: https://github.com/cakephp-fr/localized .
Si l'on en croit sa description, ce plugin semble avoir été initialement
dédié uniquement au processus de validation.

Aujourd'hui, il rassemble aussi les traductions en 11 langues du cœur
de CakePhp, mais ne définit aucune procédure pour le suivi des
versions successives de CakePhp.

Si vous avez développé en 2012 un site avec CakePHP 2.1.0 et souhaitez
parfaire aujourdh'hui sa *l10n*, il serait intéressant de pouvoir partager
votre travail, même si dans la version actuelle (2.4.2 au moment ou j'écris),
les chaînes de références (*msgid*s) ont changé.

Ce projet cakephp-fr/locale-2.x prévoit dès sa mise en place
de dédier une branche pour chaque version de CakePHP, ce qui
devrait répondre au problème.

Mais la gestion des mises à jour, avec effort de conservation des traductions
existantes est un sujet qui concerne toutes les langues.
C'est pourquoi j'ai choisi de porter ce travail sur le projet localized,
*made in France* : https://github.com/RockyRoad29/localized

Support / Suggestions / Problèmes / Discussions
-----------------------------------------------
* Pour toute suggestion ou problème, vous pouvez utiliser le système de gestion de bugs de Github : [pulse](https://github.com/RockyRoad29/locale-2.x/pulse)
