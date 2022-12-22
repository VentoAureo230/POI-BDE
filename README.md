# POI-BDE

Ce Projet Open Innovation à pour but de réaliser le site web du BDE de l'EPSI (EPSIW).


## Stack Technique

- PhP Framework Symfony (8.1+)
- JavaScript
- BDD MySQL 4.9+

## :warning: Requis pour un fonctionnement local :warning:

- PhP 8.1+
- [Wamp](https://www.wampserver.com/) avec une base de donnée MySQL 4.9+
- [Composer](https://getcomposer.org/)
- [NPM]()

## Pour commencer

Pour obtenir une copie de ce projet, ouvrez votre terminal et entrer :

```
git clone https://github.com/VentoAureo230/POI-BDE
```

## Execution :runner:

Pour exécuter le projet ouvrez votre terminal dans le dossier du projet.

1. Changez les coordonnés du .env.test pour faire correspondre à vos identifiants MySQL, puis enlevez le .test de l'extension. Wamp doit être allumé.

2. Exécutez cette suite de commande :

```
composer install
```

```
npm install --force
```

```
php bin/console assets:install
```

```
php bin/console doctrine:database:create
```

3. Exécuter les migrations précédentes (optionnel) :

```
php bin/console doctrine:migrations:migrate
```

```
php bin/console d:f:l
```

4. Démarrer le serveur Symfony :


```
npm run build
```

```
symfony server:start
```

Utilisez `symfony server:stop` pour arrêter le serveur

5. Le site est accessible sur l'url 127.0.0.1:8000

6. Enjoy !

## Auteurs

- Anthony Mény
- Antoine Garnier
- Bastien Lassaigne
- Jeanne Gablin
- Axel Lebihan

Etudiants en SN2.
